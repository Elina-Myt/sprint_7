# Sprint_7
## Финальный проект 7 спринта
В этом проекте тесты API учебного сервиса [Яндекс Самокат](https://qa-scooter.praktikum-services.ru/)

[Документация](qa-scooter.praktikum-services.ru/docs/.)

## Тесты
test_create_courier.py - тесты на создание курьера  
test_login_courier.py - тесты авторизации курьера  
test_create_order.py - тесты создания заказа  
test_order_list.py - тесты получения списка заказов  


### Запустить тесты
запустить все тесты:
```bash
pytest -v tests
```
зпустить все тесты с генерацией отчетов  
```bash
pytest tests --alluredir=allure_results 
```