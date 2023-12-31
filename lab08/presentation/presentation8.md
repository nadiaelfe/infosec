---
## Front matter
lang: ru-RU
title: Презентация по лабораторной работе № 6
subtitle: Информационная безопасность
author: Надиа Эззакат .
institute: Российский университет дружбы народов, Москва, Россия
date: 20.10.2023
## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

* Надиа Эззакат 
* студент группы НПМбд-02-20
* Факультет физико-математических и естественных наук
* Российский университет дружбы народов


:::
::::::::::::::

# Цель лабораторной работы

Освоить на практике применение режима однократного гаммирования на примере кодирования различных исходных текстов одним ключом

## Выполнение лабораторной работы(1)

Сначала я импортировала необходимые библиотеки, как показано на шаге 43. Затем я создала функцию, выполняющую сложение по модулю два для двух строк, что является ключевой частью процесса шифрования, как описано на шаге 44. У меня также были открытые/исходные тексты, которые должны были быть одинаковой длины и готовы к шифрованию, как показано на шаге 45. Далее я создала ключ той же длины, что и открытые тексты, как указано на шаге 46. После подготовки ключа и открытых текстов я получила шифротексты с использованием ранее созданной функции, при условии, что у меня были и открытые тексты и ключ, как описано на шаге 47. Для завершения процесса мне также понадобился способ получить открытые тексты из шифротекстов с использованием того же ключа, для чего я обратилась к шагу 48. Эти шаги совместно позволили мне выполнять шифрование методом однократного гаммирования для двух текстов с общим ключом.


![Приложение, реализующее режим однократного гаммирования для двух текстов одним ключом](../lab08/1.png)

## Выполнение лабораторной работы(2)

В этом процессе, сначала было выполнено сложение по модулю два над двумя шифротекстами с использованием ранее разработанной функции, как указано в In[53]. Затем, на шаге In[50], я получила открытые тексты, применяя ту же функцию, при условии, что у меня были оба шифротекста и хотя бы один из открытых текстов. Этот шаг позволил восстановить исходные сообщения. В дальнейшем, на In[52], я извлекла часть второго текста, выравнивая его с позициями символов из первого открытого текста. Эта операция зависела от ранее созданной функции и знании обоих шифротекстов и сегменте первого открытого текста. Эти ключевые шаги позволили манипулировать и восстанавливать информацию в процессе шифрования.

:::::::::::::: {.columns align=center}
::: {.column width="60%"}
![Приложение, реализующее режим однократного гаммирования для двух текстов одним ключом](../lab08/2.png)
:::
::::::::::::::


# Вывод

В ходе выполнения данной лабораторной работы я освоила на практике применение режима однократного гаммирования на примере кодирования различных
исходных текстов одним ключом.
