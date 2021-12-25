# Apache2-And-PHP-Setup-For-Termux

```
apt update
```

```
apt upgrade
```

```
apt install apache2 php-apache php
```

```
apt install git && git clone https://github.com/WLS-SD/Apache2-And-PHP-Setup-For-Termux
```

```
cd Apache2-And-PHP-Setup-For-Termux && chmod 777 * && ./apachephp.sh && termux-setup-storage
```

#To Start Server

```
httpd
```



```
apachectl
```


#To Kill Server

```
apachectl -k stop 
```

### or


```
killall httpd
```


#To watch Pid 

```
ps aux
```

