<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- 1. Resource Group & Virtual Machine
- 2. Remote Desktop
- 3. Osticket-Installation-Files.Zip
- 4. IIS (Information Internet Services)
- 5. PHP Manager for IIS, ost-config, & Heidi SQL

<h2>Installation Steps</h2>

![prereq 1](https://github.com/user-attachments/assets/b94564a8-011d-4d80-9845-01af82f3b34c)
  
<p>
I created a Windows 10 Virtual Machine on Microsoft Azure & placed it inside of the Resource Group that I also created for setting up OsTicket.
</p>
<br />

![pre req 2](https://github.com/user-attachments/assets/ba6e0cf8-90ca-44d3-a02f-64c717147748)

<p>
On my Virtual Machine I then downloaded Osticket-Installation-Files.Zip & Installed/Enabled IIS (Information Internet Services) in Windows.
</p>
<br />

![cgi](https://github.com/user-attachments/assets/9c1ba6db-fd7e-4547-b0ae-745bf8bf34cd)
  
<p>
I Installed & Enabled IIS in Windows WITH CGI in the 'World Wide Web Services' & 'Application Development Features' section.
</p>
<br />

![P](https://github.com/user-attachments/assets/8861ebae-3f60-4c4f-ad09-ba912c45b540)

<p>
From the “osTicket-Installation-Files” folder, I installed PHP Manager for IIS (PHPManagerForIIS_V1.5.0.msi)
</p>
<br />

![iis](https://github.com/user-attachments/assets/455d9405-d422-46b1-a1d3-c84729c15d7e)

<p>
From the “osTicket-Installation-Files” folder I installed the Rewrite Module (rewrite_amd64_en-US.msi)
</p>
<br />

![pre req3](https://github.com/user-attachments/assets/66141dd5-490a-43af-9f0d-6733261067f7)
  
<p>
I installed MySQL 5.5.62 (mysql-5.5.62-win32.msi) Typical Setup -> Launch Configuration Wizard (after install) -> Standard Configuration -> Username & Password
</p>
<br />

![Screenshot 2025-09-10 at 5 14 05 PM](https://github.com/user-attachments/assets/95d3ee63-97e7-483d-83d4-3c060cc0062f)

<p>
In IIS, PHP Manager, I Enabled the extensions.. php_imap.dll, php_intl.dll, & php_opcache.dll

</p>
<br />

![ost config](https://github.com/user-attachments/assets/57117d2f-c21e-467c-8da5-62af563d4087)

<p>
From: C:\inetpub\wwwroot\osTicket\include\ost-sampleconfig.php To: C:\inetpub\wwwroot\osTicket\include\ost-config.php, I Assigned Permissions: ost-config.php then disabled inheritance -> Remove All, New Permissions -> Everyone -> All. 
</p>
<br />

![heide](https://github.com/user-attachments/assets/78ad084e-dadb-42e7-bcd6-58884d26a638)

<p>
From the “osTicket-Installation-Files” folder, I installed HeidiSQL. Created & Connected a new session called “osTicket”
</p>
<br />

![installer](https://github.com/user-attachments/assets/6533421f-163c-44e9-98db-92d93b43cfea)

<p>
I continued setting up & naming my osTicket Helpdesk in the browser, Inputting the MySQL Database, Username, Password & All Osticket Admin Information. 
<p>
<br />

![pre req 5](https://github.com/user-attachments/assets/8df983d7-dc8f-429d-abb2-23a4639f302f)
  
<p>
I successfully installed osTicket & Heidi SQL was connected to execute the data per sessions from my own helpdesk.
<p>
<br />

<img width="1440" height="900" alt="final" src="https://github.com/user-attachments/assets/5877ef0d-2f7b-4dc9-9bc1-c4b3d640c4ea" />
  
<p>
I created a Windows 10 Virtual Machine on Microsoft Azure & placed it inside of the Resource Group that I also created.
</p>
<br />
