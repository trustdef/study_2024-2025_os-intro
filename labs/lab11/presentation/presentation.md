---
## Front matter
lang: ru-RU
title: Научная презентация 11
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

- Важно уметь работать с emacs.

## Цели и задачи

- Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором Emacs.

## Материалы и методы

- fedora-linux
- emacs

## Содержание исследования

Откроем Emacs (рис. [-@fig:001]).

![1](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab11/report/image/5206651981379270416.jpg){#fig:001 width=70%}

## Содержание исследования

Создадим файл lab07.sh с помощью комбинации Ctrl-x Ctrl-f и наберем текст из задания в ново созданный файл. (рис. [-@fig:002]).

![2](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab11/report/image/5206651981379270417.jpg){#fig:002 width=70%}

## Содержание исследования

Сохраним файл с помощью комбинации Ctrl-x s. Проделаем с текстом стандартные процедуры редактирования, каждое действие осуществляется комбинациями клавиш. Вырежем командой Ctrl-w. целую строку. Вставим эту строку в конец файла командой Ctrl-y. (рис. [-@fig:003]).

![3](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab11/report/image/5206651981379270418.jpg){#fig:003 width=70%}

## Содержание исследования

Выделим область текста командой Ctrl-space. (рис. [-@fig:004]).

![4](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab11/report/image/5206651981379270419.jpg){#fig:004 width=70%}

## Содержание исследования

Скопируем область в буфер обмена командой alt-w. Вставим область в конец файла. (рис. [-@fig:005]).

![5](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab11/report/image/5206651981379270420.jpg){#fig:005 width=70%}

## Содержание исследования

Вновь выделим эту область и на этот раз вырежем её командой Ctrl-w. (рис. [-@fig:006]).

![6](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab11/report/image/5206651981379270421.jpg){#fig:006 width=70%}

## Содержание исследования

Отменим последнее действие командой Ctrl-x u.
Научимся использовать команды по перемещению курсора.

    Переместим курсор в начало строки командой Ctrl-a.

    Переместим курсор в курсор строки командой Ctrl-e.

    Переместим курсор в начало буфера Alt-<.

    Переместим курсор в конец буфера Alt->.
    
## Содержание исследования   

Управление буферами. Введем Ctrl-x 2. (рис. [-@fig:007]).

![7](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab11/report/image/5206651981379270422.jpg){#fig:007 width=70%}

## Содержание исследования

Переместим вновь открытое окно Ctrl-x со списком открытых буферов и переключимся на другой буфер. (рис. [-@fig:008]).

![8](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab11/report/image/5206651981379270423.jpg){#fig:008 width=70%}

## Содержание исследования

Закроем это окно командой Ctrl-x 0. (рис. [-@fig:009]).

![9](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab11/report/image/5206651981379270424.jpg){#fig:009 width=70%}

## Содержание исследования

Теперь вновь переключимся между буферами, но уже без вывода их списка на экран Ctrl-x b. (рис. [-@fig:010]).

![10](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab11/report/image/5206651981379270425.jpg){#fig:010 width=70%}

## Содержание исследования

Поделим фрейм на 4 части: разделитм фрейм на два окна по вертикали Ctrl-x 3, а затем каждое из этих окон на две части по горизонтали Ctrl-x 2. В каждом из четырёх созданных окон откроем новый буфер (файл). (рис. [-@fig:011]).

![11](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab11/report/image/5206651981379270426.jpg){#fig:011 width=70%}

## Содержание исследования

Переключимся в режим поиска Ctrl-s и найдем несколько слов, присутствующих в тексте. Выйдем из режима поиска, нажав Ctrl-g. Перейдем в режим поиска и замены Alt-Shift %, введем текст, который следует найти и заменить, для замены нажмем Enter. После этого нажмем ! для подтверждения замены. Если мы хотим заменить конкретные слова то мы их выделяем и нажимаем Enter. Если все то ! Испробуем другой режим поиска, нажав Alt-s .
От обычного режима отличается тем, что находит не фрагмент текста, а файл.

## Результаты

В данной работе мы познакомились с еще одним редактором операционной системой Linux. Получили практические навыки работы с редактором Emacs.


## Итоговый слайд

В теории, теория и практика неразделимы. На практике это не так.
Yoggi Berra

:::

