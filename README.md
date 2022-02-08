# nmap

## scan 1-1024
```
nmap -PN lapetiteboutiquefrancaise.fr
Starting Nmap 7.70 ( https://nmap.org ) at 2022-02-08 17:38 CET
...
Not shown: 997 filtered ports
PORT    STATE SERVICE
22/tcp  open  ssh
80/tcp  open  http
443/tcp open  https

```

## scan all ports
```
nmap -n -p1-65535 -P0 localhost

Starting Nmap 6.40 ( http://nmap.org ) at 2021-05-12 15:47 CEST
Nmap scan report for localhost (127.0.0.1)
Host is up (0.000033s latency).
Other addresses for localhost (not scanned): 127.0.0.1
Not shown: 65526 closed ports
PORT      STATE SERVICE
22/tcp    open  ssh
25/tcp    open  smtp
80/tcp    open  http
443/tcp   open  https
444/tcp   open  snpp
8080/tcp  open  http-proxy
9000/tcp  open  cslistener
25000/tcp open  icl-twobase1
50000/tcp open  ibm-db2
```
