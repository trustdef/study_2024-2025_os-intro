---
## Front matter
title: "Отчет по лабораторной работе 7"
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

Ознакомление с файловой системой Linux, её структурой, именами и содержанием
каталогов. Приобретение практических навыков по применению команд для работы
с файлами и каталогами, по управлению процессами (и работами), по проверке исполь-
зования диска и обслуживанию файловой системы.

# Задание

1. Выполните все примеры, приведённые в первой части описания лабораторной работы.
2. Выполните следующие действия, зафиксировав в отчёте по лабораторной работе
используемые при этом команды и результаты их выполнения:
2.1. Скопируйте файл /usr/include/sys/io.h в домашний каталог и назовите его
equipment. Если файла io.h нет, то используйте любой другой файл в каталоге
/usr/include/sys/ вместо него.
2.2. В домашнем каталоге создайте директорию ~/ski.plases.
2.3. Переместите файл equipment в каталог ~/ski.plases.
2.4. Переименуйте файл ~/ski.plases/equipment в ~/ski.plases/equiplist.
2.5. Создайте в домашнем каталоге файл abc1 и скопируйте его в каталог
~/ski.plases, назовите его equiplist2.
2.6. Создайте каталог с именем equipment в каталоге ~/ski.plases.
2.7. Переместите файлы ~/ski.plases/equiplist и equiplist2 в каталог
~/ski.plases/equipment.
2.8. Создайте и переместите каталог ~/newdir в каталог ~/ski.plases и назовите
его plans.
Кулябов Д. С. и др. Операционные системы 53
3. Определите опции команды chmod, необходимые для того, чтобы присвоить перечис-
ленным ниже файлам выделенные права доступа, считая, что в начале таких прав
нет:
3.1. drwxr--r-- ... australia
3.2. drwx--x--x ... play
3.3. -r-xr--r-- ... my_os
3.4. -rw-rw-r-- ... feathers
При необходимости создайте нужные файлы.
4. Проделайте приведённые ниже упражнения, записывая в отчёт по лабораторной
работе используемые при этом команды:
4.1. Просмотрите содержимое файла /etc/password.
4.2. Скопируйте файл ~/feathers в файл ~/file.old.
4.3. Переместите файл ~/file.old в каталог ~/play.
4.4. Скопируйте каталог ~/play в каталог ~/fun.
4.5. Переместите каталог ~/fun в каталог ~/play и назовите его games.
4.6. Лишите владельца файла ~/feathers права на чтение.
4.7. Что произойдёт, если вы попытаетесь просмотреть файл ~/feathers командой
cat?
4.8. Что произойдёт, если вы попытаетесь скопировать файл ~/feathers?
4.9. Дайте владельцу файла ~/feathers право на чтение.
4.10. Лишите владельца каталога ~/play права на выполнение.
4.11. Перейдите в каталог ~/play. Что произошло?
4.12. Дайте владельцу каталога ~/play право на выполнение.
5. Прочитайте man по командам mount, fsck, mkfs, kill и кратко их охарактеризуйте,
приведя примеры.

# Теоретическое введение



# Выполнение лабораторной работы

Выполняю примеры 1 2 3 4 (рис. [-@fig:001], [-@fig:002], [-@fig:003], [-@fig:004]).

![примеры](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab07/report/image/5417917741882536825.jpg){#fig:001 width=70%}

![примеры](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab07/report/image/5417917741882536819.jpg){#fig:002 width=70%}

![примеры](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab07/report/image/5417917741882536820.jpg){#fig:003 width=70%}

![примеры](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab07/report/image/5417917741882536824.jpg){#fig:004 width=70%}

Выполняю 2.1 2.2 2.3 2.4 (рис. [-@fig:005]).

![2.1-2.4](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab07/report/image/5417917741882536822.jpg){#fig:005 width=70%}

Bыполняю 2.5 (рис. [-@fig:006]).

![2.5](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab07/report/image/5417917741882536823.jpg){#fig:006 width=70%}

выполняю 2.6 2.7 2.8 (рис. [-@fig:007]).

![2.6-2.8](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab07/report/image/5417917741882536821.jpg){#fig:007 width=70%}

3 чтобы задать приведённые права доступа нужны следующие опции:
3.1 111.110.010
3.2 111.100.100
3.3 010.110.010
3.4 011.011.010

Bыполняю приведённые ниже упражнения пункта 4 (рис. [-@fig:008], [-@fig:009], [-@fig:010], [-@fig:011]).

![4](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab07/report/image/5417917741882536826.jpg){#fig:008 width=70%}

![4](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab07/report/image/5417917741882536829.jpg){#fig:009 width=70%}

![4](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab07/report/image/5417917741882536828.jpg){#fig:010 width=70%}

![4](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab07/report/image/5417917741882536827.jpg){#fig:011 width=70%}

Выполняю пункт 5:

Команда mount используется для монтирования файловой системы. Она принимает два параметра: файл устройства, соответствующий диску или разделу, на котором расположена файловая система, и имя каталога, к которому будет монтироваться система. Например, чтобы смонтировать дискету MS-DOS, нужно выполнить команду:

mount -t msdos /dev/fd0 /floppy

Команда fsck служит для проверки целостности и работоспособности файловой системы. Большинство систем сконфигурировано так, что команда fsck запускается автоматически при загрузке системы. Например, чтобы проверить диск /dev/sda6, нужно выполнить команду:

sudo fsck -a /dev/sda6

Команда mkfs позволяет создать файловую систему Linux. Например, чтобы отформатировать раздел с файловой системой ext4, можно выполнить команды:

mkfs.ext4 /dev/sdb3

Команда kill используется для завершения процессов. Например, чтобы корректно завершить процесс с PID 98989, нужно выполнить команду:

kill -TERM 98989

# Выводы

Я выполнил основную цель работы:
Ознакомление с файловой системой Linux, её структурой, именами и содержанием
каталогов. Приобретение практических навыков по применению команд для работы
с файлами и каталогами, по управлению процессами (и работами), по проверке исполь-
зования диска и обслуживанию файловой системы.


# Список литературы{.unnumbered}

https://esystem.rudn.ru/
