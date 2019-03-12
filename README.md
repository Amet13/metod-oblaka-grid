metod-oblaka
============
Методические указания к выполнению лабораторных работ по дисциплине "Основы облачных технологий"

Для магистров направления "09.04.01 Информатика и вычислительная техника" Севастопольского государственного университета

Краткое содержание
------------------
1. Лабораторная работа №1. Знакомство с виртуализацией. Система виртуализации Oracle VM VirtualBox
2. Лабораторная работа №2. Модель обслуживания SaaS на примере развертывания облачного хранилища ownCloud
3. Лабораторная работа №3. Модель обслуживания PaaS на примере деплоя приложения в Heroku
4. Лабораторная работа №4. Модель обслуживания IaaS на примере создания инстанса в OpenStack
* A Создание виртуальной машины в VirtualBox
* B Установка Debian GNU/Linux в VirtualBox
* C Установка ownCloud Server в Debian GNU/Linux
* D Подключение ownCloud Client к серверу
* E Деплой приложения на Heroku
* F Создание инстанса в OpenStack (только для ознакомления)

Структура исходников
--------------------

В `main.tex` подключается преамбула, титульная страница, содержание, текст лабораторных работ и приложения.

В каталоге `images/` находятся рисунки, схемы, скриншоты.

В каталоге `inc/` находятся файлы, которые подключаются к `main.tex`, а именно:
* `preamble.tex` — преамбула
* `title.tex` — титульная страница
* `[1-4]-*.tex` — лабораторные работы
* `[a-f]-appendix.tex` — приложения к лабораторным работам

Работа с LaTeX
--------------
Ссылки, которые могут пригодиться для настройки LaTeX:
* Установка LaTeX: http://blog.amet13.name/2014/06/latex.html
* Использование пакета listings для оформления исходного кода: http://blog.amet13.name/2014/10/latex.html
* Установка PSCyr для красивых шрифтов в PDFLaTeX: http://blog.amet13.name/2014/10/pscyr.html

Пример сборки документа при помощи Makefile:
```bash
git clone https://github.com/Amet13/metod-oblaka
cd metod-oblaka/
make
```

Или с помощью Docker:
```bash
make docker
```

Пример очистки сборочных файлов (кроме PDF):
```bash
make clean
```

Лицензия
--------
[Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](http://creativecommons.org/licenses/by-sa/4.0/deed.ru)

![CC BY SA](https://licensebuttons.net/l/by-sa/4.0/88x31.png)
