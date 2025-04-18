---
## Front matter
lang: ru-RU
title: Научная презентация 
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

# Вводная часть

## Актуальность

- Важно уметь уметь пользоваться виртуальными машинами 
- Полезно уметь устанавливать и настраивать операционные системы 

## Объект и предмет исследования

- Виртуальная машина VirtualBox 
- Операционная система LinuxSwaySpin 

## Цели и задачи

- Целью данной работы является приобретение практических навыков установки операционной системы на виртуальную машину, настройки минимально необходимых для дальнейшей работы сервисов.

## Материалы и методы

- Файл установщик VB
- ISO файл FedoraSwaySpin41

# Создание презентации

## Процессор `pandoc`

- Pandoc: преобразователь текстовых файлов
- Сайт: <https://pandoc.org/>
- Репозиторий: <https://github.com/jgm/pandoc>

## Формат `pdf`

- Использование LaTeX
- Пакет для презентации: [beamer](https://ctan.org/pkg/beamer)
- Тема оформления: `metropolis`

## Код для формата `pdf`

```yaml
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
```

## Формат `html`

- Используется фреймворк [reveal.js](https://revealjs.com/)
- Используется [тема](https://revealjs.com/themes/) `beige`

## Код для формата `html`

- Тема задаётся в файле `Makefile`

```make
REVEALJS_THEME = beige 
```
# Результаты

## Получающиеся форматы

- Полученный `pdf`-файл можно демонстрировать в любой программе просмотра `pdf`
- Полученный `html`-файл содержит в себе все ресурсы: изображения, css, скрипты

# Элементы презентации

## Актуальность

- Важно уметь уметь пользоваться виртуальными машинами 
- Полезно уметь устанавливать и настраивать операционные системы 

## Цели и задачи

- Целью данной работы является приобретение практических навыков установки операционной системы на виртуальную машину, настройки минимально необходимых для дальнейшей работы сервисов.

## Материалы и методы

- Файл установщик VB
- ISO файл FedoraSwaySpin41

## Содержание исследования

Установка Linux на Virtualbox.
Virtualbox был установлен в прошлом семестре, поэтому перейдем к созданию виртуальной машины.  (рис. [-@fig:001]).

![создание виртуальной машины](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab01/presentation/image/5346002465880927059.jpg){#fig:001 width=70%}

## Содержание исследования

Настройки после установки
После установки виртуальной машины, вхожу в OC под заданной при установке учетной записью и устанавливаю драйвера для Virtualbox. (рис. [-@fig:002]).

![drivers for VirtualBox](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab01/presentation/image/5346002465880927065.jpg){#fig:002 width=70%}

## Содержание исследования

Отключаю selinux. (рис. [-@fig:003]).

![Selinux](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab01/presentation/image/5346002465880927064.jpg){#fig:003 width=70%}

## Содержание исследования

Далее настраиваю раскладку клавиатуры. (рис. [-@fig:004]).

![настройка раскладки клавиатуры](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab01/presentation/image/5346002465880927066.jpg){#fig:004 width=70%}

## Содержание исследования

Установка программного обеспечения для создания документации
Запустив терминальный мультиплексор tmux и переключившись на роль супер-пользователя, устанавливаю с помощью менеджера пакетов pandoc и pandoc-crossref для работы с языком разметки Markdown, а также дистрибутив TeXlive. (рис. [-@fig:005], рис. [-@fig:006], рис. [-@fig:007]).

![Texlive](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab01/presentation/image/5346002465880927069.jpg){#fig:005 width=70%}

## Содержание исследования

![wget Pandoc, Pandoc-crosseref](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab01/presentation/image/5346002465880927067.jpg){#fig:006 width=70%}

![tar,cp](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab01/presentation/image/5346002465880927068.jpg){#fig:007 width=70%}

## Содержание исследования

Выполнение заданий для самостоятельной работы
Выполняя команду dmesg | grep -i “то,что ищем”, получаю информацию о версии ядра Linux, частоте и модели процессора, объеме доступной оперативной памяти, типе обнаруженного гипервизора и файловой системы корневого раздела и последовательности монтирования файловых систем. (рис. [-@fig:008]рис., [-@fig:009]рис., [-@fig:010]рис., [-@fig:011]рис., [-@fig:012]рис., [-@fig:013]).,

![1](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab01/presentation/image/5346002465880927071.jpg){#fig:008 width=70%}

## Содержание исследования

![2](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab01/presentation/image/5346002465880927073.jpg){#fig:009 width=70%}

## Содержание исследования

![3](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab01/presentation/image/5346002465880927074.jpg){#fig:010 width=70%}

## Содержание исследования

![4](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab01/presentation/image/5346002465880927075.jpg){#fig:011 width=70%}

## Содержание исследования

![5](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab01/presentation/image/5346002465880927076.jpg){#fig:012 width=70%}

## Содержание исследования

![6](/home/davidalekhin/work/study/2025-2026/Операционные системы/os-intro/labs/lab01/presentation/image/5346002465880927077.jpg){#fig:013 width=70%}


## Результаты

В итоге я выполнил основную цель работы:
Целью данной работы является приобретение практических навыков установки операционной системы на виртуальную машину, настройки минимально необходимых для дальнейшей работы сервисов.
## Итоговый слайд

В теории, теория и практика неразделимы. На практике это не так.
Yoggi Berra

:::

