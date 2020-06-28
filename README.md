### Nginx reverse proxy to webserver local like apache

## Steps

# 1.Install nginx and rename the nginx.conf file

```sh
yum install nginx -y
```

# 2. Add the nginx.conf file, start and enable nginx

```sh
systemctl enable nginx && systemctl start nginx
```
