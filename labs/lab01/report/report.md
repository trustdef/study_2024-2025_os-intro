---
## Front matter
title: "Отчет по лабораторной работе №1"
subtitle: "Дисциплина: Операционные системы"
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

Целью данной работы является приобретение практических навыков установки операционной системы на виртуальную машину, настройки минимально необходимых для дальнейшей работы сервисов.

# Задание

Установка Linux на Virtualbox.
Настройки после установки.
Установка программного обеспечения для создания документации.
Выполнение заданий для самостоятельной работы.

# Теоретическое введение

 

# Выполнение лабораторной работы

Установка Linux на Virtualbox.
Virtualbox был установлен в прошлом семестре, поэтому перейдем к созданию виртуальной машины.  (рис. [-@fig:001]).

![создание виртуальной машины](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab01/report/image/5346002465880927059.jpg){#fig:001 width=70%}

Настройки после установки
После установки виртуальной машины, вхожу в OC под заданной при установке учетной записью и устанавливаю драйвера для Virtualbox. (рис. [-@fig:002]).

![drivers for VirtualBox](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab01/report/image/5346002465880927065.jpg){#fig:002 width=70%}

Отключаю selinux. (рис. [-@fig:003]).

![Selinux](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab01/report/image/5346002465880927064.jpg){#fig:003 width=70%}

Далее настраиваю раскладку клавиатуры. (рис. [-@fig:004]).

![настройка раскладки клавиатуры](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab01/report/image/5346002465880927066.jpg){#fig:004 width=70%}

Установка программного обеспечения для создания документации
Запустив терминальный мультиплексор tmux и переключившись на роль супер-пользователя, устанавливаю с помощью менеджера пакетов pandoc и pandoc-crossref для работы с языком разметки Markdown, а также дистрибутив TeXlive. (рис. [-@fig:005], рис. [-@fig:006], рис. [-@fig:007]).

![Texlive](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab01/report/image/5346002465880927069.jpg){#fig:005 width=70%}

![wget Pandoc, Pandoc-crosseref](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab01/report/image/5346002465880927067.jpg){#fig:006 width=70%}

![tar,cp](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab01/report/image/5346002465880927068.jpg){#fig:007 width=70%}

Выполнение заданий для самостоятельной работы
Выполняя команду dmesg | grep -i “то,что ищем”, получаю информацию о версии ядра Linux, частоте и модели процессора, объеме доступной оперативной памяти, типе обнаруженного гипервизора и файловой системы корневого раздела и последовательности монтирования файловых систем. (рис. [-@fig:008]рис., [-@fig:009]рис., [-@fig:010]рис., [-@fig:011]рис., [-@fig:012]рис., [-@fig:013]).,

![1](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab01/report/image/5346002465880927071.jpg){#fig:008 width=70%}

![2](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab01/report/image/5346002465880927073.jpg){#fig:009 width=70%}

![3](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab01/report/image/5346002465880927074.jpg){#fig:010 width=70%}

![4](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab01/report/image/5346002465880927075.jpg){#fig:011 width=70%}

![5](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab01/report/image/5346002465880927076.jpg){#fig:012 width=70%}

![6](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab01/report/image/5346002465880927077.jpg){#fig:013 width=70%}



# Выводы

Вывод
Я приобрел практические навыки установки операционной системы на виртуальную машину и настройки минимально необходимых для дальнейшей работы сервисов.

# Список литературы{.unnumbered}

https://esystem.rudn.ru/
