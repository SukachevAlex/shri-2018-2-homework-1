# Домашнее задание #1

## Запуск

Установить зависимости `npm install`

Запустить проект `npm run start`

Собрать проект `npm run build`

Проверка eslint'ом `npm run lint`

## Ссылка на проект gh-pages

[Ссылка](https://sukachevalex.github.io/shri-2018-2-homework-1/)

## Основные задачи

* Адаптировал верстку для экранов размером от 320px до 1920px.
* Добавил раздел "Авторские права" в подвал сайта с ссылкой на лицензию.
* Реализовал карточки событий 3х видов (занимающие 2, 3 и 4 колонки в grid-сетке).
* Заголовоки могут состоять не более, чем из двух строк, остальное обрезается многоточием.
* Ориентировался и проверил работу в Яндекс.Браузер, Edge, Firefox, Safari (Пока не проверил в Edge & Safari).

## Дополнительные задачи

* Адаптировал изображения.
* Адаптировал типографику.
* Вариативные шрифты (Как я понял, Arial не вариативный, поэтому попробовать не получилось).
* Написал простой шаблонизатор (на базе ,`<template>`-тега).

## Основные моменты

* Добавил `<meta name="robots" content="noindex">`.
* Изменил events.json значение image в последнем событии на Bitmap.png для отображения картинки события.
* Проверил весь написанный код на соответствие styleguide.
* Минимизировал файлы проекта и изображения.
* Проверил разметку проекта на валидность.
* Убрал `fill="#333333"` в некоторых svg (особенности ипорта sketch'a).
* Убрал border у шапки и подвала на разрешении менее 768px (На мобильных версиях border'а нет, решил убирать его начиная с 768px).
* Также с 768px разместил подвал сайта в 1 колонку, а с 560px убираю меню в burger (раскрытие меню при клике на бургер решил не делать).
* Добавил троеточие названию трека в плееере.
* Содержимое карточки при большой высоте прилипает к низу.
* Неоднозначное решение с отображением `x` `>` на тач устройствах на постоянной основе
* Необходимо правильно определять каким устройством пользуется пользователь для отображения информации под фото пылесоса (приближение и яркость) (**TO DO**).
* Нет оптимизации под большие разрешения.
