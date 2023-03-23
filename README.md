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

-   Microsoft Azure 
-   osTicket installation file
-   Heidi SQL
-   PhP Manager for IIS
-   MySQL Server

<h2>Installation Steps</h2>

Create Resource Group in Azure
Create Virtual Machine in Azure ( make sure the Resource Group & VM are in the same Region ex: US-east-4)
Remote Desktop into Virtual Machine (PC:Remote Desktop / Mac:Microsoft Rempte Desktop App)
login to virtual server and install and enable IIS (Internet information services its a webserver that allows the computer to serve up websites)


<img src="https://i.imgur.com/NmXuuBq.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/i7YMkRV.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>



Next we will open our Virtual Machine using Remote Desktop and using the IP address of our Azure Virtual Machine to log in.
<img src="https://i.imgur.com/26ne9dR.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/YSicZpU.png" height="30%" width="40%" alt="Disk Sanitization Steps"/>


Next we are going to configure and install IIS and PHP. IIS (Internet Information Services) which is a web server that allows this computer to serve up websites because osTicket runs out of a website, and PHP is backend web programming language that osTicket needs to run on
</p>
<img src="https://i.imgur.com/kubyFW1.png"40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
<img src="https://i.imgur.com/kTzj77h.png="40%" width="40%" alt="Disk Sanitization Steps"/>

</p> Now im going to create a directory fro PHP in the C drive for when I download the installtion files I can unzip it into the PHP folder
<img src="https://i.imgur.com/gmd7MlW.png"40%" width="40%" alt="Disk Sanitization Steps"/>

</p> Now its time to install MySQl server which is database thats installed on the computer and stores osTicket data such as the users,tickets,etc
<img src="https://i.imgur.com/eZIKuuw.png" width="40%" alt="Disk Sanitization Steps"/>

</p> Now im going to open IIS and run as administrator to register PHP and begin the osTicket installation
<img src="https://i.imgur.com/V2tq2Q1.png"40%" width="40%" alt="Disk Sanitization Steps"/>

</p>
<img src="https://i.imgur.com/M2Udsi7.png" width="40%" alt="Disk Sanitization Steps"/>
</p> Downloading osTicket from installation files from PHP folder
<img src="https://i.imgur.com/vYUXXb3.png" width="40%" alt="Disk Sanitization Steps"/>
</p>
<img src="https://i.imgur.com/oXbSe4V.png" width="40%" alt="Disk Sanitization Steps"/>
</p>
<img src="https://i.imgur.com/GxGBOI4.png" width="40%" alt="Disk Sanitization Steps"/>

</p> Now im going to setup HediSQL which is a database client which connects to the MySQL server and lets you interact with it.
<img src="https://i.imgur.com/MFybykW.png"40%" width="40%" alt="Disk Sanitization Steps"/>
</p>Heidi Session manager is gonna allow me set up a new connection to the database
<img src="https://i.imgur.com/1J5RAwc.png"40%" width="40%" alt="Disk Sanitization Steps"/>

</p> Now im going to create an osTicket database to connect to the server
<img src="https://i.imgur.com/ADm5vB9.png"40%" width="40%" alt="Disk Sanitization Steps"/>

</p> The osTicket database is connected to the server and is up and running
<img src="https://i.imgur.com/IEK9Lwv.png"40%" width="40%" alt="Disk Sanitization Steps"/>




