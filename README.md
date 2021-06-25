# proyectoedu
pasos para instalar:
git clone https://github.com/belliniedu/proyectoedu
cd proyectoedu
composer install
php bin/console doctrine:database:create
bin/console doctrine:schema:update --force

saludos