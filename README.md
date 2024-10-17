### Install Multiple PHP
If already have php, add the repo below then install a different version.
```vim
$sudo apt update
$add-apt-repository ppa:ondrej/php
$sudo apt install php8.3
$sudo apt-get install -y php8.3-cli php8.3-mysql php8.3-fpm php8.3-common php8.3-zip php8.3-gd php8.3-mbstring php8.3-curl php8.3-xml php8.3-bcmath php8.3-dom
```
### Switch to PHP version
```vim
$sudo update-alternatives --config php
$sudo a2dismod php5.6
$sudo a2enmod php7.2
```
### Switching between the version of PHP (webserver and command line)
```vim
$ sudo update-alternatives --config php
```
```vim
There are 4 choices for the alternative php (providing /usr/bin/php).

  Selection    Path             Priority   Status
------------------------------------------------------------
* 0            /usr/bin/php7.2   72        auto mode
  1            /usr/bin/php5.6   56        manual mode
  2            /usr/bin/php7.0   70        manual mode
  3            /usr/bin/php7.1   71        manual mode
  4            /usr/bin/php7.2   72        manual mode
Press <enter> to keep the current choice[*], or type selection number:
```
### INSTALL AND UNINSTALL
Install
```vim
$sudo apt-get install php
```
Uninstall
```vim
$sudo apt-get remove –purge php*
$sudo apt-get purge php*
$sudo apt-get autoremove
$sudo apt-get autoclean
```
### CHECK PHP INI PATH
```vim
$php --ini
```
### Install Module
```
$sudo apt-get install php8.1-package_name
```
### NGINX
Update nginx from 7.4 to 8.1
```vim
fastcgi_pass unix:/run/php/php8.1-fpm.sock;
```
### PHP 8.1
[how-to-install-php-8_1-for-nginx-on-ubuntu-20_04](https://www.vps-mart.com/blog/how-to-install-php-8_1-for-nginx-on-ubuntu-20_04)

[how-to-install-php-8-1-and-set-up-a-local-development-environment-on-ubuntu-22-04](https://www.digitalocean.com/community/tutorials/how-to-install-php-8-1-and-set-up-a-local-development-environment-on-ubuntu-22-04)
### INSTALL PHP 7.2 AND MYSQL 5.7 IN Ubuntu 20
[how-to-install-php-7-2-on-ubuntu-16-04](https://www.rosehosting.com/blog/how-to-install-php-7-2-on-ubuntu-16-04/)

[how-to-install-mysql-on-ubuntu-focal](https://computingforgeeks.com/how-to-install-mysql-on-ubuntu-focal/)
