metod-oblaka-grid
=================
Методические указания к выполнению лабораторных работ по дисциплине "Основы облачных технологий"

Краткое содержание
------------------
1. Лабораторная работа №1. Знакомство с виртуализацией. Система виртуализации Oracle VM VirtualBox
2. Лабораторная работа №2. Модель обслуживания SaaS (Software-as-a-Service) на примере развертывания облачного хранилища ownCloud
3. Лабораторная работа №3. Модель обслуживания PaaS (Platform-as-a-Service) на примере деплоя приложения в Heroku
4. Лабораторная работа №4. Модель обслуживания IaaS (Infrastructure-as-a-Service) на примере создания инстанса в OpenStack
* A Пример создания виртуальной машины в Oracle VM VirtualBox
* B Пример установки Debian GNU/Linux в VirtualBox
* C Пример установки ownCloud в Debian GNU/Linux
* D Настройка подключения ownCloud Client к серверу
* E Пример деплоя приложения на Heroku
* F Пример создания инстанса в OpenStack

Структура исходников
--------------------
Структура каталогов:
```
.
├── images
└── inc
```

В корневом каталоге `.` находится файл `main.tex`.
В `main.tex` инклудится преамбула, титул, содержание, основное содержимое методических указаний, список литературы и приложения.

В каталоге `images/` находятся рисунки, схемы, скриншоты. Схемы рисовал на этом сайте: https://www.draw.io

В каталоге `inc/` находятся файлы, которые инклудятся к `main.tex`, а именно:
* `preamble.tex` - преамбула
* `title.tex` - титул
* `?-*.tex` - основное содержимое методических указаний
* `*-appendix.tex` - приложения

Работа с LaTeX
--------------
Для работы с LaTeX рекомендую использовать PDFLaTeX и IDE [LaTeXila](https://wiki.gnome.org/Apps/LaTeXila).

Шаблон документа взят [отсюда](https://github.com/Amet13/openvz-tutorial).

Ссылки, которые могут пригодиться для настройки LaTeX:
* Установка LaTeX: http://blog.amet13.name/2014/06/latex.html
* Использование пакета listings для оформления исходного кода: http://blog.amet13.name/2014/10/latex.html
* Установка PSCyr для красивых шрифтов в PDFLaTeX: http://blog.amet13.name/2014/10/pscyr.html

Для пользователей GNU/Linux можно воспользоваться Makefile.
Пример компиляции проекта:
```bash
cd metod-oblaka-grid/
make
```
Пример очистки ненужных файлов после компиляции:
```bash
make clean
```

Лицензия
--------
[Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](http://creativecommons.org/licenses/by-sa/4.0/deed.ru)

![CC BY SA](https://licensebuttons.net/l/by-sa/4.0/88x31.png)
