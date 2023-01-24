# Laravel Filemanager Integration Demo
This project already integrated [unisharp/laravel-filemanager](https://github.com/UniSharp/laravel-filemanager) with a clean Laravel. Allowing developers to try out all features without integrating into their projects. End-to-end tests are also included, which developers should test their codes before sending new pull requests.

## Init this project
1. Clone and cd into this project
2. `make init`
3. `php artisan serve`
4. Go to your browser and visit `localhost:8000/laravel-filemanager/demo`

## Notes for developers
Remember to run `make test`, make sure all tests are passed before sending new pull requests.




# Fix Step
## docker compose
```bash
docker-compose up --build -d
```

## app container bash
```bash
make init
php artisan serve&   # 必要なし？ 要チェック
```

## mysql
```
# 必要なし？ 要チェック
mysql -uroot -h 127.0.0.1 -p -P 33061 -D filemanager
    secret
```
