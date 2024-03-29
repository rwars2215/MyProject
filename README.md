<img alt="Static Badge" src="https://img.shields.io/badge/Download%20Guide-yellow?style=flat-square&label=Python&labelColor=%234169e1&color=%23efcc00">


# Как установить Python на Windows 10

### Введение
Python — самый популярный язык программирования, на котором разрабатывают ИИ, игры и сложные системы. Разбираемся с его установкой. Python — это высокоуровневый язык программирования общего назначения с минималистичным и простым в освоении синтаксисом. Он был создан под влиянием языка ABC, который изначально задумывался как обучающий и над которым ранее работал автор Python Гвидо ван Россум.

К сожалению, не все ОС содержат Python по умолчанию. В таких случаях, чтобы начать программировать на языке, его придётся установить. В этой статье мы расскажем, как это сделать.

<a href="url"><img src="https://248006.selcdn.ru/main/iblock/efc/efc7db960c417258ce2fb3fa18e15cb1/2c9de04a58d02d205400ad9d92e2be4e.png" align-items="center" width="100%" ></a>

## Какую версию Python выбрать
Вообще, для решения простых задач или знакомства с языком хватит и онлайн-интерпретатора. Это сервис, который позволяет писать и запускать код прямо в браузере, ничего не скачивая. Самые популярные онлайн-интерпретаторы — <a href="https://replit.com/languages/python3" target="_blank">Replit</a>, <a href="https://www.programiz.com/python-programming/online-compiler/" target="_blank">Programiz</a>, и <a href="https://www.online-python.com/" target="_blank">Online Python</a>.

Это хороший инструмент, но только для написания простых программ. Там сложно тестировать приложения, полноценно работать с файлами и использовать продвинутые возможности языка.

Для полноценной разработки всё-таки нужно будет установить Python на компьютер. Но, поверьте, оно того стоит: вы сможете легко подключать сторонние библиотеки, использовать утилиты и создавать сложные проекты.

Выбор версии языка — тоже важный этап. Очевидно, что в новых версиях больше интересных фишек и, как правило, меньше багов — поэтому для собственных проектов лучше скачивать самый свежий дистрибутив. На момент написания статьи это Python 3.11.2.

Однако для поддержки старых проектов, которые не могут переехать на Python 3, придётся скачивать Python 2 и разбираться в различиях версий. Поэтому даже в 2023 году в вакансиях среди требований можно найти «уверенное знание Python 2.7».

В состав базовой версии Python входят следующие компоненты:

* IDLE — простая среда разработки Python-программ;
* документация — инструкция по использованию Python;
* стандартная библиотека — набор функций, которые упрощают работу с числами, файлами, API сторонних сервисов и так далее;
* пакетный менеджер PIP — утилита для скачивания и установки библиотек, фреймворков и других пакетов, расширяющих функциональность Python;
* стандартный набор тестов — чтобы проверять надёжность программы;
* Python Launcher — приложение для запуска программ с расширением .py.

Этого набора вполне хватит, чтобы начать изучение языка и писать простые программы.

## Как установить Python на Windows
Перед установкой убедитесь, что ваш компьютер удовлетворяет системным требованиям:

* 64- или 32-разрядный процессор на архитектуре Intel или AMD;
* 2 ГБ оперативной памяти, желательно 4 ГБ;
* 5 ГБ свободного места в памяти компьютера;
* версия операционной системы: Windows 10

Дистрибутивы Python есть для всех популярных операционных систем, они перечислены на официальном сайте python.org. По большому счёту, не так важно, какую конкретно версию Python вы скачаете, — главное, чтобы её номер начинался с цифры 3.

<a href="url"><img src="https://skillbox.ru/upload/setka_images/08374522032023_e3039f248dd555899a396179b51a05be377f9973.png" align-items="center" width="100%" ></a>

## Установка в Windows 10
Скачайте установочный файл, нажав на жёлтую кнопку **Download Python**, и запустите его.

Выберите путь установки и поставьте обе галочки: во втором пункте мы указываем, что нужно добавить Python в переменную окружения PATH — это позволит вызывать его из любой директории. Затем выбираем «Установка для всех пользователей» (**Install for all users**), нажимаем **Install Now** и разрешаем приложению вносить изменения:

<a href="url"><img src="https://skillbox.ru/upload/setka_images/08374622032023_ee673444daa2c4c150863fb4fe2e59385df85324.png" align-items="center" width="100%" ></a>

Когда всё установится, вы увидите окно завершения инсталляции:

<a href="url"><img src="https://skillbox.ru/upload/setka_images/08395922032023_a3e9b924b0c79cb7169afa563a255fa0a5b1cadd.png" align-items="center" width="100%" ></a>

Теперь проверим, что Python действительно установлен. Для этого откроем окно «Выполнить» сочетанием клавиш **Win + R** и введём cmd:

<a href="url"><img src="https://skillbox.ru/upload/setka_images/08395922032023_cae856732bd4226855875d839121e46dd85999a9.png" align-items="center" width="100%" ></a>

Откроется командная строка. Введите в ней команду py или python, чтобы запустить интерпретатор. На экране появится примерно такое сообщение:

```
Microsoft Windows [Version 10.0.19043.1889]
(c) Корпорация Майкрософт (Microsoft Corporation). Все права защищены.

C:\Users\User>py
Python 3.11.2 (tags/v3.11.2:9c7b4bd, Feb 2 2023, 18:38:48) [MSC v.1932 64 bit (AMD64)] on win 32
Type "help", "copyright", "credits" or "license" for more information.
>>>
```


Оно означает, что Python установлен на ваш компьютер и работает.

<img alt="Static Badge" src="https://img.shields.io/badge/%D0%A3%D0%B4%D0%B0%D1%87%D0%B8%20%D0%B2%20%D0%BE%D1%81%D0%B2%D0%BE%D0%B5%D0%BD%D0%B8%D0%B8%20Python!-black?style=flat-square">

