---
## Front matter
title: "Отчет по лабораторной работе 11"
subtitle: "Дисциплина: архитектура компьютера"
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

Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором Emacs.

# Задание

1. Ознакомиться с теоретическим материалом.
2. Ознакомиться с редактором emacs.
3. Выполнить упражнения.
4. Ответить на контрольные вопросы.

# Теоретическое введение



# Выполнение лабораторной работы

Откроем Emacs (рис. [-@fig:001]).

![1](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab11/report/image/5206651981379270416.jpg){#fig:001 width=70%}

Создадим файл lab07.sh с помощью комбинации Ctrl-x Ctrl-f и наберем текст из задания в ново созданный файл. (рис. [-@fig:002]).

![2](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab11/report/image/5206651981379270417.jpg){#fig:002 width=70%}

Сохраним файл с помощью комбинации Ctrl-x s. Проделаем с текстом стандартные процедуры редактирования, каждое действие осуществляется комбинациями клавиш. Вырежем командой Ctrl-w. целую строку. Вставим эту строку в конец файла командой Ctrl-y. (рис. [-@fig:003]).

![3](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab11/report/image/5206651981379270418.jpg){#fig:003 width=70%}

Выделим область текста командой Ctrl-space. (рис. [-@fig:004]).

![4](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab11/report/image/5206651981379270419.jpg){#fig:004 width=70%}

Скопируем область в буфер обмена командой alt-w. Вставим область в конец файла. (рис. [-@fig:005]).

![5](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab11/report/image/5206651981379270420.jpg){#fig:005 width=70%}

Вновь выделим эту область и на этот раз вырежем её командой Ctrl-w. (рис. [-@fig:006]).

![6](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab11/report/image/5206651981379270421.jpg){#fig:006 width=70%}

Отменим последнее действие командой Ctrl-x u.
Научимся использовать команды по перемещению курсора.

    Переместим курсор в начало строки командой Ctrl-a.

    Переместим курсор в курсор строки командой Ctrl-e.

    Переместим курсор в начало буфера Alt-<.

    Переместим курсор в конец буфера Alt->.


Управление буферами. Введем Ctrl-x 2. (рис. [-@fig:007]).

![7](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab11/report/image/5206651981379270422.jpg){#fig:007 width=70%}

Переместим вновь открытое окно Ctrl-x со списком открытых буферов и переключимся на другой буфер. (рис. [-@fig:008]).

![8](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab11/report/image/5206651981379270423.jpg){#fig:008 width=70%}

Закроем это окно командой Ctrl-x 0. (рис. [-@fig:009]).

![9](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab11/report/image/5206651981379270424.jpg){#fig:009 width=70%}

Теперь вновь переключимся между буферами, но уже без вывода их списка на экран Ctrl-x b. (рис. [-@fig:010]).

![10](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab11/report/image/5206651981379270425.jpg){#fig:010 width=70%}

Поделим фрейм на 4 части: разделитм фрейм на два окна по вертикали Ctrl-x 3, а затем каждое из этих окон на две части по горизонтали Ctrl-x 2. В каждом из четырёх созданных окон откроем новый буфер (файл). (рис. [-@fig:011]).

![11](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab11/report/image/5206651981379270426.jpg){#fig:011 width=70%}

Переключимся в режим поиска Ctrl-s и найдем несколько слов, присутствующих в тексте. Выйдем из режима поиска, нажав Ctrl-g. Перейдем в режим поиска и замены Alt-Shift %, введем текст, который следует найти и заменить, для замены нажмем Enter. После этого нажмем ! для подтверждения замены. Если мы хотим заменить конкретные слова то мы их выделяем и нажимаем Enter. Если все то ! Испробуем другой режим поиска, нажав Alt-s .
От обычного режима отличается тем, что находит не фрагмент текста, а файл.


# Выводы

В данной работе мы познакомились с еще одним редактором операционной системой Linux. Получили практические навыки работы с редактором Emacs.

# Список литературы{.unnumbered}

https://esystem.rudn.ru/
