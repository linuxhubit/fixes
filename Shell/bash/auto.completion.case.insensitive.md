## Problem
Bash shell only complete case-sensitive.

## Solution
Make completion case-insensitive.

Append the following to `~/.bashrc`:

```
bind 'TAB':menu-complete
bind "set show-all-if-ambiguous on"
bind "set completion-ignore-case on"
```

*Restart* shell:

```
source ~/.bashrc
```

### Tested platforms
- Fedora 33
- Arch Linux
- Ubuntu 20.10
