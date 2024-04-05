# Portfolio of Alexey Prikhodko

    Portfolio : 
    - https://github.com/Lexatol


## Tender platform - тендерная платоформа
    Описание:
        В данном проекте разработан функционал 
            - Регистрация пользователя
            - Добавление заказа на платформу
            - Отклики на заказы других пользователей
            - Выбор из откликнувшихся победителя
            - Смена статуса заказов, если прошел месяц
            - Отправка сообщений в случае создания заказа, отклика заказа, выбора исполнителя заказа и др
    Стэк:
        Spring Boot 3, Spring Cloud, Spring JPA, FlyWay, Loombok, PostgreSQL, GateWay, Discovery Eureka
    Архитектура:
        Проект разработан на микросервисной архитектуре
            - микросервис - Специализации
            - Микросервис - тендеры
            - Микросервис - Пользователи
            - Микросервис - телеграм бот
            - Микросервис - чат
            - Конфиг-сервер
    Ссылка:
        https://github.com/Lexatol/TenderPlatforms

## Cloud Storage - клиент серверное приложение:
    Особенности:
        Разработка клиент серверного приложения 
        для сохрания файлов на сервере с локальной машины
    Стэк:
        - Java 11, Netty, Swing, Maven
    Архитектура:
       Приложение построено из модулей
        - Модуль клиента
        - Модуль сервера
        - модуль отвечающий за работу по сети клиента и сервера
    Ссылки:
        https://github.com/Lexatol/cloud-storage


## Тестовое задание от компании Inside
    Особенности:
        Разработать сервис, который сохраняет в базу данных сообщения от авторизированных пользвателей. По конкретному запросу возвращает последние 10 сохраненных сообщений. Для авторизации использовать jwt token. Составить описание проекта, протестировать, упаковать в docker контейнер, выложить в docker hub и github, подготовить curl запросы
    Стэк:
        - Для разработки приложения был использован следующий стэк: Java 11, Spring Boot, Spring Security, JWT, FlyWay, H2database, PostgreSQL, Lombok. 
        - Тестирование: Junit 5, Mockito
        - Приложение упаковано в docker сontainer и разворачивается с помощью docker-compose.
        - Файлы docker и docker-compose приложены к проекту
    Ссылка:
        https://github.com/Lexatol/testinside


## Интернет магазин (Spring cloud):

    Особенности:
    Прототип интернет магазина реализовал на микросервисной архитектуре.
    Микросервисы: мс регистрация пользователей, мс заказы (создается корзина и в
    последующем сохраняется в заказ), мс продукты. Каждый микросервис реализовал на своей базе.

    Стэк:
    Java 11, Spring boot, Spring Cloud, Spring data, Spring security, Rest Api, Hibernate, Lombor, PostgreSQL, H2
    database, FlyWay, Maven, Discovery Eureka
    
    Ссылка:
       https://gitlab.com/lexp00/supermarket

## Telegram Bot
    Особенности:
        - Разработка телеграм Бота

    Стэк: Java 11, Spring Boot, Lombok, Maven, PostgreSQL
    
    Ссылка: https://github.com/Lexatol/TelegramBot


## Интернет магазин (монолит):

    Особенности:
    - Аутентификация и авторизация пользователей на JWT
    - Список товаров с категориям из базы данных с возможностью добавления новых товаров с фронта,
    фильтрация товаров
    - Корзина: добавление товаров, редактирования кол-ва, вывод общей стоимости и указание адреса
    доставки, сохранение в базу данных и создания заказа.
    
    Стэк:
    Spring boot, Spring Data, Spring Security, REST API, Hibernate, PostgreSQL, Lombok, Maven, Html,
    AngularJs, JUnit, Mockito, Docker
    
    Ссылки:
       https://github.com/Lexatol/Market


## Клиент серверное приложение - чат:

    Стэк:
    - Client: Java 8, JavaFX
    - Server: Java 11
    - Netty
    
    Ссылки:
       https://github.com/Lexatol/chat

## ИГРА для desktop:
    игра разработана на java с применением LibGDX
    
    Особенности:
    - реализация игры на java для desktop версии с возможностью расширения на android
    
    Стэк: LibGDX, Gradle

    Ссылки:
       https://github.com/Lexatol/StarGame

