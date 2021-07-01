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
### Switching between the version of PHP (webserver and command line)
```
$ sudo update-alternatives --config php
output:
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
