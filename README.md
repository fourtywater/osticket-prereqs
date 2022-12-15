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

- Add MySQL 5.5
- Add all simple versions of x86 PHP up to v7.3
- Install osTicket v1.15.8
- Reload IIS (open IIS, Stop and Start the server) 
- Enable extensions in IIS
- Refresh the osTicket site in your browser and observe the changes

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/zHQ3ykz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 1
  Install or enable IIS by opening the control panel. IIS will will enable a web server on your computer to run osTicket from the web. You can do this by typing "control panel" from your search bar within your task bar at the bottom of your desktop. 
</p>
<br />
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go to Programs and select uninstall program. 
</p>
<br />
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once you on the uninstall or change a program screen. Select Turn Windows features on or off on the right. 
</p>
<br />
<p>
<img src="https://imgur.com/a/FhIR7G5" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Select the Internet Information Services radio button in the dialog box. 
</p>
<br />
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once IIS has been installed 
</p>
<br />
<p>
<img src="https://i.imgur.com/THXv7zF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />
<p>
<img src="https://i.imgur.com/X7Fu35v.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Search the web and install: "Web Platform Installer" & open "Web Platform Installer". In the dialog box, search Web Platform Installer to add "MySQL 5.5" & search to add all simple versions of (x86) PHP up until 7.3. 
</p>
<br />
<p>
<img src="https://i.imgur.com/gWpbvb3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create a username and password when asked to finish installation. 
</p>
<br />
<p>
<img src="https://i.imgur.com/HTBMgNO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Web installer will attempt to finish installing all of the prerequistes that are checked (some of the downloads will fail, just manually download C++ redistribuable & PHP Manager via files found online). Continue to finish with installation. Find and install "PHP Manager" version 7.3.8 & version 1.5.0.
</p>
<br />
<p>
<img src="https://i.imgur.com/Pkh9Y3s.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Install Microsoft Visual C++ 
</p>
<br />
<p>
<img src="https://i.imgur.com/xcIWPE5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Install PHP Manager
</p>
<br />
<p>
<img src="https://i.imgur.com/eqFSUiY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Installation errors should be fixed at this point.  Download and install the osTicket software.  You will need to extract the zip file once downloaded. 
</p>
<br />
<p>
<img src="https://i.imgur.com/UPXpiYv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once osTicket has been installed, open the download folder and copy it into your wwroot folder that was created from IIS and rename the folder from upload to osTicket. 
</p>
<br />
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
