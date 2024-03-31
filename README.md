<h1>Virtualized Active Directory Home Lab</h1>

<h2>Description</h2>
<p>This home lab project represents a virtualized network environment. At its core, the setup features a Domain Controller (DC) running Server 2019 with complete Active Directory services and another virtual machine running Windows 10 to mimic a real-world internal network.
<ul>
  <li><b>Network Services</b>: Incorporates core services such as DNS, showcasing the ability to configure and manage name resolution for networked devices, essential for internal and external communications.</li>
  <li><b>User and Admin Interaction</b>: Demonstrates the setup and administration of multiple user accounts, providing insight into the management of different access levels.</li>
  <li><b>VPN Implementation</b>: Implements a Virtual Private Network to extend secure remote access capabilities for network security and remote connectivity.</li>
  <li><b>RAS and NAT</b>: Configures Remote Access Service (RAS) and Network Address Translation (NAT) to enable private network communication with external networks.</li>
</ul></p>

<h2>Languages and Utilities Used</h2>
<ul>
<li><b>PowerShell</b></li>
<li><b>Oracle VirtualBox</b></li>
</ul>

<h2>Environments Used </h2>
<ul>
<li><b>Windows Server 2019 virtual machine</b></li>
<li><b>Windows 10 virtual machine</b></li>
</ul>

<h2>Network Diagram</h2>
<p>Below is a visual representation of the network architecture designed in this virtualized environment:</p>
<p align="center">
  <img src="HomeLabDirectory/assets/diagram.png" width="80%" alt="Network Diagram"/>
</p>

<h2>Technical Details and Explanations</h2>
<p>Here's a brief overview of the key components of this project and their roles in a network environment:</p>

<dl>
<dt>DC Server 19</dt>
<dd>A Domain Controller running Windows Server 2019, which is fundamental for managing network security, user data, and providing authentication and authorization services within a domain.</dd>

<dt>RAS (Remote Access Service)</dt>
<dd>Enables remote users to connect to the network, offering secure access to internal resources from outside the local environment, which is pivotal for remote work scenarios and distributed teams.</dd>

<dt>NAT (Network Address Translation)</dt>
<dd>Allows multiple devices on a private network to access the internet using a single public IP address. This conserves public IP addresses and adds a layer of security as individual device IPs are hidden from the external network.</dd>

<dt>DNS (Domain Name System)</dt>
<dd>The service that translates domain names into IP addresses, facilitating users' connection to websites and services on both the internet and internal networks.</dd>

<dt>DHCP (Dynamic Host Configuration Protocol)</dt>
<dd>Automatically assigns IP addresses to devices on a network, streamlining network management and ensuring seamless communication between devices.</dd>
</dl>

<h2>Acknowledgments</h2>
<p>I would like to express my gratitude to Josh Madakor for his tutorial, which guided me through setting up and configuring the network services in this lab. His tutorial provided me with a foundational understanding and hands-on experience in a controlled environment. For further information and access to the scripts used, please refer to Josh Madakor's original materials.</p>

<h2>PowerShell Script for Creating Users</h2>
<p>The PowerShell script for creating the 1000 users in this project was adapted from a script provided by Josh Madakor's tutorial. For the original script and further details, please visit [Josh Madakor's GitHub repository](https://github.com/joshmadakor1/AD_PS).</p>


<h2>Project Outcomes</h2>
<p>This home lab project allowed me to gain hands-on experience with Windows Server administration, networking principles, and security best practices. It served as a practical exercise in setting up and configuring core services like Active Directory, DNS, DHCP, and VPN. Such skills are vital for a career in system administration, network engineering, or IT support.</p>



