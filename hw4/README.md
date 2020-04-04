#### Запуск проекта

    docker-compose up -d

#### Запуск сервера

1. Откройте новый терминал и введите:    
    
    docker-compose exec php bash    
    
2. Внутри запущенного контейнера запустите скрипт сервера:    

    php server.php    
    
#### Запуск клиента

1. Откройте новый терминал и введите:    
    
    docker-compose exec php bash    
    
2. Внутри запущенного контейнера запустите скрипт сервера:    

    php client.php    
    
#### Проверка работы

В терминале с запущенным скриптом client.php введите текст, затем нажмите Enter.    
После этого должен придти ответ от сервера:    
    
    You say 'Ваш текст'    
    
Для завершения работы клиента введите:    

    exit 
     
Сервер закроет соединение с данным клиентом.