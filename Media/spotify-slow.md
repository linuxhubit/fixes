## Problem
Spotify is slow with obvious lag.

## Solution
Pass the `LIBGL_ALWAYS_SOFTWARE=1` env to the executable:

```
LIBGL_ALWAYS_SOFTWARE=1 spotify
```

For desktop entries:

```
env LIBGL_ALWAYS_SOFTWARE=1 spotify
```

Ref: https://community.spotify.com/t5/Desktop-Linux/Troubleshooting-Linux-Spotify/td-p/1192307/page/14

### Tested platforms
- Ubuntu 20.10
