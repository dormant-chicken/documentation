When a desktop environment is not installed along with its dependencies, for example when using a minimal installation with a tiling window manager manually installed, 
SMB shares can be unaccessible, install `gvfs` so that it can be accessed:

For example on debian:
```
sudo apt install gvfs*
```
