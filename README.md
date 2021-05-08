## *HomeWork 1*
# TODO
# **Задание 1**
Даны 2 переменных, в которых хранятся строки произвольной длины: phrase_1 и phrase_2.
Напишите код, который проверяет какая из этих строк длиннее.

Примеры работы программы:

phrase_1 = 'Насколько проще было бы писать программы, если бы не заказчики’
phrase_2 = '640Кб должно хватить для любых задач. Билл Гейтс (по легенде)'
Результат:
Фраза 1 длиннее фразы 2

phrase_1 = '640Кб должно хватить для любых задач. Билл Гейтс (по легенде)'
phrase_2 = 'Насколько проще было бы писать программы, если бы не заказчики’
Результат:
Фраза 2 длиннее фразы 1

phrase_1 = 'Насколько проще было бы писать программы, если бы не заказчики’
phrase_2 = 'Насколько проще было бы писать программы, если бы не заказчики’
Результат:
Фразы равной длины

**Задание 2**
Дана переменная, в которой хранится четырехзначное число (год). Необходимо написать программу, которая выведет, является ли данный год високосным или обычным.

Пример работы программы:

year = 2020
Результат:
Високосный год

year = 2019
Результат:
Обычный год

**Задание 3**
Необходимо написать программу, которая будет запрашивать у пользователя месяц и дату рождения и выводить соответствующий знак зодиака.

Пример работы программы:

Введите день:
30

Введите месяц:
Август
Результат:
Ваш знак зодиака: Дева

Введите день:
29

Введите месяц:
Октябрь
Результат:
Ваш знак зодиака: Скорпион

**Задание 4**
Вам нужно написать программу для подбора упаковок по размерам товара. Размеры хранятся в переменных (в сантиметрах):

width = 10
length = 205
height = 5
Используйте следующие правила:

если каждое из трех измерений менее 15 сантиметров, то выведите на экран “Коробка №1”;
если хотя бы одно из измерений больше 15 сантиметров, но менее 50 сантиметров, то выводите “Коробка №2”;
если длина товара больше 2 метров, то выводите “Упаковка для лыж”;
во всех остальных случаях выводите “Стандартная коробка №3”.

**Задание 5 (необязательное)**
Дана переменная, в которой хранится шестизначное число (номер проездного билета). Напишите программу, которая будет определять, является ли данный билет “счастливым”. Билет считается счастливым, если сумма первых трех цифр совпадает с суммой последних трех цифр номера.

Примеры работы программы:

number = 123456
Результат:
Неасчастливый билет

number = 123321
Результат:
Счастливый билет

**Задание 6 (необязательное)**
Напишите программу, которая сможет вычислять площади трех фигур (круг, треугольник и прямоугольник). Тип фигуры запрашиваем через пользовательский ввод, после чего делаем запрос характеристик фигуры:

если пользователь выбрал круг, запрашиваем его радиус,
если треугольник – длины трех его сторон;
если прямоугольник – длины двух его сторон.
Пример работы программы:

Введите тип фигуры:
Круг

Введите радиус круга:
10
Результат:
Площадь круга: 314.16

Введите тип фигуры:
Треугольник

Введите длину стороны A:
2

Введите длину стороны B:
2

Введите длину стороны C:
3
Результат:
Площадь треугольника: 1.98
