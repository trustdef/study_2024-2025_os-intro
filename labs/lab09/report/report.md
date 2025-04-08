---
## Front matter
title: "Отчет по лабораторной работе 9"
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

Освоение основных возможностей командной оболочки Midnight Commander. Приобретение навыков практической работы по просмотру каталогов и файлов; манипуляций с ними.

# Задание

Освоение основных возможностей командной оболочки Midnight Commander. Приобретение навыков практической работы по просмотру каталогов и файлов; манипуляций с ними.

# Теоретическое введение



# Выполнение лабораторной работы



Изучим информацию о mc при помощи справки man. Воспользуемся справкой и узнаем что для того чтобы войти в командную оболочку мы должны ввести в командной строке mc. Запустим из командной строки mc (рис. [-@fig:001]).

![1](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab09/report/image/5454099156269394517.jpg){#fig:001 width=70%}

Выполните несколько операций в mc, используя управляющие клавиши (рис. [-@fig:002], [-@fig:003]).

![2](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab09/report/image/5454099156269394518.jpg){#fig:002 width=70%}

![3](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab09/report/image/5454099156269394519.jpg){#fig:003 width=70%}

Выполните основные команды меню левой панели (рис. [-@fig:004], [-@fig:005], [-@fig:006]).

![4](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab09/report/image/5454099156269394520.jpg){#fig:004 width=70%}

![5](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab09/report/image/5454099156269394521.jpg){#fig:005 width=70%}

![6](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab09/report/image/5454099156269394522.jpg){#fig:006 width=70%}

Используя возможности подменю Файл , выполним: (рис. [-@fig:007], [-@fig:008], [-@fig:009], [-@fig:010]).

![7](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab09/report/image/5454099156269394523.jpg){#fig:007 width=70%}

![8](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab09/report/image/5454099156269394524.jpg){#fig:008 width=70%}

![9](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab09/report/image/5454099156269394525.jpg){#fig:009 width=70%}

![10](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab09/report/image/5454099156269394526.jpg){#fig:010 width=70%}

С помощью соответствующих средств подменю Команда осуществите: (рис. [-@fig:011], [-@fig:012], [-@fig:013], [-@fig:014]).

![11](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab09/report/image/5454099156269394527.jpg){#fig:011 width=70%}

![12](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab09/report/image/5454099156269394528.jpg){#fig:012 width=70%}

![13](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab09/report/image/5454099156269394529.jpg){#fig:013 width=70%}

![14](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab09/report/image/5454099156269394530.jpg){#fig:014 width=70%}

Создадим текстовой файл text.txt. Откроем этот файл с помощью встроенного в mc редактора, и вставим в открытый файл небольшой фрагмент текста, скопированный из любого другого файла или Интернета. Проделаем с текстом следующие манипуляции, используя горячие клавиши: Удалим строку текста. - F8 Выделим фрагмент текста и скопируйте его на новую строку. - F5 Сохраним файл. - F2 Отменим последнее действие. - Ctrl+U Перейдем в конец файла - PageDown или Ctrl+X Перейдем в начало файла - PageUp или Ctrl+Z Откроем файл с исходным текстом на языке программирования C (рис. [-@fig:015], [-@fig:016]).

![15](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab09/report/image/5454099156269394531.jpg){#fig:015 width=70%}

![16](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab09/report/image/5454099156269394533.jpg){#fig:016 width=70%}

# Выводы

В данной работе мы ознакомились с инструментами командной оболочки Midnight Commander. Приобрели навыки практической работы по просмотру каталогов и файлов.

# Список литературы{.unnumbered}

https://esystem.rudn.ru/
