1. Download file.
2. Run xampp.
3. create database di phpmyadmin dengan nama laravel_socialite
4. Pastikan nama database pada file .env -> DB_DATABASE=laravel_socialite
5. Dapatkan CLiENT ID & SECRET ID google dan GitHub
6. Masukkan CLiENT ID & SECRET ID google dan GitHub pada file .env
    GOOGLE_CLIENT_ID= {isi dengan client ID google anda}
    GOOGLE_CLIENT_SECRET= {isi dengan client secret google anda}
    GOOGLE_CLIENT_REDIRECT=http://localhost:8000/auth/google/callback

    GITHUB_CLIENT_ID= {isi dengan client ID GitHub anda}
    GITHUB_CLIENT_SECRET={isi dengan client secret GitHub anda}
    GITHUB_CLIENT_REDIRECT=http://localhost:8000/auth/github/callback

7. Jalankan perintah "php artisan migrate"
8. Jalankan perintah "php artisan serve"
9. Terdapat tombol login dan register pada bagian atas kiri website atau ke halaman http://localhost:8000/login dan juga http://localhost:8000/register
