---
title: Язык разметки Markdown
date: 2023-04-08
math: true
image:
  placement: 2
  caption: 'Image credit: [**John Moeses Bauan**](https://unsplash.com/photos/OGZtQF8iC0g)'
---

# Введение - Базовые сведения о Markdown

Чтобы создать заголовок, используйте знак #, например:

```
# This is heading 1
## This is heading 2
### This is heading 3
#### This is heading 4

```

Чтобы задать для текста полужирное начертание, заключите его в двойные
звездочки:

```
This text is **bold**.
```

Чтобы задать для текста курсивное начертание, заключите его в одинарные
звездочки:

```
This text is *italic*.
```

Чтобы задать для текста полужирное и курсивное начертание, заключите его
в тройные звездочки:

This is text is both 

```
***bold and italic***
```

Блоки цитирования создаются с помощью символа >:

> The drought had lasted now for ten million years, and the reign of
the terrible lizards had long since ended. Here on the Equator,
in the continent which would one day be known as Africa, the
battle for existence had reached a new climax of ferocity, and
the victor was not yet in sight. In this barren and desiccated
land, only the small or the swift or the fierce could flourish,
or even hope to survive.

Упорядоченный список можно отформатировать с помощью соответствую-
щих цифр:

```
1. First instruction
  1. Sub-instruction
  1. Sub-instruction
1. Second instruction
```

Чтобы вложить один список в другой, добавьте отступ для элементов дочер-
него списка:

```
1. First instruction
1. Second instruction
1. Third instruction
```

Неупорядоченный (маркированный) список можно отформатировать с помо-
щью звездочек или тире:

```
* List item 1
* List item 2
* List item 3
```

Чтобы вложить один список в другой, добавьте отступ для элементов дочер-
него списка:

```
- List item 1
- List item A
- List item B
- List item 2
```

Синтаксис Markdown для встроенной ссылки состоит из части [link text],
представляющей текст гиперссылки, и части (file-name.md) – URL-адреса или
имени файла, на который дается ссылка:

```
[link text](file-name.md)
```

или

```
[link text](http://example.com/ "Необязательная подсказка")
```

Markdown поддерживает как встраивание фрагментов кода в предложение,
так и их размещение между предложениями в виде отдельных огражденных
блоков. Огражденные блоки кода — это простой способ выделить синтаксис для
фрагментов кода. Общий формат огражденных блоков кода:

``` language
your code goes in here
```

