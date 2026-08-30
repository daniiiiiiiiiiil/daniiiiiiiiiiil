## Хакатоны

### Tula — платформа для помощи животным
**Хакатон, команда из 5 человек (3 фронтенда, 2 бэкенда) | Team Lead фронтенда**

Тиндер для животных: свайп-подбор питомцев из приютов. Отвечал за фронтенд-часть команды и распределял задачи между фронтендерами.

**Что сделал:**
- Главная страница
- Профиль пользователя — полностью
- Админ-панель
- Лента карточек животных в формате свайпа
- Страница видео с животными, лайки, комментарии, страница приюта
- Секция "Подробнее" по животному
- Чат — частично
- Авторизация — частично

**Стек:** React, TypeScript, SCSS, HTML

[github.com/SVEND-1/Tula](https://github.com/SVEND-1/Tula)

Ссылка на сам хакатон: https://hackrus.ru/1136

### Chat-AI — чат с нейросетью
**Хакатон | Frontend (React/TS)**

Приложение с чатом на базе нейросети и системой поддержки пользователей.

**Что сделал:**
- Авторизация
- Чат с нейросетью на WebSocket
- Чат поддержки на WebSocket
- Создание тикета в поддержку

**Стек:** React, TypeScript, WebSocket, SCSS, HTML

[github.com/SVEND-1/Chat-AI](https://github.com/SVEND-1/Chat-AI)

Ссылка на сам хакатон: https://changellenge.com/championships/changellenge-cup-russia-2026/?utm_source=ip&utm_medium=jobs_juniors_remote&utm_campaign=tg-post&erid=2W5zFK969BP

## Главный проект

### [Finance Microservices](https://github.com/daniiiiiiiiiiil/finance-microservices)

Учёт личных финансов на микросервисной архитектуре. 6 сервисов на Go, взаимодействие через gRPC и Kafka, оркестрируемая Saga для распределённых транзакций (удаление пользователя со всеми его данными в других сервисах), database-per-service (отдельная PostgreSQL под каждый домен), Redis для кэша и read-моделей, MinIO для хранения экспортированных отчётов. Полный стек observability — метрики в Prometheus, трейсинг в Jaeger, Swagger-документация REST API через grpc-gateway. CI/CD на GitHub Actions, деплой на Timeweb.

**Стек:** Go, gRPC, REST API, Kafka, PostgreSQL, Redis, MinIO, Prometheus, Jaeger, Swagger, Docker, CI/CD

Дополнительная информация в README файле проекта

## Практика

### ЦИТ (Центр информационных технологий Республики Коми)
Разрабатывал проект по тестированию специалистов.

[github.com/daniiiiiiiiiiil/CIT](https://github.com/daniiiiiiiiiiil/CIT)

### РФСОО "Федерация Фиджитал Спорта Республики Коми"
Переписывал фронтенд организации на новый стек, работал с их API.

**Что сделал:**
- Страница соревнований
- Отправка флага (ответа)
- Список соревнований
- Список новостей
- Таблица лидеров (3 главные команды)
- Подсказки к заданиям

## Технологии и инструменты

**Backend:**  
![Go](https://img.shields.io/badge/-Go-00ADD8?logo=go&logoColor=white)

**Базы данных:**  
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/-SQLite-003B57?logo=sqlite&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?logo=redis&logoColor=white)

**Брокер сообщений:**  
![Kafka](https://img.shields.io/badge/-Kafka-231F20?logo=apachekafka&logoColor=white)

**Объектное хранилище:**  
![MinIO](https://img.shields.io/badge/-MinIO%20(S3)-C72E49?logo=minio&logoColor=white)

**API и протоколы связи**

![gRPC](https://img.shields.io/badge/-gRPC-4285F4?logo=google&logoColor=white)
![REST API](https://img.shields.io/badge/-REST%20API-02569B?logo=fastapi&logoColor=white)

**Мониторинг и трейсинг:**  
![Prometheus](https://img.shields.io/badge/-Prometheus-E6522C?logo=prometheus&logoColor=white)
![Jaeger](https://img.shields.io/badge/-Jaeger-66CFE3?logo=jaeger&logoColor=white)

**Документация API:**  
![Swagger](https://img.shields.io/badge/-Swagger-85EA2D?logo=swagger&logoColor=black)

**Frontend:**  
![React](https://img.shields.io/badge/-React-61DAFB?logo=react&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white)
![HTML](https://img.shields.io/badge/-HTML-E34F26?logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/-CSS-1572B6?logo=css3&logoColor=white)
![SCSS](https://img.shields.io/badge/-SCSS-CC6699?logo=sass&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black)

**Инструменты и инфраструктура:**  
![Git](https://img.shields.io/badge/-Git-F05032?logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/-GitHub-181717?logo=github&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white)
![CI/CD](https://img.shields.io/badge/-CI%2FCD-2088FF?logo=githubactions&logoColor=white)
![Postman](https://img.shields.io/badge/-Postman-FF6C37?logo=postman&logoColor=white)


## Unit-тесты

![Testify](https://img.shields.io/badge/-Testify-00ADD8?logo=go&logoColor=white)
![Mock](https://img.shields.io/badge/-Mock-00ADD8?logo=go&logoColor=white)

## UML Диаграммы

Доступные диаграммы:

- Диаграммы — вариантов использования, последовательности, состояний, деятельности, классов, map  
  https://drive.google.com/drive/folders/1JsBLzclQ8KX07gHV7htqRGFTXEEHmYfa

## Другие проекты

1. [Library](https://github.com/daniiiiiiiiiiil/Library) — система управления библиотекой: Go + React

## Как связаться

[Telegram](https://t.me/weqrete) · Телефон: +7 904 201 78 69 · Почта: napalkov-danil@list.ru
