# Система управления личными финансами

Backend-приложение для управления личными финансами.

## Требования

- Java 11 или выше
- Maven 3.6+

## Запуск

```bash
mvn exec:java
```

Или через JAR:

```bash
mvn package
java -jar target/personal-finance-manager-1.0-SNAPSHOT.jar
```

## Тесты

```bash
mvn test
```

## Команды

- `register` - регистрация
- `login` - вход
- `income <категория> <сумма>` - добавить доход
- `expense <категория> <сумма>` - добавить расход
- `budget <категория> <сумма>` - установить бюджет
- `stats` - статистика
- `balance` - баланс
- `transfer <логин> <сумма>` - перевод
- `export [файл]` - экспорт отчета
- `help` - справка
- `exit` - выход
