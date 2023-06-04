
# About Linux Operating System

Linux is an open-source Unix-like operating system-based family on the Linux kernel, and the OS kernel was first published on 17 September 1991 by Linus Torvalds. Typically, Linux is packaged as the Linux distribution, which contains the supporting libraries and system software and kernel, several of which are offered by the GNU Project. Several Linux distributions use the term "Linux" in the title, but the Free Software Foundation uses the "GNU/Linux" title to focus on the necessity of GNU software, causing a few controversies.

Famous Linux distributions are Ubuntu, Fedora Linux, and Debian, the latter of which is composed of several different modifications and distributions, including Xubuntu and Lubuntu. Commercial distributions are SUSE Linux Enterprise and Red Hat Enterprise Linux. Desktop distributions of Linux are windowing systems like Wayland or X11 and desktop environments like KDE Plasma and GNOME.

    Originally, Linux was designed for personal computers that were Intel x86 architecture-based, but it has since been moved to more environments than other operating systems.
    Including Android, Linux has the biggest installed base of every general-purpose operating system because of the control of the Linux-based Android over smartphones as of May 2022.
    However, Linux is used by just around 2.6% of desktop computers as of November 2022.
    Also, Linux executes on many embedded systems, i.e., devices whose OS is typically designed into the firmware and is extremely customized to the system.
    It includes spacecraft (Perseverance rover, Dragon crew capsule, and Falcon 9 rocket), automobiles (Toyota, Hyundai, Mercedes-Benz, Audi, and Tesla), televisions (LG and Samsung Smart TVs), video game consoles, smart home devices, automation controls, and routers.

Linux is one of the most outstanding examples of open-source and free software collaboration. The source code may be distributed, modified, and used non-commercially or commercially by everyone under the conditions of its respective licenses, like the GNU GPL (General Public License).

Difference between Linux and Windows Operating System

Linux vs. Windows has always been one of the most frequently asked questions related to the operating system. Users often get confused about which one is better for them. There is diversity between the users as most users prefer the graphical user interface (GUI) and most command-line interface (CLI). There are many disagreements and acrimonious behavior among users, and it seems that it will be forever.

# Linux vs. Windows

In this section, we will discuss the differences between Linux and Windows by considering several parameters such as performance, usability, security, ease of use, and more to clear a picture of using both operating systems. Further, we will see the advantages of Linux over other operating systems such as Windows and Mac OS. This will help you to decide which one is better for you.

To understand the difference between Linux and Windows, let's see a brief introduction to both operating systems. Later we will talk on their features and security options.

# Windows Operating System

Windows is a graphical operating system developed and marketed by Microsoft. It is also referred to as Microsoft Windows. Several versions of Windows have been introduced in the market; the current version is Windows 10. The first version of Windows was introduced on November 20, 1985, as a graphical operating system for MS-DOS.

Microsoft Windows is a family of various operating systems. It comes with two versions, i.e., 64 bit and 32 bit. It facilitates both client and server versions. The latest client version is Windows 10, and the server version is Windows server 2019.

Windows is a straight forward and simple to use. Generally, it is designed for users having no programming knowledge. So, mostly it is used for business and alternative industrial purposes.

# Linux Operating System

Linux is an open-source operating system. As it is open-source, it is special and different from other operating systems, which means that you can customize it by editing source code. It provides programming as well as a graphical user interface. Linux is built by Linux Torvalds because he wanted to create a free operating system kernel that anyone can use.

Linux is a collection of operating systems that are based on Linux kernel. The first version of Linux was released in the year 1991. The Linux system is most commonly used for servers; however, it is available in desktop versions as well.

Ubuntu, Devian, and Fedora are some popular Linux distributions. Also, we have SUSE Linux Enterprise Server (SLES) and RedHat Enterprise Linux for the commercial distribution of Linux. As it is open-source, we can modify the source code and make variations in the operating system.

# Linux distribution


## Distribution	 
    Ubuntu
    Linuxmint
    Debian
    Fedora
    Red hat enterprise
    centos
    opensuse
    Arch Linux
   ## Why To Use
	It works like Mac OS and easy to use.
    It works like windows and should be use by new comers.
	It provides stability but not recommended to a new user.
    If you want to use red hat and latest software.
    To be used commercially.
	If you want to use red hat but without its trademark.
	It works same as Fedora but slightly older and more stable.
	It is not for the beginners because every package has to be installed by yourself.

# kali Linux

## How to set up  kali Linux in vm machine:
    vmware:https://www.vmware.com/products/workstation-player/workstation-player-evaluation.html

    vmbox:https://www.virtualbox.org/wiki/Downloads

    Download Kali :https://www.kali.org/get-kali#kali-virtual-machines
    
Installing process and setup process video ,you can get from youtube easily.



# Navigating File System

pwd (Print Working Directory):

        Explanation: Displays the current working directory.
        Example: Running pwd in the terminal would show the absolute path of the current directory, such as "/home/user/documents".

cd (Change Directory):

        Explanation: Allows you to change the current working directory.
        Example: Running cd /home/user/documents would change the directory to "/home/user/documents".

cd .. (Change to Parent Directory):

        Explanation: Moves up one level in the directory hierarchy.
        Example: Running cd .. in "/home/user/documents" would move to the "/home/user" directory.

ls (List Directory Contents):

        Explanation: Lists the files and directories in the current directory.
        Example: Running ls would display the files and directories in the current directory.

ls -la (List Detailed Directory Contents):

        Explanation: Lists detailed information about files and directories, including hidden files.
        Example: Running ls -la would display a detailed list of files and directories, including hidden files, in the current directory.

mkdir (Make Directory):

        Explanation: Creates a new directory.
        Example: Running mkdir new_folder would create a new directory named "new_folder" in the current directory.

rmdir (Remove Directory):

        Explanation: Removes an empty directory.
        Example: Running rmdir empty_folder would remove the directory named "empty_folder" if it is empty.

man (Manual):

        Explanation: Displays the manual pages for a specified command.
        Example: Running man ls would show the manual pages with detailed information about the ls command.

echo:

        Explanation: Displays text or variables as output.
        Example: Running echo "Hello, world!" would output "Hello, world!" in the terminal.

> (Output Redirection):

        Explanation: Redirects the output of a command to a file and overwrites the file if it already exists.
        Example: Running echo "Hello" > greeting.txt would write the text "Hello" to a file named "greeting.txt" or overwrite the file if it exists.

>> (Append Output):

        Explanation: Redirects the output of a command and appends it to a file.
        Example: Running echo "World!" >> greeting.txt would append the text "World!" to the end of the "greeting.txt" file.

rm (Remove):

        Explanation: Deletes files or directories.
        Example: Running rm file.txt would delete the file named "file.txt" from the current directory.

mv (Move):

        Explanation: Moves or renames files and directories.
        Example: Running mv file.txt new_directory/file_renamed.txt would move the file "file.txt" to the "new_directory" and rename it as "file_renamed.txt".

cp (Copy):

        Explanation: Copies files and directories.
        Example: Running cp file.txt backup/file_copy.txt would create a copy of "file.txt" named "file_copy.txt" in the "backup" directory.

locate:

        Explanation: Searches for files and directories in a prebuilt database.
        Example: Running locate myfile.txt would search for the file named "myfile.txt" in the prebuilt database and display its path if found.

updatedb:

        Explanation: Updates the database used by the locate command to reflect recent changes in the file system.
        Example: Running updatedb would update the database, allowing the locate command to provide up-to-date search results.

passwd:

        Explanation: Allows a user to change their password.
        Example: Running passwd would prompt the user to enter their current password and then set a new password.

Remember to exercise caution when using commands like rm as they can permanently delete files. It's always a good practice to double-check before executing such commands.




#  Kali Linux File System
## / — The Root Directory

    Everything on your Linux system is located under the / directory, known as the root directory. You can think of the / directory as being similar to the C:\ directory on Windows — but this isn’t strictly true, as Linux doesn’t have drive letters. While another partition would be located at D:\ on Windows, this other partition would appear in another folder under / on Linux.

 ## /bin — Essential User Binaries

    The /bin directory contains the essential user binaries (programs) that must be present when the system is mounted in single-user mode. Applications such as Firefox are stored in /usr/bin, while important system programs and utilities such as the bash shell are located in /bin. The /usr directory may be stored on another partition — placing these files in the /bin directory ensures the system will have these important utilities even if no other file systems are mounted. The /sbin directory is similar — it contains essential system administration binaries.

## /boot — Static Boot Files

    The /boot directory contains the files needed to boot the system — for example, the GRUB boot loader’s files and your Linux kernels are stored here. The boot loader’s configuration files aren’t located here, though — they’re in /etc with the other configuration files.
## /cdrom — Historical Mount Point for CD-ROMs

    The /cdrom directory isn’t part of the FHS standard, but you’ll still find it on Ubuntu and other operating systems. It’s a temporary location for CD-ROMs inserted in the system. However, the standard location for temporary media is inside the /media directory.
## /dev — Device Files

    Linux exposes devices as files, and the /dev directory contains a number of special files that represent devices. These are not actual files as we know them, but they appear as files — for example, /dev/sda represents the first SATA drive in the system. If you wanted to partition it, you could start a partition editor and tell it to edit /dev/sda.

    This directory also contains pseudo-devices, which are virtual devices that don’t actually correspond to hardware. For example, /dev/random produces random numbers. /dev/null is a special device that produces no output and automatically discards all input — when you pipe the output of a command to /dev/null, you discard it.

## /etc — Configuration Files

    The /etc directory contains configuration files, which can generally be edited by hand in a text editor. Note that the /etc/ directory contains system-wide configuration files — user-specific configuration files are located in each user’s home directory.
## /home — Home Folders

    The /home directory contains a home folder for each user. For example, if your user name is bob, you have a home folder located at /home/bob. This home folder contains the user’s data files and user-specific configuration files. Each user only has write access to their own home folder and must obtain elevated permissions (become the root user) to modify other files on the system.

## /lib — Essential Shared Libraries

The /lib directory contains libraries needed by the essential binaries in the /bin and /sbin folder. Libraries needed by the binaries in the /usr/bin folder are located in /usr/lib.
/lost+found — Recovered Files

    Each Linux file system has a lost+found directory. If the file system crashes, a file system check will be performed at next boot. Any corrupted files found will be placed in the lost+found directory, so you can attempt to recover as much data as possible.
## /media — Removable Media

    The /media directory contains subdirectories where removable media devices inserted into the computer are mounted. For example, when you insert a CD into your Linux system, a directory will automatically be created inside the /media directory. You can access the contents of the CD inside this directory.
## /mnt — Temporary Mount Points

    Historically speaking, the /mnt directory is where system administrators mounted temporary file systems while using them. For example, if you’re mounting a Windows partition to perform some file recovery operations, you might mount it at /mnt/windows. However, you can mount other file systems anywhere on the system.
## /opt — Optional Packages

    The /opt directory contains subdirectories for optional software packages. It’s commonly used by proprietary software that doesn’t obey the standard file system hierarchy — for example, a proprietary program might dump its files in /opt/application when you install it.
##  /proc — Kernel & Process Files

    The /proc directory similar to the /dev directory because it doesn’t contain standard files. It contains special files that represent system and process information.

## /root — Root Home Directory

    The /root directory is the home directory of the root user. Instead of being located at /home/root, it’s located at /root. This is distinct from /, which is the system root directory.
## /run — Application State Files

    The /run directory is fairly new, and gives applications a standard place to store transient files they require like sockets and process IDs. These files can’t be stored in /tmp because files in /tmp may be deleted.
## /sbin — System Administration Binaries

    The /sbin directory is similar to the /bin directory. It contains essential binaries that are generally intended to be run by the root user for system administration.

## /selinux — SELinux Virtual File System

    If your Linux distribution uses SELinux for security (Fedora and Red Hat, for example), the /selinux directory contains special files used by SELinux. It’s similar to /proc. Ubuntu doesn’t use SELinux, so the presence of this folder on Ubuntu appears to be a bug.
## /srv — Service Data

    The /srv directory contains “data for services provided by the system.” If you were using the Apache HTTP server to serve a website, you’d likely store your website’s files in a directory inside the /srv directory.

RELATED: How to Find Your Apache Configuration Folder
## /tmp — Temporary Files

    Applications store temporary files in the /tmp directory. These files are generally deleted whenever your system is restarted and may be deleted at any time by utilities such as tmpwatch.
## /usr — User Binaries & Read-Only Data

    The /usr directory contains applications and files used by users, as opposed to applications and files used by the system. For example, non-essential applications are located inside the /usr/bin directory instead of the /bin directory and non-essential system administration binaries are located in the /usr/sbin directory instead of the /sbin directory. Libraries for each are located inside the /usr/lib directory. The /usr directory also contains other directories — for example, architecture-independent files like graphics are located in /usr/share.

The /usr/local directory is where locally compiled applications install to by default — this prevents them from mucking up the rest of the system.

## /var — Variable Data Files

    The /var directory is the writable counterpart to the /usr directory, which must be read-only in normal operation. Log files and everything else that would normally be written to /usr during normal operation are written to the /var directory. For example, you’ll find log files in /var/log.


In the ls -la output, the "rwx" refers to the permissions associated with a file or directory. The permissions are displayed for three different entities: the owner, the group, and other users. Each entity has three permission categories: read (r), write (w), and execute (x). Here's a breakdown of what each permission category represents:

    Read (r): Allows the entity to read or view the contents of a file or the names of files within a directory.
    Write (w): Enables the entity to modify or write to a file or add, delete, or rename files within a directory.
    Execute (x): Grants the entity the permission to execute a file or enter a directory. For directories, execute permission is required to access its contents.
# Users & privileges

In the ls -la output, the permissions are displayed as a series of nine characters. The first character represents the file type (e.g., - for a regular file, d for a directory). The next three characters represent the owner's permissions, followed by the group's permissions, and then the permissions for other users.

For example, let's consider an ls -la output line:

-rwxr-x--- 1 user group 4096 May 10 12:34 myfile.txt 

In this example, the permissions are broken down as follows:

    -rwxr-x---: The first character indicates that it is a regular file. The following three characters (rwx) represent the owner's permissions (read, write, and execute). The next three characters (r-x) represent the group's permissions (read and execute). The last three characters (---) represent the permissions for other users (no permissions).
    1: Indicates the number of hard links to the file.
    user: Refers to the owner of the file.
    group: Refers to the group assigned to the file.
    4096: Indicates the file size in bytes.
    May 10 12:34: Specifies the date and time of the last modification.
    myfile.txt: Represents the name of the file.

It's worth noting that if a permission is not granted for a particular entity, a hyphen (-) is displayed in its place. Additionally, the output can include additional information such as special permissions, ownership, and timestamps.

Here are explanations and examples of the commands mentioned in this video. Please note, Teachable blocks the mention of some of the sensitive paths shown in the video, so we cannot display them in text format here:

chmod (Change Mode):

        Explanation: Changes the permissions of a file or directory.
        Example: Running chmod +x script.sh would add the execute permission to the file "script.sh", allowing it to be executed as a script.

adduser:

        Explanation: Creates a new user account.
        Example: Running adduser john would create a new user account with the username "john" and prompt for additional user information.

su (Switch User):

        Explanation: Allows a user to switch to another user account.
        Example: Running su jane would switch to the user account "jane" after entering the password for that account.

/etc/sudoers:

        Explanation: Displays the content of the "/etc/sudoers" file, which contains configuration information for the sudo command.
        Example: Running /etc/sudoers would display the configuration directives for sudo access and permissions.

sudo -l:

        Explanation: Lists the commands a user is allowed to run with sudo privileges.
        Example: Running sudo -l would display the commands and permissions available to the current user with sudo access.

Please note that some of these commands require administrative privileges, and caution should be exercised when modifying system files or working with user accounts.

# Common Network command
ip a:

        Explanation: Displays the network interfaces and their associated IP addresses.
        Example: Running ip a would show information about network interfaces, including their IP addresses, MAC addresses, and other details.

ifconfig:

        Explanation: Displays the configuration and status of network interfaces.
        Example: Running ifconfig would show the configuration details, including IP addresses, MAC addresses, and other information for active network interfaces.

iwconfig:

        Explanation: Displays the configuration and status of wireless network interfaces.
        Example: Running iwconfig would show the configuration details, such as wireless signal strength, frequency, and encryption information, for active wireless interfaces.

ip n:

        Explanation: Displays the Neighbor Table, which contains the IP-to-MAC address mappings for devices in the local network.
        Example: Running ip n would show the IP and MAC addresses of devices that have recently communicated with the current device.

arp -a:

        Explanation: Displays the ARP (Address Resolution Protocol) cache, which maps IP addresses to MAC addresses.
        Example: Running arp -a would show the IP and MAC addresses of devices that have been resolved recently by the ARP protocol.

ip r:

        Explanation: Displays the routing table, which contains information about network routes.
        Example: Running ip r would show the routing table, including destination networks, gateway IP addresses, and network interfaces.

route:

        Explanation: Displays or manipulates the IP routing table.
        Example: Running route would display the routing table, similar to the ip r command.

ping:

        Explanation: Sends ICMP echo requests to a specified IP address to check network connectivity and measure round-trip time.
        Example: Running ping 8.8.8.8 would send ICMP echo requests to the IP address "8.8.8.8" (Google's DNS server) and display the round-trip time and packet loss statistics.

These commands are commonly used for network troubleshooting, configuration, and gathering network-related information in Linux systems.

# Viewing, Creating & Editing files
echo "hello" > hey.txt:

        Explanation: Creates a new file named "hey.txt" with the content "hello" and overwrites the file if it already exists.
        Example: Running echo "hello" > hey.txt would create a file named "hey.txt" and write the word "hello" into it.

echo "hello again" >> hey.txt:

        Explanation: Appends the content "hello again" to an existing file named "hey.txt" or creates a new file if it doesn't exist.
        Example: Running echo "hello again" >> hey.txt would append the text "hello again" to the end of the "hey.txt" file.

touch newfile.txt:

        Explanation: Creates a new empty file named "newfile.txt" or updates the timestamp of an existing file to the current time.
        Example: Running touch newfile.txt would create an empty file named "newfile.txt" if it doesn't exist or update its timestamp if it already exists.

nano newfile.txt:

        Explanation: Opens the text editor Nano and allows you to create or edit the content of a file named "newfile.txt".
        Example: Running nano newfile.txt would open the Nano editor, where you can enter or modify text in the "newfile.txt" file.

mousepad newfile.txt:

        Explanation: Opens the Mousepad text editor and allows you to create or edit the content of a file named "newfile.txt".
        Example: Running mousepad newfile.txt would open the Mousepad editor, where you can enter or modify text in the "newfile.txt" file.

These commands are commonly used for file manipulation and editing in Linux systems. The echo command is used to print text or variables to the terminal or redirect them to files. The touch command is used to create or update file timestamps. The nano and mousepad commands are text editors that allow you to create and modify files directly from the terminal.

# Starting and stopping Service
sudo service apache2 start:

        Explanation: Starts the Apache web server service.
        Example: Running sudo service apache2 start would initiate the Apache web server and make it available for serving web pages.

sudo service apache2 stop:

        Explanation: Stops the Apache web server service.
        Example: Running sudo service apache2 stop would halt the running Apache web server, shutting down any active web page serving.

python3 -m http.server 80:

        Explanation: Starts a simple HTTP server using Python on port 80.
        Example: Running python3 -m http.server 80 would start a basic HTTP server on port 80, allowing you to serve files from the current directory.

sudo systemctl enable ssh:

        Explanation: Enables the SSH (Secure Shell) service to start automatically on system boot.
        Example: Running sudo systemctl enable ssh would configure the system to start the SSH service during system startup.

sudo systemctl disable ssh:

        Explanation: Disables the SSH service from starting automatically on system boot.
        Example: Running sudo systemctl disable ssh would prevent the SSH service from starting automatically during system startup.

These commands are frequently used in Linux systems for managing services, starting and stopping processes, and enabling or disabling specific services at system startup. The sudo command is used to execute commands with superuser privileges. The service and systemctl commands are used to manage system services.

# Installing And Updating Tools

sudo apt update && sudo apt upgrade:

        Explanation: Updates the package lists and upgrades installed packages on a Debian-based Linux system using the APT package manager.
        Example: Running sudo apt update && sudo apt upgrade would update the package lists to retrieve information about available updates, and then upgrade the installed packages to their latest versions.

sudo apt install cron-daemon-common:

        Explanation: Installs the "cron-daemon-common" package using APT. Cron is a time-based job scheduler in Linux systems, and the "cron-daemon-common" package provides common files and utilities for the cron daemon.
        Example: Running sudo apt install cron-daemon-common would download and install the "cron-daemon-common" package on the system.

sudo git clone https://github.com/Dewalt-arch/pimpmykali.git:

        Explanation: Clones a Git repository from the specified URL using the Git version control system.
        Example: Running sudo git clone https://github.com/Dewalt-arch/pimpmykali.git would clone the repository from the given URL and create a local copy of the repository's files and version history.

These commands are commonly used in Linux systems for updating packages, installing new software, and managing version-controlled repositories. The sudo command is used to execute commands with superuser privileges. The apt command is used for package management in Debian-based distributions. The git command is used for version control and working with Git repositories.

sodu dpkg <deb name>

# some Other commands that we disscuss in physical session
   
                                                                                    




## 

Thankyou everyone
## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.

