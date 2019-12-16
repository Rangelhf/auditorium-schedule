# Auditorium Schedule
## Development of an auditorium scheduling system
Development of a web system for Crede 11 Auditorium Scheduling.

## How to Install

```bash
# Install php
sudo apt install php

# Installing php and Laravel Extensions
sudo apt install php7.2-zip
sudo apt install php7.2-mbstring
sudo apt install php-xml

#Installing Curl 
sudo apt install curl

#Installing Composer
curl -sS https://getcomposer.org/installer
sudo apt install composer

#Installing Laravel
cd /diretorio_do_Projeto
composer global require "laravel/installer"

#Creating global variable
sudo pico ~/.bashrc
export PATH="~/.config/composer/vendor/bin:$PATH"
source ~/.bashrc
```
# Creating Project with Laravel

```bash
#Creating Project
laravel new auditorium-schedule

#Creating key in Laravel
php artisan key:generate

#Creating autentication for user
composer require laravel/ui --dev
php artisan ui vue --auth

```

# References

[Documentation Laravel iniciante](https://laravel.com/docs/6.x)





