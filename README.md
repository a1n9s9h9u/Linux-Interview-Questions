## Linux Interview Questions

#### Linux

Linux is a Unix-like open-source computer operating system (OS) that directly manages hardware and resources of a system such as CPU, memory, and storage, and manages the communication between software and hardware.

#### Kernel

A kernel is considered the main component of Linux OS. It is simply a resource manager that acts as a bridge between hardware and software. Its main role is to manage hardware resources for users and is generally used to provide an interface for user-level interaction. A kernel is the first program that is loaded whenever a computer system starts. It is also referred to as low-level system software.

#### Zombie

Zombie: In this state, the process is terminated but information regarding the process still exists and is available in the process table.

#### Daemons

Daemons also referred to as the background process, is a long-running Linux program that runs in the background. They do not have any controlling terminal, therefore, they run in the background. These are the processes that are generally started when the system is bootstrapped and terminate or end only when the system is shut down. It is simply the way of extending the functionality of the base OS.

#### Cron

Cron: It is a program in Linux that is used to execute tasks at a scheduled time. It works effectively on machines that run continuously. 

#### Anacron

Anacron: It is a program in Linux that is used to execute tasks at certain intervals. It works effectively on machines that are powered off in a day or week. 

#### INODE

INODE: It is a unique name given to each file by OS. Each inode has a unique inode number within a file system. It stores various information about files in Linux such as ownership, file size, file type, access mode, number of links, etc.  

#### SSH (Secure Shell)

SSH (Secure Shell), as the name suggests, is basically a protocol that is being used to securely connect to remote servers or systems and enables two systems to communicate. It is considered the most common way to have access to remote Linux servers. It generally transmits data over encrypted channels therefore security is considered at a high level. To connect to a remote server via SSH, you need to own a domain name and IP address.

#### Hard Links vs Soft Links

Hard Links: It is a special kind of file that points to the same underlying inode as another file. It can be referred to as an additional name for an existing file on Linux OS.

Soft Links: It is also termed a symbolic Link. Soft links are kinds of files that usually point to another file. It does not include any amount of data in the target file and simply points to another entry anywhere in the file system.

#### netstat (Network statics)

netstat (Network statics) command is generally a networking tool being used for troubleshooting and configuration and used to display all network connections on a system. It simply provides a way to check whether various aspects of TCP/IP are working and what connections are present.

#### ping (Packet Internet Groper)

Linux ping (Packet Internet Groper) command is a command that is used to check connection status between source and destination. In simple words, this command is used to check whether a network is available and if the host is reachable.

#### Grep (Global regular expression print)

Grep (Global regular expression print) is a command that is used to the global search for a string of characters in a specified file. The text search pattern is generally known as a regular expression. It simply makes use of pattern-based searching.  
```powershell
Syntax: grep [options] pattern [files] 
Example: $ grep -c "linux" interview.txt  
```
The above command will usually print the total count of the word “Linux” in the file “interview.txt”.

#### env

“env” command is basically a shell command that is used to print a list of current environmental variables. Here, “env” stands for the environment.

#### pwd

“pwd” command is basically a command that is used to print the complete path of the current working directory starting from the root (/). Here, “pwd” stands for Print Working Directory.

#### free

The command used mostly to check memory status in Linux is “free”.

#### cat

“cat” command: It can be used to show or display Linux memory information. (cat/proc/meminfo)

#### vmstat

“vmstat” command: It can be used to report statistics of virtual memory. 

#### top

“top” command: It can be used to check the usage of memory. 

#### htop

“htop” command: It can be used to find the memory load of each process. 

#### pipe

In Linux, a pipe is basically a form of redirection that is used to send the output of one command to another command for further processing. It simply takes the output from one command and uses it as an input for another.

#### Umask

Umask, also known as user file-creation mask, is a Linux command that allows you to set up default permissions for new files and folders that you create. In Linux OS, umask command is used to set default file and folder permission.

#### Linux vs Unix

Linux: It is an open-source and free-to-use Operating system. It is specially designed to offer free and low-cost OS for personal computer users.

Unix is not open source and is not free to use. It is generally capable of handling activities from multiple users at the same time.
