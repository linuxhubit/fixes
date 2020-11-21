## Problem
PulseAudio can't start the daemon

## Solution
Reset all config removing manually the files and restart PulseAudio:

```bash
$ rm -rf /tmp/pulse* ~/.pulse* ~/.config/pulse
$ pulseaudio -k
$ pulseaudio --start
```


### Tested platforms
- Arch Linux
- Fedora 33
- Ubuntu 20.04

