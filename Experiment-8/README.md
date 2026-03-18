Aim:

 To understand and demonstrate how to identify storage devices in Linux, manually mount and unmount file systems, and comprehend the importance of mount points and device management in system administration and cybersecurity contexts.

Objective:

 Identify storage devices (hard disks, USB drives, external storage) in Linux.

 Manually mount and unmount file systems.

 Learn how Linux integrates storage devices into a unified directory structure.

 Understand implications for system administration and cybersecurity.

Theory:

Linux represents hardware devices as files in the /dev directory:

  /dev/sda, /dev/sdb – Hard disks

  /dev/sda1, /dev/sdb1 – Disk partitions

Mount Points: Empty directories where devices are attached, e.g., /mnt or /media.

Unmounting Devices: Safely disconnects the device from the file system to prevent data corruption.

Key Commands:

Command	Description
lsblk	List block devices
fdisk -l	Display disk partition info
mount	Mount a file system
umount	Unmount a file system
df -h	Display mounted file systems
mkdir	Create mount point
blkid	Display block device attributes
Network/Device Topology

(Attach screenshot of storage device layout or VM terminal with mounted devices in screenshots/topology.png)

Procedure
Step 1: Identify Devices
