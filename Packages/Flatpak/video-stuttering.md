## Problem
Some flatpak apps (like Firefox) suffer stuttering when reproducing videos.

## Solution
Install `org.freedesktop.Platform.openh264`:
```
flatpak install flathub org.freedesktop.Platform.openh264/x86_64/19.08
```
and `org.freedesktop.Platform.ffmpeg-full`:
```
flatpak install flathub org.freedesktop.Platform.ffmpeg-full
```

### Tested platforms
- Fedora 33
