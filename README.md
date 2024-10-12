# Partition-a-Disk-in-Linux

Partitioning a disk in Linux involves dividing a physical disk into logical segments (partitions) to organize data and allocate space for different purposes, such as installing operating systems, storing files, or configuring swap space. Each partition can be formatted with its own file system, and it acts like a separate disk. Here's an overview of how to partition a disk in Linux. I will walk with you step by step on how to partition a disk, also providing screeshot to walk you through the whole process. 


 1. Identify the disk:

   First, you need to identify the disk you want to partition. You can use the lsblk or fdisk -l command to list available disks and partitions:
   Run the Following Command: sudo fdisk -l
<p align="center">
<img src="https://imgur.com/ykogwVj.png" height="80%" width="80%" >


  2. After updating, run the following command to install ClamAV:

      sudo apt-get install clamav clamav-daemon
<p align="center">
<img src="https://imgur.com/gTy6uns.png" height="80%" width="80%" >
