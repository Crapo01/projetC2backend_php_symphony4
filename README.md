# /////////////////// SYMFONY 4 ////////////////////////////

# projetC2backend_php_symfony4

environnement PHP 7.0 min et  Composer  
wampserver  pour base de données

# create project

cmd:  
composer create-project symfony/skeleton:"7.1.*" my_project_directory  
cd my_project_directory  
composer require webapp  if needed

or 

symfony new learn_symfony4 or --webapp   if needed  


# install symfony cli

https://symfony.com/download

cmd: scoop install symfony-cli

# Start server

cmd: symphony server:start or symfony serve

# install profiler

https://symfony.com/doc/current/profiler.html

cmd: cd .\learn_symfony4\   
composer require --dev symfony/profiler-pack
 

set in .env folder  APP_ENV= DEV/PROD/TEST   (!!!!security issues!!!!)

# reinstall dependencies

composer install


