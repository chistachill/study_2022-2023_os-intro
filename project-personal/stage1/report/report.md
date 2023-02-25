---
## Front matter
title: "Отчет по выполнению индивидуального проекта"
subtitle: "Этап 1"
author: "Попова Елизавета Сергеевна"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Размещение на Github pages заготовки для персонального сайтам, а также познакомиться
с основными возможностями разметки Markdown.

# Задание

-Установить необходимое программное обеспечение.
-Скачать шаблон темы сайта.
-Разместить его на хостинге git.
-Установить параметр для URLs сайта.
-Разместить заготовку сайта на Github pages

# Выполнение лабораторной работы

Устанавливаем и распаковываем архив с необходимыми файлами (рис. @fig:001).

![Распаковка архива](image/1.png){#fig:001 width=70%}

Создаем папку bin (рис. @fig:002).

![Создание папки bin](image/2.png){#fig:002 width=70%}

Переносим исполняемый файл hugo в папку bin (рис. @fig:003).

![Перенос файла hugo в папку bin](image/3.png){#fig:003 width=70%}

Заходим на гитхаб и копируем папку с файлами в новый репозиторий (рис. @fig:004).

![Перенос папки в новый репозиторий](image/4.png){#fig:004 width=70%}

Называем новый репозиторий blog (рис. @fig:005).

![Создание нового репозитория с именем blog](image/5.png){#fig:005 width=70%}

Проверяем, что всё выполнено верно (рис. @fig:006).

![Проверка правильности выполнения](image/6.png){#fig:006 width=70%}

Перенесем репозиторий на компьютер (рис. @fig:007).

![Копирование репозитория](image/7.png){#fig:007 width=70%}

Проверяем, что всё перенесено верно (рис. @fig:008).

![Проверка правильности переноса данных](image/8.png){#fig:008 width=70%}

Запускаем исполняемый файл hugo из папки bun в папке blog (рис. @fig:009).

![Запуск исполняемого файла hugo в папке blog](image/9.png){#fig:009 width=70%}

Удаляем ненужный каталог public (рис. @fig:010).

![Удаление каталога public](image/10.png){#fig:010 width=70%}

Запускаем исполняемый файл hugo server в папке blog (рис. @fig:001).

![Запуск исполняемого файла hugo server в папке blog](image/11.png){#fig:011 width=70%}

Проверяем, что всё работает (рис. @fig:012).

![Проверка правильности выполнения](image/12.png){#fig:012 width=70%}

Создаем новый репозиторий (рис. @fig:013).

![Создание нового репозитория](image/13.png){#fig:013 width=70%}

Убедимся, что создание корректно (рис. @fig:014).

![Проверка корректности выполнения действий](image/14.png){#fig:014 width=70%}

Создание завершено (рис. @fig:015).

![Завершение создания репозитория](image/15.png){#fig:015 width=70%}

Скопируем новый репозиторий в папку work и убедимся, что всё выполнено правильно (рис. @fig:016).

![Перенос нового репозитория в папку work](image/16.png){#fig:016 width=70%}

Перейдем в созданную папку с нашим сайтом и переключимся на ветку main (рис. @fig:017).

![Подключение ветки main](image/17.png){#fig:017 width=70%}

Создадим в папке с сайтом файл README.md и загрузим всё на github (рис. @fig:018).

![Создание файла README.md и загрузка данных на github](image/18.png){#fig:018 width=70%}

Перейдем в репозиторий с нашим сайтом (рис. @fig:019).

![Переход в репозиторий с сайтом](image/19.png){#fig:019 width=70%}

Убедимся, что файл README.md загружен на github (рис. @fig:020).

![Проверка корректности выполнения наших действий](image/20.png){#fig:020 width=70%}

Перейдем в каталог blog и убедимся, что мы находимся в нужной папке (рис. @fig:021).

![Проверка корректности нахождения](image/21.png){#fig:021 width=70%}

Выполним команду git submodule add -b main (рис. @fig:022).

![Выполнение команды git submodule add -b main](image/22.png){#fig:022 width=70%}

Закомментируем команду public/ в файла .gitignore (рис. @fig:023).

![Комментирование команды public/ в файле .gitignore](image/23.png){#fig:023 width=70%}

Проверим, что мы верно выполнили действие и повторно выполним команду git submodule add -b main (рис. @fig:024).

![Проверка корректности выполнения действий](image/24.png){#fig:024 width=70%}

Перейдем в папку public, чтобы убедиться, что файлы, присутствующие в нашем репозитории присутсвтуют в папке public (рис. @fig:025).

![Проверка корректности выполнения действий](image/25.png){#fig:025 width=70%}

Выполним исполняемый файл hugo в папке blog (рис. @fig:026).

![Выполнение исполняемого файла hugo в папке blog](image/26.png){#fig:026 width=70%}

Проверим, что всё выполнено верно (рис. @fig:027).

![Проверка корректности выполнения действий](image/27.png){#fig:027 width=70%}

Выполним команду git remote -v (рис. @fig:028).

![Выполнение команды git remote -v](image/28.png){#fig:028 width=70%}

Загрузим все изменения на github (рис. @fig:029).

![Загрузка изменений на github](image/29.png){#fig:029 width=70%}

Зайдем на github и убедимся, что все файлы перенеслись (рис. @fig:030).

![Проверка корректности переноса файлов на github](image/30.png){#fig:030 width=70%}



# Выводы

Мы научились размещать на Github pages заготовки для персонального сайтам, а также познакомились
с основными возможностями разметки Markdown.

# Список литературы{.unnumbered}

::: {#refs}
:::
