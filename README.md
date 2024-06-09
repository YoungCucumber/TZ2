<h1 align="center"> Техническая документация по ТЗ2 </h1>
<hr>

![auto_tests](https://github.com/YoungCucumber/TZ2/actions/workflows/auto_tests.yml/badge.svg)
![manual_tests](https://github.com/YoungCucumber/TZ2/actions/workflows/manual_tests.yml/badge.svg)
<hr>
        <p> Файл 'input.txt' располагается в директории src. </p>
        <p> Целые числа в файле записаны в одной строке, друг от друга отделены пробелами. 
            В файле есть минимум одно число. Максимально возможное количество чисел в файле - 1 млн. </p>

Формат запуска: Имя файла <аргументы>

1. `_min` - функция принимает на вход файл, содержащий массив целых чисел и возвращает один (int) элемент целое число - минмиальное значение этого массива
2. `_max` - функция принимает на вход файл, содержащий массив целых чисел и возвращает один (int) элемент целое число -  максимальное значение этого массива
3. `_sum` - функция принимает на вход файл, содержащий массив целых чисел и возвращает один (int) элемент целое число -  сумму всех элементов этого массива 
4. `_mult` - функция принимает на вход файл, содержащий массив целых чисел и возвращает один (int) элемент целое число -  произведение всех элементов этого массива

<p>Тесты расположены в файле MainTest.java</p>
<p>Построение графика времени выполнения относительно кол-ва файлов реализовано в NumberProcessorTest.java</p>

<p>Github Actions - CI система. Программа проходит тесты при каждом push, есть возможность
ручного запуска тестов. Результат каждого теста отправляется в телеграмм чат.</p>

![](image.jpg)
