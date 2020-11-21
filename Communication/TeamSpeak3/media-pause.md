## Problem
When Team Speak 3 is running, media players are paused.

## Solution
Disable (comment) `module-role-cork` in `/etc/pulse/default.pa`, then restart pulseaudio `pulseaudio -k`.

## Tested platforms
- Arch Linux
- Fedora 32/33
- Pop!_OS 20.10
- Ubuntu 20.04/20.10
- elementary OS 5.1
- Clear Linux
