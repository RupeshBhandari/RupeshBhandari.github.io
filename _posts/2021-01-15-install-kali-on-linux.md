---
title:  "Step by step guide – How to install Kali Linux on VMware"
author: Rupesh Bhandari
date:   2021-01-15 16:15:00 +0545
categories: [LINUX, KALI, VMWARE, TUTORIAL] 
Tags: [Kali Linux, VMWARE] 
---

In this post, I will show you how to install the latest version of [Kali Linux (2021.1)](https://www.kali.org/blog/kali-linux-2021-1-release/) on [VMware Workstation 16 Pro](https://en.wikipedia.org/wiki/VMware_Workstation). This will allow you to have a Kali virtual machine as a guest operating system on your host machine. This way of using Kali is very effective and used by a lot of people. 

Kali was built and is maintained by [Offensive Security](https://www.offensive-security.com/), it has hundreds of tools available for security auditing, penetration testing and ethical hacking. Below are the steps for installing Kali Linux: –

1. Download the iso file for Kali Linux
Go to the [official Kali Linux website](https://www.kali.org/downloads/) and browse to the downloads section. From the download page, download the 64-bit or 32-bit installer based upon your system configuration.

    ![Step 1](/assets/img/kalionvm/1.jpg)

2. Open VMware Workstation and click on “Create a New Virtual Machine”
In VMware, click on File -> New Virtual Machine or click on Create a New Virtual Machine from Home. This will open the “New Virtual Machine Wizard”.

    ![Step 2](/assets/img/kalionvm/2.png)

3. “New Virtual Machine Wizard” dialogue box opens
The configuration wizard will have two options. “Typical” is for creating a virtual machine with default settings. “Custom” is for advanced options like [SCSI controller](https://en.wikipedia.org/wiki/SCSI) type, virtual disk type, etc. We will choose the default i.e. “Typical” configuration.

    ![Step 3](/assets/img/kalionvm/3.png)

4. Select the installation source
Browse to the downloaded iso file on your system and click Next. VMware usually detects the operating system in the disc image (iso file), but not with Kali Linux. So, ignore the warning and proceed further.

    ![Step 4](/assets/img/kalionvm/4.png)

5. Select the guest operating system
Select Linux as the guest operating system. Choose [Debian](https://www.debian.org/) 9.x 64-bit or 32-bit based on your system configuration and click Next. 

    ![Step 5](/assets/img/kalionvm/5.png)

6. Virtual machine name and location
Enter a name for your virtual machine. You can choose the default location which will be Documents\Virtual Machines or you can choose any other location. 

    ![Step 6](/assets/img/kalionvm/6.png)

7. Specify Disk Capacity
The maximum disk size is the maximum space that your virtual machine can utilize after it is created. You can choose the recommended size of 20 GB if your requirements are not much. Otherwise, you can increase the size if you plan on installing heavy software on your virtual machine. This has to be done based upon your system’s configuration. 

You can store the virtual disk as a single file on your computer or split it into multiple files. The flexibility to move your virtual machine from one computer to another will be better with the second option. The performance will be reduced though will larger disk files. 

    ![Step 7](/assets/img/kalionvm/7.png)

8. Ready to Create Virtual Machine
The dialogue box will show the virtual machine settings that you chose in the previous steps. You can proceed with these settings and click Finish, or you can choose to Customize Hardware. 

    ![Step 8.1](/assets/img/kalionvm/8.1.png)