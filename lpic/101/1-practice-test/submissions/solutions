D
The pre-operating steps to boot performed by a system with BIOS are the POST process, activation of basic components to  load the system, loading of the first stage of the bootloader from the MBR and the calling of the second stage of the bootloader by the first stage whereas for a system with UEFI,the POST process is done, then the UEFI reads the definitions stored in the NVRAM followed by the activation of the basic components to load the system and then loading of the loading of the kernel to start the o.s. Also, the UEFI identifies partitions and read many filesystems which is not done by the BIOS and also the BIOS relies on the MBR but the UEFI does not.
**lsmod** to list all currently loaded modules and **modprobe dummy** to load the module dummy
The /proc directory found in the root directory contains sudo files that contain information about system processes and resources. Here, we can find files such as the /proc/locks and /proc/uptime while the /sys directory also found in the root directory contains info to interact with the kernel, some sub directories found in it include the kernel,module,block and firmware directories.
C
the apt provides a high-level commandline interface for the package management system and when used to install a package, installs with dependencies and goes to the repository while dpkg is a medium level tool used to install only the package without the dependemcies 
apt --auto-remove or dpkg -r and apt upgrade

B 
cat /var/log/syslog | grep error |  wc -l
A hard link is a special  file which points directly to the inode of the original file on the disk. Deleting one of the hardlinks of a file does not delete the actual data until all the hardlinks are deleted and can not be  created accross different filesystems as symbolic links while symbolic links are special files that point to the path of another file.If the original file is deleted the link becomes broken as it points to a location that is o more.
cd /etc && find *.conf -ctime 7
The cron daemon runs continuosly and wakes up every minute to check a set of tables known as crontabs to find tasks to execute. 
B
blkid     
Both ext3 and ext4 file systems support journaling but ext4 filesystems  are designed for high capacity storage and can support files more than 4GB and the default max size of a single file in ext4 is 16TB.
First use the lsblk on your terminal  to list all block devices and choose one of them on which the partittion will be created.Type the command fdisk <block_device>. Then type the command n for new partition and then follow the instructions that follows to set the partition the way you want it to be,(instruction such as the type of partion  (either primery or extended), first and last sector sizes. Then type the p command after successfully creating the partition to display the partition table. To create the filesystem type the t command and follow the instructions to find which number is assigned to the ext4 filesystem then enter the number to create the  filesystem.To mount the partition first create the directory data using  mkdir data and  then mount <new_partion> data  
The /etc/fstab file contains information on all filesystems mounted on your system or machine.command:mount -t ext4
When the machine is powered on, the POST(power-on-self-test) process is executed to verify any hardware system failures then the BIOS activates the basic components to load the system such as video output, keyboard and storage meia then the BIOS activates the first stage of the bootloader(GRUB) from the MBR(the first  440 bytes of the first device as defined in the BIOS configuration utility). The first stage of the GRUB calls the second stage of the GRUB responsible for loading the kernel which starts the OS.
