## Описание проекта 

В рамках данного проекта были сформулированы следующие задачи:

- Проведение ручного тестирования мобильного приложения «Мобильный хоспис»;
- Создание чек-листа для оценки приложения;
- Разработка тест-кейсов для проверки функциональности приложения;
- Автоматизация выполнения тест-кейсов по составленному чек-листу;
- Подготовка отчетов о результатах тестирования.
Данное приложение выполняет функции по обработке претензий в хосписе и включает в себя:

- Информацию о претензиях и инструменты для их обработки;
- Новостной блок хосписа;
- Тематические цитаты.

## Документация 

1. [Задание дипломного проекта;](https://github.com/netology-code/qamid-diplom)
2. [План проверки и автоматизации приложения;](https://github.com/MashaOsipova/DiplomQA/blob/main/Plan.md)
3. [Чек-лист проверок;](https://github.com/MashaOsipova/DiplomQA/blob/main/Check.xlsx)
4. [Тест-кейсы;](https://github.com/MashaOsipova/DiplomQA/blob/main/Cases.xlsx)
5. [Отчет о проведённом тестировании;](https://github.com/MashaOsipova/DiplomQA/blob/main/Results.md)

## **Процедура запуска авто-тестов:**

1. Клонируйте репозиторий.
2. Откройте проект fmh-android в Android Studio.
3. Запустите эмулятор с API 29 или подключите устройство для тестирования.
4. Запустите тесты, выполнив команду в консоли: ./gradlew connectedAndroidTest.
5. После завершения тестов, выгрузите папку /data/data/ru.iteco.fmhandroid/files/allure-results с эмулятора или тестового устройства (с помощью Device Manager). Рекомендуется сохранить её в корневой директории проекта.
6. Выполните команду allure serve в терминале, находясь на уровень выше каталога allure-results.



