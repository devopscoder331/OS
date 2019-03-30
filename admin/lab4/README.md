# Пояснительная записка к л\р №4

## Требования к инструментам для выполнения л\р:
* наличие интернета для выполнение выгрузки результатов в git
* установленный git

## Что такое markdown:
 Облегчённый язык разметки, созданный с целью написания наиболее читаемого и удобного для правки текста, но пригодного для преобразования в языки для продвинутых публикаций (HTML, Rich Text и других).

## Справочник команд:

### Заголовки:
Заголовки в markdown обозачаются символом #. Количество # от 1 до 6. Чем больше # тем меньше шрифт. Минимальный шрифт это H6(обозначается ######), максимальный шрифт - H1(обозначается #):

# Так выглядит H1

###### Так выглядит H6

### Выделение текста:

``Курсив обозначается *звездочками* или _подчеркиванием_. Полужирный шрифт - двойными **звездочками** или __подчеркиванием__. Комбинированное выделение **звездочками и _подчеркиванием_** с двух сторон.Для зачеркнутого текста используются две тильды. ~~Уберите это.~~``

Пример:

*example*

**example**

~~example~~

### Списки:
Пробел представлен в виде ⋅⋅
```
1. Первый пункт нумерованного списка
2. Второй пункт
⋅⋅*Ненумерованный вложенный список.
1. Сами числа не имеют значения, лишь бы это были цифры
4. И еще один пункт.
* Ненумерованный список можно размечать звездочками
- Или минусами
+ Или плюсами
```

Как это выглядит:
1. Первый пункт нумерованного списка
2. Второй пункт
  * Ненумерованный вложенный список.
1. Сами числа не имеют значения, лишь бы это были цифры
4. И еще один пункт.

### Ссылки:

```
[Обычная ссылка в строке](https://www.google.com)
[Обычная ссылка с title](https://www.google.com "Сайт Google")
```

Как это выглядит:

1. [Обычная ссылка в строке](https://www.google.com)
2. [Обычная ссылка с title](https://www.google.com "Сайт Google")

### Вставка изображения:
```   
![alt-текст](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Текст заголовка логотипа 1")
```
![alt-текст](https://explabs.ru/img/logo-explabs.svg "Классную картинку увидел в поисковике")

### Код и подсветка синтаксиса:
```
`Подсветка синтаксиса` в строке обрамляется `обратными апострофами`.
Блоки кода выделяются либо тремя обратными апострофами ``` либо четырьмя пробелами в каждой строке. Рекомендуется использовать три апострофа, ведь они проще и только они поддерживают подсветку синтаксиса.
```
Пример:

Тут используется только одинарный `Апостроф`
```
А тут уже используется три апострофа
```
### Таблицы:
```
Вертикальные линии обозначают столбцы.

| Таблицы       | Это                | Классно |
| ------------- |:------------------:| -----:|
| столбец 3     | выровнен вправо    |  |
| столбец 2     | выровнен по центру |    |
| зебра-строки  | прикольные         |    </head> |

Внешние вертикальные линии (|) не обязательны, и они нужны только чтобы сам код Markdown выглядел красиво. Тот же код можно записать так:

Markdown | не такой | красивый
--- | --- | ---
*Но выводится* | `так же` | **клево**
1 | 2 | 3
```
Пример:


| Таблицы       | Это                | Классно |
| ------------- |:------------------:| -----:|
| столбец 3     | выровнен вправо    |  |
| столбец 2     | выровнен по центру |    |
| зебра-строки  | прикольные         |    </head> |

Markdown | не такой | красивый
--- | --- | ---
*Но выводится* | `так же` | **классно**
1 | 2 | 3

## Задание

данная работа - помощник в оформлении других лабораторных работ.
Выполнять эту эту работу следует совместно с л/р 1 и 3 - формировать отчет.

Сделайте отчеты согласно заданию. В результате вы должны поместить файл\файлы с расширением *md* в свой репозиторий.
Один отчет - один файл. Предоставьте ссылку на репозиторий в качестве отчета преподавателю.
Не создавайте отдельные репозитории под разные отчеты - делайте все в одном репозитории.