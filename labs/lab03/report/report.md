---
## Front matter
title: "Отчет по лабороторной работе №3"
subtitle: "Начало работы с markdown"
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

Научиться работать с markdown


# Выполнение лабораторной работы

Напипишем основную информацию титульного листа (рис. @fig:001).

![Название титульного листа](image/1.png){#fig:001 width=70%}

Напипишем цель выполненения лабораторной работы (рис. @fig:002).

![Цель лабораторной работы](image/3.png){#fig:002 width=70%}

Начинаем описание выполнения лабораторной работы(рис. @fig:003).

![Выполнение лаборатрной работы](image/3.png){#fig:003 width=70%}

Напипишем ответы на контрольные вопросы(рис. @fig:004).

![Ответы на контрольные вопросы](image/4.png){#fig:004 width=70%}

Сделаем выводы(рис. @fig:005).

![Вывод лабораторной работы](image/5.png){#fig:005 width=70%}


# Выводы

Мы научились работать с системой markdown.

# Список литературы{.unnumbered}

::: {#refs}
:::
