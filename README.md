# Итоговая Контрольная работа

1. Создать репозиторий на GitHub
2. Нарисовать блок-схему алгоритма (можно обойтись блок-схемой основной содержательной части, если вы выделяете её в отдельный метод)
3. Снабдить репозиторий оформленным текстовым описанием решения (файл README.md)
4. Написать программу, решающую поставленную задачу
5. Использовать контроль версий в работе над этим небольшим проектом (не должно быть так, что всё залито одним коммитом, как минимум этапы 2, 3, и 4 должны быть расположены в разных коммитах)

___

## Задача

> Написать программу, которая из имеющегося массива строк формирует массив строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

## Примеры

> ["hello", "2", "world", ":-)"] -> ["2", ":-)"]

> ["1234", "1567", "-2", "computer science"] -> ["-2"]

> ["Russia", "Denmark", "Kazan"] -> []
___

# Решение

Решение я буду приводить на уровне своих знаний на нынешнее время. Попробую решить максимально просто и коротко.

## Описание решения

1. Создание массива с типом переменных __string__ и присвоение значений массива.
2. Строчки 2 и 3 кода нужны для корректного вывода в консоль данных, как это показано в примере к задаче.
3. Через цикл __for__ перебираем каждый элемент массива.