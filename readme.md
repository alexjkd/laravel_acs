## STEPS

1. Clone the code
    git clone https://alexjkd@github.com/alexjkd/laravel_acs.git

2. Generage a application key
    php artisan key:generate
    
3. Change the folder permisstion  
    chgrp -R apache storage bootstrap/cache
    chmod -R ug+rwx storage bootstrap/cache


