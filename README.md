# Laravel-lumen-React.Js-Newborn
Aplikasi web untuk kelola data bayi dengan menggunakan backend Laravel Lumen dan frontend React.JS

download terlebih dahulu file dengan format zip, kemudian lakukan extract file here menggunakan winrar

UNTUK MENJALANKAN SERVER backend - Laravel Lumen

cd newborn
cd backend
composer install && composer update
buat database kosong di mysql dan sesuaikan database yang dibuat dengan nama database yang diatur di file .env(database di .env = backends, atau bisa juga menggunakan database yang tersedia)
php artisan migrate
php -S localhost:8000 -t public
frontend - React Js MUI

cd newborn
cd frontend
npm install(untuk membangun node_modules yang diperlukan)
npm start
running terlebih dahulu backend lumen baru setelah itu frontend react js untuk backend dan frontend running di 2 terminal yang terpisah.

aplikasi dibangun menggunakan xampp versi 8.1.17, untuk database menggunakan MySQL Yog port lumen berjalan di port 8000, sedangkan port react js berjalan di port 3000
