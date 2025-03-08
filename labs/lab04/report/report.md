---
## Front matter
title: "Отчет по лабораторной работе №4"
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

Получение навыков правильной работы с репозиториями git.

# Задание


Выполнить работу для тестового репозитория.
Преобразовать рабочий репозиторий в репозиторий с git-flow и conventional commits.


# Теоретическое введение



# Выполнение лабораторной работы

Устанавливаю gitflow (рис. [-@fig:001]).

![in gitflow](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab04/report/image/2025-03-04T21:45:59,638846277+03:00.png){#fig:001 width=70%}

Устанавливаю node js (рис. [-@fig:002]).

![in node.js](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab04/report/image/2025-03-04T21:48:19,077315268+03:00.png){#fig:002 width=70%}

Настраиваю node.js (рис. [-@fig:003]).

![settings node.js](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab04/report/image/2025-03-04T21:54:11,513093497+03:00.png){#fig:003 width=70%}

Создаю репозиторий git-extended (рис. [-@fig:004]).

![git-extended](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab04/report/image/2025-03-04T22:02:34,594017709+03:00.png){#fig:004 width=70%}

Клонирую репозиторий (рис. [-@fig:005]).

![Клонирую репозиторий](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab04/report/image/2025-03-04T22:06:16,684817651+03:00.png){#fig:005 width=70%}

Делаю первый коммит и выкладываю его на гитхаб (рис. [-@fig:006]).

![Делаю первый коммит и выкладываю его на гитхаб](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab04/report/image/2025-03-04T22:45:12,447095987+03:00.png){#fig:006 width=70%}

Настраиваю конфигурацию общепринятых коммитов (рис. [-@fig:007]).

![Настраиваю конфигурацию общепринятых коммитов](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab04/report/image/2025-03-04T23:01:14,932075908+03:00.png){#fig:007 width=70%}

Добавляю файлы, выполняю коммит и отправляю на git (рис. [-@fig:008]).

![Добавляю файлы, выполняю коммит и отправляю на git](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab04/report/image/2025-03-04T23:12:20,992123217+03:00.png){#fig:008 width=70%}

Выполняю инициализацию git-flow (рис. [-@fig:009]).

![init git-flow](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab04/report/image/2025-03-04T23:14:51,075590827+03:00.png){#fig:009 width=70%}

Проверяю ветку и загружаю весь репозиторий в хранилище (рис. [-@fig:010]).

![Проверяю ветку и загружаю весь репозиторий в хранилище](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab04/report/image/2025-03-04T23:15:44,191942637+03:00.png){#fig:010 width=70%}

Устанавливаю внешнюю ветку, как вышестоящую и создаю релиз с версией 1.0.0 (рис. [-@fig:011]).

![Устанавливаю внешнюю ветку, как вышестоящую и создаю релиз с версией 1.0.0](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab04/report/image/2025-03-04T23:16:28,582187516+03:00.png){#fig:011 width=70%}

Добавляю журнал изменений в индекс и заливаю релизную ветку в основную (рис. [-@fig:012]).

![Добавляю журнал изменений в индекс и заливаю релизную ветку в основную](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab04/report/image/2025-03-04T23:21:48,577599672+03:00.png){#fig:012 width=70%}

Отправляю данные на git и создаю там релиз (рис. [-@fig:013]).

![Отправляю данные на git и создаю там релиз](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab04/report/image/2025-03-04T23:26:28,182486545+03:00.png){#fig:013 width=70%}

Настраиваю конфигурацию общепринятых коммитов (рис. [-@fig:014]).

![Настраиваю конфигурацию общепринятых коммитов](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab04/report/image/2025-03-04T23:28:02,059096823+03:00.png){#fig:014 width=70%}

Добавляю файлы, выполняю коммит и отправляю на git (рис. [-@fig:015]).

![Добавляю файлы, выполняю коммит и отправляю на git](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab04/report/image/2025-03-04T23:28:02,059096823+03:00.png){#fig:015 width=70%}

Выполняю инициализацию git-flow (рис. [-@fig:016]).

![init git-flow](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab04/report/image/2025-03-04T23:28:02,059096823+03:00.png){#fig:016 width=70%}

Проверяю ветку и загружаю весь репозиторий в хранилище (рис. [-@fig:017]).

![Проверяю ветку и загружаю весь репозиторий в хранилище](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab04/report/image/2025-03-04T23:29:00,919322884+03:00.png){#fig:017 width=70%}

Устанавливаю внешнюю ветку, как вышестоящую и создаю релиз с версией 1.0.0 (рис. [-@fig:018]).

![Устанавливаю внешнюю ветку, как вышестоящую и создаю релиз с версией 1.0.0](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab04/report/image/2025-03-04T23:29:00,919322884+03:00.png){#fig:018 width=70%}

Добавляю журнал изменений в индекс и заливаю релизную ветку в основную (рис. [-@fig:019]).

![Добавляю журнал изменений в индекс и заливаю релизную ветку в основную](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab04/report/image/2025-03-04T23:29:00,919322884+03:00.png){#fig:019 width=70%}

Отправляю данные на git и создаю там релиз (рис. [-@fig:020]).

![Отправляю данные на git и создаю там релиз](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab04/report/image/2025-03-04T23:29:00,919322884+03:00.png){#fig:020 width=70%}

Создаю релиз с версией 1.2.3 (рис. [-@fig:021]).

![1.2.3](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab04/report/image/2025-03-04T23:29:48,852281431+03:00.png){#fig:021 width=70%}

Обновляю новое версии в package.json (рис. [-@fig:022]).

![Обновляю новое версии в package.json](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab04/report/image/2025-03-04T23:29:48,852281431+03:00.png){#fig:022 width=70%}

Создаю журнал изменений и добавляю журнал изменений в индекс (рис. [-@fig:023]).

![Создаю журнал изменений и добавляю журнал изменений в индекс](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab04/report/image/2025-03-04T23:31:05,935749174+03:00.png){#fig:023 width=70%}

Заливаю релизную ветку в основную ветку (рис. [-@fig:024]).

![Заливаю релизную ветку в основную ветку](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab04/report/image/2025-03-04T23:33:23,412049248+03:00.png){#fig:024 width=70%}

Отправляю релиз на гитхаб и создаю релиз с комментарием из журнала изменений (рис. [-@fig:025]).

![Отправляю релиз на гитхаб и создаю релиз с комментарием из журнала изменений\](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab04/report/image/2025-03-04T23:34:20,569484864+03:00.png){#fig:025 width=70%}



# Выводы

В итоге я выполнил основную цель работы:
Получение навыков правильной работы с репозиториями git.

# Список литературы{.unnumbered}

https://esystem.rudn.ru/
