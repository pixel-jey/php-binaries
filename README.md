# php-binaries

## config
sudo unzip php*

sudo \cp -r usr/ /

## openssl
ll /usr/local/openssl/openssl-1.1.1i/bin/lib/pkgconfig

echo "/usr/local/openssl/openssl-1.1.1i/bin/lib" | sudo tee /etc/ld.so.conf.d/openssl-1.1.1i.conf

sudo ldconfig -v | grep libssl #openssl

## test
ls /usr/local/php

php7.1/ php7.4/ php8.1/ php8.5/

## version
/usr/local/php7.1/bin/php -version


