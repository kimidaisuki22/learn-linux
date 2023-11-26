
## NFS

sudo apt install nfs-common

mount --mkdir -t nfs ip/path localpath
## Samba


sudo apt install cifs-utils
mount --mkdir -t cifs //SERVER/sharename /mnt/mountpoint -o username=username,password=password,workgroup=workgroup,iocharset=utf8//,uid=username,gid=group