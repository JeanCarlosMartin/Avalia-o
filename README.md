# Avaliação

# restaurar padrão config Linux

docker context use default

# Instalação com mysql

curl -s "https://laravel.build/modelo?with=mysql" | bash

# Iniciar o Docker Laravel

cd Jaquetasltda
 
./vendor/bin/sail up

# Iniciar a base de dados

./vendor/bin/sail artisan migrate

# Instalar o Breeze

composer require laravel/breeze --dev

php artisan breeze:install
 
php artisan migrate
npm install
npm run dev