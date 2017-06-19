## NDS User Meta Manager
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

## Purpose
The main purpose of this plugin is to learn WordPress plugin development as well as share knowledge of the WordPress API. 
The plugin was created using Object Oriented Constructs, and tested using PHPUnit. 
One can install the plugin using a composer package or manually.

## Description 
A simple admin plugin demo to manage user meta using object oriented constructs. 
Typically these would require tinkering with the wp_usermeta table or using the add/delete_user_meta 
It also makes use of WordPress nonces wrapped in a class to be implemented in an object oriented manner.

## Installation Manually

1. Download the latest archive: https://github.com/nuancedesignstudio/nds-user-meta-manager/archive/master.zip and extract to a folder `nds-user-meta-manager`
2. Upload `nds-user-meta-manager` to the `/wp-content/plugins/` directory
3. Activate the plugin through the 'Plugins' menu in WordPress

## Installation using Composer

1. Download `composer.json` to the root directory of your wordpress installation
2. Run `composer install`
3. Activate the plugin through the 'Plugins' menu in WordPress

## Usage

1. Adds an option in the `Users` section of the Dashboard.
2. Allows one to `view/add/delete` the user meta associated with a user
3. User Meta is added using the add_user_meta wordpress function and is stored in the $table_prefix_usermeta database table

## Credits 
Makes use of the `Plugin Boiler Plate` here: https://github.com/DevinVinson/WordPress-Plugin-Boilerplate

## Screenshots
## WordPress
![User Menu Link](http://www.nuancedesignstudio.in/nds.in/wp-content/uploads/2017/05/nds-user-meta-manager-screen1.png "Access plugin using Users menu in Dashboard")
![Add/View/Delete User Meta](http://www.nuancedesignstudio.in/nds.in/wp-content/uploads/2017/05/nds-user-meta-manager-screen2.jpg "Use Add/View/Delete to perform basic User Meta operations") 

## Composer Installation
![Composer Installation](http://www.nuancedesignstudio.in/nds.in/wp-content/uploads/2017/05/composer-installation-nds-user-meta-manager.png "Composer Installation")

## PHPUnit Tests
![PHPUnit Tests](http://www.nuancedesignstudio.in/nds.in/wp-content/uploads/2017/05/phpunit-nds-user-meta-manager.png "PHPUnit Tests")