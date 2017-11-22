# How to deploy for noobs developpers 

1 - install <a href="https://getcomposer.org/">composer</a> <br>
2 - Execute the next commandes 

```sh
cd ./userManag
composer install
php artisan key:generate
```
3 - create a vhost in your local server for the domaine 

```sh
virtualstock.ma
```

4 - if you can't find the public storage execute the next commandes

```sh
cd ./userManag
php artisan storage:link
```