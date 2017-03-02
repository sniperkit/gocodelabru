# Делаем простую базу для гео данных

Привет, гофер. Ну если ты не гофер и хочешь им стать, тоже привет.  Я предлагаю в этой кодлабе совместить две вещи. Изучить как язык Go и может быть освоить для себя пару новых вешей. Тебе понадобится установленный язык [Go](https://golang.org/). Также желательно пройти [тур по Go](https://tour.golang.org/)

# Поднимаем окружение
Тебе понадобится следующее:

1. Установленный язык [Go](https://golang.org/)
2. Настроенный `GOPATH` :trollface:
3. Ты знаком с базовыми вещами в Go. [Тур по Go](https://tour.golang.org/) может хорошо в этом помочь

# Цель лабораторной

У этой лабораторной работы две цели:

1. Получить опыт в Go
2. Научиться понимать как примерно работают key-value хранилища(redis, memcached) 
3. Как работают некоторые индексы.

По итогу БД будет уметь следующие вещи:

* Быстрый поиск по ключу;
* Поиск мест, рядом с вами;
* HTTP интерфейс к БД;
* LRU/expire механизмы для хранения данных;

По Go получите следующие знания:

* Как работает concurrency;
* Поработаете с базовыми синтаксическими вещами;
* Опыт тестирования в go;
* Базовые вещи с Makefile;

# Содержание

Этот воркшоп разделен на несколько частей.

* [Шаг 0. Что такое LRU, R-tree и постановка задачи](step00/README.md)
* [Шаг 1. Делаем структуру и архитектуру проекта](step01/README.md)
* [Шаг 2. Что нужно знать о тестировании и написании тестов в Go.](step02/README.md)
* [Шаг 3. Имплементируем LRU (часть 1)](step03/README.md)
* [Шаг 4. Имплементируем LRU (часть 2)](step04/README.md)
* [Шаг 5. Строим сторадж](step05/README.md)
* [Шаг 6. Имплементируем сторадж](step06/README.md)
* [Шаг 7. Проектируем HTTP API](step07/README.md)
* [Шаг 8. Делаем HTTP API](step08/README.md)
* [Шаг 9. Пару штук о автоматизации и Makefile](step09/README.md)
* [Шаг 10. Поздравления!](step10/README.md)
