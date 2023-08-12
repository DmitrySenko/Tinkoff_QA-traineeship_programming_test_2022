# Tinkoff-QA-traineeship-programming-test
Решения задач, которые я решал в экзамене по программированию для стажировки в Тинькове на позиции QA 

1. Ксюша недавно устроилась работать в Тинькофф. В качестве первого задания ей поручили выбрать цвета для названия нового отдела. Ксюша уже решила, что покрасит его в два цвета — желтый и черный, осталось только раскрасить.
Название отдела представляет из себя строку ﻿﻿ss﻿﻿, состоящую из нескольких слов, разделенных пробелами. Каждое слово состоит из латинских букв, суммарно в названии их ровно ﻿﻿nn﻿﻿. 
Ксюша уже придумала, в какие цвета покрасит каждую букву, но хочет, чтобы раскраска получилась наиболее красивой. Слово считается некрасивым, если в нем есть соседние буквы, покрашенные в один цвет. 
Ксюша хочет узнать, сколько слов в названии отдела окажутся некрасивыми, если раскрашивать их в соответствии с ее идеей. Пожалуйста, помогите ей сосчитать.
Формат входных данных
В первой строке вводится число ﻿﻿nn﻿﻿ ﻿﻿(1 ≤ n ≤ 100)(1≤n≤100)﻿﻿ — количество букв в названии отдела.
Во второй строке вводится само название — строка ﻿﻿ss﻿﻿ ﻿﻿(1 ≤ |s| ≤ 100)(1≤∣s∣≤100)﻿﻿, состоящая из латинских букв и пробелов. Гарантируется, что между любыми двумя буквами не более одного пробела, строка начинается и заканчивается буквой, а также содержит ровно ﻿﻿nn﻿﻿ букв.
В третьей строке вводится строка ﻿﻿bb﻿﻿ длины ﻿﻿nn﻿﻿, состоящая из букв ﻿﻿YY﻿﻿ и ﻿﻿BB﻿﻿  — Ксюшина идея раскраски названия. Если ﻿﻿b_i = Ybi=Y﻿﻿, то ﻿﻿ii﻿﻿-ая по счету буква названия должна быть покрашена в желтый цвет; если же ﻿﻿b_i = Bbi=B﻿﻿, то ﻿﻿ii﻿﻿-ая буква должна быть покрашена в черный цвет.
Формат выходных данных
В единственной строке выведите число — количество некрасивых слов в раскрашенном названии отдела.


2. Ксюша раскрасила названия, теперь ей нужно придумать новые курсы валют.

Всем известно, что существуют только три валюты: ﻿﻿AA﻿﻿, ﻿﻿BB﻿﻿ и ﻿﻿CC﻿﻿, — и каждая из них имеет свою ценность: ﻿﻿aa﻿﻿, ﻿﻿bb﻿﻿ и ﻿﻿cc﻿﻿ соответственно. По идее Ксюши банк будет предоставлять клиентам возможность обменивать одну валюту на другую: а именно, если клиент хочет обменять валюту ﻿﻿AA﻿﻿ на валюту ﻿﻿BB﻿﻿, он сможет отдать ровно ﻿﻿aa﻿﻿ единиц валюты ﻿﻿AA﻿﻿ и получить взамен ровно ﻿﻿bb﻿﻿ единиц валюты ﻿﻿BB﻿﻿. Аналогично происходит обмен между другими валютными парами.
У Ксюши на счету сейчас ﻿﻿xx﻿﻿, ﻿﻿yy﻿﻿ и ﻿﻿zz﻿﻿ единиц в валютах ﻿﻿AA﻿﻿, ﻿﻿BB﻿﻿ и ﻿﻿CC﻿﻿ соответственно. Она хочет узнать, сколько различных троек значений ﻿﻿(x, y, z)(x,y,z)﻿﻿ своего баланса она может получить, совершив некоторое количество обменов (возможно, 0). Для этого она просит вашей помощи.
Формат входных данных
В первой строке вводятся три целых числа ﻿﻿aa﻿﻿, ﻿﻿bb﻿﻿ и ﻿﻿cc﻿﻿ ﻿﻿(1 ≤ a, b, c ≤ 10^9)(1≤a,b,c≤10^9 )﻿﻿ — ценности валют.
Во второй строке вводятся три целых числа ﻿﻿xx﻿﻿, ﻿﻿yy﻿﻿ и ﻿﻿zz﻿﻿ ﻿﻿(0 ≤ x, y, z ≤ 10^9)(0≤x,y,z≤10^9 )﻿﻿ — суммы на счету у Ксюши в каждой валюте.
Формат выходных данных
В единственной строке выведите целое число — количество различных троек значений, которые Ксюша может получить путем обменных операций.


3. Для новой маркетинговой акции Ксюша придумала провести математическую лотерею. Она загадала натуральное число ﻿﻿nn﻿﻿ и напечатала на билетах пары положительных чисел ﻿﻿aa﻿﻿, ﻿﻿bb﻿﻿ такие, что ﻿﻿a + b = na+b=n﻿﻿. Победителем лотереи будет считаться участник, получивший билет с минимальным наименьшим общим кратным (НОК) чисел ﻿﻿aa﻿﻿ и ﻿﻿bb﻿﻿.
Ксюша хочет заранее понять, какие подходящие числа ﻿﻿aa﻿﻿ и ﻿﻿bb﻿﻿ можно выбрать, чтобы их НОК было минимально возможным. Поможете ей?
Формат входных данных
В единственной строке вводится натуральное число ﻿﻿nn﻿﻿ ﻿﻿(2 ≤ n ≤ 10^9)(2≤n≤10^9)﻿﻿ — загаданное Ксюшей число ﻿﻿nn﻿﻿.
Формат выходных данных
Выведите через пробел два числа ﻿﻿aa﻿﻿ и ﻿﻿bb﻿﻿ — искомую пару с минимальным НОК.
Если подходящих ответов несколько, выведите любой.


6. Сегодняшняя задача Ксюши — провести мастер-класс по программированию для стажеров Тинькофф Старта. Для этого она решила устроить небольшую игру: Ксюша будет поддерживать множество, а стажеры будут говорить числа, которые в него добавить. После каждого добавления Ксюша будет называть максимальное значения побитового исключающего ИЛИ среди всех пар чисел этого множества.
Формально, если множество после очередной операции добавления равно ﻿﻿SS﻿﻿, то Ксюша хочет найти в нем такие два числа ﻿﻿aa﻿﻿, ﻿﻿b ∈ Sb∈S﻿﻿, что значение ﻿﻿a ⊕ ba⊕b﻿﻿ максимально. Если число уже присутствовало в множестве до добавления, само множество никак не меняется. Выводить ответ при этом нужно после каждого добавления, даже если множество осталось прежним.
Ксюша знает, что кто-то из стажеров наверняка знает, как она будет считать ответы для этой игры, поэтому просит вас написать программу, которая будет обрабатывать запросы на добавление чисел.
Формат входных данных
В первой строке вводится целое число ﻿﻿qq﻿﻿ ﻿﻿(1 ≤ q ≤ 3 ⋅ 10^5)(1≤q≤3⋅10^5)﻿﻿ — количество запросов.
Следующие ﻿﻿qq﻿﻿ строк описывают запросы. ﻿﻿ii﻿﻿-ая строка содержит целое число ﻿﻿k_iki
 ﻿﻿﻿﻿(0 ≤ k_i ≤ 2^{32} - 1)(0≤ki≤2^32−1)﻿﻿, которое стажеры просят добавить во множество.
Формат выходных данных
Выведите ﻿﻿qq﻿﻿ строк, чтобы ﻿﻿ii﻿﻿-ая строка содержала единственное целое число ﻿﻿x_ixi
 ﻿﻿ — максимальное значение исключающего ИЛИ по всем парам чисел из множества после первых ﻿﻿ii﻿﻿ операций.
