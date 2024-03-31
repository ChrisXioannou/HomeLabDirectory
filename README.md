<h1>Virtualized Active Directory Home Lab</h1>

<h2>Description</h2>
<p>This home lab project represents a virtualized network environment crafted using Oracle VirtualBox. At its core, the setup features a Domain Controller (DC) running Server 2019 with a complete Active Directory services and another virtual machine running windows 10 to mimic a real-world internal network.
This environment not only showcases my capabilities in establishing and administering network infrastructure but also highlights my proficiency in interacting with both administrative and user accounts. It provides a dynamic setting for practical application of essential IT skills, including network management, user administration, nuanced access control, and enforcing robust security protocols.</p>

<h2>Languages and Utilities Used</h2>
<ul>
<li><b>PowerShell</b></li>
<li><b>Oracle VirtualBox</b></li>
</ul>

<h2>Environments Used </h2>
<ul>
<li><b>Windows Server 2019</b></li>
<li><b>Active Directory</b></li>
<li><b>VirtualBox</b></li>
</ul>

<h2>Technical Details and Explanations</h2>
<p>Here's a brief overview of the key components of this project and their roles in a network environment:</p>

<dl>
<dt>DC Server 19</dt>
<dd>Refers to a Domain Controller running Windows Server 2019. This server is crucial for managing network security, user data, and services such as authentication and authorization within a domain.</dd>

<dt>RAS/NAT</dt>
<dd>Remote Access Service (RAS) and Network Address Translation (NAT) work together to provide secure remote connections to the network and allow private IP addresses to communicate with the Internet by mapping them to a public IP.</dd>

<dt>DNS</dt>
<dd>Domain Name System (DNS) is the service that translates human-friendly domain names to IP addresses, allowing users to connect to websites and other resources on the Internet or an intranet.</dd>

<dt>DHCP</dt>
<dd>Dynamic Host Configuration Protocol (DHCP) dynamically assigns IP addresses to devices on a network, simplifying the management of IP assignments and ensuring devices can communicate effectively.</dd>
</dl>

<h2>Lab Configuration Walk-through:</h2>

<p align="center">
1) Overview of the VirtualBox environment with the DC and network configuration:<br/>
<img src="assets/network_diagram.png" width="80%" alt="Network Diagram"/>
<br />
<br />
2) Detail of the Active Directory Users and Computers management console, showing the organization of the created user accounts and administrative groups:<br/>
<img src="assets/ad_users.png" width="80%" alt="AD Users"/>
<br />
<br />
3) Configuration of DHCP scope and its properties within the network:<br/>
<img src="assets/dhcp_scope.png" width="80%" alt="DHCP Scope"/>
<br />
<br />
4) Setup of VPN connectivity, demonstrating the ability to configure secure network access for remote users:<br/>
<img src="assets/vpn_configuration.png" width="80%" alt="VPN Configuration"/>
<br />
<br />
</p>

<h2>Acknowledgments</h2>
<p>I would like to express my gratitude to Josh Madakor for his tutorial, which guided me through setting up and configuring the network services in this lab. His tutorial provided me with a foundational understanding and hands-on experience in a controlled environment. For further information and access to the scripts used, please refer to Josh Madakor's original materials.</p>

<h2>PowerShell Script for Creating Users</h2>
<p>The PowerShell script used for creating the 1000 users was adapted from Josh Madakor's tutorial. Due to licensing, the script is not included here, but viewers are encouraged to refer to the tutorial for detailed instructions and access to the script.</p>

<h2>Project Outcomes</h2>
<p>This home lab project allowed me to gain hands-on experience with Windows Server administration, networking principles, and security best practices. It served as a practical exercise in setting up and configuring core services like Active Directory, DNS, DHCP, and VPN. Such skills are vital for a career in system administration, network engineering, or IT support.</p>
