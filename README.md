# metis-cosmic

***Extra pkgfiles // packages for @metis-os***

Setup:

Add the following line to your `/etc/pacman.conf`
```bash
[cosmic]
SigLevel = Optional TrustAll
Include = /etc/pacman.d/metis-cosmic
```
and add the server adress to `/etc/pacman.d/metis-cosmic`

```
# main
Server = https://metis-os.github.io/repo-cosmic/$repo/os/$arch

# subdomain
Server = https://repo-cosmic.metislinux.org/$repo/os/$arch
```

