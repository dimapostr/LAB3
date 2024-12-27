# Department Web Application

## Опис проекту
Веб-застосунок для управління інформацією оргтехніки, розроблений з використанням Java Spring Framework.

## Технології
- Java
- Spring Framework
- Maven
- PostgreSQL
- Docker

## Передумови
Для запуску проекту вам потрібно мати встановлено:
- Docker
- Docker Compose
- PostgreSQL
- pgAdmin (для налаштування бази даних)
- JDK 17 або вище
- Maven

## Налаштування бази даних
1. Відкрийте pgAdmin
2. Підключіться до вашого PostgreSQL сервера
3. Знайдіть в корені проекту SQL файл
4. Виконайте SQL скрипт для створення та наповнення бази даних

## Запуск проекту
1. Клонуйте репозиторій:
```bash
git clone [url-репозиторію]
```

2. Перейдіть до директорії проекту:
```bash
cd [назва-директорії]
```

3. Запустіть Docker контейнери:
```bash
docker-compose up -d
```

4. Запустіть застосунок:
```bash
mvn spring-boot:run
```

## Порти за замовчуванням
- Веб-застосунок: `http://localhost:8080/home`
- PostgreSQL: `5432`


## Конфігурація
Основні налаштування застосунку:
- Порт сервера: 2222
- Налаштування підключення до бази даних знаходяться в файлі `application.properties` або `application.yml`
- Головний застосунук знаходиться в папці LAB3
