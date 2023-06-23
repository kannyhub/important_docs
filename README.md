# Laravel important commands
1 php artisan cache:clear
2 php artisan config:cache
3 php artisan config:clear
4 php artisan route:cache
5 php artisan route:clear
6 php artisan optimize
7 php artisan optimize --force
8 php artisan view:clear
9 php artisan route:clear
10 php artisan clear-compiled


# Laravel cache clear code
Route::get('clear', function () {
    Artisan::call('cache:clear');
    Artisan::call('config:clear');
    Artisan::call('view:clear');
    Artisan::call('route:clear');
    dd('cleared');
});


# Laravel Form Documentation
https://laravelcollective.com/docs/6.x/html
