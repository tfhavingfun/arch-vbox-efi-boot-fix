# arch-vbox-efi-boot-fix
Fixes the boot problem when you're using efi on virtualbox

    # mkdir /mnt/boot
    # mount /dev/YourBootPartition /mnt/boot
    # echo '\EFI\arch_grub\grubx64.efi' > startup.nsh
    # umount /dev/YourBootPartition
