# Инструкция для работы с  Markdown

## Выделение текста

Чтобы выделить текст курсивом, необходимо обрамить его звездочками (*), например, *вот так*. или еще можно выделить при помощи нижнего подчеркивания (_), например, _вот так_. 

Чтобы быделить текст полужирным, необходимо обрамить его двойными звездочками (**), например, **вот так**. Также можно это сделать при помощи двойного подчеркивания (__), __вот так__.

Чтобы выделить текст и курсивом и полужирным, нужно совместить оба способа выделения текста. Например, *__вот так__*.

## Списки

Чтобы добавить ненумерованные списки, необходимо пункты выделить звездочкой и поставить пробел (*). Также можно выделить (+). Например, вот так:
* Элемент 1
* Элемент 2
* Элемент 3
+ Элемент 4

Чтобы добавить нумерованнные списки, необходимо просто пронумеровать пункты:
1. Элемент 1
2. Элемент 2

## Работа с изображениями

Чтобы вставить изображение в текст, достаточно написать следующее:

![Название картинки](ссылка, откуда картинку надо достать), если изображение находится в папке вместе с нашим файлом, достаточно просто вставить название изображения вместо ссылки.
![Это панда](%D0%BF%D0%B0%D0%BD%D0%B4%D0%B0.jpg)

## Ссылки

Ссылки можно оформлять разными способами:

1. Ссылки в тексте
___
* Обычная ссылка в строке: [название ссылки в квадратных скобках](сама ссылка рядом в круглых скобках)
[Google](https://www.google.com)

* Обычная ссылка с заголовком при наведении курсора: [Отображаемый текст](ссылка и отображаемый заголовок в кавычках) 
[Обычная ссылка с заголовком](https://www.google.com "Сайт Google")

2. Ссылки со сноской
___

* Вариант 1 - при оформлении сноски используется произвольный текст:
[Ссылка со сноской][Произвольный регистронезависимый текст]

[произвольный регистронезависимый текст]: https://www.google.com

* Вариант 2 - при оформлении сноски используются цифры: [Для ссылок со сноской можно использовать цифры][1]

[1]: http://www.google.com

* Вариант 3 - можно просто вставить ссылку в квадратные скобки [текст ссылки]

[текст ссылки]: http://www.google.com

## Работа с таблицами

Таблицы не являются частью Markdown, но многие обработчики, например Markdown Here и Github, поддерживают их. Они позволяют легко добавить таблицы в электронное письмо - в других случаях для этого нужно копировать их из другого приложения.

чтобы оформить таблицу внутри документа, необходимо столбцы отделить (|), текст нужно отделять пробелами от черточек, первую строку - заголовок нужно отделить отчеркиванием с помощью дефисов (---), настройки выравнивания текста задаются двоеточием.

| Столбец 1 | Столбец 2 | столбец 3 |
| --------- | :---------: | ---------: |
| Таблицы | Это | Красиво |
| *текст внутри* | `можно` | ~~редактировать~~ |


## Цитаты

Чтобы оформить цитату, нужно поставить угловую скобочку (>) и пробел в начале строки.

> Эта строка является частью цитаты.

Здесь цитата прерывается.

> Можно писать много-много текста, и он автоматически всё преобразует в одну цитату. Также `можно` использовать ~~различные~~ *стили оформления* в **цитате**. *__Красота!__*

## Заключение

Markdown -  облегчённый язык разметки, созданный с целью обозначения форматирования в простом тексте, с максимальным сохранением его читаемости человеком, и пригодный для машинного преобразования в языки для продвинутых публикаций.

