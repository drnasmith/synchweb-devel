# PHP Composer test 
This shows an example composer.json file for php dependency management.

# Use
Assuming composer.phar is downloaded in this directory...

php composer.phar install

This will download the relevant packages (and specific versions where specified) to a vendor directory.

PHP classes can be loaded by including (requiring) the vendor/autoload.php file

# Repositories
For packages not in packagist.org a git repo can be used - see the dhl_api fork included in this composer.json file.

Found that for git repos the development tag @dev needs to be included.
