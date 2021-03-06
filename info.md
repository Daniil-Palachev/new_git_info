# Инструкция по работе с git
Для создания локального репозитория нужно запустить команду:
> git init

Для добавления файла к следующему комиту:
> git add

и фиксируем эти файлы:
> git commit

Для отслеживания состояния репозитория, можно ввести команду:
> git status

Чтобы посмотреть все комиты:
> git log

Для просмотра разницы между закомиченными и текущими изменениями:
> git diff

Для ерехода к прошлым комитам, можно использовать:
> git checkout commit_code

и чтобы вернуться:
> git checkout master

![какая-то картинка](i.jpg) 
qeqwq
# Синтаксис языка Markdown.wqeqe

> Для выделения заголовка первого уровня необходимо использовать # перед заголовком. 

Например:
# Пример заголовка

> Для упорядочивания списка можн использовать нумерацию (ставим * перед каждым пунктом списка), или список без использования цифрового обозначения (- или +). 
Например:

1. пункт 1
2. пункт 2
3. пункт 3

или

* пункт 1
* пункт 2
* пункт 3

> Для ввыделения "жирным" текста необходимо использовать ** перед текстом и ** после. 

Например:

**Пример выделения текстом "жирным"**

> Для выделения текста "курсивом" необходимо использовать * перед текстом и * после текста.

**Пример выделения текстом "жирным"**

> Для выделения текста "курсивом" необходимо использовать * перед текстом и * после текста.

Например:

*Пример курсива*

> Для выделения текста "жирным курсивом необходимо перед текстом поставить *, затем обрамить текст _ в начале и _ в конце, затем закочить символом *.

Например:

**_Пример текста, выделенного "жирным курсивом"_**

>Три звездочки подряд *** между двумя строками текста создают горизонтальную линию.

Например:
Первая часть текста, который необходимо разделить
***
Вторая часть текста, который необходимо разделить

Для просмотра всех веток:
> git branch

Чтобы создать ветку, нужно:
> git branch branch_name

Для совмещения текущей ветки с веткой branch_name:
> git merge branch_name
Для того, чтобы удалить ветку нужно написать:
>git branch -d branch_name

изменения добавятся в текущую
Для перехода к ветке branch_name:
> git checkout branch_name

Для визуализации веток можно использовать:
> git log --graph

> Для создании таблиц используется символ (|). Вертикальная черта используется для разделения стобцов.

for example):

|наименование пищи|полезно,вредно| 
|:--:|:--:|
| чипсы | полезно |
| огурцы | полезно|
| говядина | вредно |
