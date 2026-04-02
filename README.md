# Basic Linux Commands and Dual Boot Setup
## Common Linux Commands

Below are some essential Linux commands and their functions:

* `whoami` – Displays the currently logged-in user
* `pwd` – Shows the full path of the current working directory
* `ls` – Lists files and directories
* `ls -a` – Displays all files, including hidden ones
* `cd` – Changes the current directory
* `cd ..` – Moves to the parent directory
* `mkdir` – Creates a new directory
* `rmdir` – Removes an empty directory
* `touch` – Creates a new empty file
* `nano` – Opens a file in a terminal editor
* `cat` – Displays file contents
* `cp` – Copies files or directories
* `mv` – Moves or renames files/directories
* `rm` – Deletes files or directories

---

## Dual Boot Setup (Windows and Linux)

### Overview

This project involves setting up a dual boot system to run both Windows and Linux on the same machine. This setup allows flexibility in using different operating systems based on requirements.

---

## Steps Followed

### 1. Creating a Bootable USB

The Linux ISO file (Ubuntu) was downloaded and a bootable USB drive was created using Rufus.

---

### 2. Allocating Disk Space

Using Windows Disk Management, an existing partition was reduced to create approximately 30GB of unallocated space for Linux installation.

---

### 3. Booting from USB

The system was restarted and the boot menu was accessed (using F12 key). The USB drive was selected to initiate the installation process.

---

### 4. Installing Linux

The "Install alongside Windows" option was chosen during installation. This allowed automatic partitioning and simplified the setup process.

---

### 5. Bootloader Configuration

The GRUB bootloader was installed automatically. It provides the option to select the operating system during system startup.

---

## Key Learnings

* Windows Fast Startup can cause issues in a dual boot environment
* Proper shutdown in Windows is necessary to avoid file system conflicts
* GRUB is responsible for managing multiple operating systems
* Disk partitioning is a critical step and must be handled carefully

---

## Issues Faced

* Encountered a read-only filesystem issue
* Resolved by disabling hibernation and Fast Startup in Windows

---

## Conclusion

Setting up a dual boot system is a practical way to use both Windows and Linux on a single machine. While minor issues may occur, they can be resolved with proper configuration. This process provides valuable hands-on experience in system setup and operating system management.

