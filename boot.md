
info grub
man grub-install(8)

## Background
`GRUB_BACKGROUND` in `/etc/default/grub`
or
/boot/grub


## Mount
`/etc/fstab`
man fstab(5)

`/etc/crypttab`
man crypttab(5)

RAID
`/etc/mdadm/mdadm.conf`
man mdadm.conf(5)


## Emptied after mount
/tmp
/var/lock
/var/run


## Show kernel message

`dmesg`
addition options:
+ -n@level@    [0 important - 7 details]

## Show system message
`journalctl -b`
