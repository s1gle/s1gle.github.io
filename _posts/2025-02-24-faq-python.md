---
layout: post
title: faq python
date: '2025-02-24 20:27'
tags:
  - python
  - faq
description: Частозадаваемые вопросы по Python
---

# Как сложить числа? :fu:
## С помощью оператора +
```python
num1 = 5
num2 = 10
res = num1 + num2
print(res)
#result
15
```
## С помощью метода fsum модуля math
```python
import math

lst = [2, 4, 6]
print(math.fsum(lst))
#result
12.0
```
# Как умножить числа? :u7533:
```python
num1 = 5
num2 = 10
res = num1 * num2
print(res)
#result
50
```
# Как разделить числа? :dizzy_face:
```python
num1 = 5
num2 = 10
res = num1 / num2
print(res)
#result
0.5
```
# Как сгенерировать числа? :two_hearts:
Чтобы сгенерировать числа или последовательность чисел можно воспользоваться функцией range, в первом необязательном параметре которой можно указать число, с которого начнется последовательность, во втором параметре - число, на котором закончится генерация. А в третьем необязательном параметре можно задать шаг между началом и концом последовательности чисел, по умолчанию он равен 1.
```python
res = range(5, 10, 2)
for num in res:
	print(num)
#result
5
7
9
```
# Как возвести число в степень? :sparkler:
## С помощью оператора **
```python
num = 5
res = num ** 3
print(res)
#result
125
```
## С помощью метода pow модуля math
В первом параметре метода указываем нужное нам число, во втором параметре - в какую степень мы хотим его возвести.
```python
import math

num = 5
res = math.pow(5, 2)
print(res)
#result
25.0
```
# Как найти максимальное число? :cat2:
```python
num1 = 2
num2 = 5
num3 = 10
print(max(num1, num2, num3))
#result
10
```