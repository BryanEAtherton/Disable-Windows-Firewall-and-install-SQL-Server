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

 

<h2> DIsable Windows Firewall Protections </h2>


<br />

<p>
1.  Here we can see a failed Ping attempt on the Windows VM because the Firewall protections are active. 
</p>
<img src="https://i.imgur.com/3aQPBRc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>


<p>
2. RDP into the Windows VM, open Windows Defender Firewall, and select WIndows Defender Firewall Properties. 
</p>
<p>
<img src="https://i.imgur.com/UZYoWJY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

[Click here to view instructions on how to create an Azure VM and access it using Remote Desktop](https://github.com/BryanEAtherton/Azure-Virtual-Machine)

<br />


<p>
 3. Create a new rule to allow all traffic into the VM.
</p>
<p>
<img src="https://i.imgur.com/3NPTV98.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/8iTnSg6.png" height="50%" width="40%" alt="Disk Sanitization Steps"/>
</p>

<p>   
4. Repeat the process in step 2 for the Windows VM by deleting the RDP inbound rule.
<p>
<img src="https://i.imgur.com/vYFfEl4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
5. Repeat step 3 for the Windows VM and create a new rule to allow all traffic into the VM.
<p>
<img src="https://i.imgur.com/EoHjiaZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>

[Click here to return to the Security Project 1 Homepage](https://github.com/BryanEAtherton/Security-Project-1)
</p>





