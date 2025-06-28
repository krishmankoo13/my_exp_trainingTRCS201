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



