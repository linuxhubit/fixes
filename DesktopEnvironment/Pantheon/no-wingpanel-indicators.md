## Problem
There is no systemtray in wingpanel.

## Solution
Install patched wingpanel-indicator-ayatana:

```
mkdir ~/.tmp && cd ~/.tmp
wget https://github.com/mdh34/elementary-indicators/releases/download/0.1/indicator-application-patched.deb
dpkg -i indicator-application-patched.deb
wget https://github.com/Lafydev/wingpanel-indicator-ayatana/blob/master/com.github.lafydev.wingpanel-indicator-ayatana_2.0.7_odin.deb
dpkg -i com.github.lafydev.wingpanel-indicator-ayatana_2.0.7_odin.deb
rm com.github.lafydev.wingpanel-indicator-ayatana_2.0.7_odin.deb com.github.lafydev.wingpanel-indicator-ayatana_2.0.7_odin.deb
reboot
```

Ref: https://github.com/Lafydev/wingpanel-indicator-ayatana

### Tested platforms
- elementary OS 6
