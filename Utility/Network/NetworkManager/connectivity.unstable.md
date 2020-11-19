## Problem
Unstable connection due to roaming.

## Solution
Force the BSSID for the active network.

We are going to disable the Connectivity Check option in NetworkManager. This by editing the file in `/var/lib/NetworkManager/NetworkManager-intern.conf` and adding the following instructions at the end:

```
[connectivity]
.set.enabled=false
```

Restart service:

```
systemctl restart NetworkManager
```

### Tested platforms
- Pop!_OS 20.10
- Fedora 33
- Arch Linux