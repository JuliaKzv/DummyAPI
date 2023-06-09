## API Service [DummyAPI](https://dummyapi.io/)
**DummyAPI** - фейковый API сервис, содержащий фиктивные данные, позволяющий создавать пользователей, создавать посты от имени пользователей, прописывать тэг-лист к посту и оставлять комментарии. Сервис использовался мною для обучения тестированию API и работе в Postman. В данном проекте написаны тесты для объекта [Post](https://dummyapi.io/docs/post) (Get List и Create Post).

Вся необходимая документация по данному сервису содержится [здесь](https://dummyapi.io/docs). 

Выполненные тесты были описаны с помощью [майнд-карты](DummyAPI.xmind).

В [окружении](DummyAPI.postman_environment.json) прописаны: 

- AppID, который позволяет получить персональный доступ к данным, которые были созданы или обновлены.
- Переменная host, которая содержит в себе базовый URL сайта.

[Коллекция](Post.postman_collection.json) содержит в себе все запросы, которые были описаны в майнд-карте.

Коллекция [Autotests.postman_collection.json](Autotests.postman_collection.json) содержит в себе автотесты, покрывающие объект Post.
