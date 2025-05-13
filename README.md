# Security-Project-1

<p align="center">
<img src="https://i.imgur.com/NlylI1S.jpeg"/>
 <img src="https://i.imgur.com/e5QOGvB.jpeg"/>
</p>

<h1>Disable Windows Firewall and install SQL Server</h1>
Here, we will RDP into the Windows VM, disable the Windows firewall protections, then install and configure SQL Server. This will add another program to the Honeypot to entice attacks from the internet. 

<h2>Environments and Technologies Used</h2>

- Windows 10
- Windows Firewall Defender
- SQL Server

 

<h2> Disable Windows Firewall Protections </h2>


<br />

<p>
1.  Here we can see a failed Ping attempt on the Windows VM because the Firewall protections are active. 
</p>
<img src="https://i.imgur.com/3aQPBRc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>


<p>
2. RDP into the Windows VM, open Windows Defender Firewall, and select Windows Defender Firewall Properties. 
</p>
<p>
<img src="https://i.imgur.com/UZYoWJY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

[Click here to view instructions on how to create an Azure VM and access it using Remote Desktop](https://github.com/BryanEAtherton/Azure-Virtual-Machine)

<br />


<p>
 3. On the Domain, Public, and Private tabs, turn the firewall state to "off." Then select Apply, then Ok.
</p>
<p>
<img src="https://i.imgur.com/ArXHVD8.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/yHe1C81.png" height="50%" width="40%" alt="Disk Sanitization Steps"/>
</p>

<p>   
4. Windows will show an alert message that the Firewall is off, and Ping attempts on the Windows VM will now be successful.
</p>
<p>
<img src="https://i.imgur.com/MLI0f2I.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/zfCSDTh.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>

<br />

<h2> Install and configure SQL Server </h2>

<br />

<p>
1. In the Windows VM, Google search for SQL Server Evaluation Center and select.
</p>
<p>
2. Fill out all required information for the free trial and select Download.
</p>
<p>
<img src="https://i.imgur.com/uhujolq.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
 <img src="https://i.imgur.com/ALmsvry.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>

<p>
3. Select the "64-bit edition EXE" and open the download.
</p>
<p>
<img src="https://i.imgur.com/vWK5nbF.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>

<p>
4. Select the "Download Media" option.
<p>
<img src="https://i.imgur.com/zSOb7ZI.jpeg" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>

<p>
5. Download the ISO version to the Desktop of the Windows VM. Once downloaded, open the folder.
</p>
<p>
<img src="https://i.imgur.com/FAKDVvR.jpeg" height="40%" width="40%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/v55u2n9.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>

<p>
6. Right-click the icon and select "Mount."
</p>
<p>
<img src="https://i.imgur.com/tSgXqL3.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>

<p>
7. Select Setup from the list.
</p>
<p>
<img src="https://i.imgur.com/o7gwKUB.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>

<p>
8. Select Installation, then select "New SQL Server stand-alone installation or add features to an existing installation."
</p>
<p>
<img src="https://i.imgur.com/JJ1Tcyj.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>


<p>
9. On the next screen, leave the free edition as an Evaluation and click Next.
</p>
<p>
<img src="https://i.imgur.com/6CBgssU.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>


<p>
10. Check the box to accept the license and terms, and click Next. Then click Next on the next screen.
</p>
<p>
<img src="https://i.imgur.com/nEAU8Vl.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/Lik9hK6.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>

<p>
11. Under Instance Features, check the box for Database Engine Services, then click Next.
</p>
<p>
<img src="https://i.imgur.com/LX3PTBm.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>

<p>
12. Click Next through the following 2 screens.
</p>
<p>
<img src="https://i.imgur.com/XM3bqUE.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/PnrZsqj.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>

<p>
13. Select Mixed Mode, set a password, then select Add current user, and click Next.
</p>
<p>
<img src="https://i.imgur.com/wnigx0l.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/vSWpTvg.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>

<p>
14.
</p>
<p>
<img src="https://i.imgur.com/nEAU8Vl.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/Lik9hK6.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>


[Click here to return to the Security Project 1 Homepage](https://github.com/BryanEAtherton/Security-Project-1)
</p>





