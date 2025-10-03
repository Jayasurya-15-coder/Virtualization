# Ex.3 Virtualization: Installation and Configuration of Oracle VirtualBox & Kali Linux, and Execution of Linux Commands
## NAME: JAYASURYA B
## REGISTER NUMBER: 212224100026
## Aim:
To set up a virtualized environment using Oracle VirtualBox, install Kali Linux as a guest OS, and execute fundamental Linux commands.

## 3.a) Installation and Configuration of Oracle VirtualBox
## Aim:
To install and configure Oracle VM VirtualBox.

## Pre-requisites:
- Machine with Internet access
- Minimum 4 GB RAM
- Sufficient storage space
## Steps:
1.Download Oracle VM VirtualBox:

- Visit Oracle VirtualBox Official Site
- Download installer for your OS (Windows/macOS/Linux).

2.Install Oracle VM VirtualBox (Example: Windows):

- Launch Installer → Allow Changes → Click Next.
- Choose Installation Options → Click Next.
- Accept Network Interface Warning → Click Yes.
- Click Install.
- Finish Installation and Launch VirtualBox.

3.Configure VirtualBox:

- Open VirtualBox.
- Click New → Name VM → Select Type (Linux/Windows) and Version.
- Allocate:
  
     Minimum 2 GB RAM
  
     Create Virtual Hard Disk (20 GB recommended).
  
- Start Virtual Machine and provide ISO to install OS.
## Result:
Thus, Oracle VM VirtualBox was installed successfully.

## 3.b) Installation and Configuration of Kali Linux
## Aim:
To install and configure Kali Linux in Oracle VirtualBox.

## Pre-requisites:
- Oracle VM VirtualBox Installed
- 4 GB RAM and 20 GB Storage Minimum
- Kali Linux ISO image
## Steps:

1.Download Kali Linux ISO:
- Visit Kali Linux Official Site
- Download 64-bit ISO (Installer version).
  
2.Create a New Virtual Machine:
- Open VirtualBox → Click New.
- Name: "Kali Linux" → Type: Linux → Version: Debian (64-bit).

3. Allocate Memory:
- Minimum 2 GB RAM (recommended 4 GB).
  
4.Create Virtual Hard Disk:
- Select VDI (VirtualBox Disk Image).
- Choose Dynamically allocated.
- Set Disk size to 20 GB or more.
  
5.Configure ISO Image:
- Settings → Storage → Controller: IDE → Empty CD → Choose Disk File → Select Kali Linux ISO.
  
6.Start Installation:
- Boot Virtual Machine → Choose Graphical Install.
- Set Language, Region, Keyboard.
- Configure Network → Set Hostname (e.g., kali).
- Set root password.
- Disk Partitioning: Use entire disk → All files in one partition.
- Install System → Install GRUB Bootloader → Finish Installation.
  
7.Login to Kali Linux:
- Use root credentials.
  
8.(Optional) Install Guest Additions:
- Devices → Insert Guest Additions CD Image → Follow steps inside Kali.
  
## Snapshots:
AWS Account Creation Snapshot

## Snapshot 2: Ubuntu Running in Virtual image

![1](https://github.com/user-attachments/assets/f3e8cb23-563d-49c1-b193-880754f282b0)

## Result:
Thus, Kali Linux guest OS was installed and configured successfully.

## 3.c) Execution of Linux Commands in Kali
## About Linux:
- Open-source operating system.
- Kernel manages communication between hardware and software.
- Commands are case-sensitive.
## Commands:
## 1) ls Command
The ls command is used to display a list of content of a directory.

Syntax: ls

![ls](https://github.com/user-attachments/assets/45173a46-65e5-46a4-a6f8-10df7160f785)

## 2) pwd Command
The pwd command is used to display the location of the current working directory.

Syntax: pwd

![pwd](https://github.com/user-attachments/assets/38cca321-1f9f-44a6-8a7c-21e90fe4570f)


## 3) mkdir Command
The mkdir command is used to create a new directory under any directory.

Syntax: mkdir

![WhatsApp Image 2025-10-03 at 13 27 12_0c29f469](https://github.com/user-attachments/assets/5b7ce570-7682-4fb9-aea7-40e87ea9b8ea)

## 4) rmdir Command
The rmdir command is used to delete a directory.

Syntax: rmdir

![rem](https://github.com/user-attachments/assets/b080f9d0-33bf-4ab5-9a60-a16ab5878255)


## 5) cd Command
The cd command is used to change the current directory.

Syntax: cd

![cd](https://github.com/user-attachments/assets/1c0d6e12-1f32-45c3-a0b9-c24f0b26c682)


## 6) cat Command
The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

![cat](https://github.com/user-attachments/assets/2ef74f14-e20a-4f80-8c30-8408bff82f2d)


## 7) cp Command
The cp command is used to copy a file or directory.

Syntax: cp

![cp](https://github.com/user-attachments/assets/815aa88e-6ebf-4762-bec6-f3249364d91b)


## 8) gedit Command
The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

![grt](https://github.com/user-attachments/assets/853f433f-9836-4cbc-ab37-8e0eb5c09ff7)

## 9) head Command
The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head

![head](https://github.com/user-attachments/assets/fa45a42e-18af-45a1-8be6-b16af6e21f58)


## 10) tail Command
The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail

![tail](https://github.com/user-attachments/assets/a7d3b43b-2327-4434-b501-03179ca998ac)


## 11) id Command
The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

![id](https://github.com/user-attachments/assets/2b4d2a47-28e2-47dc-857b-c1cf64efa6fb)


## 12) grep Command
The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep


![ge](https://github.com/user-attachments/assets/dac8f962-07e5-4af5-afef-7cc70b108683)


## 13) tr Command
The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

![tr](https://github.com/user-attachments/assets/1b4ef769-ca1f-41d8-bdf7-e37f4c403200)

## 14) sort Command
The sort command is used to sort files in alphabetical order.

Syntax:sort

![sort](https://github.com/user-attachments/assets/ab11e4f8-a836-4f96-bbc4-2979c117606f)

## 15) cal Command
The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

![cal](https://github.com/user-attachments/assets/11e7db2f-d82c-4d11-b6b4-21e84409be9c)


## Result:
Thus, the execution of various Linux commands is executed successfully using Kali Linux.

