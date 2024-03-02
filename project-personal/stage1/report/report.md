---
## Front matter
title: "Отчёт 1 этап индивидуального проекта"
subtitle: "Установка Kali Linux"
author: "Кудряшов Артём Николаевич"

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
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
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

Установить Kali Linux

# Задание

- Скачать файл с официального сайта
- Запустить его на VirualBox
- Создать отчёт и презентацию

# Выполнение лабораторной работы

Зайдём на официальный сайт Kali и скачаем нужный файл (рис. [-@fig:001]).

![Сайт Kali](image/1.jpg){#fig:001 width=70%}

Распакуем и запустим скачанный файл, сразу открывается приложение VirtualBox (рис. [-@fig:002]).

![Окно VirtualBox](image/2.jpg){#fig:002 width=70%}

Войдём в систему с помощью учётной записи (рис. [-@fig:003]):
  - Логин: kali
  - Пароль: kali

![Вход в систему](image/3.jpg){#fig:003 width=70%}

Как мы видим, установка прошла успешно. (рис. [-@fig:004]).

![Рабочий стол Kali](image/4.jpg){#fig:004 width=70%}

# Выводы

На данном этапе выполнения индивидуального проекта мы установили Kali Linux.
