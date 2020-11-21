## Problem 
Problem with plasma and kde-applications configuration

## solution
reset all config removing manually the files:

```bash
cd 
rm -rf .config/plasma-workspace .kde4  .local/share/plasma* .config/kde* 
reboot  
```

### Tested platforms
- Archlinux
