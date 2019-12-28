## Небольшая wiki по работе с git


Простые правила поведения в репозиториях:
```
– Изменения в репозитории производятся с помощью пулл-реквестов через свои форки.
– Перед созданием пулл-реквеста, необходимо стянуть актуальную master ветку и смержить ветку-фичу с ней.
– При создании пулл-реквеста, добавить хотя бы минимальное описание.
– Следить за неймингом и чистотой кода (по возможности).
```


Команды:
========

В папке склонированного проекта-форка добавляете ссылку на исходный проект (который форкнули).

```Shell
$ git remote add upstream git@github.com:amm-vsu-2015/wiki.git
```

Обновляем свой проект (скачиваем изменения из исходного проекта)

```Shell
$ git fetch upstream
```

Делаем слияние ветки master своего локального проекта с веткой исходного проекта.
Изменения будут сохранены в текущей ветке.

```Shell
$ git merge upstream/master
```

Отправляем обновленную мастер-ветку в свой форк на гитхаб.

```Shell
$ git push origin feature_branch
```



# Список всех задач:

1. Первый курс (основы и pascal)
   - Простые арифметические задачи
   - Пропала из памяти :D
   - [Задача на матрицы](https://github.com/amm-vsu-2015/1y1s_basic/tree/master/task3)
   - [Задача на строки](https://github.com/amm-vsu-2015/1y1s_basic/tree/master/task4)

   - [Задача на однонаправленные линейные списки](https://github.com/amm-vsu-2015/1y2s_basis/tree/master/task1)
   - [Задача на двунаправленные линейные списки](https://github.com/amm-vsu-2015/1y2s_basis/tree/master/task2)
   - [Задача на парсинг строк и файлы](https://github.com/amm-vsu-2015/1y2s_basis/tree/master/task3)
   - Задачи на работу с очередями.

2. Второй курс (алгоритмы и C++)
   - [Сравнить скорость выполнения двух сортировок](https://github.com/amm-vsu-2015/2y1s_algorithms/tree/master/task1)
   - [Задача на ход коня](https://github.com/amm-vsu-2015/2y1s_algorithms/tree/master/task2)
   - [Задача о восьми ферзях](https://github.com/amm-vsu-2015/2y1s_algorithms/tree/master/task3)

   - [Простая геометрическая задача на треугольники](https://github.com/amm-vsu-2015/2y2s_cpp/tree/master/task1)
   - [Задача поиск минимального значения в массиве с определенными условиями](https://github.com/amm-vsu-2015/2y2s_cpp/tree/master/task2)
   - [Динамическая генерация лабиринта и поиск выхода](https://github.com/amm-vsu-2015/2y2s_cpp/tree/master/task3)
   - [Задача на списки](https://github.com/amm-vsu-2015/2y2s_cpp/tree/master/task4)

3. Третий курс (ООП)

   - [Математическая задача на конструкторы](https://github.com/amm-vsu-2015/3y1s_oop/tree/master/task1)
   - [Еще одна матем. задача с наследованием](https://github.com/amm-vsu-2015/3y1s_oop/tree/master/task2)
   - [Задача на создание сущностей студентов и производных классов](https://github.com/amm-vsu-2015/3y1s_oop/tree/master/task3)
   - [Задача на определение валидности строки, имеющей открывающие и закрывающие скобки](https://github.com/amm-vsu-2015/3y1s_oop/tree/master/task4)

4. Четвертый курс (Java / Python)

   - [python] [Задача на бросок объекта](https://github.com/amm-vsu-2015/4y1s_python/tree/master/homeworks/hw3)
   - [python] [Просто список задачек](https://github.com/amm-vsu-2015/4y1s_python/tree/master/homeworks/hw4)
   - [java] [Проверка матрицы на возрастание по траектории змейки](https://github.com/amm-vsu-2015/4y1s_java/tree/master/labs/easy_level/LinearSequenceMatrix)
   - [java] [Обнуление столбца матрицы](https://github.com/amm-vsu-2015/4y1s_java/tree/master/labs/easy_level/MatrixZeroing)
   - [java] [Обход шахматной доски королевой](https://github.com/amm-vsu-2015/4y1s_java/tree/master/labs/mid_level/QueensBoard)
   - [java] [Design-driven development achitecture](https://github.com/amm-vsu-2015/outsource/tree/master/le/4th_course/java/RabbitBag)


5. Пятый курс (infosec / design patterns on swift)

   - [strategy pattern](https://github.com/amm-vsu-2015/5y1s_design_patterns/tree/master/strategy)
   - [template pattern](https://github.com/amm-vsu-2015/5y1s_design_patterns/tree/master/template)
   - [factory pattern](https://github.com/amm-vsu-2015/5y1s_design_patterns/tree/master/factory)
   - [command pattern](https://github.com/amm-vsu-2015/5y1s_design_patterns/tree/master/command)
   - [adapter pattern](https://github.com/amm-vsu-2015/5y1s_design_patterns/tree/master/adapter)
