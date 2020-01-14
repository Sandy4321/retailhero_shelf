# Python baseline задачи про расстановку

## Что это такое и зачем
Baseline для задачи https://retailhero.ai/c/shelf_allocation/overview переписанный с C++ на python. 
Отличия:
1. Категории товаров перебираются в порядке убывания количества товаров в категории, а не по номеру
2. Под группу подбирается не самая пустая полка, а самая полная из тех на которую влезут все товары категории, а если таких нет, то самая пустая
3. Добавил несколько пару примеров на которых были ошибки при сабмите: все товары одной группы не влезают, свободные места кончились раньше чем категории с товарами

## Как запускать?
1. Клонируйте репозиторий
2. python x5_shelf.py < input.txt

## Каковы результаты?

publiclb - 22800099,8247 немного ниже чем оригинал, на сегодня попыток у меня больше нет