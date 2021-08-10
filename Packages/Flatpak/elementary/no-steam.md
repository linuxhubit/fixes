## Problem
Steam is not available on elementary repositories.

## Solution
Enable multiverse.

```
dpkg --add-architecture i386
sudo add-apt-repository multiverse
sudo apt-get update
sudo apt-get dist-upgrade
```

Ref: https://askubuntu.com/a/958965

### Tested platforms
- elementary OS 6
