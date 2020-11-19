## Problem
Some flatpak apps can't connect to the internet.

## Solution

Add `rc-manager=symlink` to `[main]` section in  `/etc/NetworkManager/NetworkManager.conf`.

Deelte the file at location:
```
/etc/resolv.conf
```
and restart NetworkManager:
```
systemctl restart NetworkManager
```

Ref: https://bugzilla.suse.com/show_bug.cgi?id=1128358#c4

### Tested platforms
- Fedora 33