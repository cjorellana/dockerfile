composer create-project laravel/laravel app



docker build -t laravel1 .
docker run -d --name desa --rm -p 8181:8181 laravel1