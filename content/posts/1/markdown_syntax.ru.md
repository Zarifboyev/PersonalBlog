---
author: "Лобар Каландарова"
title: "Руководство по синтаксису Markdown"
date: "2019-03-11"
description: "Примерная статья, демонстрирующая базовый синтаксис и форматирование Markdown для HTML-элементов."
теги: ["markdown", "css", "html", "темы"]
категории: ["темы", "синтаксис"]
серии: ["Руководства по темам"]
aliases: ["миграция-с-jekyll"]
cover:
  image: img/clean_keyboard.jpg
  caption: "Загружено из Google"
ShowToc: true
TocOpen: true
---


Эта статья представляет собой пример базового синтаксиса Markdown, который можно использовать в файлах контента Hugo, а также показывает, как базовые элементы HTML оформляются с помощью CSS в теме Hugo.

<!--more-->

## Заголовки

Следующие HTML-элементы `<h1>`—`<h6>` представляют собой шесть уровней заголовков разделов. `<h1>` — это самый высокий уровень раздела, а `<h6>` — самый низкий.

# H1

## H2

### H3

#### H4

##### H5

###### H6

## Параграф

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed non risus. Suspendisse lectus tortor, dignissim sit amet, adipiscing nec, ultricies sed, dolor. Cras elementum ultrices diam. Maecenas ligula massa, varius a, semper congue, euismod non, mi. Proin porttitor, orci nec nonummy molestie, enim est eleifend mi, non fermentum diam nisl sit amet erat. Duis semper. Duis arcu massa, scelerisque vitae, consequat in, pretium a, enim. Pellentesque congue. Ut in risus volutpat libero pharetra tempor. Cras vestibulum bibendum augue. Praesent egestas leo in pede. Praesent blandit odio eu enim. Pellentesque sed dui ut augue blandit sodales. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Aliquam nibh. Mauris ac mauris sed pede pellentesque fermentum. Maecenas adipiscing ante non diam sodales hendrerit.

## Цитаты

Элемент блок-цитаты представляет собой контент, который цитируется из другого источника, возможно, с указанием ссылки, которая должна быть внутри элемента `footer` или `cite`, а также возможно с inline-изменениями, такими как аннотации и аббревиатуры.

#### Цитата без авторства

> Tiam, ad mint andaepu dandae nostion secatur sequo quae.
> **Примечание**: вы можете использовать _синтаксис Markdown_ внутри блок-цитаты.

#### Цитата с автором

> Не общайтесь, делясь памятью, делитесь памятью, общаясь.
>
> — <cite>Роб Пайк[^1]</cite>

[^1]: Цитата выше взята из [выступления Робa Пайка](https://www.youtube.com/watch?v=PAAkCSZUG1c) на Gopherfest, 18 ноября 2015 года.

## Таблицы

Таблицы не являются частью основного синтаксиса Markdown, но Hugo поддерживает их «из коробки».

| Имя   | Возраст |
| ----- | ------- |
| Боб   | 27      |
| Алиса | 23      |

#### Встроенный Markdown в таблицах

| Италика    | Жирный    | Код    |
| ---------- | --------- | ------ |
| _италика_  | **жирный** | `код`  |

## Блоки кода

#### Встроенный код

`Это встроенный код`

#### Только `pre`

<pre>
Это текст в теге pre
</pre>

#### Блок кода с обратными кавычками
