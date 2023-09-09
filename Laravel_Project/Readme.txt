docker compose run --rm composer create-project --prefer-dist laravel/laravel .
docker compose up -d server php mysql


docker compose run --rm artisan migrate


docker compose up -d --build