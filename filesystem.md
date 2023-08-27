/etc/      system config
/var/log/  system logs
/home/     user directory
/dev/



## Owner ship
chown
change owner

chgrp
change file group

chmod
change file access mode

umask
change new file's access mode



## Groups
Some useful group with more power
- audio
- video
- adm
- staff
- sudo
- lpadmin

## File time stamp
mtime
 modify time

ctime
 status modify time

atime
 access time


## Links

- Hard link
  ln

- Symbol link
  ln -s

## Pipe
mkfifo @name@
 make file named pipe(first in first out)


## Special devices
/dev/
- null
- zero
- random
- urandom
- full

## Process files
*Only* on Linux
/proc/


## Tmpfs

- /run
- /var/run  -> /run
- /var/lock -> /run/lock
- /dev/shm  -> /run/shm