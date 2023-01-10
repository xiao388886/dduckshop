# dduckshop
RewriteEngine on
RewriteCond %{SERVER_PORT} 80
RewriteRule ^(.*)$ https://xiao388886.github.io/dduckshop/index.html$1 [R,L]
