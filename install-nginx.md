# A/B Testing two versions of a site using Nginx

https://en.wikipedia.org/wiki/A/B_testing


# Installing nginx in mac

` brew install nginx `

# Nginx configuration file

/usr/local/etc/nginx/nginx.conf

The default port is 8080

# Start stop and restarting nginx

`brew services start nginx`

`brew services stop nginx`

`brew services restart nginx`


# Nginx upstream module

http://nginx.org/en/docs/http/ngx_http_upstream_module.html

# Nginx split clients module

http://nginx.org/en/docs/http/ngx_http_split_clients_module.html

# Nginx map module

http://nginx.org/en/docs/http/ngx_http_map_module.html

# Nginx proxy pass module

http://nginx.org/en/docs/http/ngx_http_proxy_module.html#proxy_pass

# Nginx set cookie

add_header set-Cookie "cookie-name:value"