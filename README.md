[![Build Status](https://travis-ci.com/nguyentodo/php-fpm.svg?branch=7.2)](https://travis-ci.com/nguyentodo/php-fpm)

# PHP7-FPM

PHP-FPM from php:7-fpm-alpine3.7 image with some php extension

````
[PHP Modules]
bcmath
Core
ctype
curl
date
dom
exif
fileinfo
filter
ftp
gd
gettext
hash
iconv
intl
json
libxml
mbstring
mcrypt
memcached
mysqli
mysqlnd
openssl
pcre
PDO
pdo_mysql
pdo_pgsql
pgsql
Phar
Reflection
session
SimpleXML
SPL
sqlite3
standard
tokenizer
xml
xmlwriter
xsl
Zend OPcache
zip
zlib

[Zend Modules]
Zend OPcache
````

Also this container turn on the errorlogs for debug and increase post_max_size, upload_max_filesize to 100M
