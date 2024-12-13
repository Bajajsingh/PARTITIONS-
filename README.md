# Create a HOWTO document to explain how to add 2 additional drive to a virtual machine.

Im am using linux 
first step: open vitural box
.make your virtural machine must be turn off

. open setting and click on storege

. click on add hard disk later click on create and set size of hard disk and click svae 

.inorder to add another one more drive just follow the same path

. Turn on thr machine and use gparted aplicartion to  loclate the drive

.select the drive which you want to locate and click on device and apply to create partition table to apply

.the click on partition and select the size for partion 

. if want to create more patitions click again on partition and select the size and click on add

.after adding the partition click on the tick mark wich you can see downside the help  option and click apply 

# In windows partition a disk drive into 3 partition

.Ensure the disk you want to partition is unallocated (empty). If the disk has data, back it up as partitioning will erase all data on the drive
.Open Disk Management locate the unallocated drive (it will show as Unallocated)

.Right-click the unallocated space and select New Simple Volume

.The New Simple Volume Wizard will appear. Click Next

.Specify the volume size for the first partition. You can choose any size (e.g., 100 GB)

.Choose NTFS as the file system and assign a drive letter (e.g., E:)

.Complete the wizard, and the partition will be created and formatted

.inorde to create more partition right-click the remaining unallocated space Select New Simple Volume and repeat the process as you did for the first partition

.Assign the desired size and file system (NTFS).
