Назаров Сергей ИБ-119
# Лабораторная работа 2.
## Сравнение сортировок по времени выполнения и используемой памяти.
Для сравнения выбраны 5 сортировок:
* Вставками (Insertion sort)
* Выбором (Selection sort)
* Слиянием (Merge sort)
* Итеративная слиянием (Merge sort)
* Шелла (Shell sort)

Были проведены замеры времени и памяти, используемые каждой сортировкой при определенном количестве входных элементов. Проверка каждой сортировки производится 5 раз, после вычисляется средний результат из полученных данных.
## Результаты измерений
### Затрачиваемое время
По вертикали отложены количества входных данных.
По горизонтали - затраченное время в милисекундах.

Сортировка Вставками:

<img style="float: left;" src="/lab2/images/time_insert.png">
Сортировка Выбором:

<img style="float: left;" src="/lab2/images/time_select.png">
Сортировка Слиянием:

![Merge sort spent time](/lab2/images/time_merge.png)

Сортировка Слиянием (итеративная):

![IterMerge sort spent time](/lab2/images/time_iterMerge.png)

Сортировка Шелла:

![Shell sort spent time](/lab2/images/time_shell.png)

### Используемая память
По вертикали указано количество используемой памяти в МБ. По вертикали указаны типы сортировок.
![Used memory 1250](/lab2/images/memory_1250.png)
![Used memory 10000](/lab2/images/memory_10000.png)
![Used memory 15000](/lab2/images/memory_15000.png)
![Used memory 25000](/lab2/images/memory_25000.png)
![Used memory 60000](/lab2/images/memory_60000.png)
![Used memory 100000](/lab2/images/memory_100000.png)
