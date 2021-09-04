# vigilant-robot
a graphic designer that wants to learn to code by organizing notes in a logistic fashion visual learning..style
https://duckduckgo.com/?q=how+to+increase+max+file+upload+size+in+xampp+wordpress&t=chromentp&ia=videos#:~:text=Canada%20(en),has%20increased%20successfully.
Type in terminal: cd C:\xampp\apache makecert Type in httpd-xampp.conf: -IfModule mod_rewrite.c- RewriteEngine On # Redirect -xampp folder to https RewriteCond %{HTTPS} !=on RewriteCond %{REQUEST_URI} xampp RewriteRule ^(.*) https:--%{SERVER_NAME}$1 [R,L] # Redirect -phpMyAdmin folder to https RewriteCond %{HTTPS} !=on RewriteCond %{REQUEST_URI} phpmyadmin RewriteRule ^(.*) https:--%{SERVER_NAME}$1 [R,L] # Redirect -security folder to https RewriteCond %{HTTPS} !=on RewriteCond %{REQUEST_URI} security RewriteRule ^(.*) https:--%{SERVER_NAME}$1 [R,L] # Redirect -webalizer folder to https RewriteCond %{HTTPS} !=on RewriteCond %{REQUEST_URI} webalizer RewriteRule ^(.*) https:--%{SERVER_NAME}$1 [R,L] --IfModule-

From <https://www.youtube.com/watch?v=PQZ8wzV9VU8> 
# BEGIN WordPress
# The directives (lines) between "BEGIN WordPress" and "END WordPress" are
# dynamically generated, and should only be modified via WordPress filters.
# Any changes to the directives between these markers will be overwritten.
<IfModule mod_rewrite.c>
RewriteEngine On
RewriteRule .* - [E=HTTP_AUTHORIZATION:%{HTTP:Authorization}]
RewriteBase /
RewriteRule ^index\.php$ - [L]
RewriteCond %{REQUEST_FILENAME} !-f
RewriteCond %{REQUEST_FILENAME} !-d
RewriteRule . /index.php [L]
</IfModule>

# END WordPress
Protocol:	Unknown
Security type:	Unknown
Manufacturer:	Realtek Semiconductor Corp.
Description:	Realtek RTL8821CE 802.11ac PCIe Adapter
Driver version:	2024.0.10.222
Network channel:	7471220
Link speed (Receive/Transmit):	14/14 (Mbps)
Link-local IPv6 address:	fe80::14ca:e604:c3ee:bee1%21
IPv6 DNS servers:	fec0:0:0:ffff::1%1 (Unencrypted)
fec0:0:0:ffff::2%1 (Unencrypted)
fec0:0:0:ffff::3%1 (Unencrypted)
Physical address (MAC):	8C-C8-4B-6A-01-31
