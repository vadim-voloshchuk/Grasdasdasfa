# GRAPHVIZ
Библиотека для взаимодействия с социальными графами. Проект собран с использованием docker-compose и содержит:
- микросервер;
- dashboard, отражающий основные метрики.
![Alt text](<main_scheme.png>)
Актуально для следующих ОС:
- Windows 10 и выше;
- Ubuntu 18.04 и выше(и все семейства ветки).

## Описание ПО
### Функционал
- загрузка данных в систему в форматах:
    - .xml;
    - .json;
    - .html;
    - .xlsx;
    - .csv.
- обработка данных:
    - семплирование(выделение) сущностей;
    - поиск/расчёт метрик;
    - выделение сообществ;
    - добавление данных;
    - удаление данных;
    - редактирование данных.
- визуализация:
    - интерактивное отображение графа;
    - выделение сущностей графа.

## Установка
Необходимо:
- Docker;
- Git.

Сначала склонируйте репозиторий в рабочую директорию. Далее выполните следующую команду в рабочей директории для сборки и запуска проекта:
```
docker-compose build
docker-compose up
```
Затем перейдите по следующему адресу:
```
http://127.0.0.0.0:3080/
```

# Использование
Документация проекта расположена по следующей сслыке:
- [Документация](./server/ENDPOINTS.md)