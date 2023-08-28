
## Edit source

/etc/apt/sources.list

/etc/apt/sources.list.d/*.list
/etc/apt/sources.list.d/*.source


## User build

install your build to `/usr/local` or `/opt`


## new style source

```
Types: deb deb-src
URIs: http://deb.debian.org/debian/
Suites: bookworm
Components: main non-free-firmware contrib non-free

Types: deb deb-src
URIs: http://security.debian.org/debian-security/
Suites: bookworm-security
Components: main non-free-firmware contrib non-free
```

## Alternatives

`update-alternatives`


## Auto update
/etc/cron.daily/apt

## Configurations

speed limit(kbits/s)
`APT::Acquire::http::Dl-Limit "800";`


## Proxy

man apt.conf(5)
`$http_proxy` `/etc/apt/apt.conf`
