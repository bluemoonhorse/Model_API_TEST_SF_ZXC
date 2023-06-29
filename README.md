28.9.11

PYDANTIC: API автотесты

API: restful-booker.herokuapp.com

Libs: requests, pytest, pydantic

Параметризованные негативные и позитивные тесты[tests].

1. Тесты авторизации и получения токена - tests_auth.py
2. Тесты не требующие токен - tests_without_token.py
3. Тесты требующие токен - tests_required_token.py 

авторизация, заказ - методы.

api[api], auth_model[serializers], booking_model[serializers] - токен апи методы, pydantic авторизация, pydantic заказы

проверка response по if elif 
