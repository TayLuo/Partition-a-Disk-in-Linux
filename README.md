# Partition-a-Disk-in-Linux

Partitioning a disk in Linux involves dividing a physical disk into logical segments (partitions) to organize data and allocate space for different purposes, such as installing operating systems, storing files, or configuring swap space. Each partition can be formatted with its own file system, and it acts like a separate disk. Here's an overview of how to partition a disk in Linux. I will walk with you step by step on how to partition a disk, also providing screeshot to walk you through the whole process. 


 1. Identify the disk:

     First, you need to identify the disk you want to partition. You can use the "sudo fdisk -l" command to list available disks and partitions:
     Run the Following Command: sudo fdisk -l
<p align="center">
<img src="https://imgur.com/uYSnwkH.png" height="80%" width="80%" >


 2. Adding a virtual disk on Azure:

<p align="center">
<img src="https://imgur.com/l7WUlQF.png" height="80%" width="80%" >

 3. Verify the virtual disk just added to the VM.


     Run the Following Command: sudo fdisk -l
<p align="center">
<img src="https://imgur.com/i3Owace.png" height="80%" width="80%" >

 4. Launch the Partitioning Tool:

    This command opens the fdisk utility for the specified disk (/dev/sdc in this example).

    sudo fdisk /dev/sdc
<p align="center">
<img src="https://imgur.com/iS5goDv.png" height="80%" width="80%" >


 5. Create a New Partition: 

    Use this command to create a new partition (inside fdisk):
    
    
     Run the Following Command: n
<p align="center">
<img src="https://imgur.com/DRtJi4L.png" height="80%" width="80%" >


 6. Identify the disk:

     First, you need to identify the disk you want to partition. You can use the "sudo fdisk -l" command to list available disks and partitions:
     Run the Following Command: sudo fdisk -l
<p align="center">
<img src="https://imgur.com/uYSnwkH.png" height="80%" width="80%" >

 1. Identify the disk:

     First, you need to identify the disk you want to partition. You can use the "sudo fdisk -l" command to list available disks and partitions:
     Run the Following Command: sudo fdisk -l
<p align="center">
<img src="https://imgur.com/uYSnwkH.png" height="80%" width="80%" >


 1. Identify the disk:

     First, you need to identify the disk you want to partition. You can use the "sudo fdisk -l" command to list available disks and partitions:
     Run the Following Command: sudo fdisk -l
<p align="center">
<img src="https://imgur.com/uYSnwkH.png" height="80%" width="80%" >
