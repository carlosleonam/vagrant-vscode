# vagrant-vscode
## Debug PHP project hosted on Vagrant VM with VSCode (Visual Studio Code)

I'm using this environment:
- Vagrant Hosted on Windows 7 (called "Host")
- PHP 7.1 install on **Host**
- VM based on Ubuntu 14.04

### Testing Xdebug on VM
Run this command (pay attention to CamelCase)
```
php -i | grep Xdebug
```
If result like this:
```
with Xdebug v2.5.5, Copyright (c) 2002-2017, by Derick Rethans
```
Xdebug is enabled on your VM. Otherwise, install it follow any of instructions links:

_Xdebug on Ubuntu 16.04 with PHP7
http://www.dieuwe.com/blog/xdebug-ubuntu-1604-php7_


