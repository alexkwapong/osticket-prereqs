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

- Enable Internet Information Services
- Install Web Platform Installer
- Install C++ Redistributable
- Configure Permissions
- Install osTicket

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Install/Enable Internet "Internet Information Services" (IIS) in windows: control panel --> programs --> Turn Windows features on or off --> check box titled "Internet Information Services". IIS is a windows server in which OsTicket requires to be enabled in order to run properly, even though OsTicket runs through the web browser.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Search the internet for the installation files you will need to insatll. Find and install: "Web Platform Installer" & open "Web Platform Installer". Search Web Platform Installer to add "MySQL 5.5" & search to add all simple versions of PHP (x86) up until 7.3. "Create username" and "password" when asked to finish installation. Web installer will attempt to finish installing all of the prerequistes that are checked (some of the downloads will fail, just manually download C++ redistribuable & PHP Manager via files found online). Continue to finish with installation. Find and install "PHP Manager" version 7.3.8 & version 1.5.0.</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Search the internet for "osTicket-v1.15.8" and download it. Next, copy the "upload folder" from inside the OsTicket installation files to "c:\inetpub\wwwroot". Within c:\inetput\wwwroot folder --> rename "upload folder" to "OsTicket" --> Open IIS--> osTicket--> Browse*80 --> restart IIS

</p>
<br />
