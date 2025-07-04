---
## Front matter
lang: ru-RU
title: Научная презентация 12
subtitle: Дисциплина:Операционные системы
author:
  - Алехин Давид Андреевич
institute:
  - Российский университет дружбы народов, Москва, Россия
  - Математический институт имени Никольского, Москва, Россия
date: 06.03.25

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Алехин Давид Андреевич 
  * Студент 
  * Студент НММбд-01-24
  * Российский университет дружбы народов
  * [1132246830@pfur.ru](mailto:trustdef@gamil.com)
  * <https://github.com/trustdef>

:::
::: {.column width="30%"}

![]()

:::
::::::::::::::



# Элементы презентации

## Цели и задачи

- Изучить основы программирования в оболочке ОС UNIX/Linux. Научиться писать небольшие командные файлы.

## Материалы и методы

- fedora-linux

## Содержание исследования

Написали скрипт, который при запуске делает резервную копию самого себя (то есть файла, в котором содержится его исходный код) в другую директорию backup в моём домашнем каталоге. При этом файл архивируется одним из архиваторов на выбор zip , bzip2 или tar . Способ использования команд архивации узнали, изучив справку. (рис. [-@fig:001], [-@fig:002]).

![1](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab12/report/image/5237820047945233639.jpg){#fig:001 width=70%}

## Содержание исследования

![2](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab12/report/image/5237820047945233641.jpg){#fig:002 width=70%}

## Содержание исследования

Написали пример командного файла, обрабатывающего любое произвольное число аргументов командной строки, в том числе превышающее десять. Например, скрипт может последовательно распечатывать значения всех переданных аргументов (рис. [-@fig:003], [-@fig:004]).

![3](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab12/report/image/5237820047945233637.jpg){#fig:003 width=70%}

## Содержание исследования

![4](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab12/report/image/5237820047945233638.jpg){#fig:004 width=70%}

## Содержание исследования

Написали командный файл — аналог команды ls (без использования самой этой команды и команды dir ). Он выдает информацию о нужном каталоге и выводит информацию о возможностях доступа к файлам этого каталога. (рис. [-@fig:005], [-@fig:006]).

![5](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab12/report/image/5237820047945233640.jpg){#fig:005 width=70%}

## Содержание исследования

![6](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab12/report/image/5237820047945233643.jpg){#fig:006 width=70%}

## Содержание исследования

Написали командный файл, который получает в качестве аргумента командной строки формат файла ( .txt , .doc , .jpg , .pdf и т.д.) и вычисляет количество таких файлов в указанной директории. Путь к директории также передаётся в виде аргумента командной строки. (рис. [-@fig:007], [-@fig:008]).

![7](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab12/report/image/5237820047945233642.jpg){#fig:007 width=70%}

## Содержание исследования

![8](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab12/report/image/5237820047945233644.jpg){#fig:008 width=70%}

## Результаты

В данной работе мы изучили основы программирования в оболочке ОС UNIX/Linux. Научились писать небольшие командные файлы и скрипты на языке bush.


## Итоговый слайд

В теории, теория и практика неразделимы. На практике это не так.
Yoggi Berra

:::

