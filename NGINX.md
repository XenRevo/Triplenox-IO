#NGINX Configuration

Below you can find the code for the NGINX configuration, if you're using NGINX instead of .htaccess; add this into your configuration located at /etc/nginx/sites-available/default (Ubuntu) for it to work, and restart NGINX.

```
server {
    error_page 404 /404.html;
    error_page 403 /403.html;
    autoindex off;
}
```
