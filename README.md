# Group bons plans
**Requeries :**  
php version => *7.4*

Symfony version => *4.4*

*Composer* for Symfony(best utility for  understanding symfony commands)

Install *WampServer*( the best one!)


if first time , execute the following commands :

     composer install
     php bin/console d:d:c
     php bin/console d:s:u --force
     php bin/console doctrine:fixtures:load( load fake data)
then import the user.sql file to your database

if not first time, execute :

    php bin/console composer install

launch server using the commande : symfony serve.
