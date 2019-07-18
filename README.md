Тестовое задание для AIMCo
==========================

Пояснение
=========
Результат работы находится в тестовом классе

`` 
\src\test\java\ru\glazkov\task\ParseCSV.java
``

Задание
========

``
\src\main\resources\Тестовое задание Java.docx
``

Цель
=====
Цель произвести парсинг CSV файлов

- Пример входных данных:
input1.csv:
id;version;path;
0;1;/hello/уточка;
1;2;/hello/лошадка;
2;2;/hello/собачка;
input2.csv:
id;name;sex;
0;ричард;м;
1;жорж;м;
2;мария;ж;
3;пьер;м;

- Пример результата
id:
0;1;2;3;
version:
1;2;
path:
/hello/уточка;/hello/лошадка;/hello/собачка;
name:
ричард;жорж;мария;пьер;
sex:
м;ж;

Результат тестового задания 
- Список ключей и значений к ним
{ id=[0, 1, 2, 3],
 version=[1, 2],
 path=[/hello/уточка, /hello/лошадка, /hello/собачка],
 name=[ричард, жорж, мария, пьер],
 sex=[ж, м] }


