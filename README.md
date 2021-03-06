Учебный проект "landing-page"
================================

### Используемые технологии

1. Фреймворк Bootstrap 3
2. Библиотека JavaScript - jQuery для работы Bootstrap

### Используемые шрифты и иконки

1. Dosis light, regular, Open Sans regular
2. Font-Awesome, Et-line - иконочные шрифты 

### Стандартные компоненты и классы

***Компоненты***
1. Задаем отступы внутри блока:
```
    .default-section - стандартная секция
    .small-section - переопеделяем отступ внутри секции
```
2. Задаем стили шапке и меню
```
    .header - шапка
    .header-nav - меню
    .header .navbar-toggle - мобильное меню
    .header .navbar-toggle .icon-bar - цвет бургер кнопки
    .logo - логотип
```
3. Стилизируем иконки
```
    .rhomb-icon - ромб содержащий внутри иконку Font-Awesome
    .rhomb-icon.black-icon - цвет ромба и иконки внутри
    .rhomb-icon.white-icon 
    .rhomb-icon.transparent-icon 
```
4. Стилизируем заголовки:
```
    .title - стандартный заголовок
    .title.light - переопределяем жирность и отступ между буквами заголовка
    .title.small-title - переопределяем размер шрифта, отступ между буквами заголовка
    .title.less-margin - переопрделяем отступ заголовка
```
5. Стилизируем текст и цитаты:
```
    .default-text - стандартный текст
    blockquote - стиль цитаты
    blockquote span
```
6. Навигационные стили для вкладок
```
    .nav-tabs
    .nav-tabs > li
    .nav > li > a
    .nav-tabs > li > a
```
7. Стилизируем стандартные кнопки:
```
    .btn - стандартные стили кнопки
    .btn.btn-default - цвет кнопки
    .btn.btn-darkgrey
    .btn.btn-black
    .btn.btn-xs - переопределяем отступы внутри кнопки и размер текста 
    .btn.btn-md
```
8. Стилизируем дефолтные формы и элементы форм:
```
    .form-control
    textarea.form-control
```

***Классы***
1. Задаем цвет:
```
    .bg-black
    .bg-grey
    .text-white
```
---

### Контрольные точки media-запросов

1. @media (max-width: 1199px) - устройства c разрешением до 1199px
2. @media (max-width: 991px) - устройства c разрешением до 991px
3. @media (max-width: 767px) - устройства c разрешением до 767px
4. @media (max-width: 599px) - мобильные устройства c разрешением до 599px
5. @media (max-width: 479px) - мобильные устройства c разрешением до 479px
---

Название файла  | Содержание файла
----------------|----------------------
style.css       | Файл каскадной таблицы стилей, содержит стили
script.js       | Файл содержащий скрипт плавного скроллинга страницы  
index.html      | Индексный файл содержащий разметку
