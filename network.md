
## DNS

mdns

/etc/hostname

/etc/resolv.conf

## Set network

/etc/systemd/network/

samples:


/etc/systemd/network/dhcp.network
```
[Match]
Name=en*

[Network]
DHCP=yes
```


/etc/systemd/network/static.network
```
[Match]
Name=en*

[Network]
Address=192.168.0.15/24
Gateway=192.168.0.1
```


## Use iproute2

`apt install iproute2`

ip addr

ip route
ip neigh
ip maddr
ip tunnel
ifrename
ethtool


## Tools

`apt install iftop bmon ethstats`