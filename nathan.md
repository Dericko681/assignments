## Sample answer

## Section 1
  1. B. lscpu
   C. top
  2. BIOS is the older version while UEFI is the newer version.

  3. lsmod

  4. /proc: It is used to keep files  of runnig processes.
          It keeps records of the proceeses in the computer and in each domain.
   /sys: It is a file system which keeps computer systems.
         Stores information about all machine ayatems.

## Section 2
  5. apt install package
  6. apt is used to manage repositeries while dpkg is used to install locally.
  apt has the install, update, upgrade and remove function ehile the dpkg has the
  install and remove uptions.
  apt is a high level package manager while dpkg is a low level package manager.
  7. sudo apt list --installed | grep package | apt autoremove
  8. Go to the directory /etc/yum.repos.d and create a file

## Section 3
  9. B. tail
  10. cat /var/log/syslog | grep error | wc -l
  11. Hard  links points to the source file itself while softlink point to the
      to the path of the file.
      Hard links has same inode number as the original file while soft links has
      different inode number.
      Hard link represented using ln command while soft link represented using the ln -s command.
  12. $ sudo find /etc -name .conf -mtime -7
  13. A cron daemon is a sheduled background process which executes commands without the user's
    intervention. for example 0 0 * * * ./backup.sh

Section 4
    14. B. Disk usage in human-readable format
    15. blkid
    16. ext3 has maximum file size of 2TB and snd volume size of 4TB whhie ext4 has  maximum file size of 16TB and snd     volume size of 1EB.
    ext3 supports abit of journaling while ext4 greatly supports journaling
    ext4 has faster performance than ext3
    17. do fdisk -l to see the partition. 
    Choose the partition by fdisk /path to partition
    Choose n to create
    18. /etc/fstab file is a file that contains info about mount partitions and files.
