# Composer
Composer is used to list PHP dependencies as well as external assets.  
A few packages are used to expand composer's functionality:
- [cweagans/composer-patches](https://github.com/cweagans/composer-patches): applies custom patches to dependencies
- [wikimedia/composer-merge-plugin](https://github.com/wikimedia/composer-merge-plugin): merges additional composer.json files
- [composer/installers](https://github.com/composer/installers): supports additional types of packages and their custom paths
- [mnsami/composer-custom-directory-installer](https://github.com/mnsami/composer-custom-directory-installer): allows custom paths for any type of package
- [derhasi/composer-preserve-paths](https://github.com/derhasi/composer-preserve-paths): to force paths and files to be preserved

## Dependencies
The dependences and managed and organized into different directories:
- app: phpMyAdmin Core
- vendor: Composer packages and phpMyAdmin dependencies

## Configuration
Composer will look for composer.json configuration files in a variety of places.  

### Standard
The main file is loaded with the minimum set of configuration and dependencies:
- composer.json

### Composer directory
The `composer/` directory may contain files to add additional dependencies. 
Custom configuration and dependencies may be loaded from:
- composer/composer.local.json

### phpMyAdmin Core
The Core configuration is loaded to provide additional dependencies:
- app/composer.json
