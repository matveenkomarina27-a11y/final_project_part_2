# Финальный проект Часть 2
## Задание 1. 
 Список логинов курьеров с количеством их заказов в статусе «В доставке» (поле inDelivery = true). https://github.com/matveenkomarina27-a11y/final_project_part_2/blob/main/задание%201%20работа%20с%20базой%20данных.png

## Задание 2.
Трекеры заказов и их статусы - https://github.com/matveenkomarina27-a11y/final_project_part_2/blob/main/задание%202%20работа%20с%20базой%20данных.png

## Автоматизация теста к API
- Для запуска теста должны быть установлены пакеты pytest и requests
- Запуск всех тестов выполняется командой pytest
- В файле *configuration.py* указаны url сервера и endpoint API
- В файле *data.py* указаны данные для запросов: order_body, headers
- В файле *sender_stand_request.py* описаны функции создания нового заказа и получения заказа по номеру
- В файле *create_order_test.py* прописан сам тест
- Перед запуском тестов необходимо актуализировать переменную URL_SERVICE в *configuration.py*

скриншот с результатами теста https://github.com/matveenkomarina27-a11y/final_project_part_2/blob/main/Результат%20автотеста%20.png
