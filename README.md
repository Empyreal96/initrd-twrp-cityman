# initrd-twrp-cityman (TWRP4GRUB?)
# Repo containing my edits on the Nexus 6P TWRP Ramdisk working with the Lumia 950 XL (When I say working.. It boots and touch works, partitions will need to be manually reflected in the fstab)
# This is just a 'For Fun' project I am doing, this is by no means a start to running Android or anything like that.. I am just wasting time with what I can do with TWRP and Grub


# Recent Edits: #

- Added bash binary to ramdisk compiled for ARM (https://forum.xda-developers.com/android/software-hacking/dev-lastest-bash-android-t2898295)

- Replaced with my modified version of the Material TWRP theme.. It's now a 'Windows Mobile' inspired theme. (Original theme: https://forum.xda-developers.com/android/themes/theme-twrp-materialised-dark-light-play-t2915584)


# Second Edits: #

- Tweaked the UI to give it a more 'Windows' feel.

- Edited the fstab to hopefully prevent modifying 'unique' partitions, still need to block PLAT partition, help would be welcomed.

- Can back up Windows System, EFIESP and Windows Data to TWRP's Allocated partition.

# First Edits: #

- Initial public upload, VERY basic and most things don't work.

- NTFS support,

- Linked to MY partition layout, Windows MainOS Drive as System, Windows Data as Internal, EFIESP as Boot



Thanks to @ J0SH1X on Twitter for the initial pointers on loading TWRP, And thanks to Fadil Fadz @ YT for helping with ideas and helping test!

For some reason on my Dual Boot system, my Ubuntu install is still linked to my old account (mrfloaty) and notthe current one, despite changing my settings.

# This is the raw ramdisk, not the actual files needed to boot
# If you want to try this but don't know how to 'install' it, go through the means and head over to WoA-project's github, install Windows ARM64 and all the requirements (bootshim, UEFI loader etc.), then after you are familiar with that, head over to my website and follow the Linux on 950XL guide on my website, specifically obtaining the boot files (grub) and the required android kernel and initramfs found In that repo, copy to device and configure grub..
