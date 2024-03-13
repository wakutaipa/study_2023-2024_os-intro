---
## Front matter
lang: ru-RU
title: Презентация по второму этапу индивидуального проекта
subtitle: Архитектура компьютеров и операционные системы
author:
  - Вакутайпа М.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 13 марта 2024

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
  * НКА-02-23
  * Факультет: Физико-математический и естественный наук 
  * Российский университет дружбы народов
  * [1032239009@rudn.ru](1032239009@rudn.ru)
  * <https://wakutaipa.github.io/>

:::
::: {.column width="30%"}
:::
::::::::::::::

# Цель работы

Изучение размещения посты на сайте.

# Задание

1. Добавлять данные:
   1. Разместить фотографию владельца сайта
   2. Разместить краткое описание владельца сайта
   3. Добавить информацию об интересах
   4. Добавить информацию об образовании
   
2. Сделать пост по прошедшей неделе
3. Сделать пост по теме "Управление версиями GIT" 


## Добавление данных

### Разместить фотографию владельца сайта

Я запускаю hugo в каталоге ~/work/blog/, чтобы начать создание сайта:

![Запуск hugo](image/8.PNG){#fig:001 width=70%}

### Разместить фотографию владельца сайта

Запускаю hugo server, чтобы получить локальный хост-сайт, где я могу видеть вносимые мной изменения: 

![Запуск hugo server](image/9.PNG){#fig:002 width=70%}

### Разместить фотографию владельца сайта

Для того, чтобы добавить фотографию на сайта я перехожу в каталог ~/work/blog/content/author:

![~/work/blog/content/author](image/1.PNG){#fig:003 width=70%}

### Разместить фотографию владельца сайта

Заменяю avatar.jpg на свою фотографию и она устанавливается автоматический:

![Замена фотографии](image/10.0.PNG){#fig:004 width=70%}

### Разместить краткое описание владельца сайта

Далее с помощью gedit я редактирую файл index.md, который ноходится в ~/work/blog/content/author и добавляю свою краткую биографию:

![Файл с информацией владельца](image/3.PNG){#fig:005 width=70%}

### Разместить краткое описание владельца сайта

![Краткая биография](image/4.PNG){#fig:006 width=70%}

### Разместить краткое описание владельца сайта

Проверяю изменении на сайте:

![Проверка на сайте](image/10.PNG){#fig:009 width=70%}

### Добавить информацию об интересах

Также изменяю информацию об интересах:

![Интересы](image/5.PNG){#fig:007 width=70%}

### Добавить информацию об образовании

Также изменяю информацию об образовании:

![Образование](image/6.PNG){#fig:008 width=70%}

## Пост по прошедшей неделе

Я перехожу в катклог ~/work/blog/content/post и создаю новую папку. Создаю файл index.md и вставляю фотографию featured.jpg:

![~/work/blog/content/post/FirstWeekofMarch](image/12.PNG){#fig:0010 width=70%}

## Пост по прошедшей неделе

Я редактирую файл и добавляю информацию по прошедшей неделе:

![Пост по прошедшей неделе](image/12.1.PNG){#fig:0011 width=70%}

## Пост по теме "Управление версиями GIT"

Создаю ещё одну новую папку в ~/work/blog/content/post. Создаю файл index.md и вставляю фотографию featured.jpg:

![~/work/blog/content/post/VersionControl](image/14.PNG){#fig:0012 width=70%}

## Пост по теме "Управление версиями GIT"

Я редактирую файл и добавляю информацию об управлении версиями GIT (Что это такое и как работает):

![Редактирование поста об управлении версиями GIT](image/13.PNG){#fig:0013 width=70%}

## Пост по теме "Управление версиями GIT"

После сохранения изменении, я отправляю все на github:

![Развертывание сайта](image/19.PNG){#fig:0014 width=70%}

# Выводы

При выполнении данной работы, я освоила размещение посты на сайте по шаблону hugo.