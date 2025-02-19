**Донской Фрол МИБ-201**

Приложение с героями Марвел


![photo_2_2025-02-14_17-00-40](https://github.com/user-attachments/assets/fba5b0f6-f137-40d7-898c-964dda784393)![photo_1_2025-02-14_17-00-40](https://github.com/user-attachments/assets/414f3a8d-5fc6-40dc-802c-6c08b672c167)


**Подробнее по файлам:**

Apikeys: получил апи ключи после регистрации на сайте

AppNavigator: создана навигация в приложении

FallbackScreen: экран заглушка, если данные не смогли загрузится

Hero: модель данных для работы с АПИ марвела

HeroBD: локальная база данных, которая хранит данные о супергероях

HeroCard: карточка супергероя в которой он отображается

HeroDetailScreen: экран с подробным описанием героя

HeroDetailViewModel:  загрузка данных героя, кэширование в БД Room и обработка ошибок

HeroListScreen: экран списка супергроев, отображение их в горизонтальном виде 

MainActivity: основа, загружает героев из локальной БД и АПИ марвела

Mapper: обеспечивает конвертацию между данными, которые приходят из БД, АПИ и теми, что используются в ЮАЙ

MarvelApiService: интерфейс для работы с АПИ и реализация функции для генерации MD5 хэша, который используется для безопасности АПИ запросов

RetrofitInstance: конфигурация для взаимодействия с АПИ марвела. В нем создается RetrofitInstance, который отвечает за настройку Retrofit — библиотеки для отправки HTTP запросов
