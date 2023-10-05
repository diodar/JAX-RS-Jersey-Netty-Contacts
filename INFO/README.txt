TEST REST API
---------------

Отримання всіх даних
    GET
    http://localhost:8082/api/v1.0/contacts

Отримання даних за id
    GET
    http://localhost:8082/api/v1.0/contacts/2

Створення даних
    POST
    http://localhost:8082/api/v1.0/contacts

    у форматі:

    {
    "id": 5,
    "name": "John",
    "phone": "john@mail.com"
    }

Оновлення даних за id
    PUT
    http://localhost:8082/api/v1.0/contacts/2

    у форматі:

    {
    "name": "Alex",
    "phone": "123 456-7889"
    }

Оновлення імені за id
    PUT
    http://localhost:8082/api/v1.0/contacts/2/name

    у форматі:

    {
    "name": "Alex"
    }

Оновлення телефону за id
    PUT
    http://localhost:8082/api/v1.0/contacts/2/phone

    у форматі:

    {
    "phone": "123 456-7889"
    }

Видалення даних за id
    DELETE
    http://localhost:8082/api/v1.0/contacts/3