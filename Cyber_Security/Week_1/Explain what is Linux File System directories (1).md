**Explain what is Linux File System directories.**

A directory contains large information about the files, including location and attributes. So, this is useful to the user in keeping track of files. The directories are useful to the file management system. It provides access control and other services to users.

A directory is a file the solo job of which is to store the file names and the related information. All the files, whether ordinary, special, or directory, are contained in directories. Unix uses a hierarchical structure for organizing files and directories. This structure is often referred to as a directory tree.

The Linux File Hierarchy Structure or the File system Hierarchy Standard (FHS) defines the directory structure and directory contents in Unix-like operating systems. In the FHS, all files and directories appear under the root directory /, even if they are stored on different physical or virtual devices.

A Linux file system is a structured collection of files on a disk drive or a partition. The general-purpose computer system needs to store data systematically so that we can easily access the files in less time. It stores the data on hard disks (HDD) or some equivalent storage type. Linux supports seven different types of files. These file types are the Regular file, Directory file, Link file, Character special file, Block special file, Socket file, and Named pipe file

There are various types of directory structure:

Single-Level Directory.

Two-Level Directory.

Tree-Structured Directory.

Acyclic Graph Directory.

General-Graph Directory.

**Single-Level Directory** is the easiest directory structure.

Types of files in the Linux system. 

General Files – It is also called ordinary files. It may be an image, video, program, or simple text files. These types of files can be in ASCII or Binary format. It is the most commonly used file in the Linux system.

Directory Files – These types of files are a warehouse for other file types. It may be a directory file within a directory (subdirectory).

Device Files – In a Windows-like operating system, devices like CD-ROM, and hard drives are represented as drive letters like F: G: H whereas in the Linux system device are represented as files. As for example, /dev/sda1, /dev/sda2 and so on.





These are the common top-level directories associated with the root directory:

` `/bin – binary or executable programs.

/etc – system configuration files.

/home – home directory. It is the default current directory.

/opt – optional or third-party software.

/tmp – temporary space, typically cleared on reboot.

/usr – User related programs.

/var – log files.








Some other directories in the Linux system:

/boot- It contains all the boot-related information files and folders such as conf, grub, etc.

/dev – It is the location of the device files such as dev/sda1, dev/sda2, etc.

/lib – It contains kernel modules and a shared library.

/lost+found – It is used to find recovered bits of corrupted files.

/media – It contains subdirectories where removal media devices inserted.

/mnt – It contains temporary mount directories for mounting the file system.

/proc – It is a virtual and pseudo-file system to contains info about the running processes with a specific process ID or PID.

/run – It stores volatile runtime data.

/sbin – binary executable programs for an administrator.

/srv – It contains server-specific and server-related files.

/sys – It is a virtual file system for modern Linux distributions to store and allows modification of the devices connected to the system.



Exploring directories and their usability:

We know that Linux is a very complex system that requires an efficient way to start, stop, maintain and reboot a system, unlike Windows operating system. In the Linux system some well-defined configuration files, binaries, man pages information files available for every process. 

Linux Kernel File:

/boot/vmlinux – The Linux kernel file.

Device Files:

/dev/hda – Device file for the first IDE HDD.

/dev/hdc – A pseudo-device that output garbage output is redirected to /dev/null.

System Configuration Files:

/etc/bashrc – It is used by bash shell that contains system defaults and aliases.

/etc/crontab – A shell script to run specified commands on a predefined time interval.

/etc/exports – It contains information on the file system available on the network.

/etc/fstab – Information of the Disk Drive and their mount point.

/etc/group – It is a text file to define Information of Security Group.

/etc/grub.conf – It is the grub bootloader configuration file.

/etc/init.d – Service startup Script.

/etc/lilo.conf – It contains lilo bootloader configuration file.

/etc/hosts – Information of IP and corresponding hostnames.

/etc/hosts.allow – It contains a list of hosts allowed accessing services on the local machine.

/etc/host.deny – List of hosts denied to access services on the local machine.

/etc/inittab – INIT process and their interaction at the various run level.

/etc/issue – Allows editing the pre-login message.

/etc/modules.conf – It contains the configuration files for the system modules.

/etc/motd – It contains the message of the day.

/etc/mtab – Currently mounted blocks information.

/etc/passwd – It contains username, password of the system, users in a shadow file.

/etc/printcap – It contains printer Information.

/etc/profile – Bash shell defaults.

/etc/profile.d –  It contains other scripts like application scripts, executed after login.

/etc/rc.d – It avoids script duplication.

/etc/rc.d/init.d – Run Level Initialisation Script.

/etc/resolv.conf – DNS being used by System.

/etc/securetty – It contains the name of terminals where root login is possible.

/etc/skel – Script that initiates new user home directory.

/etc/termcap – An ASCII file that defines the behavior of different types of the terminal.

/etc/X11 –  Directory tree contains all the conf files for the X-window System.

User Related Files:

/usr/bin – It contains most of the executable files.

/usr/bin/X11 – Symbolic link of /usr/bin.

/usr/include – It contains standard include files used by C program.

/usr/share – It contains architecture independent shareable text files.

/usr/lib – It contains object files and libraries.

/usr/sbin – It contains commands for Super User, for System Administration.

Virtual and Pseudo Process Related Files:

/proc/cpuinfo – CPU Information

/proc/filesystems – It keeps the useful info about the processes that are running currently.

/proc/interrupts – it keeps the information about the number of interrupts per IRQ.

/proc/ioports – Contains all the Input and Output addresses used by devices on the server.

/proc/meminfo –  It reports the memory usage information.

/proc/modules – Currently using kernel module.

/proc/mount – Mounted File-system Information.

/proc/stat –  It displays the detailed statistics of the current system.

/proc/swaps –  It contains swap file information.

Version Information File:

/version – It displays the Linux version information.

Log Files:

/var/log/lastlog – It stores user last login info.

/var/log/messages – It has all the global system messages.

/var/log/wtmp – It keeps a history of login and logout information.

To check the Linux directories open the terminal and execute sudo -s followed by system password to give root privilege. 

Then after changing the current home directory to the root directory and check the list of all available directories in the base directory as shown below. 



