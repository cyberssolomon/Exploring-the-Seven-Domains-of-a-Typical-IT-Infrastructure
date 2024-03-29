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
Project consists of exploring the seven domains within the context of a virtual lab environment: reviewing basic security controls on a Windows workstation, exploring additional devices on a LAN segment(including a LINUX-based switch and a FREEBSD-based dial server), and connecting to a router-firewall to learn about the network perimeter.
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
<img src="https://i.imgur.com/SiOcTif.png" height="80%" width="80%" alt="Section 1n Steps"/>
<br />
<br />
Show the blocked attachment message:  <br/>
<img src="https://i.imgur.com/MhGHBvc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Show successful connection to the user folder:  <br/>
<img src="https://i.imgur.com/nKyuwco.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Show the failed connection to another user folder:  <br/>
<img src="https://i.imgur.com/ATA0Ap2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Show the successful connection to the Marketing shared folder:  <br/>
<img src="https://i.imgur.com/LqeeoBo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Show the failed connection to another shared folder:  <br/>
<img src="https://i.imgur.com/tyzg3TR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

 <h2>Explore the LAN Domain:</h2>







<p align="center">
Show vWorkstation's original ARP table: <br/>
<img src="https://i.imgur.com/yJlmNOa.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show VWorkstation's updated ARP table::  <br/>
<img src="https://i.imgur.com/4L7aLKq.pngS" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show Switch01 forwarding table: <br/>
<img src="https://i.imgur.com/g9w9wNB.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show contents of the Employees directory:  <br/>
<img src="https://i.imgur.com/HhM5T8J.png" height="80%" width="80%" alt="Section 1n Steps"/>

 <h2>Explore the LAN-to-WAN Domain:</h2>







<p align="center">
Show the Outbound NAT settings: <br/>
<img src="https://i.imgur.com/pCQYiBO.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the permissive LAN rules::  <br/>
<img src="https://i.imgur.com/U3O1Lc6.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the Static Routes page: <br/>
<img src="https://i.imgur.com/txnRiEP.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the result of your tracert to the pfSense=dc appliance:  <br/>
<img src=https://i.imgur.com/55q5jEc.png"" height="80%" width="80%" alt="Section 1n Steps"/>
<br />
<br />
Show the Port Forward rules for the web server: <br/>
<img src="https://i.imgur.com/ahZs4Y2.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the DMZ firewall rules: <br/>
<img src=https://i.imgur.com/xM71R9q.png"" height="80%" width="80%" alt="Section 1 Steps"/>

 ### Section 2

<h2>Explore the WAN Domain:</h2>










<p align="center">
Show the static route for the point-to-point connection: <br/>
<img src="https://i.imgur.com/K2NA8GX.png" height="80%" width="80%" alt="Section 2 Steps"/>
<br />
<br />
Show the BPG neighbor ping results:  <br/>
<img src="https://i.imgur.com/OrTRpYs.png" height="80%" width="80%" alt="Section 2 Steps"/>
<br />
<br />
Show the traceroute to the file server: <br/>
<img src="https://i.imgur.com/q0mlR5n.png" height="80%" width="80%" alt="Section 2 Steps"/>
<br />
<br />

 <h2>Explore the Remote Access Domain:</h2>










<p align="center">
Show the successful connection to the email server: <br/>
<img src="https://i.imgur.com/2QXdU81.png" height="80%" width="80%" alt="Section 2 Steps"/>
<br />
<br />
Document whether the VPN connection is a split tunnel or full tunnel, based on tracert results: <br/>
<img src="https://i.imgur.com/LJOR0EW.png" height="80%" width="80%" alt="Section 2 Steps"/>
<br />
<br />
Show the successful reverse DNS lookup for the internet host: <br/>
<img src="https://i.imgur.com/96XwcCH.png" height="80%" width="80%" alt="Section 2 Steps"/>
<br />
<br />

 <h2>Explore the System/Application Domain:</h2>










<p align="center">
Show the whoami results: <br/>
<img src="https://i.imgur.com/B4iQOo4.png" height="80%" width="80%" alt="Section 2 Steps"/>
<br />
<br />
Show the members of the Developers AD group:  <br/>
<img src="https://i.imgur.com/z2VDreK.png" height="80%" width="80%" alt="Section 2 Steps"/>
<br />
<br />
Show the password policy settings in the Group Policy Management Console: <br/>
<img src="https://i.imgur.com/6IcjNtu.png" height="80%" width="80%" alt="Section 2 Steps"/>
<br />
<br />
Show the DNS entries:  <br/>
<img src="https://i.imgur.com/KlplGTi.png" height="80%" width="80%" alt="Section 2 Steps"/>
<br />
<br />
Show the Docker service status:  <br/>
<img src="https://i.imgur.com/1Iu2Dge.png" height="80%" width="80%" alt="Section 2 Steps"/>
<br />
<br />
Show the juiceshop.com web page:  <br/>
<img src="https://i.imgur.com/EMa6Fe4.png" height="80%" width="80%" alt="Section 2 Steps"/>
<br />
<br />
Show the disks in the tank volume:  <br/>
<img src="https://i.imgur.com/KlF7i8w.png" height="80%" width="80%" alt="Section 2 Steps"/>

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
