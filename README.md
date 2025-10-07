# フリマサイト

## 環境構築
Dockerビルド
1. docker-compose.ymlを作成
2. docker conpose up -d --build

Laravel環境構築
1. docker-compose exec php bash
2. composer インストール
3. .envの変更
4. php artisan key:generate
5. php artisan migtate
6. php artisan db seed

## 使用技術
・Laravel Framework 8.83.29  
・PHP 8.1.33  
・nginx 1.21.1  
・mysql 8.0.26  
・phpmyadmin 5.2.
・stripe 

## URL
・開発環境:localhost/  
・管理者画面:localhost/admin/  
・phpadmin:localhost:8080/

## 特記事項
商品詳細画面にあるお気に入りボタンとコメント投稿欄は、
ログインしたユーザーのみが利用できる機能のため、
コーチと相談の上、未ログインの場合は両機能の表示を
非表示にしています。
