# Messenger
## PHP8.2+MySQL8+nginx+Laravel10+node.js+Pusher+Chatify
### Настраиваем переменные окруженя под себя или оставляем как есть
```shell
cp src/.env.example src/.env
```
### Поднимаем контейнеры
```shell
docker-compose up -d
```
### Накатываем миграции
```shell
docker exec -it messenger-php-1 php /var/www/application/artisan migrate
```
### Регистрируем несколько пользователей http://127.0.0.1:8000/register

### Пользуемся мессенджером http://127.0.0.1:8000/chatify
![img_1.png](src%2Fexample%2Fimg_1.png)
![img_2.png](src%2Fexample%2Fimg_2.png)