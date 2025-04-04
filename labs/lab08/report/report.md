---
## Front matter
title: "Отчет по лабораторной работе"
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

Ознакомление с инструментами поиска файлов и фильтрации текстовых данных. Приобретение практических навыков: по управлению процессами, по проверке использования диска и обслуживанию файловых систем.

# Задание

Ознакомление с инструментами поиска файлов и фильтрации текстовых данных. Приобретение практических навыков: по управлению процессами, по проверке использования диска и обслуживанию файловых систем.

# Теоретическое введение



# Выполнение лабораторной работы

Запишем в файл file.txt названия файлов, содержащихся в каталоге /etc. Допишем в этот же файл названия файлов, содержащихся в нашем домашнем каталоге (рис. [-@fig:001]).

![etc/davidalekhin](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab08/report/image/5436353944835189186.jpg){#fig:001 width=70%}

Выведем имена всех файлов из file.txt, имеющих расширение .conf, после чего запишем их в новый текстовой файл conf.txt (рис. [-@fig:002]).

![.conf](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab08/report/image/5436353944835189188.jpg){#fig:002 width=70%}

Определили, какие файлы в нашем домашнем каталоге имеют имена, начинавшиеся с символа c? (рис. [-@fig:003]).

![c](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab08/report/image/5436353944835189187.jpg){#fig:003 width=70%}

Выведем на экран (постранично) имена файлов из каталога /etc, начинающиеся с символа h (рис. [-@fig:004]).

![etc h*](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab08/report/image/5436353944835189192.jpg){#fig:004 width=70%}

Запустили в фоновом режиме процесс, который будет записывать в файл ~/logfile файлы, имена которых начинаются с log. Процесс выполнен. Удалили файл ~/logfile. Но сначала убили процесс в нем (рис. [-@fig:005]).

![log](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab08/report/image/5436353944835189190.jpg){#fig:005 width=70%}

Запустили из консоли в фоновом режиме редактор gedit. Определили идентификатор процесса gedit, используя команду ps, конвейер и фильтр grep. Прочитали справку (man) команды kill, после чего используйте её для завершения процесса gedit (рис. [-@fig:006]).

![gedit](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab08/report/image/5436353944835189189.jpg){#fig:006 width=70%}

Выполним команды df и du, предварительно получив более подробную информацию об этих командах, с помощью команды man (рис. [-@fig:007], [-@fig:008]).

![df](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab08/report/image/5436353944835189193.jpg){#fig:007 width=70%}

![du](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab08/report/image/5436353944835189191.jpg){#fig:008 width=70%}

Воспользовавшись справкой команды find, вывести имена всех директорий, имеющихся в нашем домашнем каталоге (рис. [-@fig:009]).

![find](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab08/report/image/5436353944835189194.jpg){#fig:009 width=70%}

# Выводы

В данной работе мы ознакомились с инструментами поиска файлов и фильтрации текстовых данных. А также приобрели практические навыки по управлению процессами.

# Список литературы{.unnumbered}

https://esystem.rudn.ru/
