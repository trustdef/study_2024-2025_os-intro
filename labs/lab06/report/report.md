---
## Front matter
title: "Отчет по лабораторной работе"
subtitle: "Дисциплина:Операционные системы"
author: "Алехин Давид Андреевич"

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

Приобретение практических навыков взаимодействия пользователя с системой по-
средством командной строки.

# Задание

Выполнить все задания в работе.

# Теоретическое введение

# Выполнение лабораторной работы

Выполняю пункт 1. Выполняю пункт 2.1 (рис. [-@fig:001]).

![1](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab06/report/image/5393596974172861340.jpg){#fig:001 width=70%}

Выполняю пункт 2.2. С помощью различных опций команды ls вывожу содержимое на экран( меняется предоставляемая информация и файлы , который можно видеть ) (рис. [-@fig:002]).

![2](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab06/report/image/5393596974172861341.jpg){#fig:002 width=70%}

Выполняю пункт 2.3 (Да, есть). Выполняю пункт 2.4 (Владельцем является alekhin_david). Выполняю пункт 3.1. Выполняю пункт 3.2 (рис. [-@fig:003]).

![2-3](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab06/report/image/5393596974172861342.jpg){#fig:003 width=70%}

Выполняю пункт 3.3. Выполняю пункт 3.4 (Нет , не был удалён). Выполняю пункт 3.5 (Удаляю morefun, убеждаюсь , что удалён)Выполняю пункт 4 (Надо использовать опцию -R). Выполняю пункт 5 (Надо использовать опцию -l). Выполняю пункт 6 (
rm удаляет каталоги, которые могут содержать содержимое, включая файлы и подкаталоги. 
rmdir удаляет только пустые каталоги. Если каталог содержит файлы или подкаталоги, эта команда не будет работать.
Cd - перемещение по системе
Pwd полный путь к файлу
Mkdir создание директори) (рис. [-@fig:004]).

![3-6](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab06/report/image/5393596974172861343.jpg){#fig:004 width=70%}

Выполняю пункт 7 (рис. [-@fig:005]).

![7](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab06/report/image/5393596974172861344.jpg){#fig:005 width=70%}

# Выводы

Я выполнил основную цель работы:
Приобретение практических навыков взаимодействия пользователя с системой по-
средством командной строки.

# Список литературы{.unnumbered}

https://esystem.rudn.ru/course/view.php?id=20442
