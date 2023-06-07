**UI тесты для [Stellar Burgers](https://stellarburgers.nomoreparties.site/)**

- Тестируются сценарии: регистрация, вход, переход в личный кабинет, раздел «Конструктор».
- Тестирование в браузера:  Google Chrome, Yandex.Browser.
- В maven подключены библиотеки: selenide, JUnit 4, Allure. Настроен на работу с Java 11.

Команды:
- для запуска тестовых сценариев: mvn clean test
- для формирования Allure отчёта: mvn allure:serve