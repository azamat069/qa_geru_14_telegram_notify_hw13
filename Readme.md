Команды генерации allure отчета после прохождения тестов:

1. allure serve tests/allure-results  - генерация страницы allure отчета
2. allure generate --clean tests/allure-results - формирует allure report предварительно очистив предыдущие данные
3. java "-DconfigFile=notifications/telegram.json" -jar allure-notifications-4.7.0.jar - команда формирования и отправки отчета в телеграм чат

