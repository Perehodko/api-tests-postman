API тестируемых сервисов:

- http://petstore.swagger.io/
- https://testbase.atlassian.net/wiki/spaces/USERS/overview

Методы:

- GET
- POST
- PUT
- DELETE

Тестирование организованно с помощью:

- Postman

Для установки Postman выполните следующую команду в командной строке Linux:
```
snap install postman
```

Для запуска коллекции необхрдимо сделать следующее:
1) Запустить Postman;
2) Импортировать коллекцию;
3) Перейти на вкладку Runner;
4) Выбрать импортированную коллекцию из списка доступных коллекций, например, "PetStoreUploadImage";
5) Нажать на кнопку "Run PetStoreUploadImage";

Произойдет запуск тестов. Результаты будут отображен в том же окне.
