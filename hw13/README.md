#### Первый запуск проекта

Запуск контейнеров и восстановление бэкапа mongodb:   

    docker-compose up 
    
#### Проверка

1. Проверка вывода коллекции билетов с помощью фильтра    

        ['id' => [2, 3], 'session_id' => 2]    
         
        http://localhost/?id[]=2&id[]=3&session_id=2     

2. Проверка работы Lazy Load. Тот же фильтр, но уже будут доступны    
дополнительные данные сущностей.              

        http://http://localhost/lazy_load?id[]=2&id[]=3&session_id=2    
        





    
    
