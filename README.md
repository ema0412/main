環境構築
Dockerビルド
1. git@github.com:ema0412/main.git
2. docker-compose up -d -build

Laravel環境構築
1.docker-compose exec php bash
2.composer install
3.env.exampleファイルから.envを作成し、環境変数を変更
4.php artisan key:generate

使用技術
・PHP8.0
・Laravel10.0
・MySQL8.0

URL
・開発環境：http://localhost/
・phpMYAdmin:http://localhost:8080/
