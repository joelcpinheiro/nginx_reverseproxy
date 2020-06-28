### Nginx Reverse Proxy with cache to webserver local like apache running on port 8080

#### Steps

##### 1. Install nginx and rename the nginx.conf file

```sh
yum install nginx -y
```

##### 2. Clone this repository on /etc/nginx/, enable and start nginx

```sh
systemctl enable nginx && systemctl start nginx
```

Done!
