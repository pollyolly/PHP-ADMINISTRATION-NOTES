### Install Multiple PHP
```
If already have php, add the repo below then install a different version.
$add-apt-repository ppa:ondrej/php
$sudo apt-install php7.2
```
### Switch to PHP version
```
$sudo update-alternatives --config php
$sudo a2dismod php5.6
$sudo a2enmod php7.2
```
