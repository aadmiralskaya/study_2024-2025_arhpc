---
## Front matter
title: "Отчёт по лабораторной работе №3"
subtitle: "Дисциплина: архитектура компьютера"
author: "Адмиральская Александра Андреевна"

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
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
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

Освоение процедуры оформления отчетов с помощью языка разметки Markdown.

# Задание

Заполнение отчета по выполнению лабораторной работы №3 с помощью языка разметки Markdown и выполнение задания для самостоятельной работы.

# Выполнение лабораторной работы

Для начала открываем терминал и переходим в каталог курса сформированный при выполнении лабораторной работы №2. Далее обновляем локальный репозиторий, скачав изменения из удаленного репозитория (рис. [-@fig:001]).

![Переход в каталог курса и обновление локального репозитория.](image/1.jpg){#fig:001 width=70%}

Затем переходим в каталог с шаблоном отчета по лабораторной работе № 3 (рис. [-@fig:002]).

![Переход в каталог с шаблоном отчета по лабораторной работе № 3.](image/2.jpg){#fig:002 width=70%}

Проводим компиляцию шаблона с использованием Makefile при помощи команды make (рис. [-@fig:003]). 

![Компиляция шаблона с использованием Makefile.](image/2.2.jpg){#fig:003 width=70%}

Далее удаляем полученные файлы с использованием Makefile при помощи команды make clean (рис. [-@fig:004]).

![Удаление полученных файлов с использованием Makefile.](image/3.jpg){#fig:004 width=70%}

Открываем файл report.md c помощью текстового редактора gedit (рис. [-@fig:005]). 

![Открытие файла report.md.](image/4.jpg){#fig:005 width=70%}

Внимательно изучаем структуру этого файла (рис. [-@fig:006]). 

![Структура файла report.md.](image/5.jpg){#fig:006 width=70%}

Начинаем заполнять отчет с использованием Makefile (рис. [-@fig:007]).

![Заполнение отчета.](image/6.png){#fig:007 width=70%}

Компилируем файл с отчетом. Загружаем файлы на Github.

# Выводы

Здесь кратко описываются итоги проделанной работы.

# Список литературы{.unnumbered}

::: {#refs}
:::
