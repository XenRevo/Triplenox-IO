#NGINX Configuration

Below you can find the code for the NGINX configuration, if you're using NGINX instead of .htaccess; add this into your configuration in /etc/nginx/sites-available/default for it to work, and restart NGINX.

```
server {
    error_page 404 /404.html;
    error_page 403 /403.html;
    autoindex off;
}
```