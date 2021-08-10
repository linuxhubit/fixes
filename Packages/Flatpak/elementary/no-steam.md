## Problem
Steam is not available on elementary repositories.

## Solution
Enable multiverse.

```
dpkg --add-architecture i386
add-apt-repository multiverse
apt install software-properties-common
apt update
apt dist-upgrade
apt install steam
```

Ref: https://askubuntu.com/a/958965

### Tested platforms
- elementary OS 6
