# lemp-basic
Conf files of a simple Nginx/PHP/MySQL on Amazon Linux2 AMI.

I'll be adding detailed instructions on the how to install each module

This was made at an Amazon Linux2 AMI (RedHat based): ami-04681a1dbd79675a5  (As of 17/09/2018)

## Notes about the files in this repo:
- nginx-basic.conf -> goes to /etc/nginx/sites-available/  (with its proper symlink ln -s /etc/nginx/sites-available/nginx-basic.conf /etc/nginx/sites-enabled/nginx-basic.conf)

- nginx.conf -> goes to /etc/nginx  (backup the original if there isn't a backup already : mv /etc/nginx.conf /etc/nginx.conf.backup)

- php-fpm.conf -> goes to /etc/ (backup the original if there isn't a backup already : mv /etc/php-fpm.conf /etc/php-fpm.conf.backup)

- www.conf -> goes to /etc/php-conf.d/ (again, backup the original if there isn't a backup already : mv /etc/php-conf.d/www.conf /etc/php-conf.d/www.conf.backup)
