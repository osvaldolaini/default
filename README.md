# default

# list
    - Laravel 8x
    - Breeze 1.9.2
    - Font awesome
    - Socialite
    - Login personalizado com tailwindcss
 # leng
    - composer require lucascudo/laravel-pt-br-localization --dev
    - php artisan vendor:publish --tag=laravel-pt-br-localization
    
    // Altere Linha 83 do arquivo config/app.php para:
    'locale' => 'pt-BR',
    // Altere Linha 70 do arquivo config/app.php para:
    'timezone' => 'America/Sao_Paulo',
