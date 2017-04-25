# phpmyadmin-boilerplate
[![Build Status](https://travis-ci.org/solsoft/phpmyadmin-boilerplate.svg?branch=4.x)](https://travis-ci.org/solsoft/phpmyadmin-boilerplate)
[![Dependency Status](https://www.versioneye.com/user/projects/58feac47710da23f8cb4e927/badge.svg?style=flat-square)](https://www.versioneye.com/user/projects/58feac47710da23f8cb4e927)
[![Packagist](https://img.shields.io/packagist/vpre/solsoft/phpmyadmin-boilerplate.svg)](https://packagist.org/packages/solsoft/phpmyadmin-boilerplate)
[![PHP 7 ready](https://php7ready.timesplinter.ch/solsoft/phpmyadmin-boilerplate/4.x/badge.svg)](https://travis-ci.org/solsoft/phpmyadmin-boilerplate)
[![License](https://poser.pugx.org/solsoft/phpmyadmin-boilerplate/license)](https://github.com/solsoft/phpmyadmin-boilerplate/blob/4.x/LICENSE)

Boilerplate for deploying new [phpMyAdmin](https://www.phpmyadmin.net/) projects.  
Using [Composer](https://getcomposer.org/) and associated plugins, and the official [phpmyadmin.net](https://www.phpmyadmin.net) repository.  
Packages are published and updated regularly at [Packagist](https://packagist.org/packages/solsoft/phpmyadmin-boilerplate).  

## phpMyAdmin versions supported
- phpMyAdmin 4.7.x

## Development branches
- 4.x - development branch for the latest phpMyAdmin 4.7.x

## Usage
Before starting, consult the Composer reference for standard usage instructions.  
Use `composer create-project` to deploy a new project, specifying one branch.

```
composer create-project solsoft/phpmyadmin-boilerplate:4.x-dev my-project --stability dev --no-interaction;
cd my-project;
composer update;
composer show;
composer run;
```

## Contributing
Clone the git repository pointing to one of the development branches.  
Merge requests should be submitted against these branches.

```
git clone -b 4.x git@github.com:solsoft/phpmyadmin-boilerplate.git;
cd phpmyadmin-boilerplate;
composer install;
composer update;
composer show;
composer run;
```

### Extras
The project can be reset by running `composer cleanup-project` to delete
the `vendor/` and `app/` directories and the `composer.lock` file.

## Credits
phpMyAdmin Boilerplate  
Copyright (C) 2017 SOL-Soft  
Luís Pedro Algarvio  

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
