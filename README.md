# testrail-api-tests
Professional TestRail API testing suite with security-first approach and comprehensive error handling
# TestRail API Testing Suite

![Postman](https://img.shields.io/badge/Postman-API_Testing-orange?logo=postman)
![TestRail](https://img.shields.io/badge/TestRail-Test_Management-blue)
![Security](https://img.shields.io/badge/Security-Environment_Variables-green)

Профессиональная коллекция для тестирования TestRail API с акцентом на безопасность и автоматизацию.

## 🎯 Демонстрируемые навыки

### 🔐 Security-First Approach
- **Environment Variables** для конфиденциальных данных
- **Basic Authentication** с использованием переменных окружения
- **Никаких хардкодных credentials** в коде

### 📊 Advanced Features
- **Визуализация данных** в HTML таблицах
- **CRUD операции** с тест-кейсами (создание, чтение, обновление)
- **Параметризация** тестовых данных

### 🛡️ Real-World Testing
- Обработка сценариев недоступности сервиса
- Профессиональная работа с ошибками аутентификации
- Тестирование в условиях неидеального API

## 📁 Структура коллекции

### Тестируемые эндпоинты
- **GET /get_cases** - получение списка тест-кейсов с визуализацией
- **GET /get_case/{id}** - получение конкретного тест-кейса
- **POST /add_case** - создание нового тест-кейса
- **POST /update_case/{id}** - обновление тест-кейса

## 🚀 Быстрый старт

1. **Импортируйте коллекцию** в Postman
2. **Импортируйте Environment Template** и заполните переменные:
   - `testrail_username` = ваш email для TestRail
   - `testrail_password` = ваш пароль/API ключ
   - `testrail_baseurl` = ваш URL TestRail
3. **Запустите тесты**

## 💡 Особенности реализации

- Визуализация тест-кейсов в табличном формате
- Обработка различных сценариев ответов API
- Безопасное хранение чувствительных данных

---

<div align="center">

**Готово к использованию в реальных проектах!** 🚀

</div>
