# EX 3 (A-B) Virtualization: Installation and configuration of Oracle VirtualBox & Kali Linux, and execution of Linux commands

## NAME : KEERTHIVASAN S
## REG NO : 212223220046

## Aim:
This focuses on setting up a virtualized environment using Oracle VirtualBox, followed by the installation of Kali Linux as a guest operating system. It also covers the execution of fundamental Linux commands, enabling learners to interact with the system via the command line interface. 

## Procedure:

a.	Installation and configuration of Oracle VirtualBox on the host system
b.	Downloading and setting up Kali Linux within the virtual machine
c.	Execution of essential Linux commands 

# 3.A) Installation and configuration of Oracle VirtualBox

## Aim: 
To install and configure Oracle VM VirtualBox on your system.

## Pre-requisites:
1. Access to a machine with internet connectivity.
2. Minimum of 4 GB RAM (recommended for running virtual machines smoothly).
3. Sufficient storage space to host virtual machines.

## Steps:
1. Download Oracle VM VirtualBox.
2. Navigate to the Official Website.
3. Go to Oracle VM VirtualBox official website.
4. Download the installer.
5. On the homepage, click on Download VirtualBox.
6. Select the version for your operating system (Windows, macOS, Linux, Solaris).
7. For Windows, download the Windows Hosts executable.
8. For macOS, download the OS X Hosts file.
9. For Linux, download the relevant package for your distribution (Debian, Ubuntu, Fedora, etc.).
10. Install Oracle VM VirtualBox (Windows example):

### Step 1: Launch Installer
1. Double-click the downloaded installer file to begin.
2. The installer will prompt you to allow changes to your device; click Yes.

### Step 2: VirtualBox Setup Wizard:
The VirtualBox Setup Wizard will open. Click Next to proceed.

### Step 3: Select Installation Options:
1. Choose the default installation settings unless you need specific configurations.
2. Check or uncheck additional components such as networking features or shortcut creation.

### Step 4: Network Interface Warning:
A prompt may inform you that the network connection will be temporarily interrupted during installation. Click Yes to proceed.

### Step 5: Install VirtualBox:
1. Click Install to begin the installation.
2. Wait for the process to complete.

### Step 6: Complete Installation:
1. Once the installation finishes, click Finish.
2. You will be prompted to launch VirtualBox after installation if the checkbox is checked.
3. Configure VirtualBox
4. Launch Oracle VM VirtualBox
5. Open the application from the start menu or desktop shortcut.
6. Create a Virtual Machine
7. Click New to create a virtual machine.
8. Give the machine a name, choose the type (Linux, Windows, etc.), and the version of the operating system you want to install.
9. Allocate Resources
10. Assign the virtual machine the required resources, including:
11. Memory (RAM): Allocate at least 2 GB for Linux or 4 GB for Windows machines.
12. Virtual Hard Disk: Create a new virtual hard disk or use an existing one. Recommended size is at least 20 GB.
13. Start Virtual Machine.
14. After creating the virtual machine, you will need to provide an ISO image of the operating system to install.
15. Click Start and then select your OS installer ISO.
16. Follow the prompts in the virtual machine to install the operating system.

### Result :
Thus, the Oracle VM Virtual Box was installed successfully.

# 3.B) Installation and configuration of Kali Linux

## Aim:
To install and configure Kali Linux in Oracle VM VirtualBox.

## Pre-requisites:
1. A system with Oracle VM VirtualBox installed.
2. At least 4 GB RAM and 20 GB free disk space.
3. Kali Linux ISO image, which can be downloaded from the official website.

## Step-by-Step Installation Guide:

### Step 1: Download Kali Linux ISO
1. Go to the Kali Linux download page.
2. Download the Kali Linux ISO file.
3. Choose between 32-bit or 64-bit depending on your system (most systems are 64-bit).
4. Download the Installer version for a full installation.

### Step 2: Open Oracle VM VirtualBox
Launch VirtualBox on your computer.

### Step 3: Create a New Virtual Machine
1. In VirtualBox, click on the New button to create a new virtual machine.
2. Name and Type Settings:
3. Name: Give a name like "Kali Linux".
4. Type: Select Linux.
5. Version: Select Debian (64-bit) or Debian (32-bit) depending on the ISO version you downloaded.
6. Click Next to proceed.

### Step 4: Allocate Memory (RAM)
1. Choose how much RAM to allocate to your virtual machine.
2. Recommended: At least 2 GB (2048 MB) for Kali Linux, or 4 GB if possible.
3. Click Next.

### Step 5: Create a Virtual Hard Disk
1. Select Create a virtual hard disk now.
2. Click Create.

### Step 6: Select Hard Disk File Type
1. Choose VDI (VirtualBox Disk Image).
2. Click Next.

### Step 7: Storage on Physical Hard Disk
1. Select Dynamically allocated (so the disk will grow as needed).
2. Click Next.

### Step 8: Allocate Storage Space
1. Set the hard disk size. Kali Linux requires at least 20 GB of storage.
2. You can increase this if you plan to install many additional tools later.
3.	Click Create.

### Step 9: Configure Kali Linux ISO
1. Select the VM from the list in VirtualBox and click Settings.
2. Navigate to Storage from the side menu.
3. Under Controller: IDE, click the Empty CD icon.
4. On the right, click the CD icon next to Optical Drive and choose Choose a disk file.
5. Locate and select the Kali Linux ISO you downloaded.
6.	Click OK.

### Step 10: Start the Virtual Machine
In VirtualBox, click Start to boot up your Kali Linux virtual machine.

### Step 11: Begin Kali Linux Installation
The VM will now boot from the ISO. You’ll see a boot menu. Select Graphical Install and press Enter.

### Step 12: Select Language and Region
1.	Choose your language, location, and keyboard layout.
2.	These can be configured to your preference.
3.	Click Continue after each selection.

### Step 13: Configure the Network
1.	You’ll be prompted to configure the network.
2.	Enter a hostname for your system (e.g., kali).
3.	You can leave the domain name empty if you don’t need to set up a domain.

### Step 14: Set Up Users and Passwords
1.	Create a root password for the administrator account.
2.	Choose a strong password and re-enter it for confirmation.

### Step 15: Partition Disks
1.	Choose Guided - use entire disk for simplicity (recommended for beginners).
2.	Select the virtual disk you created earlier.
3.	Choose All files in one partition.
4.	Finish partitioning and confirm to write the changes to disk.

### Step 16: Install the System
The installer will now copy files and install Kali Linux. This may take several minutes.

### Step 17: Install GRUB Bootloader
1. When prompted to install the GRUB bootloader, choose Yes.
2.	Select the virtual hard disk as the location to install GRUB.

### Step 18: Complete Installation
After the installation is complete, click Continue to reboot the virtual machine.

### Step 19: Login to Kali Linux
1.	Once the machine reboots, you’ll be presented with a login screen.
2.	Log in using the root account and the password you set earlier.

### Optional: Install Guest Additions
1.	Guest Additions enhance performance by providing better screen resolution and seamless mouse integration.
2.	To install them:
•	Go to Devices in the VirtualBox menu.
•	Select Insert Guest Additions CD Image and follow the installation steps inside Kali Linux.

### Output:

### Snapshot 1 - Installing Oracle VirtualBox 

![ex3op1](https://github.com/user-attachments/assets/103fd622-fbe5-44ad-abe5-fe90580fcca0)

### Snapshot 2 - Adding Kali (Guest OS) on Oracle VirtualBox

![ex3op2](https://github.com/user-attachments/assets/7b033b72-70f2-4b8f-b1c3-5d0b1d3c4cdc)

### Snapshot 3 - Kali - The guest OS on Oracle Virtualbox

![ex3op3](https://github.com/user-attachments/assets/42c49bca-bfad-4c3d-aeba-29d7859efb9f)

## Result:
Thus, the guest OS Kali Linux was installed and configured successfully.
