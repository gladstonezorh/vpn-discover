# vpn-discover<p align="center">
<img src="https://imgur.com/pLHPMdJ.png" alt="VPN"/>
</p>

<h1>Observing and Understanding Virtual Private Networks</h1>
In this tutorial, we observe and understand a Virtual Private Network and how it helps to securely link two computers or networks. Also, this explores how different IP address are assigned under different computers. <br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- What Is My IP Address website
- Proton VPN

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>High-Level Steps</h2>

- Create Virtual Machine in Azure
- Remote Desktop to Virtual Machine
- Create login for Proton VPN
- Observe VPN connection in Proton VPN

<h2>Actions and Observations</h2>

<h2>Create Virtual Machine in Azure</h2>

<p>
<img src="https://imgur.com/31xtyEZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Login to Microsoft Azure to create a Virtual Machine. Search for "Virtual Machine" in Azure, select "Create and "Azure Virtual Machine". Next, "Create a Resource Group" and add the virtual machine name, region, image (operating system), and size of the virtual machine. Next, open a browser to whatismyipaddress.com and take note of the IP address.
</p>
<br />
<h2>Remote Desktop to Virtual Machine</h2>
<p>
<img src="https://imgur.com/GpBqUcv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, login remotely to the virtual machine using "Remote Desktop Connection". Toggle back to Azure: Search for "Virtual Machine", select the Virtual Machine that was created, copy the Public IP address and paste into the remote desktop "Computer" text box to login.
</p>
<br />
<h2>Remote Desktop to Virtual Machine Contined</h2>
<p>
<img src="https://imgur.com/LziFGOW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Ensure that all privacy settings are turned off, open a web browser in the virtual machine, and toggle to "WhatIsMyIPAddress.com" to collect the IP address for the Virtual Machine.
</p>
<br />
<h2>Download and Install Proton VPN</h2>
<p>
<img src="https://imgur.com/upsJ48z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Open a web browser and search for "Proton VPN".
</p>
<br />
<h2>Download and Install Proton VPN Continued</h2>
<p>
<img src="https://imgur.com/J2QrGLL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Select "Download Proton VPN" and follow the steps for the Setup Wizard Configuration. Once completed, open Proton VPN.
</p>
<br />
<h2>Create login for Proton VPN</h2>
<p>
<img src="https://imgur.com/I2yfDY0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Select "Create Account" and follow steps to setup login credentials for Proton VPN. Once you have created your account, login to Proton VPN.
</p>
<br />
<h2>Observe VPN connection in Proton VPN</h2>
<p>
<img src="https://imgur.com/M1PL8oX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once you have logged in, connect to a VPN in another country. Choose the country of your choice and select "Connect". Next, navigate to whatismyipaddress.com to see the IP address of the VPN and compare the results. After navigating to the web browser, you should see the region that you are connected to on the VPN.
</p>
<br />
<h2>Observe VPN connection in Proton VPN Continued</h2>
<p>
<img src="https://imgur.com/xVDoIAo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After reviewing the IP address and region for the VPN connection, try to browse a website and observe the location and differences of the site based on the VPN server connection (ie. language, URL, and website content). In this tutorial, we can review that the region in located in the Netherlands. After completing the lab, make sure that you delete your resource group in Azure!
Done
</p>
<br />
