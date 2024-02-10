<h1>Exploring the Seven Domains of a Typical IT Infrastructure</h1>

<h2>Tools and Software Used</h2>

- <b>PuTTy</b> 
- <b>Ping</b>
- <b>Open vSwitch</b> 
- <b>TrueNAS</b>
- <b>pfSense</b> 
- <b>Traceroute</b>
- <b>Nslookup</b> 
- <b>OpenVPN</b>
- <b>OWASP Juiceshop</b> 

<h2>Environments Used </h2>

- <b>vWorkstation (Windows Server 2022)</b> 
- <b>Switch01 (Linux: Debian 11)</b>
- <b>FileServer01 (FreeBSD)</b>
- <b>pfSense Office (FreeBSD)</b>
- <b>pfSense-dc (FreeBSD)</b>
- <b>DomainController01 (Windows Server 2019)</b>
- <b>WebServer01 (Linux: Ubuntu 20)</b>
- <b>RemoteWindows01 (Windows Server 2019)</b>
- <b>AttackLinux01 (Linux: Kali)</b>
 
<h2>Description</h2>
Project consists reviewing basic security controls on a Windows workstation, exploring additional devices on a LAN segment(including a LINUX-based switch and a FREEBSD-based dial server), and connecting to a router-firewall to learn about the network perimeter.
<br />

### Section 1

<h2>Explore the Workstation Domain:</h2>








<p align="center">
Show sign-in options for the user's account: <br/>
<img src="https://i.imgur.com/Hb10h22.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
View configured update policies page:  <br/>
<img src="https://i.imgur.com/9S721Q5.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
View virus and threat protection settings: <br/>
<img src="https://i.imgur.com/9YXgEnl.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show security warning from attempting to run an executable file:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Section 1n Steps"/>
<br />
<br />
Show the blocked attachment message:  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Show successful connection to the user folder:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Show the failed connection to another user folder:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Show the successful connection to the Marketing shared folder:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Show the failed connection to another shared folder:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

 <h2>Explore the LAN Domain:</h2>







<p align="center">
Show vWorkstation's original ARP table: <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show VWorkstation's updated ARP table::  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show Switch01 forwarding table: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show contents of the Employees directory:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Section 1n Steps"/>

 <h2>Explore the LAN-to-WAN Domain:</h2>







<p align="center">
Show the Outbound NAT settings: <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the permissive LAN rules::  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the Static Routes page: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the result of your tracert to the pfSense=dc appliance:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Section 1n Steps"/>
<br />
<br />
Show the Port Forward rules for the web server: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the DMZ firewall rules: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Section 1 Steps"/>

 ### Section 2

<h2>Explore the WAN Domain:</h2>










<p align="center">
Show the static route for the point-to-point connection: <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the BPG neighbor ping results:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the traceroute to the file server: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />

 <h2>Explore the Remote Access Domain:</h2>










<p align="center">
Show the successful connection to the email server: <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Document whether the VPN connection is a split tunnel or full tunnel, based on tracert results: <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the successful reverse DNS lookup for the internet host: <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />

 <h2>Explore the System/Application Domain:</h2>










<p align="center">
Show the whoami results: <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the members of the Developers AD group:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the password policy settings in the Group Policy Management Console: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the DNS entries:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Section 1n Steps"/>
<br />
<br />
Show the Docker service status:  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Show the juiceshop.com web page:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Show the disks in the tank volume:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
