# AkmoshTest

## Markdown

Markdown - облегченный язык разметки.
 1. История
 2. Примеры синтаксиса 
 3. Реализация
## *История*
---
*Первоначально создан в 2004 году **Джоном Грубером и Аароном Шварцем.** Многие идеи языка были позаимствованы из существующих соглашений по разметке текста в электронных письмах. Реализации языка Markdown преобразуют текст в формате Markdown в валидный, правильно построенный XHTML и заменяют левые угловые скобки («<») и амперсанды («&») на соответствующие коды сущностей. Первой реализацией Markdown стала написанная Грубером реализация на Perl, однако спустя некоторое время появилось множество реализаций от сторонних разработчиков (см. ниже). *

## *Примеры синтаксиса*
---
*Ниже приведены примеры использования Markdown, однако это далеко не полное руководство. Полное описание языка может быть найдено на официальном сайте. Символы, которые обычно рассматриваются в Markdown как специальные, могут быть экранированы с помощью обратного слеша. Например, последовательность «\*» выведет символ «*», а не будет являться признаком начала выделенного текста. Кроме того, Markdown не преобразует текст внутри «сырых» блоков XHTML. Таким образом, в Markdown-документ можно включать секции XHTML, заключив их предварительно в теги уровня блока.*
**Программный код**
Элементы кода могут быть внутри строки (inline) либо многострочными блоками.Внутри строки код выделяется символом "`"

*Ниже начинается многострочный блок кода *
```
 <!doctype html>
    <html>
        <head>
            <!-- Заголовок документа -->
        </head>
        <body>
            <!-- Тело документа -->
        </body>
    </html>
```
*Цитаты (тег blockquote)*
>Цитата 
>> вложенная цитата

*Списки*
*маркированный список 
1.нумерованный список

*Ссылки*
[Ссылка на Markdown](https://ru.wikipedia.org/wiki/Markdown)

*Изображения*

Значок Markdown
[![значок Markdown](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/1024px-Markdown-mark.svg.png)](https://ru.wikipedia.org/wiki/Markdown)
*Таблицы*
| № | 1 | 2 | 3 | 4 |
|---|---|---|---|---|
| 1 | a | b | c | d |
| 2 | e | f | g | h |
| 3 | i | j | k | l |
*Список дел*
* [x] To do 1
* [x] To do 2
* [ ] To do 3
Жаннур

