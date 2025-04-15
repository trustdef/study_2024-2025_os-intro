---
## Front matter
title: "Отчет по лабораторной работе 10"
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

Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором vi, установленным по умолчанию практически во всех дистрибутивах.

# Задание

Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором vi, установленным по умолчанию практически во всех дистрибутивах.

# Теоретическое введение



# Выполнение лабораторной работы



Создадим каталог с именем ~/work/os/lab06.
Перейдем во вновь созданный каталог. (рис. [-@fig:001]).

![1](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab10/report/image/5472294664959813981.jpg){#fig:001 width=70%}

Вызовем vi и создадим файл hello.sh vi hello.sh 
Нажмем клавишу i и введем текст из задания.
Нажмем клавишу Esc для перехода в командный режим после завершения ввода текста.
Нажмем : для перехода в режим последней строки и внизу нашего экрана появится приглашение в виде двоеточия.
Нажмем w (записать) и q (выйти), а затем нажмем клавишу Enter для сохранения нашего текста и завершения работы. (рис. [-@fig:002]).

![2](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab10/report/image/5472294664959813978.jpg){#fig:002 width=70%}

Сделаем наш файл исполняемым и попытаемся его исполнить. (рис. [-@fig:003]).

![3](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab10/report/image/5472294664959813980.jpg){#fig:003 width=70%}

Вызовем vi на редактирование файла vi ~/work/os/lab06/hello.sh
Установим курсор в конец слова HELL второй строки.
Перейдем в режим вставки и заменим на HELLO. Нажмем Esc для возврата в командный режим.
Установим курсор на четвертую строку и сотрем слово LOCAL.
Перейдем в режим вставки и наберем следующий текст: local, нажмем Esc для возврата в командный режим.
Установим курсор на последней строке файла. Вставим после неё строку, со- держащую следующий текст: echo $HELLO.
Нажмем Esc для перехода в командный режим.
Удалим последнюю строку.
Введем команду отмены изменений u для отмены последней команды.
Введем символ : для перехода в режим последней строки. Запишем произведённые изменения и выйдем из vi. (рис. [-@fig:004], [-@fig:005]).

![4](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab10/report/image/5472294664959813982.jpg){#fig:004 width=70%}

![5](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab10/report/image/5472294664959813979.jpg){#fig:005 width=70%}

# Выводы

В ходе роботы мы познакомились с операционной системой Linux, и получили практические навыки работы с редактором vi, установленным по умолчанию практически во всех дистрибутивах UNIX. А также освоили основные режимы и команды.

# Список литературы{.unnumbered}

https://esystem.rudn.ru/
