# metis-cosmic
System files packages for @metis-os

Setup:

Add the following line to your `/etc/pacman.conf`
```bash
[cosmic]
SigLevel = Optional TrustAll
Include = /etc/pacman.d/metis-cosmic
```
and add the server adress to `/etc/pacman.d/metis-cosmic`

```
Server = https://metis-os.github.io/metis-cosmic/$repo/os/$arch
```
