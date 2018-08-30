## STEPS

1. Clone the code <br>
    git clone https://alexjkd@github.com/alexjkd/laravel_acs.git

2. Generage a application key<br>
    php artisan key:generate
    
3. Change the folder permisstion<br>  
    chgrp -R apache storage bootstrap/cache<br>
    chmod -R ug+rwx storage bootstrap/cache


