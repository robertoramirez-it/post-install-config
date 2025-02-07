<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This project outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Steps</h2>

<p>
We will use a VM setting for this project enabling IIS & CGI - needed to run osTicket.  
</p>

![vm](https://github.com/user-attachments/assets/09e60e6a-2e4f-4221-a9fb-51df56f15bd2)
![iis and cgi](https://github.com/user-attachments/assets/78694e85-f1bd-461a-92fa-67307a0948b9)


<p>
We need a web server with PHP 7.2+ and a MySQL or MariaDB database. We also need specific PHP extensions like IMAP and GD for features like email handling and image management. Ensuring the server has appropriate file permissions and an email server setup for ticket notifications.
</p>

![osticket install](https://github.com/user-attachments/assets/532372eb-a88a-40a9-97e6-88a6a6740f76)
![osticket and php extensions](https://github.com/user-attachments/assets/a666bab9-1691-4fb0-8dc3-133081db519d)
![osticket installer](https://github.com/user-attachments/assets/9b1f1604-ff4b-4ac0-81bc-04fbaaa06e9e)
![database setup](https://github.com/user-attachments/assets/4fc1426b-0163-4434-99a2-50c9706b5405)

<p>
We verify the installation is successful, moving on to configure osTicket to our intended SLA and Help Topics.
</p>

![install complete](https://github.com/user-attachments/assets/2a8723fa-a751-4d80-85c5-3f1a4c5f6a00)
![install  verified](https://github.com/user-attachments/assets/bf66210d-0b0b-4f5e-a8de-1d8ed42984c2)
![SLAs](https://github.com/user-attachments/assets/b2118e0a-c171-4cba-a93c-2c2ba0978a4b)
![help topics](https://github.com/user-attachments/assets/7974196a-4027-420a-899d-bb19bab00366)

