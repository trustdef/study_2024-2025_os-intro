---
## Front matter
title: "Отчет по лабораторной работе №2"
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

Изучить идеологию и применение средств контроля версий.
Освоить умения по работе с git.

# Задание

Создать базовую конфигурацию для работы с git.
Создать ключ SSH.
Cоздать ключ PGP.
Настроить подписи git.
Зарегистрироваться на Github.
Создать локальный каталог для выполнения заданий по предмету.

# Теоретическое введение



# Выполнение лабораторной работы

Устанавливаю git (рис. [-@fig:001]).

![in git](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab02/report/image/2025-02-26T10:45:58,102889965+03:00.png){#fig:001 width=70%}

Устанавливаю gh (рис. [-@fig:002]).

![in gh](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab02/report/image/2025-02-26T10:45:58,102889965+03:00.png){#fig:002 width=70%}

Провожу базовую настройку гит
(рис. [-@fig:003]).

![Настройка гит](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab02/report/image/2025-02-26T10:59:26,521033892+03:00.png){#fig:003 width=70%}

Создаю ssh и pgp ключи (рис. [-@fig:004]).

![ssh, gpg](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab02/report/image/2025-02-28T18:48:11,135136276+03:00.png){#fig:004 width=70%}

С первого семестра у меня уже есть учётная запись git , буду работать через неё.

Копирую и добавляю pgp ключ на gh (рис. [-@fig:005]).

![Копирую и добавляю pgp ключ на gh](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab02/report/image/2025-02-28T18:51:57,191398719+03:00.png){#fig:005 width=70%}

Настраиваю автоматические подписи коммитов git, а также авторизируюсь в gh (рис. [-@fig:006]).

![Автоматические подписки коммитов, авторизация ](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab02/report/image/2025-02-28T19:18:22,706051135+03:00.png){#fig:006 width=70%}

Создаю репозиторий курса (рис. [-@fig:007]).

![Репозиторий курса](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab02/report/image/2025-02-28T19:30:32,930697300+03:00.png){#fig:007 width=70%}

Настройка каталога

Удаляю лишние каталоги (рис. [-@fig:008]).

![Удаляю лишние каталоги](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab02/report/image/2025-02-28T19:32:53,123112137+03:00.png){#fig:008 width=70%}

Создаю необходимые каталоги (рис. [-@fig:009]).

![Создаю необходимые каталоги](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab02/report/image/2025-02-28T19:33:15,235050838+03:00.png){#fig:009 width=70%}

Отправляю файлы на сервер(рис. [-@fig:010]).

![Отправляю файлы на сервер](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab02/report/image/2025-02-28T19:43:14,958471529+03:00.png){#fig:010 width=70%}


# Выводы

В итоге я выполнил основную цель работы:
Изучить идеологию и применение средств контроля версий.
Освоить умения по работе с git.

# Список литературы{.unnumbered}

https://esystem.rudn.ru/
