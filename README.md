<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Installation Steps</h2>

![prereq 1](https://github.com/user-attachments/assets/b94564a8-011d-4d80-9845-01af82f3b34c)
  
<p>
I created a Windows 10 Virtual Machine on Microsoft Azure & placed it inside of the Resource Group that I also created.
</p>
<br />

![prereq 1](https://github.com/user-attachments/assets/b94564a8-011d-4d80-9845-01af82f3b34c)
  
<p>
On my Virtual Machine I then downloaded Osticket-Installation-Files.Zip & Installed/Enabled IIS (Information Internet Services) in Windows.
</p>
<br />

![prereq 1](https://github.com/user-attachments/assets/b94564a8-011d-4d80-9845-01af82f3b34c)
  
<p>
I then installed the database & foundation for osTicket to be ran properly. PHP Manager for IIS, the Rewrite Module, VC_redist.x86.exe, & MySQL 5.5.62 were the 4 installations needed to begin. 
</p>
<br />

![prereq 1](https://github.com/user-attachments/assets/b94564a8-011d-4d80-9845-01af82f3b34c)
  
<p>
I continued the installation process by enabling 3 extensions on the PHP Manager in IIS & assigning permissions for ost-config
<p>
<br />

![pre req 5](https://github.com/user-attachments/assets/8df983d7-dc8f-429d-abb2-23a4639f302f)
  
<p>
Lastly, I successfully installed osTicket & Heidi SQL to execute the data per sessions from my own helpdesk.
<p>
<br />
