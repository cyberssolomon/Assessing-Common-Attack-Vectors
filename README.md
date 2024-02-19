<h1>Assessing Common Attack Vectors</h1>

<h2>Tools and Software Used</h2>

- <b>OWASP Juice Shop</b> 
- <b>Firefix Web Developer Tools</b>
- <b>Metasploit Framework</b> 
- <b>Irssi</b>
- <b>Social Engineering Toolkit (SET)</b> 
- <b>Thunderbird</b>
 

<h2>Environments Used </h2>

- <b>vWorkstation (Windows: Server 2016)</b> 
- <b>pfSense (FreeBSD: pfSense)</b>
- <b>WebServer01 (Linux: Ubuntu 20)</b>
- <b>TargetWindows02 (Windows: Server 2019)</b>
- <b>AttackLinux01 (Linux: Kali)</b>
- <b>TargetPi (Raspberry Pi OS)</b>
- <b>Debnet (Linux: Debian 11) [contains additional Docker hosts]</b>
- <b>TargetLinux02 (Linux: Ubuntu 20)</b>

 
<h2>Description</h2>
Project consists of exploring several common attack vectors: injection-based attacks, malware-based attacks, denial-of-service attacks, and social engineering attacks.
<br />

### Section 1

<h2>Perform an Injection Attack:</h2>








<p align="center">
Show the DOM XSS dialog box: <br/>
<img src="https://i.imgur.com/7aHD4iE.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the successful admin login:  <br/>
<img src="https://i.imgur.com/JOB3hhA.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the successful Reflected XSS injection: <br/>
<img src="https://i.imgur.com/OnhZR4f.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the user with the @owasp.org email:  <br/>
<img src="https://i.imgur.com/EuwMdlk.png" height="80%" width="80%" alt="Section 1n Steps"/>
<
 <h2>Perform a Malware Attack:</h2>







<p align="center">
Show the msfvenom output: <br/>
<img src="https://i.imgur.com/VSbVFM1.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the Opening malwarePayload.exe dialog box::  <br/>
<img src="https://i.imgur.com/vTW4VSS.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the output of the sysinfo command: <br/>
<img src="https://i.imgur.com/EB44TMv.png" height="80%" width="80%" alt="Section 1 Steps"/>









 ### Section 2

<h2>Perform a Distributed Denial-of-Service Attack:</h2>










<p align="center">
Show the newly recruited hosts: <br/>
<img src="https://i.imgur.com/XN5lWrn.png" height="80%" width="80%" alt="Section 2 Steps"/>
<br />
<br />
Show the drisst.org webpage:  <br/>
<img src="https://i.imgur.com/PhBA3zS.png" height="80%" width="80%" alt="Section 2 Steps"/>
<br />
<br />
Show the failed connection to drisst.org: <br/>
<img src="https://i.imgur.com/wSMPJkb.png" height="80%" width="80%" alt="Section 2 Steps"/>
<br />
<br />
Show the "PF states limit reached" error message : <br/>
<img src="https://i.imgur.com/DUqJ5ex.png" height="80%" width="80%" alt="Section 2 Steps"/>


 <h2>Perform a Social Engineering Attack:</h2>










<p align="center">
Show the finished SET phising email composition: <br/>
<img src="https://i.imgur.com/8UDXCUR.png" height="80%" width="80%" alt="Section 2 Steps"/>
<br />
<br />
Show the transaction.php page in the browser: <br/>
<img src="https://i.imgur.com/tHLsMPr.png" height="80%" width="80%" alt="Section 2 Steps"/>











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
