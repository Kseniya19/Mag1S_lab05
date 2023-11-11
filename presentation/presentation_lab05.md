---
# Front matter
lang: ru-RU
title: Защита лабораторной работы №5
subtitle: Вероятностные алгоритмы проверки чисел на простоту 
author: "Бурдина К. П."
institute: Российский университет дружбы народов, Москва, Россия
date: 9 ноября 2023

# Formatting
toc: false
slide_level: 2
header-includes: 
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true
theme: metropolis

---

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

    * Бурдина Ксения Павловна
    * студентка группы НФИмд-02-23
    * студ. билет № 1132236896
    * Российский университет дружбы народов
    * 1132236896@rudn.ru

:::
::: {.column width="30%"}

![](screens/bkp.jpg)

:::
::::::::::::::

# Вводная часть 

## Цель выполнения лабораторной работы

- Освоение вероятностных алгоритмов проверки чисел на простоту
- Программная реализация представленных алгоритмов проверки чисел на простоту

## Теоретические сведения

Пусть $a$ - целое число. Числа $\pm 1, \pm a$ называются *тривиальными делителями* числа $a$.

Целое число $p \in Z / \lbrace 0\rbrace$ называется *простым*, если оно не является делителем единицы и не имеет других делителей, кроме тривиальных. В противном случае число $p \in Z / \lbrace -1, 0, 1\rbrace$ называется *составным*.

Например, числа $\pm 2, \pm 3, \pm 5, \pm 7,\pm 11,\pm 13,\pm 17,\pm 19,\pm 23,\pm 29$ являются простыми.

## Теоретические сведения

Алгоритмы проверки на простоту можно разделить на вероятностные и детерминированные.

*Детерминированный* алгоритм всегда действует по одной и той же схеме и гарантированно решает поставленную задачу (или не дает никакого ответа).

*Вероятностный* алгоритм использует генератор случайных чисел и дает не гарантированно точный ответ.

## Теоретические сведения

Схема вероятностного алгоритма проверки числа на простоту:

![Схема проверки числа](screens/0.jpg){width=80%}

# Результат выполнения лабораторной работы

## Результат выполнения лабораторной работы

Постановка задачи:

Реализовать вероятностные алгоритмы проверки чисел на простоту, такие как:
- Алгоритм, реализующий тест Ферма
- Алгоритм вычисления символа Якоби
- Алгоритм, реализующий тест Соловэя-Штрассена
- Алгоритм, реализующий тест Миллера-Рабина

## Результат выполнения лабораторной работы

Алгоритм, реализующий тест Ферма:

![Тест Ферма](screens/1.jpg){width=90%}

## Результат выполнения лабораторной работы

Алгоритм вычисления символа Якоби:

![Символ Якоби](screens/2.jpg){width=80%}

## Результат выполнения лабораторной работы

Алгоритм, реализующий тест Соловэя-Штрассена:

![Тест Соловэя-Штрассена](screens/4.jpg){width=80%}

## Результат выполнения лабораторной работы

Алгоритм, реализующий тест Миллера-Рабина:

![Тест Миллера-Рабина](screens/5.jpg){width=80%}

## Результат выполнения лабораторной работы

Проверка работы алгоритмов:

![Проверка работы алгоритмов 1](screens/7.jpg){width=70%}

## Результат выполнения лабораторной работы

Проверка работы алгоритмов:

![Проверка работы алгоритмов 2](screens/8.jpg){width=70%}

# Выводы

## Выводы

1. Изучили вероятностные алгоритмы проверки чисел на простоту
2. Программно реализовали представленные алгоритмы проверки чисел на простоту