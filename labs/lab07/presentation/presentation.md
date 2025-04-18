---
## Front matter
lang: ru-RU
title: Научная презентация 7
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

## Актуальность

- Важно уметь работать с файловой системой.

## Цели и задачи

- Приобретение практических навыков взаимодействия пользователя с системой по-
средством командной строки.

## Материалы и методы

- fedora-linux

## Содержание исследования

Выполняю примеры 1 2 3 4 (рис. [-@fig:001], [-@fig:002], [-@fig:003], [-@fig:004]).

![примеры](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab07/report/image/5417917741882536825.jpg){#fig:001 width=70%}

## Содержание исследования

![примеры](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab07/report/image/5417917741882536819.jpg){#fig:002 width=70%}

## Содержание исследования

![примеры](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab07/report/image/5417917741882536820.jpg){#fig:003 width=70%}

## Содержание исследования

![примеры](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab07/report/image/5417917741882536824.jpg){#fig:004 width=70%}

## Содержание исследования

Выполняю 2.1 2.2 2.3 2.4 (рис. [-@fig:005]).

![2.1-2.4](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab07/report/image/5417917741882536822.jpg){#fig:005 width=70%}

## Содержание исследования

Bыполняю 2.5 (рис. [-@fig:006]).

![2.5](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab07/report/image/5417917741882536823.jpg){#fig:006 width=70%}

## Содержание исследования

выполняю 2.6 2.7 2.8 (рис. [-@fig:007]).

![2.6-2.8](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab07/report/image/5417917741882536821.jpg){#fig:007 width=70%}

## Содержание исследования

3 чтобы задать приведённые права доступа нужны следующие опции:
3.1 111.110.010
3.2 111.100.100
3.3 010.110.010
3.4 011.011.010

Bыполняю приведённые ниже упражнения пункта 4 (рис. [-@fig:008], [-@fig:009], [-@fig:010], [-@fig:011]).

![4](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab07/report/image/5417917741882536826.jpg){#fig:008 width=70%}

## Содержание исследования

![4](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab07/report/image/5417917741882536829.jpg){#fig:009 width=70%}

## Содержание исследования

![4](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab07/report/image/5417917741882536828.jpg){#fig:010 width=70%}

## Содержание исследования

![4](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab07/report/image/5417917741882536827.jpg){#fig:011 width=70%}

## Содержание исследования

Выполняю пункт 5:

Команда mount используется для монтирования файловой системы. Она принимает два параметра: файл устройства, соответствующий диску или разделу, на котором расположена файловая система, и имя каталога, к которому будет монтироваться система. Например, чтобы смонтировать дискету MS-DOS, нужно выполнить команду:

mount -t msdos /dev/fd0 /floppy

Команда fsck служит для проверки целостности и работоспособности файловой системы. Большинство систем сконфигурировано так, что команда fsck запускается автоматически при загрузке системы. Например, чтобы проверить диск /dev/sda6, нужно выполнить команду:

sudo fsck -a /dev/sda6

## Содержание исследования

Команда mkfs позволяет создать файловую систему Linux. Например, чтобы отформатировать раздел с файловой системой ext4, можно выполнить команды:

mkfs.ext4 /dev/sdb3

Команда kill используется для завершения процессов. Например, чтобы корректно завершить процесс с PID 98989, нужно выполнить команду:

kill -TERM 98989

## Результаты

Я выполнил основную цель работы:
Ознакомление с файловой системой Linux, её структурой, именами и содержанием
каталогов. Приобретение практических навыков по применению команд для работы
с файлами и каталогами, по управлению процессами (и работами), по проверке исполь-
зования диска и обслуживанию файловой системы.

## Итоговый слайд

В теории, теория и практика неразделимы. На практике это не так.
Yoggi Berra

:::

