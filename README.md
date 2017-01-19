# Issues

ubuntu远程桌面连接闪退

change the file in /root/.vnc/xstartup to the below:
```
#!/bin/sh

unset SESSION_MANAGER
exec /etc/X11/xinit/xinitrc
```
