---
## Front matter
title: "Отчет по лабораторной работе 13"
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



# Задание

1. Используя команды getopts grep, написать командный файл, который анализирует
командную строку с ключами:
– -iinputfile — прочитать данные из указанного файла;
– -ooutputfile — вывести данные в указанный файл;
– -pшаблон — указать шаблон для поиска;
– -C — различать большие и малые буквы;
– -n — выдавать номера строк.
а затем ищет в указанном файле нужные строки, определяемые ключом -p.
2. Написать на языке Си программу, которая вводит число и определяет, является ли оно
больше нуля, меньше нуля или равно нулю. Затем программа завершается с помощью
функции exit(n), передавая информацию в о коде завершения в оболочку. Команд-
ный файл должен вызывать эту программу и, проанализировав с помощью команды
$?, выдать сообщение о том, какое число было введено.
3. Написать командный файл, создающий указанное число файлов, пронумерованных
последовательно от 1 до 𝑁 (например 1.tmp, 2.tmp, 3.tmp,4.tmp и т.д.). Число файлов,
которые необходимо создать, передаётся в аргументы командной строки. Этот же ко-
мандный файл должен уметь удалять все созданные им файлы (если они существуют).
4. Написать командный файл, который с помощью команды tar запаковывает в архив
все файлы в указанной директории. Модифицировать его так, чтобы запаковывались
только те файлы, которые были изменены менее недели тому назад (использовать
команду find).


# Теоретическое введение



# Выполнение лабораторной работы

Используя команды getopts grep напишем командный файл, который анализирует командную строку с ключами и выполним его: -i inputfile — прочитать данные из указанного файла; -o outputfile — вывести данные в указанный файл; -p шаблон — указать шаблон для поиска; -C — различать большие и малые буквы; -n — выдавать номера строк; а затем ищет в указанном файле нужные строки (рис. [-@fig:001], [-@fig:002]).

![1](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab13/report/image/5258429933846393509.jpg){#fig:001 width=70%}

![2](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab13/report/image/5258429933846393517.jpg){#fig:002 width=70%}

Напишем сначала на языке Си программу, которая вводит число и определяет, является ли оно больше нуля, меньше нуля или равно нулю. Затем завершим программу при помощи функции exit(n), передавая информацию о коде завершения в оболочку. Командный файл вызовет эту программу и, проанализировав с помощью команды $?, выдаст сообщение о том, какое число было введено (рис. [-@fig:003], [-@fig:004], [-@fig:005] ).

![3](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab13/report/image/5258429933846393510.jpg){#fig:003 width=70%}

![4](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab13/report/image/5258429933846393511.jpg){#fig:004 width=70%}

![5](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab13/report/image/5258429933846393512.jpg){#fig:005 width=70%}

Напишем командный файл, создающий указанное число файлов, пронумерованных последовательно от 1 до N (рис. [-@fig:006], [-@fig:007]).

![6](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab13/report/image/5258429933846393513.jpg){#fig:006 width=70%}

![7](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab13/report/image/5258429933846393514.jpg){#fig:007 width=70%}

Напишем командный файл, который с помощью команды tar запаковывает в архив все файлы в указанной директории. Модифицируем его так, чтобы запаковывались только те файлы, которые были изменены менее недели тому назад. (рис. [-@fig:008], [-@fig:009]).

![8](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab13/report/image/5258429933846393515.jpg){#fig:008 width=70%}

![9](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab13/report/image/5258429933846393516.jpg){#fig:009 width=70%}

# Выводы

В данной работе мы изучили основы программирования в оболочке ОС UNIX и писать более сложные командные файлы с использованием логических управляющих конструкций и циклов.

# Список литературы{.unnumbered}

https://esystem.rudn.ru/
