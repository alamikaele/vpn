# Vitual Private Network (VPN)
<p align="center">
<img src="https://i.imgur.com/hFhqVwg.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h1>VPN - Prerequisites and Installation</h1>
This tutorial guides you on the installation and use of a virtual private network (VPN).<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- A VPN (Proton VPN)
- Internet Information Services (IIS)
- Remote Desktop


<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Summary of Steps</h2>

- Find IP address
- Azure Virtual Machine Creation
- Login to Virtual Machine
- Find Virtual Machine IP 
- Install ProtonVPN Server
- Find IP address for Proton VPN Server
Note: We are going to be looking at the IPv4 not IPv6.


<h2>Lab Installation Steps</h2>



<h3 align="center"> Find IP address </h3>

<p align="center">
Go to https://whatismyipaddress.com/ on your actual computer and find your IP address and take note of it (preferably in a notepad/textedit (plain text file).
</p>
<br/>
<p>
<img src="https://i.imgur.com/3XjWfdT.png" height="75%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<br/>

<h3 align="center"> Azure Virtual Machine Creation </h3>

<p align="center">
Head to Microsoft Azure and Add a Virtual Machine. Image: windows 10 pro. Size: 2 vcpus. Press Review and Create
</p>
<br/>
<p>
<img src="https://i.imgur.com/0NZNyOY.png" height="75%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<br/>

<h3 align="center"> Login to Virtual Machine </h3>

<p align="center">
Get public ip address in microsoft azure and setup virtual machine through remote directory (windows app for MacOs users).
</p>
<br/>
<p>
<img src="https://i.imgur.com/4tSKQkj.png" height="75%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<br/>

<p align="center">
setup virtual machine through remote directory (windows app for MacOs users).
</p>
<br/>
<p>
<img src="https://i.imgur.com/hapXpBM.png" height="75%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<br/>

<h3 align="center"> Find Virtual Machine IP  </h3>

<p align="center">
Head to https://whatismyipaddress.com/ and take note of the IP address and other contents in a notepad txt file (in the virtual machine)
</p>
<br/>
<p>
<img src="https://i.imgur.com/u3IJ5xU.png" height="75%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<br/>

<h3 align="center">Install ProtonVPN Server</h3>

<p align="center">
On your actual computer sign up for free version of Proton VPN: https://account.protonvpn.com/signup?plan=free&language=en. Enter into your virtual machine > downloads tab > download for Windows
</p>
<br/>
<p>
<img src="https://i.imgur.com/u3IJ5xU.png" height="75%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<br/>

<p align="center">
Connect to the vpn by signing in to proton vpn through the downloaded application. Press quick connect and you are now connected to a virtual private network!
</p>
<br/>
<p>
<img src="https://i.imgur.com/6PsLuT9.png" height="75%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<br/>

<h3 align="center">Find IP address for Proton VPN Server</h3>

<p align="center">
Head to https://whatismyipaddress.com/ and note the IPv4 address and its contents. Notice how it is now different than the virtual machines actual address.
</p>
<br/>
<p>
<img src="https://i.imgur.com/BxF0Pw9.png" height="75%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<br/>

<p align="center">
You can go to other sites as well and note (if you're vpn connection is to a server outside your country) that the tabs, etc are in a different language.
</p>
<br/>
<p>
<img src="https://i.imgur.com/FfV8mV8.png" height="75%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<br/>

<p align="center">
In order to save money delete the resource group created earlier in Microsoft Azure and make sure that all contents within it has been deleted as well.
</p>
<br/>
<p>
<img src="https://i.imgur.com/98N9OHW.png" height="75%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<br/>

<p> This tutorial walked through setting up a VPN using Microsoft Azure and Proton VPN. We recorded our actual computer's IP address, created a virtual machine (VM) in Azure, and logged in via Remote Desktop. After noting the VM's IP, we installed and connected to Proton VPN, observing the IP change. This demonstrated how VPNs mask original locations and ISPs. Finally, we deleted the Azure resource group to avoid charges.
IP Address Notes:

- Actual Computer: IPv4: 108.75.133.226 (AT&T Enterprises LLC, San Diego, California, United States)
- Virtual Machine: IPv4: 40.76.125.90 (Microsoft Corporation, Washington, Virginia, United States)
- ProtonVPN Connection: IPv4: 138.199.21.202 (DataCamp Limited, Tokyo, Japan)
</p>

END OF TUTORIAL
