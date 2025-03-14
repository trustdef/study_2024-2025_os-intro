---
## Front matter
title: "Отчет по 1 этапу создания сайта"
subtitle: "Дисциплина:Операционные системы"
author: "Абрамова Ульяна Михайловна"

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
lofTitle: "Список иллюстраций"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Размещение на Github pages заготовки для персонального сайта.

# Задание

  1.  Установить необходимое программное обеспечение.
  2.  Скачать шаблон темы сайта.
  3.  Разместить его на хостинге git.
  4.  Установить параметр для URLs сайта.
  5.  Разместить заготовку сайта на Github pages.

# Выполнение лабораторной работы
## Установка программного обеспечения для Hugo 
Устанавливаю необходимое программное обеспечение (рис.1)

![Установка программного обеспечения для Hugo](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab15/report/image/1.jpg){#fig:fig1 width=80%}

## Загрузка шаблона темы сайта
Скачиваю шаблон темы сайта (рис.2)

![Загрузка шаблона](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab15/report/image/2.jpg){#fig:fig2 width=80%}

## Размещение шаблона темы сайта на хостинге git
Установка темы (внешнего вида) сайта (рис.3,4)

![Установка темы сайта](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab15/report/image/3.jpg){#fig:fig3 width=80%}

![Установка темы сайта](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab15/report/image/4.jpg){#fig:fig4 width=80%}

## Публикация сайта
Создаю репозиторий для страницы пользователя на Github (рис.5)

![Создание репозитория для страницы пользователя на Github](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab15/report/image/5.jpg){#fig:fig5 width=80%}

Генерирую и развёртываю сайт (рис.6)

![Генерация и развёртывание сайта](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab15/report/image/6.jpg){#fig:fig6 width=80%}

Отправляю контент на github (рис.7)

![Отправка контента на github](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab15/report/image/7.jpg){#fig:fig7 width=80%}

# Выводы

В итоге я научилась размещать на github pages заготовки для персонального сайта.

# Список литературы{.unnumbered}
1. [Операционные системы](https://esystem.rudn.ru/mod/page/view.php?id=1224217)
