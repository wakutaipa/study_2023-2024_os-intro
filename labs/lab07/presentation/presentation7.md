---
## Front matter
lang: ru-RU
title: Презентация по лабораторной работе №7
subtitle: Анализ файловой системы Linux. Команды для работы с файлами и каталогами
author:
  - Вакутайпа М.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 19 марта 2024

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

  * Вакутайпа Милдред
  * НКА 02-23
  * Факультет физико-математический и естественных наук
  * Российский университет дружбы народов
  * [1032239009@rudn.ru](1032239009@rudn.ru)
  * <https://wakutaipa.github.io/>

:::
::: {.column width="30%"}
:::
::::::::::::::


## Работа с файлами и каталогами

Создаю файл abc1 с помощью touch и копирую его с новыми именами april и may исползуя cp:

![Создание файлов abc1, april и may](image/1.PNG){#fig:001 width=70%}

## Работа с файлами и каталогами

Создаю каталог monthly и копирую april и may в нем исползуя cp. Проверяю с ls:

![Создание monthly](image/2.PNG){#fig:002 width=70%}

## Работа с файлами и каталогами

Копирую каталог monthly в каталог monthly.00 с помощью опции cp -r:

![копирование каталога monthly](image/4.PNG){#fig:004 width=70%}

## Работа с файлами и каталогами

Изменяю название файла april на july в домашнем каталоге и перемещаю файл july в каталог monthly.00:

![Перемещение файла july ](image/6.PNG){#fig:006 width=70%}

## Работа с файлами и каталогами

 Перемещаю файл equipment в каталог ~/ski.plases:

![Перемещение файла equipment](image/16.PNG){#fig:0011 width=70%}

## Работа с файлами и каталогами

Переименую файл ~/ski.plases/equipment в ~/ski.plases/equiplist и копирую abc1 в каталог ~/ski.plases, назову его equiplist2:

![Переименование файла /equipment](image/17.PNG){#fig:0012 width=70%}

## Работа с файлами и каталогами

Создаю каталог с именем equipment в каталоге ~/ski.plases и перемещаю файлы ~/ski.plases/equiplist и equiplist2 в каталог ~/ski.plases/equipment:

![Создание каталога equipment, перемещение файлов ](image/19.PNG){#fig:0013 width=70%}

## Работа с файлами и каталогами

Создаю каталог australia. Удаляю права на исполнение для группы (g-x) и владелца(u-x):

![Создание australia](image/21.PNG){#fig:0015 width=70%}

## Работа с файлами и каталогами

![Удаление права](image/21.1.PNG){#fig:0016 width=70%}

## Работа с файлами и каталогами

Изменяю права доступа к каталогу play и проверяю:

![Измениеие прав](image/22.PNG){#fig:0017 width=70%}

## Работа с файлами и каталогами

![Проверка изменений](image/23.PNG){#fig:0018 width=70%}

## Работа с файлами и каталогами

Изменяю права доступа к файлу feathers и проверяю:

![Измениеие прав к файлу feathers](image/26.PNG){#fig:0019 width=70%}

## Работа с файлами и каталогами

Смотрю содержимое файла /etc/passwd:

![команда cat](image/27.PNG){#fig:0020 width=70%}

## Работа с файлами и каталогами

Лишаю пользователя файла ~/feathers права на чтение:

![Лишение права на читение](image/30.PNG){#fig:0023 width=70%}

## Работа с файлами и каталогами

Когда я попытаюсь просмотреть файл ~/feathers командой cat, система запрешает мне:

![Посмотра файла feathers](image/31.PNG){#fig:0024 width=70%}

## Работа с файлами и каталогами

Лишаю владельца каталога ~/play права на выполнение. Когда я попробую перейти в этот же каталог, система запрешает мне:

![Лишение права на выполнение](image/32.PNG){#fig:0025 width=70%}

## Работа с файлами и каталогами

Даю владельцу каталога ~/play право на выполнение:

![Название рисунка](image/33.PNG){#fig:0026 width=70%}

## Работа с файлами и каталогами

С помощью man прочитаю по mount — утилита командной строки в UNIX-подобных операционных системах. Применяется для монтирования файловых систем.

![mount](image/34.PNG){#fig:0027 width=70%}
