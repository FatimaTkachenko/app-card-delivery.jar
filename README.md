[![CI](https://github.com/FatimaTkachenko/app-card-delivery.jar/actions/workflows/gradle.yml/badge.svg)](https://github.com/FatimaTkachenko/app-card-delivery.jar/actions/workflows/gradle.yml)

# Selenide Delivery Test

## Описание проекта
Автотест для формы заказа доставки карты с использованием Selenide.

## Технологии
- Java 11
- Selenide 6.19.1
- JUnit 5.10.2
- Gradle

## Запуск тестов
1. Запустите SUT: `java -jar ./artifacts/app-card-delivery.jar`
2. Откройте страницу: http://localhost:9999
3. Запустите тест: `./gradlew test`