
## Browser

apt install chromium firefox w3m

## SSH

apt install openssh-client openssh-server

```
ssh
sshd
ssh-agent
ssh-keygen
ssh-add

/etc/ssh/ssh_config
/etc/ssh/sshd_config

~/.ssh/authorized_keys
~/.ssh/id_rsa
```


```
ssh-keygen -t rsa
cat .ssh/id_rsa.pub | ssh user1@remote "cat - >>.ssh/authorized_keys"
```


## Share files

apt install samba nfs-kernel-server netatalk proftpd-basic squid

samba for windows
nfs-kernel-server for Unix
netatalk for Apple
proftpd for ftp share
squid for web proxy

## Others

apt install
netcat
nfs-common
smbclient
cifs-utils
wget
curl
