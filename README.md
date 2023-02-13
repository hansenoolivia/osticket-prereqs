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

- Install / Enable IIS in Windowns with CGI 
- Install PHP Manager for IIS 
- 
- 

<h2>Installation Steps</h2>
- Installing and Enabling Information Internet Services on Windows with CGI
 
<p>
<img src="https://i.imgur.com/y6SuxGq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
IIS: Internet Information Services - Web server that allows this computer to serve up websites. 

Right click start menu, click run, type control for control panel, under programs, click turn windows features on / off,
click and expand Information Internet Services, expand world wide web services, expand application development features, click CGI (CGI lets us install PHP Manager), 
Install.

Test web sever: Type 127.0.0.1 into URL search bar, it should load IIS Default Website. 
</p>
<br />

-From the Installation Files, download and install PHP Manager for IIS (PHPManagerForIIS_V1.5.0.msi)
<p>
<img src="https://i.imgur.com/G9lgwnZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download PHP from installation files to computer, open downloads folder and double click to install, hit next, I agree, close app. Next we will download and install the Rewrite Module.
</p>
<br />

-From the Installation Files, download and install the Rewrite Module (rewrite_amd64_en-US.msi)
<p>
<img src="https://i.imgur.com/AX4ClvR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download Rewrite Module, open downloads folder, double click to install, finish. 
</p>
<br />

</p>
<br />


<p>
<img src="https://i.imgur.com/AX4ClvR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 
</p>
<br />
