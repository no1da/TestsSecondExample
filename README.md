# TestsSecondExample
## Описание проекта

Данный проект представляет собой автоматизированные Api-тесты разработанные в рамках практикума SDET, на языке Java с использованием фреймворка JUnit 5.

### Описание тест-кейсов 

test-cases.md

### Стек технологий

- Язык программирования: Java
- Версия Java: 17
- Тестовый фреймворк: JUnit 5
- Сборщик проекта: Maven
- Документация Allure

### Настройка окружения

1. Убедитесь, что на вашем компьютере установлены следующие программные обеспечения:
   - Java Development Kit  17.
   - Apache Maven.
2. Запустите сервис "test-service"
3. https://github.com/sun6r0/test-service
4. Для запуска параллельного тестирования используется механизм конфигурации Create Run со следущими аргументами:
   - Djunit.jupiter.execution.parallel.enabled=true
   - Djunit.jupiter.execution.parallel.mode.default=concurrent

   

