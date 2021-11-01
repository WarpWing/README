![Profile views](https://gpvc.arturio.dev/BEPb) ![GitHub top language](https://img.shields.io/github/languages/top/BEPb/README) ![GitHub language count](https://img.shields.io/github/languages/count/BEPb/README)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/BEPb/README)
![GitHub repo size](https://img.shields.io/github/repo-size/BEPb/README) ![GitHub](https://img.shields.io/github/license/BEPb/README) ![GitHub last commit](https://img.shields.io/github/last-commit/BEPb/README)

![GitHub User's stars](https://img.shields.io/github/stars/BEPb?style=social)

# Все о разметке файла README.md


## Откуда появился термин «README»? (Этимология)

Важную информацию, которую пользователь должен прочитать, прежде чем продолжить, описания проектов на GitHub на языке 
разметки markdown размещают в файле «README.md»

Этот термин появился как минимум к 1970-м годам, к тем временам, когда информационные бумажные заметки помещались на стопки
перфокарт. «ПРОЧИТАЙТЕ МЕНЯ!» нацарапал на них, описывая их использование. Возможно название README 
может быть шутливым подталкиванием к «Приключениям Алисы в стране чудес» Льюиса Кэрролла, где есть зелье и торт с 
надписью «ВЫПЕЙ МЕНЯ» и «СЪЕШЬ МЕНЯ» соответственно.

Образец README, отображаемый заглавными буквами, является неизменным аспектом на протяжении всей истории. 
В дополнение к визуальной выразительности использования заглавных букв, системы UNIX сортируют заглавные буквы перед
строчными буквами, удобно помещая README перед остальным содержимым каталога.



## Оглавление

1. [Горизонтальная линия](#Горизонтальная-линия)
2. [Заголовок](#Заголовок)
3. [Текст](#Текст)
   * 3.1. Обычный текст
   * 3.2. Одна строка текста
   * 3.3. Многострочный текст
   * 3.4. Выделение текста
   * 3.5. Перенос строк
   * 3.6. Курсив
   * 3.7. Жирный
   * 3.8. Зачеркнутый
4. [Вставка таблиц](#Вставка-таблиц)
5. [Списки](#Списки)
    * 5.1. Маркированный
    * 5.2. Нумерованный
6. [Ссылки](#Ссылки)
    * 6.1. Текстовая гиперссылка
    * 6.2. Ссылка изображения
7. [Полезные ссылки](#Полезные-ссылки)
    * 7.1. Шильды
    * 7.2. Эмоджи

    
## Горизонтальная линия

Горизонтальную линию (разделительную черту) можно получить тремя способами:
* *** (используя три подряд символа '*' (звездочка))、
***
* --- (используя три подряд символа '-' (тире))、
---
* ___ (используя три подряд символа '_' (подчеркивание))
___

все они отображают эффект горизонтальной линии
____

[К оглавлению](#Оглавление)
____
## Заголовок

Размер заголовка (шрифта) может быть 6-ти уровней, он зависит от количества символов `#` (решетки) в начале строки.


```
# Заголовок первого уровня
## Заголовок второго уровня
### Заголовок третьего уровня
#### Заголовок четвертого уровня
##### Заголовок пятого уровня
###### Заголовок шестого уровня
```

# Заголовок первого уровня
## Заголовок второго уровня
### Заголовок третьего уровня
#### Заголовок четвертого уровня
##### Заголовок пятого уровня
###### Заголовок шестого уровня

Заголовок 1 (еще один способ)
=
Заголовок первого уровня также можно создать при помощи одного или нескольких символов '=' размещенного на 
следующей за оглавлением строке:

```
Заголовок 1
=
```

Заголовок 2 (еще один способ)
-
Заголовок второго уровня также можно создать при помощи одного или нескольких символов '-' размещенного на 
следующей за оглавлением строке:

```
Заголовок 2
-
```

[К оглавлению](#Оглавление)
____

## Текст
### 3.1. Обычный текст
Здесь отображен обычны текст, без каких либо манипуляций.


[К оглавлению](#Оглавление)
____
### 3.2. Одна строка текста
    текст в одну строку

Добавьте 4 пробела в начале строки и Ваш текст будет выделен в отдельном окне, как на примере. Иногда срабатывает по 
знаку табуляции, но не всегда.... т.к. знак табуляции иногда отступает на 3 или иное количество пробелов.


[К оглавлению](#Оглавление)
____
### 3.3. Многострочный текст
    ВОТ ЗДЕСЬ ЛЕЖИТ БОЛЬШОЙ СТУДЕНТ;
    ЕГО СУДЬБА НЕУМОЛИМА.
    НЕСИТЕ ПРОЧЬ МЕДИКАМЕНТ:
    БОЛЕЗНЬ ЛЮБВИ НЕИЗЛЕЧИМА!

Добавьте 4 пробела в начале каждой строки и Ваш текст будет выделен в отдельном окне, как на примере. 

[К оглавлению](#Оглавление)
____
### 3.4. Выделение текста
Выше приведенные примеры не смогут сохранить отсупы сложного текста в каждой строке, для этих целей используйте в 
три обратные ковычки "```", при этом они должны находится на отдельных строках перед текстом и после, соответственно.

```
"Стремитесь не к успеху, а к ценностям, которые он дает."
                                          Альберт Эйнштейн
```
Если Вы используете только пару обратных кавычек, то Ваш текст будет выделен, но без сохранения отступов. Так же 
можно выделять отдельные слова в тексте.

``
Жизнь - это то, что с тобой происходит, пока ты строишь планы.                                                      
                                                      Джон Леннон
``

``Логика`` может привести Вас от пункта А к пункту Б, а ``воображение`` — куда угодно. (Альберт Эйнштейн)

Но это не все, часто мы испытываем необходимость поместить фрагменты кода, желательно не только сохранить отступы, 
но и выдилить цветом, для этого нужно после первых трех кавычек указать язык программирования 
```python
from django.contrib import admin
# настройка админки
# Register your models here.

from .models import Phonenumber, Division, MilitaryUnit


class PhonenumberAdmin(admin.ModelAdmin):  # описываем раздел админки "Справочник"
    # указываем отображаемые поля
    list_display = (
        'id',
        'military_unit',  # указываем воинскую часть из таблицы MilitaryUnit
        'division',  # указываем подразделение из таблицы Division
        'subdivision',
    )
```
____

[К оглавлению](#Оглавление)
____
### 3.5. Перенос строк
Возможно это не обычно и не привычно, но при нажатии кнопки "Enter", Ваш текст по прежне будет отображаться в одну 
строку, а для того что бы Ваш перенос заработал, необходимо в конце строки добавить два пробела

Или просто добавьте пустую строку, т.е. нажмите "Enter" 2 раза. В этом случае эффект переноса будет достигнут, но 
междустрочный интервал будет больше. 

[К оглавлению](#Оглавление)
____
### 3.6. Курсив
Поместите текст между двумя символами '*' (звездочки) или '_' (подчеркивания) и он превратится в  
*НАКЛОННЫЙ ТЕКСТ* или _НАКЛОННЫЙ ТЕКСТ_
```
*НАКЛОННЫЙ ТЕКСТ* или _НАКЛОННЫЙ ТЕКСТ_
```
[К оглавлению](#Оглавление)
____
### 3.7. Жирный
Поместите текст между двумя двойными символами '*' (звездочки) или '_' (подчеркивания) и он превратится в  
__ЖИРНЫЙ ТЕКСТ__ или **ЖИРНЫЙ ТЕКСТ**
```
__ЖИРНЫЙ ТЕКСТ__ или **ЖИРНЫЙ ТЕКСТ**
```
Текст между тремя символами '*' (звездочки) или '_' (подчеркивания) превращают его в жирный наклонный текст:  
___Жирный наклонный текст___  или ***Жирный наклонный текст***
```
___Жирный наклонный текст___  или ***Жирный наклонный текст***
```

[К оглавлению](#Оглавление)
____
### 3.8. Зачеркнутый
Поместите текст между двумя двойными символами '~' и он превратится в
~~ЗАЧЕРКНУТЫЙ ТЕКСТ~~
```
~~ЗАЧЕРКНУТЫЙ ТЕКСТ~~
```

[К оглавлению](#Оглавление)
____
## Вставка таблиц

Простая таблица
```
|Автор|Андрей Маринченко|
|---|---|
|Профессия| Python-developer|
|Статья| О разметке файла README|
```
|Автор|Андрей Маринченко|
|---|---|
|Профессия| Python-developer|
|Статья| О разметке файла README|

[К оглавлению](#Оглавление)
____

## Списки
### 5.1. Маркированный
Маркированный список образуется символами -, + или * с которых начинается каждая новая строка списка
- первый
- второй
- третий
### 5.2. Нумерованный
Нумерованный список создается как обычная нумерация строк, 
1. первый  
1.1. первый подпункт  
1.2. второй подпункт  
1.3. третий подпункт
2. второй  
3. третий   
4. четвертый

[К оглавлению](#Оглавление)
____
## Ссылки
## 6.1. Текстовая гиперссылка
##  Ссылка на внешний URL
Можно просто добавить ссылку из браузера https://github.com/BEPb, и она будет работать, но если мы хотим скрыть ее 
за текстом то ссылку необходимо поместить в круглые скобки, а текст в квадратные сразу перед ссылкой
```
Жми сюда ---> [тыц](https://github.com/BEPb)
```
Жми сюда ---> [тыц](https://github.com/BEPb)
    
##  Ссылка на текст внутри README.md
Если мы формируем ссылку внутри файла README.md, то следует помнить, что сослаться мы может на только заглавки, 
[Cмотри раздел "Заголовок"](#Заголовок)
```
[Cмотри раздел "Заголовок"](#Заголовок)
```
А что делать если заголовок состоит из нескольких слов?... Необходимо все пробелы заменить на '-' как раздел про 
[Горизонтальную линию](#Горизонтальная-линия)
```
[Горизонтальную линию](#Горизонтальная-линия)
```
## 6.2. Ссылка изображения
Все работает точно также сочетание восклицательного знака + квадратных скобок + круглые скобки
```
![Не важно](https://avatars.githubusercontent.com/u/57312267?v=4 "подпиши картинку при наведении")
```
![Не важно](https://avatars.githubusercontent.com/u/57312267?v=4 "подпиши картинку при наведении")

Если Вы предварительно создали папку с изображениями, которые желаете применить в своем README файле, то для 
отображения таких изображений необходимо указать относительный адрес Вашего файла в репозитории, например у меня в 
папке media находится изображение с названием super.jfif, для отображения необходимо ввести
```
![](./media/super.jfif)
```
![](./media/super.jfif)

Основной текст
>>> Скрытый текст<<< 
Продолжение
> фвпфпфвп
> фвафыва
> фвыафыва
> фывафваы
> фваффффффффффффффффффффффффффффффффффффффффффффффффффффффффффффффф
> фффффффффффффффффффффффффффффффффффффффффффф
> фаааааааааааааааааааааааа
>>> Скрытый текст<<< 
> 
> 
> 


[К оглавлению](#Оглавление)
____
### Полезные ссылки

https://shields.io/ - Если есть желание добавить шильды, например тех, что находятся в начале этого файла, то 
переходите на сайт, выбираете шильду, вбиваете как правило имя на гихабе, имя репозитория и копируете код шильды в 
свой readme-файл.

https://github.com/BEPb/README/blob/master/emogi.md - Если есть желание украсить свой readmi-файл эмодзи 
:smiling_imp: ,  :innocent: то просто скопируйте код из таблицы напротив нужного.
