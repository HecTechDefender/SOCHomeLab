<h1>Building a SOC Home Lab</h1>

 ### 

<h2>Description</h2>
In this project, I'm on a mission to build a SOC home lab! This project will cover pfSense, Active Directory, Windows Workstation, Sysmon and CrowdSec. My goal? Creating a space where I can experiment and learn the ropes of real-world cybersecurity from the comfort of my home! 
<br />


<h2>Utilities Used</h2>

- <b>pfSense</b>
- <b>Active Directory</b>
- <b>Windows Workstation</b>
- <b>Sysmon</b>
- <b>CrowdSec</b>


<h2>Environments Used </h2>

- <b>Windows 10</b> (22H2)

<h2>Program walk-through:</h2>

<p align="center">
Create a new virtual machine <br/>
<img src="https://i.imgur.com/eK0RfQN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
  <br/>
<img src="https://i.imgur.com/V5iavld.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 <br/>
<img src="https://i.imgur.com/q1VUcZd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
  <br/>
<img src="https://i.imgur.com/NcZ2dHy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
  <br/>
<img src="https://i.imgur.com/gul50UU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection: <br/>
<img src="https://i.imgur.com/5rRMZ7J.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Go to the VM properties. In Network tab, activate 3 adapters. Making note of the MAC Addresses of each adapters will be useful for future actions. This will be the RED CARD. (external network) <br />
<img src="https://i.imgur.com/p7VjUeg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<br />
  <br/> This will be the GREEN CARD (internal network)
<img src="https://i.imgur.com/1pk3nhj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<br />
This will be the ORANGE CARD (DMZ) <br/>
<img src="https://i.imgur.com/l4x8wnB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<br />
 Launch the VM. It will ask you which ISO Virtualbox must mount on the VM, load the pfsense one. <br/>
<img src="https://i.imgur.com/6BB7SE6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<br />
 Install and accept the Copyright and Trademark Notices.     <br/>
<img src="https://i.imgur.com/StEzyOr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<br />
              <br/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<br />
               <br/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
