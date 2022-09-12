# Portfolio of Alexey Prikhodko

    Portfolio : 
    - https://github.com/Lexatol

## For House Club - Строительный портал
        Разрабатываю строительный портал для управления проектами, проведения тендеров на бирже, 
    подготовка сметных расчетов в строительстве
    Проект разрабатываем в команде из разработчиков backend, frontend, mobile, дизайнеров, тестировщиков, аналитиков
    
    Особенности:
    - Сервис регистрации и авторизации пользователей на JWT token, создание личных кабинетов компаний
    - Составление сметного расчета на строительный объект и сохранение его в базу, сметный расчет
      закрепляется за компанией
    - объявление тендера на основании подготовленного сметного расчета
    - участие в тендере и объявление победителей
    - управление проектом (СРМ система)

    Стэк:
    Java 11, Angular Js, Spring boot, Spring security, REST API, Hibernate, Lombok, Swagger, PostgreSQL, H2
    database, Flyway, Maven, Docker
    
    Ссылки:
    - https://gitlab.com/lexp00/ForHouseClub/-/tree/dev
    - https://www.youtube.com/watch?v=q1Vi0Xn7cCo&t=14s
    
    Deploy:
    - http://forhouse.club/fhc

    Документация проекта:
    - http://37.228.116.126:8189/swagger-ui/index.html 

## Тестовое задание от компании Inside
    Особенности:
        Разработать сервис, который сохраняет в базу данных сообщения от авторизированных пользвателей. По конкретному запросу возвращает последние 10 сохраненных сообщений. Для авторизации использовать jwt token. Составить описание проекта, протестировать, упаковать в docker контейнер, выложить в docker hub и github, подготовить curl запросы
    
    Стэк:
        - Для разработки приложения был использован следующий стэк: Java 11, Spring Boot, Spring Security, JWT, FlyWay, H2database, PostgreSQL, Lombok. 
        - Тестирование: Junit 5, Mockito
        - Приложение упаковано в docker сontainer и разворачивается с помощью docker-compose.
        - Файлы docker и docker-compose приложены к проекту
    
    Ссылка:
    - https://github.com/Lexatol/testinside


## Интернет магазин (Spring cloud):

    Особенности:
    Прототип интернет магазина реализовал на микросервисной архитектуре.
    Микросервисы: мс регистрация пользователей, мс заказы (создается корзина и в
    последующем сохраняется в заказ), мс продукты. Каждый микросервис реализовал на своей базе.
    
    Стэк:
    Java 11, Spring boot, Spring Cloud, Spring data, Spring security, Rest Api, Hibernate, Lombor, PostgreSQL, H2
    database, FlyWay, Maven, Discovery Eureka
    
    Ссылка:
    - https://gitlab.com/lexp00/supermarket

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
    - https://github.com/Lexatol/Market


## Клиент серверное приложение - чат:

    Стэк:
    - Client: Java 8, JavaFX
    - Server: Java 11
    - Netty
    
    Ссылки:
    - https://github.com/Lexatol/chat

## ИГРА для desktop:
    игра разработана на java с применением LibGDX
    
    Особенности:
    - реализация игры на java для desktop версии с возможностью расширения на android
    
    Стэк: LibGDX, Gradle

    Ссылки:
    - https://github.com/Lexatol/StarGame