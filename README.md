# Apache2-And-PHP-Setup-For-Termux

# Command 1:~ 

```
apt update
```
# Command 2 :~

```
apt upgrade
```

# Command 3:~ 
```
apt install apache2 php-apache php
```

# Command 4:~ 
```
apt install git && git clone https://github.com/WLS-SD/Apache2-And-PHP-Setup-For-Termux
```

# Command 5:~ 
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

