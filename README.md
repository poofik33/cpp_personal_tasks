# Personal tasks in C++ course

[![Build Status](https://travis-ci.org/poofik33/cpp_personal_tasks.svg?branch=for_pt2_check)](https://travis-ci.org/poofik33/cpp_personal_tasks)
[![codecov](https://codecov.io/gh/poofik33/cpp_personal_tasks/branch/for_pt2_check/graph/badge.svg)](https://codecov.io/gh/poofik33/cpp_personal_tasks)

 # Постников Александр АПО-11
 
 
 # Условие ИЗ№1:
 Создать структуру для хранения записей блога: названия, содержимого, тегов, комментариев к записи, ее оценок и даты.
 Составить с ее использованием программу поиска записей блога, набравших наибольшее количество комментариев и оценок
 в первый месяц после их публикации.
 
 # Условие ИЗ№2:
 ИЗ2 посвящено приобретению навыков системной разработки на C и работе с внешними библиотеками. В качестве результата ИЗ2    ожидается:
* грамотное разбиение проекта на файлы;
* наличие двух реализаций – последовательной и параллельной, оформленных в виде статической и динамической библиотеки, а также тестирующей программы, которая будет сравнивать на разных входных данных результаты обеих реализаций между собой;
* максимальная утилизация ресурсов процессора при параллельной обработке данных путём использования нескольких процессов или потоков;
* продуманные структуры данных в целях экономии оперативной памяти;
* реализация алгоритмов, эффективно взаимодействующих с кэш-памятью.

В вашем распоряжении — матрица размером 10 000 x 5000 чисел. Составьте наивный алгоритм зеркального отображения матрицы относительно побочной диагонали, а затем реализуйте параллельный алгоритм решения этой задачи с использованием нескольких процессов с учетом оптимизации работы с кэш-памятью.

# Результаты сравнения времени работы однопроцессного и мультипроцессного алгоритмов
Среднее время работы однопроцессного алгоритма = 0.152с
Среднее время работы мультипроцессного алгоритма = 0.39с
