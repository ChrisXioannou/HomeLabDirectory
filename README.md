<h1>Virtualized Active Directory Home Lab</h1>

<h2>Description</h2>
<p>This home lab project is a virtualized network environment created using Oracle VirtualBox. It includes a Domain Controller (DC) running Server 2019, configured with Active Directory services for a simulated internal network. The lab is designed to showcase my ability to set up and manage a network infrastructure, demonstrating core IT skills such as network management, user administration, and security principles.</p>

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

<h2>Network Services and Configuration:</h2>
<p>This section explains the various network services and components used in the lab setup:</p>

<ol>
<li><b>Active Directory</b>: Used for creating and managing multiple user accounts, handling authentication and authorization within the network.</li>
<li><b>Domain Name System (DNS)</b>: Essential for the functioning of the Active Directory, as it provides a way to match domain names (like those of computers or services) to their respective IP addresses.</li>
<li><b>Dynamic Host Configuration Protocol (DHCP)</b>: Automates the IP address configuration for devices on the network, including a defined range (scope) for dynamic assignment.</li>
<li><b>Remote Access Service (RAS)/Network Address Translation (NAT)/Virtual Private Network (VPN)</b>: Provides remote access to the network, enabling NAT to facilitate internet connectivity for multiple hosts on the internal private network, and VPN to securely connect remote users to the lab network.</li>
</ol>

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

<h2>Project Outcomes</h2>
<p>This home lab project allowed me to gain hands-on experience with Windows Server administration, networking principles, and security best practices. It served as a practical exercise in setting up and configuring core services like Active Directory, DNS, DHCP, and VPN. Such skills are vital for a career in system administration, network engineering, or IT support.</p>
