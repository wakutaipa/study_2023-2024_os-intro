---
## Front matter
lang: ru-RU
title: Презентация по лаблраторной работе №4
subtitle: Архитектура Компьютеров и Операционные Системы 
author:
  - Вакутайпа М.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 07 марта 2024

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
  * Студентка НКА-02-23
  * Факультет Физико-математический и естественный наук
  * Российский университет дружбы народов
  * [1032239009@pfur.ru](mailto:1032239009@pfur.ru)
  * <https://wakutaipa.github.io/ru/>

:::
::: {.column width="30%"}
:::
::::::::::::::


# Цель работы

Цель данной работы является получением навыков правильной работы с репозиториями git.

# Выполнение лабораторной работы

## Установка git-flow

Gitflow Workflow предполагает выстраивание строгой модели ветвления с учётом выпуска проекта. Сначала я включаю репозиторий copr:

![включение copr](image/1.0.PNG){#fig:001 width=60%}

## Установка git-flow

Используя dnf install скачаю gitflow:

![dnf install gitflow ](image/2.PNG){#fig:002 width=60%}

## Установка Node.js

Для семантического версионирования и общепринятых коммитов я устанавливаю Nodejs и pnpm:

![Установка Nodejs](image/3.PNG){#fig:003 width=60%}

## Установка Node.js

![Установка pnpm](image/4.PNG){#fig:004 width=60%}

## Настройка Node.js

Запуская pnpm setup я добавляю каталог с исполняемыми файлами, устанавливаемыми yarn для работы с Node.js в переменную PATH:

![Запуск pnpm](image/5.PNG){#fig:005 width=60%}

## Настройка Node.js

Далее перелогинуюсь и выполняю source ~/.bashrc:

![~/.bashrc](image/6.PNG){#fig:006 width=60%}

## Общепринятые коммиты

Для помощи в форматировании коммитов добавляю программу commitizen:

![добавление commitizen](image/7.PNG){#fig:007 width=60%}

## Общепринятые коммиты

Добавляю standard-changelog для помощи в создании логов:

![добавление standard-changelog](image/8.PNG){#fig:008 width=60%}

## Общепринятые коммиты

Создаю репозиторий на GitHub назову его git-extended:

![Создание git-extended](image/9.PNG){#fig:009 width=60%}

## Общепринятые коммиты

Делаю первый коммит и выкладываю на github:

![Первый коммит](image/12.PNG){#fig:0012 width=60%}

## Общепринятые коммиты

Я инициализирую pnpm:

![Инициализирование pnpm](image/13.PNG){#fig:0013 width=60%}

## Общепринятые коммиты

Заполняю несколько параметров пакета (файл package.json):

![Заполнение пакетов](image/14.PNG){#fig:0014 width=60%}

## Общепринятые коммиты

Добавляю новые файлы и выполняю коммит (указиваю тип коммит (feat)) и отправляю на гит:

![Добавление новых файлов](image/15.PNG){#fig:0015 width=60%}

## Общепринятые коммиты

Инициализирую git-flow и указываю ветки:

![Инициализирование git-flow](image/17.PNG){#fig:0016 width=60%}

## Общепринятые коммиты

Преверяю что я на ветке develop с промощью git branch:

![Проверка ветки](image/18.PNG){#fig:0017 width=60%}

## Общепринятые коммиты

Загружаю весь репозиторий в хранилище с помощью git push --all:

![Загрузка репозиторий](image/19.PNG){#fig:0018 width=60%}

## Общепринятые коммиты

Установливаю внешнюю ветку как вышестоящую для этой ветки (develop):

![установка внешней ветки](image/20.PNG){#fig:0019 width=60%}

## Общепринятые коммиты

Создаю релиз с версией 1.0.0 и журнал изменений (standard-changelog)::

![Создание релиза](image/21.PNG){#fig:0020 width=60%}

## Общепринятые коммиты

Добавляю журнал изменений в индекс:

![Добавление журнала изменений](image/22.PNG){#fig:0021 width=60%}

## Общепринятые коммиты

Залью релизную ветку в основную ветку:

![Замена ветки](image/23.PNG){#fig:0032 width=60%}

## Общепринятые коммиты

Отправляю данные на github:

![Отправка на гит](image/24.PNG){#fig:0022 width=60%}

## Общепринятые коммиты

Создаю релиз на github. Для этого использую утилиты работы с github gh (gh release create):

![Создание релиза](image/25.PNG){#fig:0023 width=60%}

## Общепринятые коммиты

Создаю ветку для новой функциональности:

![Создание ветки feature_branch](image/26.PNG){#fig:0024 width=60%}

## Общепринятые коммиты

Далее, продолжаю работу c git как обычно. Создаю релиз с версией 1.2.3:

![Создание релиза с версией 1.2.3](image/27.PNG){#fig:0025 width=60%}

## Общепринятые коммиты

Обновляю номер версии в файле package.json в 1.2.3:

![Обновление номера версии](image/28.PNG){#fig:0026 width=60%}

## Общепринятые коммиты

Создаю журнал изменений (standard-changelog):

![Создание нового журнала изменений](image/29.PNG){#fig:0027 width=60%}

## Общепринятые коммиты

Добавляю журнал изменений в индекс:

![Добавление журнала](image/30.PNG){#fig:0028 width=60%}

## Общепринятые коммиты

Залью релизную ветку в основную ветку:

![Замена ветки](image/31.PNG){#fig:0029 width=60%}

## Общепринятые коммиты

Отправляю данные на github:

![Отправка данных](image/32.PNG){#fig:0030 width=60%}

## Общепринятые коммиты

Создаю релиз на github с комментарием из журнала изменений:

![Cоздание релиза](image/33.PNG){#fig:0031 width=60%}

# Выводы

При выполнение работы я получила навыки правильной работы с репозиториями git.