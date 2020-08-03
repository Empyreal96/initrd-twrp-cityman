# initrd-twrp-cityman
# Repo containing my edits on the Nexus 6P TWRP Ramdisk working with the Lumia 950 XL (When I say working.. It boots and touch works, partitions will need to be manually reflected in the fstab)


- Tweaked the UI to give it a more 'Windows' feel.

- Edited the fstab to hopefully prevent modifying 'unique' partitions, still need to block PLAT partition, help would be welcomed.

- Can back up Windows System, EFIESP and Windows Data to TWRP's Allocated partition.



- Initial public upload, VERY basic and most things don't work.

- NTFS rw support,

- Linked to MY partition layout, Windows MainOS Drive as System, Windows Data as Internal, EFIESP as Boot



# This is the raw ramdisk, not the actual files needed to boot
# If you want to try this but don't know how to 'install' it, go through the means and head over to WoA-project's github, install Windows ARM64 and all the requirements (bootshim, UEFI loader etc.), then after you are familiar with that, head over to my website and follow the Linux on 950XL guide on my website, specifically obtaining the boot files (grub) and the required android kernel and initramfs found In that repo, copy to device and configure grub..
