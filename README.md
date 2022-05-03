Стартиране на API:
    1. След сваляне на проекта се насочва към папката "api".
    2. Стартира се командата -> "composer install"
    3. Копира се ".env.example" фаила като ".env" -> "cp -a .env.example .env"
    4. Стартира се сървъра -> "php artisan serve"
    5. Създава се "API_KEY" и се чисти кеша -> "php artisan key:generate" и после "php artisan config:cache"