![Logo](https://github.com/user-attachments/assets/8f4c9483-8df2-4a66-898a-2d48c6f67c55)
# osTicket
In this lab, I installed and configured osTicket on a Microsoft Azure Virtual Machine and gained real-world experience with the ticketing software.

## Technologies and Tools Used
- Microsoft Azure (Virtual Machine/Compute)
- Remote Desktop
- Windows 11 Pro
- osTicket
- Internet Information Services (IIS)
- PHP Manager
- IIS URL Rewrite Module 2
- MySQL
- IIS Manager

## Create Virtual Machine
Created the virtual machine in Microsoft Azure. I also created the resource name, the virtual machine's name, and the virtual machine's image. Additionally, I selected the size of the virtual machine, including the number of vCPUs and memory it will have. I left the other settings at their default or auto-create settings.
<img width="1280" alt="Create VM" src="https://github.com/user-attachments/assets/f919cb84-72fe-45fe-8643-e36741b73971" />

## Virtual Machine Setup for osTicket
I had to enable IIS and CGI in the Control Panel to set up the web server.
<img width="845" alt="IIS Enable" src="https://github.com/user-attachments/assets/5071c146-9d06-4790-942c-2dcb20e4a2f0" />

Installed PHP Manager for IIS.

<img width="391" alt="Install PHP Manager" src="https://github.com/user-attachments/assets/7456cce0-5fae-4508-a0a0-7ebc8f711673" />

Installed the IIS URL Rewrite Module 2 for IIS.

<img width="387" alt="Install Rewrite Module" src="https://github.com/user-attachments/assets/eef9e450-2365-443b-a271-ea52d0154b7b" />

Installed MySQL.

<img width="387" alt="MySQL Install" src="https://github.com/user-attachments/assets/a54d4568-9b48-4b34-b3c2-a13a0289b2a1" />

Configured MySQL.

<img width="375" alt="MySQL Config" src="https://github.com/user-attachments/assets/c5c479a0-d559-43db-a443-4e81f14c4120" />

Registered PHP from within the IIS Manager.
<img width="949" alt="PHP Register" src="https://github.com/user-attachments/assets/819d8b46-7ffb-4770-a949-eb8d2dd5ece1" />

## Download and Installation of osTicket
Opened the osTicker installer in the IIS Manager.
<img width="1280" height="764" alt="open osticket installer in iis" src="https://github.com/user-attachments/assets/e4c9de45-df2f-430a-b5bd-c182cbe980c5" />

Went into the IIS Manager and enabled the PHP extensions that are needed for osTicket, such as:
- 1
- 2
- 3
<img width="949" height="552" alt="enabled php extensions" src="https://github.com/user-attachments/assets/47885d70-1cb9-4ffe-824c-29dbd82003f7" />

Installed HeidiSQL setup wizard.

<img width="449" height="339" alt="installed HeidiSQL" src="https://github.com/user-attachments/assets/2a8a37b8-3f01-42da-bdeb-13b4713f9a8a" />

Filled in the basic information to set up osTicket.
<img width="1280" height="764" alt="osticket setup info" src="https://github.com/user-attachments/assets/3dd00030-6839-4cf8-a274-c45ed1652a12" />

Installed osTicket.
<img width="1280" height="764" alt="installed osticket" src="https://github.com/user-attachments/assets/b471585b-d623-4071-b4a8-7c55047149fc" />

## Configuration of osTicket
Created a Role.

Created a Team.

Created a Department.

Added Agent Jane.

Added Agent John.

Created User Karen.

Configured SLAs.
- 1
- 2
- 3

Configured Help Topics.
- 1
- 2
- 3
- 4
- 5
- 6

## Usage
