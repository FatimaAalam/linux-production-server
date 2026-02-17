# linux-nginx-server-deployment
Created EC2 instance. Allowed SSh, HTTPS, HHTP.
Connected instance using SSH.
Updated system 
```
Sudo apt Update
```
Install nginx 
```
sudo apt install nginx -y
sudo systemctl enable nginx
```

Check nginx status
```
systemctl status nginx
```
Goto folder `/var/wwww/html` folder created html file.
Write HTML code to serve.
Paste ip on chrome -- Boom -- HTML on chorome-
