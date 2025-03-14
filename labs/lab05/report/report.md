---
## Front matter
title: "Отчет по лабораторной работе"
subtitle: "Дисциплина:Операционные системы"
author: "Отчет по лабораторной работе"

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

Настройка интерфейса с броузером
Управление файлами конфигурации
Использование chezmoi на нескольких машинах

# Задание

Настройка интерфейса с броузером
Управление файлами конфигурации
Использование chezmoi на нескольких машинах

# Теоретическое введение



# Выполнение лабораторной работы

Устанавливаю pass и  gopass (рис. [-@fig:001], рис. [-@fig:002]).

![pass](/home/davidalekhin/Изображения/2025-03-10T15:12:52,230844190+03:00.png){#fig:001 width=70%}

![gopass](/home/davidalekhin/Изображения/2025-03-10T15:13:26,050267247+03:00.png){#fig:002 width=70%}

Просматриваю список ключей и инициализирую хранилище. А также создаю структуру гит (рис. [-@fig:003]).

![инициализирую хранилище, создаю структуру гит](/home/davidalekhin/Изображения/2025-03-10T15:15:19,689353156+03:00.png){#fig:003 width=70%}

Создаю новый репозиторий и задаю адрес репрозитория на хостинге, а также выполняю синхронизацию (рис. [-@fig:004]).

![Создаю новый репозиторий и задаю адрес репрозитория на хостинге](/home/davidalekhin/Изображения/2025-03-10T15:32:02,745215025+03:00.png){#fig:004 width=70%}

Устанавливаю browserpass (рис. [-@fig:005]).

![browserpass](/home/davidalekhin/Изображения/2025-03-10T15:36:19,630279881+03:00.png){#fig:005 width=70%}

Образую пароль в ранее созданном файле (рис. [-@fig:006]).

![пароль](/home/davidalekhin/Изображения/2025-03-10T15:42:05,203780851+03:00.png){#fig:006 width=70%}

После заменяю существующий пароль (рис. [-@fig:007]).

![заменяю существующий пароль](/home/davidalekhin/Изображения/2025-03-10T15:44:03,528577066+03:00.png){#fig:007 width=70%}

Устанавливаю по и шрифты (рис. [-@fig:008]).

![по и шрифты](/home/davidalekhin/Изображения/2025-03-10T15:47:25,999559172+03:00.png){#fig:008 width=70%}

Устанавливаю shezmoi и создаю свой репозиторий для конфигурационных файлов на основе шаблона (рис. [-@fig:009]).

![shezmoi](/home/davidalekhin/Изображения/2025-03-11T20:30:09,972908700+03:00.png){#fig:009 width=70%}

Подключаю репозиторий к своей системе (рис. [-@fig:010]).

![Подключаю репозиторий к своей системе](/home/davidalekhin/Изображения/2025-03-11T20:49:15,444440616+03:00.png){#fig:010 width=70%}

Проверяю внесённые изменения и соглашаюсь с ними (рис. [-@fig:011]).

![Проверяю внесённые изменения](/home/davidalekhin/Изображения/2025-03-11T20:49:32,787147946+03:00.png){#fig:011 width=70%}

# Выводы

В результате я выполнил основные задачи лабораторной работы а именно:
Настройка интерфейса с броузером
Управление файлами конфигурации
Использование chezmoi на нескольких машинах

# Список литературы{.unnumbered}

https://esystem.rudn.ru/mod/page/view.php?id=1224236#orgb06553f

