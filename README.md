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

Create a Resource Group in Azure.
Create a Virtual Machine in Azure, ensuring that the Resource Group and VM are in the same region (e.g. US-east-4).
Remote Desktop into the Virtual Machine using the PC's Remote Desktop or Mac's Microsoft Remote Desktop App.
Login to the virtual server and install and enable IIS (Internet Information Services), which is a webserver that allows the computer to serve up websites.

<p>
<img src="https://i.imgur.com/NmXuuBq.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/i7YMkRV.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
</p>
Next, open the Virtual Machine using Remote Desktop, and use the IP address of the Azure Virtual Machine to log in.

<p>
<img src="https://i.imgur.com/26ne9dR.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/yGSSlj8.png" height="30%" width="40%" alt="Disk Sanitization Steps"/>
</p>
After that, configure and install IIS and PHP. IIS is a web server that allows the computer to serve up websites, and PHP is a backend web programming language that osTicket needs to run on.

<img src="https://i.imgur.com/tmTZAFR.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
Now, create a directory for PHP in the C drive so that when you download the installation files, you can unzip them into the PHP folder.

<img src="https://i.imgur.com/gmd7MlW.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
Next, install MySQL server, which is a database that is installed on the computer and stores osTicket data, such as the users, tickets, etc.

<img src="https://i.imgur.com/VSVk1Uy.png" width="40%" alt="Disk Sanitization Steps"/>
After that, open IIS and run it as an administrator to register PHP and begin the osTicket installation.

<img src="https://i.imgur.com/vzhfvYj.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/M2Udsi7.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
Download the osTicket installation files from the PHP folder.

<img src="https://i.imgur.com/vYUXXb3.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/bhmibCP.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/VlNrmn3.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
Finally, set up HeidiSQL, which is a database client that connects to the MySQL server and lets you interact with it. Use the Heidi Session Manager to set up a new connection to the database. Create an osTicket database to connect to the server, and the osTicket database will be up and running.

<img src="https://i.imgur.com/SMTxkYP.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/2JBDDF0.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
<img src="https


