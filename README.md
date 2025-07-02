# My Experience in Summer Training by Krish Mankoo
## In this repositry I will share my Experience in 3rd semester training at GNDEC ludhiana
## DAY 1:
### Orientation
The day started with our introduction to our core department - Computer Science and Engineering. Dr Priyanka introduced us with our department and Dr Kiran Jyoti(HOD CSE department) gave us a brief overview about our syllabus scheme.After that we were escorted to our respective labs.

### Learning about Fundametals of linux
Our lab professor then gave us a brief introduction about linux and how to download it.To download linux we required Oracle Virtual Box,Visual C++ Redistribuable Version and Ubuntu Desktop LTS. She helped us understand the applications of it and told us how we can apply it in our future fields.I came to know that linux is used in big companies as it is more secure & open source.We were motivated to also go for startups and other companies along with our studies.I got to know the difference between service-based companies and product-based companies.

After we were explained about booting and its types.Booting, in the context of computers, refers to the process of starting up a computer and loading the operating system.It has two types Cold Boot(eg- Linux and MacOS) and Warm Boot(eg- Windows).After we revised the concepts ourself.We also learned about dual boot which Dual allows you to install two operating systems on the same machine, and choose which one to use at startup.

While starting the virtual machine we had to partition our system and then we were introduced with the concept of partitioning.Partitioning splits your hard drive into separate sections (partitions) for better organization.There are two types: MBR(Master Boot Record) and GPT(Guided Partition Table).MBR is the older partitioning system, used since the early days of PCs. On the other hand GPT is the modern replacement for MBR, part of the UEFI (Unified Extensible Firmware Interface) system.

It really motivated and inspired me alot and I was more curious about the upcoming days of training as there are a lot of things for me to learn.

## DAY 2:
 Our day started today at 8:30 a.m with a positive mindset and a desire to learn something new.
*“The future belongs to those who prepare for it today.”*
With this thought, we stepped into our labs, ready to absorb and explore the tech world further.
### Kernal and Shell
We were introduced to the core components of the Linux operating system — the Kernel and the Shell.

The Kernel is the heart of the operating system. It directly interacts with the hardware and manages system resources like CPU, memory, and devices. It ensures that each process and application gets the required time and resources to function properly.

The Shell is the interface between the user and the kernel. It interprets the commands we type and communicates them to the kernel.There are four types of shell-Bash,Sh,Zsh and Fish.But in this training session we used Bash shell.Also there are two types of categories- Command Line Shells and Graphical Shells

![Image](https://www.emblogic.com/blog/wp-content/uploads/2020/02/Shell-figure.png)

### File System Structures
The Linux file system is structured hierarchically, starting from a root directory denoted by /. 
![Image](https://media.geeksforgeeks.org/wp-content/uploads/20230516105759/151.webp)

### Commands in Linux
The most fun part of today was learning commands in Linux.We learned a lot of basic commands today and had hand's on practice too.Multiple errors also occured but solving them was fun and challenging too.
### Types of Command
- whoami- Returns the current domain and user name.
  
- date- Returns current date.

- ls (list)- Returns content of a specified Directory

- cd- Changes directory.

- mkdir- Creates a new directory.

- pwd- Prints the current working directory.

- touch- Creates empty file.

- cat- Creates file with content.

- whereis- Finds the location of specified file.

- cp- To copy content of a file to the other.

- mv- To move or rename a file.

- whatis- Gives short description of a command.

  The screenshots of the commands I practiced are below.

![image alt](https://github.com/krishmankoo13/my_exp_trainingTRCS201/blob/main/Screenshot%202025-06-26%20115048.png?raw=true)
![image alt](https://github.com/krishmankoo13/my_exp_trainingTRCS201/blob/main/Screenshot%202025-06-26%20115131.png?raw=true)
![image alt](https://github.com/krishmankoo13/my_exp_trainingTRCS201/blob/main/Screenshot%202025-06-26%20115152.png?raw=true)

## DAY 3:
On the third day, We first had our viva for day1 and day2.

### File and Directory Permissions
- chmod (change mode):  It is used to change the access permissions of files and directories.
Some of its types are:

| Syntax                | Meaning                                                       |
|-----------------------|---------------------------------------------------------------|
| `chmod +x filename.sh`  | Gives permission to **run** the script (makes it executable). |
| `chmod 444 filename.sh` | Sets file to **read-only** for everyone.                     |
| `chmod 644 filename.sh` | Gives **read/write** to the owner, **read-only** to others.  |


- chown (change owner ): It is used to **change the ownership** of files and directories.

Some of its types are:

| Type                           | Meaning                                      | Syntax Example                          |
|--------------------------------|----------------------------------------------|------------------------------------------|
| Change Owner                   | Changes only the user (owner)                | `chown krish file.txt`                  |
| Change Owner and Group         | Changes user and group                       | `chown krish:developers file.txt`       |
| Change Only Group              | Use empty owner before `:`                   | `chown :developers file.txt`            |
| Recursive Ownership Change     | Applies changes to all sub-files and folders | `chown -R krish:devs foldername/`       |


### Redirection

Redirection in Linux is used to **send output to files**, **take input from files**, or **append data** instead of showing it on the screen.

| Type | Meaning                        | Syntax & Example                    |
|------|--------------------------------|-------------------------------------|
| `>`  | Write/overwrite to a file      | `echo hi > file.txt`                |
| `>>` | Append to a file               | `echo hi >> file.txt`               |
| `<`  | Input redirection (read from a file) | `sort < file.txt`             |

### PIPES

The **pipe** symbol (`|`) is used to **connect multiple commands**, where the **output of one command becomes the input of the next**.  
It is commonly used for **filtering and processing data** in a single line.

## 🔢 Shell Scripting Examples

---

### 1. 📝 Using Variables

![Using Variables - Part 1](https://github.com/krishmankoo13/my_exp_trainingTRCS201/blob/main/Screenshot%202025-06-27%20114225.png?raw=true)  
![Using Variables - Part 2](https://github.com/krishmankoo13/my_exp_trainingTRCS201/blob/main/Screenshot%202025-06-27%20113813.png?raw=true)

---

### 2. ✖️ Multiplication Table

![Multiplication Table - Part 1](https://github.com/krishmankoo13/my_exp_trainingTRCS201/blob/main/Screenshot%202025-06-27%20115323.png?raw=true)  
![Multiplication Table - Part 2](https://github.com/krishmankoo13/my_exp_trainingTRCS201/blob/main/Screenshot%202025-06-27%20115241.png?raw=true)

---

### 3. 🔁 Comparing Two Numbers

![Comparing Two Numbers - Part 1](https://github.com/krishmankoo13/my_exp_trainingTRCS201/blob/main/Screenshot%202025-06-27%20112538.png?raw=true)  
![Comparing Two Numbers - Part 2](https://github.com/krishmankoo13/my_exp_trainingTRCS201/blob/main/Screenshot%202025-06-27%20113028.png?raw=true)

## DAY 4:
### PC Hardware

![image alt](https://github.com/krishmankoo13/my_exp_trainingTRCS201/blob/main/cpu.jpg?raw=true)

### 🔧 1. Motherboard (Main Circuit Board)
- It is the central PCB that connects all major components like CPU, RAM, storage, GPU, and power.

---

### Components Found on the Motherboard

- **CPU Socket** – Slot where the processor (CPU) is installed.
- **RAM Slots** – Used to install RAM (memory) modules.
- **24-pin and 8-pin Power Connectors** – Supply power to the motherboard and CPU.
- **SATA Ports** – Connect hard drives and SSDs.
- **IDE Connector** – Connects older hard drives or optical drives.
- **AGP/PCI/PCIe Slots** – Allow expansion cards like GPU or sound cards to be installed.
- **BIOS Chip** – Stores firmware that helps boot the system.
- **USB Ports** – Connect USB devices such as keyboard, mouse, or pen drives.
- **Audio, VGA, HDMI, and Modem Ports** – Provide various external connectivity options.
- **Fan Connector** – Powers and controls system or CPU cooling fans.
- **Heat Sink Area** – Holds the heat sink for CPU cooling.
- **CMOS Battery** – Powers the BIOS to retain date, time, and hardware settings when PC is off.

![image alt](https://github.com/krishmankoo13/my_exp_trainingTRCS201/blob/main/mb.jpg?raw=true)


###  Other Key Components Inside the CPU Cabinet

- **Optical Drive** – Reads/writes CDs and DVDs.
- **Hard Disk Drive (HDD)** – Stores the operating system, files, and programs.
- **Power Supply Unit (PSU)** – Converts electricity from wall to usable power for components.
- **Fan** – Keeps the internal temperature low by circulating air.
- **Connectors** – Provide external connection ports for peripherals like keyboard, mouse, etc.
- **Expansion Slots** – Allow you to add extra components like a graphics card or network card.

---

**Importance of Cache Memory**
- Cache memory stores frequently accessed data close to the CPU, allowing faster access than RAM.


### Linux File Compression

| Command      | One-Line Meaning                            | Syntax                  | Example                       |
|--------------|---------------------------------------------|-------------------------|-------------------------------|
| `gzip`       | Compresses a file and deletes the original  | `gzip filename`         | `gzip file.txt` → creates `file.txt.gz` and deletes `file.txt` |
| `gunzip`     | Decompresses a `.gz` file                   | `gunzip filename.gz`    | `gunzip file.txt.gz` → restores `file.txt` and deletes `.gz` |
| `gzip -k`    | Compresses file but keeps the original file | `gzip -k filename`      | `gzip -k file.txt` → creates `file.txt.gz` and keeps `file.txt` |


![image alt](https://github.com/krishmankoo13/my_exp_trainingTRCS201/blob/main/Screenshot%202025-06-30%20112658.png?raw=true)

### Wildcards 

| Wildcard     | One-Line Meaning                                | Syntax Example         | Matches Example Files                  |
|--------------|--------------------------------------------------|------------------------|----------------------------------------|
| `*`          | Matches zero or more characters                  | `ls *.txt`             | `notes.txt`, `a.txt`, `123.txt`        |
| `?`          | Matches exactly one character                    | `ls ?.txt`             | `a.txt`, `1.txt` (not `ab.txt`)        |
| `[a-z]`      | Matches any **one** character in the range       | `ls file[1-3].txt`     | `file1.txt`, `file2.txt`, `file3.txt`  |

![image alt](https://github.com/krishmankoo13/my_exp_trainingTRCS201/blob/main/Screenshot%202025-06-30%20113327.png?raw=true)

### Escaping Characters

Escape characters are special sequences used to represent characters that cannot be typed or have a special meaning in shell. They are typically used with the `echo -e` command to format output.

| Escape Character | Definition                                | Syntax Example                    | Output Example               |
|------------------|--------------------------------------------|-----------------------------------|------------------------------|
| `\n`             | Inserts a new line                         | `echo -e "Line1\nLine2"`          | Line1 <br> Line2             |
| `\t`             | Inserts a horizontal tab                   | `echo -e "A\tB"`                  | A  B                         |
| `\\`             | Prints a backslash                         | `echo "\\"`                       | \                            |
| `\"`             | Prints a double quote inside double quotes | `echo "She said, \"Hi\""`         | She said, "Hi"               |
| `\'`             | Prints a single quote inside single quotes | `echo 'It'\''s fine'`             | It's fine                    |


![image alt](https://github.com/krishmankoo13/my_exp_trainingTRCS201/blob/main/Screenshot%202025-06-30%20114826.png?raw=true)

## DAY 5:

## Common PC Problems and Solutions

Help Shortcut:
Press F1 to open help tool in Windows.

Today we learned about common issues encountered on personal computers and how to fix them. Each point includes both the cause and the recommended solution.

### PC Maintenance Issues

- **C Drive Full or Slowing Down**  
  The C drive stores essential system files. Avoid saving personal files here. Free space using Disk Cleanup, uninstall unused programs, or move data to D or E drive. You can also delete temporary files using `%temp%`.

- **PC Running Slowly**  
  Caused by too many background processes or lack of memory. Open Task Manager to disable startup apps, delete temp files, and remove unused software.

- **Fragmented Hard Drive (HDD only)**  
  Fragmentation slows down file access. Use "Defragment and Optimize Drives" in Windows to improve speed (note: not needed for SSDs).

- **Too Many Temporary or Junk Files**  
  These files build up from software usage. Use Disk Cleanup or manually delete files from `%temp%`, `temp`, and `prefetch` folders.

- **System Takes Long to Start**  
  Caused by unnecessary startup programs and services. Disable unwanted startup applications using Task Manager under the "Startup" tab.

### Software & Application Issues

- **Software Freezes or Crashes**  
  Can happen due to corrupted installations or insufficient RAM. Force quit using Task Manager and reinstall or update the app.

- **Software Installation Fails**  
  Common reasons include lack of admin permissions or incompatible versions. Use "Run as administrator" and ensure correct 32/64-bit installer is downloaded.

- **Windows Update Not Working**  
  Sometimes the update cache is corrupted. Run the Windows Update Troubleshooter or delete contents in `C:\Windows\SoftwareDistribution` folder.

### Hardware & Peripheral Issues

- **Printer Not Responding**  
  Usually caused by driver problems or connection issues. Restart the printer and PC, check cable or network, and reinstall drivers if needed.

- **Drive Not Detected**  
  A new or unformatted drive won’t show in Explorer. Go to Disk Management, assign it a drive letter, and format if necessary.

- **Computer Automatically Restarts or Overheats**  
  Often caused by clogged fans or poor airflow. Clean the dust from CPU fan, vents, and use cooling pads for laptops. Also check if thermal paste needs reapplying.

### Network & Security Issues

- **Internet Not Working Despite Being Connected**  
  Likely a DNS or driver issue. Restart the router, run Windows Network Troubleshooter, or open Command Prompt and run `ipconfig /flushdns`.

- **Antivirus Slowing Down the System**  
  Heavy or multiple antivirus programs can reduce speed. Use only one trusted antivirus (like Windows Defender), and disable unnecessary real-time scanning features.

### Account & Graphics Issues

- **Forgotten Login Password**  
  For local accounts, use Safe Mode or reset via another admin account. For Microsoft accounts, reset using Microsoft’s online password recovery.

- **Low Graphics Performance**  
  Happens due to outdated GPU drivers or background apps using resources. Download latest drivers from NVIDIA/AMD and close all unnecessary apps during usage.

##  What is Blue Screen of Death (BSOD)?

The **Blue Screen of Death (BSOD)** is a critical system error screen displayed by Windows when the operating system can no longer operate safely due to a severe issue. It is also called a **Stop Error** or **bug check**.

![imagealt](https://www.cnet.com/a/img/resize/a75db4f15b0c02ccde4100ed1e26b9606557080a/hub/2025/06/26/f9a73c79-3ee4-4fab-b23a-e6fd8833cee0/blue-screen-of-death-gettyimages-1328389388-1.jpg?auto=webp&fit=crop&height=675&width=1200)
###  Why Does BSOD Happen?

BSOD typically occurs due to:

- **Faulty device drivers** (graphics, network, etc.)
- **Corrupted system files**
- **Faulty or incompatible hardware** (RAM, hard drive, GPU)
- **Overheating or power issues**
- **Malware affecting system-level processes**
- **Overclocking or BIOS misconfigurations**
- **Critical kernel or memory management errors**

---

###  How to Analyze a BSOD?

1. **Read the Error Message**  
   The BSOD screen will display a `STOP CODE` like:  
   `DRIVER_IRQL_NOT_LESS_OR_EQUAL` or `CRITICAL_PROCESS_DIED`.

2. **Use Reliability Monitor**  
   Open `Reliability Monitor` (search in Start menu) to check system events before the crash.

3. **View Dump File**
   After a BSOD, Windows creates a dump file that records what happened before the crash.
   Analyze crash dumps stored at:  
   `C:\Windows\Minidump\` using tools like:
   - **BlueScreenView** (NirSoft)
   - **WinDbg** (Microsoft Debugger)
   - **WhoCrashed**

4. **Event Viewer**  
   Use `eventvwr.msc` to see system logs and warnings before the BSOD occurred.


### Solutions to Fix BSOD

| Step | Action |
|------|--------|
|  1. **Update Drivers** | Go to Device Manager and update all major drivers (especially GPU, chipset, and network). |
|  2. **Uninstall Recent Software** | Remove any software or drivers recently installed before the BSOD started. |
|  3. **Run System File Checker** | Run `sfc /scannow` in Command Prompt as administrator to repair corrupted system files. |
| 4. **Check RAM** | Run **Windows Memory Diagnostic** to check for faulty memory. |
|  5. **Scan for Malware** | Use Windows Defender or Malwarebytes to check for deep infections. |
| 6. **Reset Overclocking** | If using overclocked settings, restore BIOS/UEFI to default values. |
|  7. **Perform a System Restore** | Roll back to a working system point using System Restore. |
|  8. **Update Windows** | Keep the OS up to date with the latest security and stability patches. |

### Preventive Measures

- Avoid installing untrusted drivers or registry cleaners.
- Keep a restore point or full backup before major updates.
- Ensure proper cooling and power supply to prevent hardware issues.

##  Assignment on BIOS/UEFI Settings and POST Errors

### What is BIOS/UEFI?

- **BIOS (Basic Input/Output System)** and **UEFI (Unified Extensible Firmware Interface)** are low-level firmware interfaces between the computer's hardware and its operating system.
- BIOS is the **older** system, while UEFI is the **modern standard** in most PCs since 2010.
- These interfaces allow you to configure hardware settings, boot order, security options, and more.

### Common BIOS/UEFI Settings

| Setting | Description |
|--------|-------------|
| **Boot Order** | Determines which device (HDD, SSD, USB) the PC checks first when starting. |
| **Secure Boot** | Prevents unauthorized OS or bootloaders from loading (enabled in UEFI). |
| **Virtualization** | Enables support for virtual machines (VT-x, AMD-V). |
| **XMP/DOCP Profile** | Enables full-speed RAM performance (must be manually enabled in some PCs). |
| **Fan Control** | Sets custom cooling profiles based on temperature. |
| **Date/Time** | Sets the system clock — affects OS time if incorrect. |
| **SATA Mode** | Selects IDE, AHCI, or RAID for hard drive behavior. |
| **Integrated Peripherals** | Enables/disables onboard devices (e.g., audio, LAN, USB ports). |
| **Password Setup** | Sets BIOS or boot passwords for security. |

### What is POST?

**POST (Power-On Self Test)** is a diagnostic process run by BIOS/UEFI during startup to check if essential hardware (CPU, RAM, GPU, keyboard, etc.) is working.

If POST fails, it usually halts the boot process and gives error **beeps or messages**.

### Common POST Errors & Beep Codes

| Error / Beep | Meaning | Suggested Fix |
|--------------|---------|----------------|
| **No Display / Blank Screen** | GPU or RAM issue | Reseat graphics card and RAM |
| **Continuous Beeps** | RAM failure | Check RAM sticks or try different slots |
| **1 Long, 2 Short Beeps** | GPU not detected | Reinsert GPU properly or test another |
| **Keyboard Not Detected** | Faulty or unplugged keyboard | Try another USB port or replace keyboard |
| **CMOS Checksum Error** | BIOS settings corrupt | Reset BIOS using Clear CMOS jumper |
| **Date and Time Reset** | CMOS battery drained | Replace the small coin-cell battery on motherboard |

> Beep codes vary by **BIOS manufacturer** (AMI, Phoenix, Award). Refer to your motherboard manual for exact beep meanings.


### How to Access BIOS/UEFI

- Restart your PC and press the correct key during startup:  
  - **DEL** or **F2** (common for most desktops/laptops)  
  - **ESC**, **F1**, or **F10** for others  
- You may also access UEFI through Windows:
  - Go to **Settings > Update & Security > Recovery > Advanced Startup > Restart Now > UEFI Firmware Settings**


### Resetting BIOS/UEFI to Default

If you misconfigured a setting or can’t boot:

- Enter BIOS/UEFI → Choose **"Load Setup Defaults"** or **"Reset to Default"**
- Or remove the CMOS battery for a few minutes and reinsert it
- Or use the **Clear CMOS jumper** on the motherboard

## DAY 6:
## System Troubleshooting Guide

### 1. Safe Mode

Safe Mode is a diagnostic startup mode that loads only essential system files and drivers. It is used to troubleshoot issues that prevent Windows from starting or running properly.

**Types of Safe Mode:**
- Safe Mode
- Safe Mode with Networking
- Safe Mode with Command Prompt

**How to Access:**
- Press Shift + Restart → Troubleshoot → Advanced Options → Startup Settings
- Or interrupt boot process 3 times to enter recovery mode

---

### 2. Recovery Tools

Recovery Tools are built-in Windows utilities used to fix, restore, or reset system functionality after crashes, failed updates, or boot errors.

**Key Recovery Options:**

| Tool                    | Description                                                    |
|-------------------------|----------------------------------------------------------------|
| System Restore          | Reverts the system to a previously created restore point       |
| Startup Repair          | Fixes boot-related problems automatically                      |
| Reset This PC           | Reinstalls Windows with an option to keep or remove user data  |
| System Image Recovery   | Restores Windows using a full system image backup              |
| Command Prompt          | Allows advanced troubleshooting using terminal commands        |

**Access via:**  
Settings → Recovery → Advanced Startup  
Or press F11/Shift + Restart during boot

---

### 3. OS Repair (Operating System Repair)

OS repair involves fixing core system files and configurations to restore normal Windows operations.

**Common Repair Methods:**

| Method               | Description                                                      |
|----------------------|------------------------------------------------------------------|
| sfc /scannow         | Scans and repairs corrupted system files                         |
| DISM /RestoreHealth  | Repairs the Windows image if SFC is not sufficient               |
| Startup Repair       | Automatically fixes boot-related files                           |
| Reset This PC        | Reinstalls Windows while offering data preservation options      |

**Commands:**
sfc /scannow
DISM /Online /Cleanup-Image /RestoreHealth

## Virus and Malware

### Symptoms of Infection

- System becomes slow or unresponsive
- Frequent crashes or freezes
- Unexpected pop-ups or ads appear
- Antivirus software is disabled automatically
- Unknown programs start running or installed
- Files or folders are missing, renamed, or encrypted
- High CPU, memory, or disk usage without visible cause
- Browser redirects to unknown websites or search engines

---

### Basic Malware Removal Steps

1. **Boot into Safe Mode with Networking**
   - Press Shift + Restart → Troubleshoot → Advanced Options → Startup Settings

2. **Run Full System Scans**
   - Use Windows Defender or a trusted tool like Malwarebytes

3. **Uninstall Suspicious Applications**
   - Go to Control Panel → Programs → Uninstall unknown software

4. **Disable Unwanted Startup Programs**
   - Open Task Manager → Startup tab → Disable unknown entries

5. **Reset Browsers**
   - Remove unknown extensions and reset settings in Chrome, Firefox, etc.

6. **Review Scheduled Tasks and Services**
   - Use Task Scheduler and `services.msc` to identify unusual entries

7. **Perform System Restore or Reset This PC**
   - Use a restore point or reinstall Windows to eliminate persistent threats

## Networking Cable and Connectors

### Ethernet Cable and RJ45 Connector

- Ethernet cables are used to connect computers, routers, and switches for network communication.
- The RJ45 connector is a standard 8-pin connector used at both ends of the cable.

---

### RJ45 Color Code (TIA/EIA 568B Standard)

Wiring order from **left to right** (with clip facing down):

`White-Orange, Orange, White-Green, Blue, White-Blue, Green, White-Brown, Brown`

| Pin Number | Wire Color     |
|------------|----------------|
| 1          | White-Orange   |
| 2          | Orange         |
| 3          | White-Green    |
| 4          | Blue           |
| 5          | White-Blue     |
| 6          | Green          |
| 7          | White-Brown    |
| 8          | Brown          |

![IMG_5017](https://github.com/user-attachments/assets/08b58187-9139-421c-a645-0bac8adeed9e)

---

### Crimping Basics

Crimping is the process of attaching an RJ45 connector to the end of a network cable.

**Steps:**
1. Strip about 1 inch of outer cable jacket.
2. Untwist and arrange the wires in the correct color order.
3. Trim all wires to the same length.
4. Insert wires into the RJ45 connector.
5. Use a crimping tool to lock the connector in place.

---

### Cable Testing

After crimping, a cable tester is used to check:

- Proper pin connections (1 to 1, 2 to 2, etc.)
- Continuity across all 8 wires
- No shorts, opens, or miswiring

A basic tester will light up each pin in sequence to show a successful connection.
