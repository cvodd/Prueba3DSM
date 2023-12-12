# Prueba3DSM

PASOS BACKEND

copy .env.example .env

composer install

php artisan key:generate

-CONFIGURACION SQL

crear base de datos con los datos definidos en el .env

php artisan migrate --seed

php artisan serve

PASOS FRONTEND

npm install
npx expo start --web

no es necesario cambiar la direccion de la api porque funciona con la red local
