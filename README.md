# Описание проекта
Изначально планировалось написать на языке С два алгоритма сортировки - выбором и слиянием, бенчмарк к ним и python-скрипт, генерирующий экспериментальные и теоретические графики зависимостей времени сортировки от количества элементов для последующего их сравнения.  
После реализации задуманного пришла идея сделать визуализацию обеих сортировок с использованием микроконтроллера STM32 и TFT-дисплея, что также было успешно реализовано.

### Программная часть
В представленной программе реализованы два алгоритма сортировки - выбором и слиянием.  
Реализована возможность программного замера времени, используемого тем или иным алгоритмом на тех или иных входных данных.  
Также с использованием языка python реализовано построение графиков зависимостей времени сортировки от объема входных данных для заданных алгортимов.

### "Железная" часть
Реализована анимация обоих сортировок на микроконтроллере STM32F411RE и TFT дисплее.
Для сортировки создается массив на 160 элементов, в котором все элементы имеют значение от 0 до 159, после чего элементы случайным образом перемешиваются.

> Обе части по факту являются разными проектами, поэтому внутри себя так же имеют свои README
