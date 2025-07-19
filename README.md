#  Installation of Ubuntu Linux on a Virtual Machine (VM)

## Introduction

This project demonstrates my practical ability to set up and configure a Linux operating system—Ubuntu—within a virtualized environment. The task involved downloading the appropriate ISO, setting up a Virtual Machine (VM) using Oracle VM VirtualBox, configuring system resources, and successfully installing and running Ubuntu OS. This project serves as foundational proof of my proficiency in system setup, virtualization, and Linux basics.

## Objectives

- To demonstrate the process of downloading and installing a Linux distribution (Ubuntu) on a virtual machine.
- To develop hands-on experience with virtualization software (Oracle VM VirtualBox).
- To understand and configure virtual hardware resources including RAM, storage, and networking.
- To verify successful installation and perform basic post-installation checks.

## Tools and Technologies Used

| Tool                       | Purpose                                     |
| -------------------------- | ------------------------------------------- |
| Ubuntu 22.04 LTS ISO       | Linux distribution to be installed          |
| Oracle VM VirtualBox       | Virtualization software                     |
| Host System: Windows 10    | Environment used to run VirtualBox          |
| Terminal                   | Used for post-installation commands         |

##  Project Approach

### 1. Downloaded and Installed a VirtualBox
-	Visited the VirtualBox official website https://www.virtualbox.org/wiki/Downloads
-	Selected the appropriate VirtualBox platform package (In my case, Windows) 
-	Clicked the host (Windows) and allow to download.
-	Double-clicked on the downloaded Oracle VirtualBox installation file and start the installation.
-	See step by step guide in the [Windows-11-Virtual-Homelab-Setup](https://github.com/Judeorabueze/Windows-11-Virtual-Homelab-Setup)

### 2. Downloaded Ubuntu ISO
- Visited the official Ubuntu website - https://ubuntu.com
- Clicked on <b>Download Ubuntu</b> and then <b>Download Ubuntu Desktop</b>.
  
![Ubuntu 1](https://github.com/Judeorabueze/Installation-of-Ubuntu-Linux-on-a-Virtual-Machine-VM-/blob/main/Ubuntu%201.PNG)

- Selected <b>Ubuntu 24.04.2 LTS</b> and clicked on <b>Download</b> to start the download.
  (The choice of Ubuntu ISO version was due to its long-term support - Five (5) years of free security and maintenance updates).

![Ubuntu 2](https://github.com/Judeorabueze/Installation-of-Ubuntu-Linux-on-a-Virtual-Machine-VM-/blob/main/image.png)

At the completion of the file download, the Ubuntu ISO file was saved to my desktop.

### 3. Installed and Configured VirtualBox
- Launched the already-installed Oracle VirtualBox.
- On the <b>Tools bar</b>, clicked <b>New</b>.
- In the <b>Create Virtual Machine</b> dialog box that appeared, I named my Ubuntu virtual machine <b>Ubuntu 1</b>.
- Uploaded the downloaded Ubuntu ISO image.
- The <b>Type, Subtype, and Version</b> fields were automatically populated.
- Skipped <b> Unattended Installation</b>.

[Ubuntu 3](https://github.com/Judeorabueze/Installation-of-Ubuntu-Linux-on-a-Virtual-Machine-VM-/blob/main/Ubuntu%203.PNG)

- Clicked on <b>Hardware</b> to allocate system resources via the hypervisor.
  I assigned memory and processor cores based on my computer’s available base resources while ensuring i stayed within the green zone to avoid over-allocating and ensure stable performance.

