---
author: "Lobar Qalandarova"
title: "Markdown Sintaksis Qo'llanmasi"
date: "2019-03-11"
description: "HTML elementlari uchun asosiy Markdown sintaksisi va formatlashni namoyish etuvchi namunaviy maqola."
tags: ["markdown", "css", "html", "mavzular"]
kategoriya: ["mavzular", "sintaks"]
series: ["Mavzu yo'riqnomalari"]
aliases: ["jekyll-dan0-migratsiya-qilish"]
cover:
  image: images/clean_keyboard.jpg
  caption: "Google dan yuklab olindi"
ShowToc: true
TocOpen: true
---

Ushbu maqola Hugo kontent fayllarida ishlatilishi mumkin bo'lgan asosiy Markdown sintaksisining namunalarini taqdim etadi, shuningdek, Hugo mavzusida asosiy HTML elementlarining CSS bilan bezatilganligini ko'rsatadi.

<!--more-->

## Sarlavhalar

Quyidagi HTML `<h1>`—`<h6>` elementlari bo'lim sarlavhalarining oltita darajasini anglatadi. `<h1>` eng yuqori bo'lim darajasi, `<h6>` esa eng past daraja hisoblanadi.

# H1

## H2

### H3

#### H4

##### H5

###### H6

## Paragraf

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed non risus. Suspendisse lectus tortor, dignissim sit amet, adipiscing nec, ultricies sed, dolor. Cras elementum ultrices diam. Maecenas ligula massa, varius a, semper congue, euismod non, mi. Proin porttitor, orci nec nonummy molestie, enim est eleifend mi, non fermentum diam nisl sit amet erat. Duis semper. Duis arcu massa, scelerisque vitae, consequat in, pretium a, enim. Pellentesque congue. Ut in risus volutpat libero pharetra tempor. Cras vestibulum bibendum augue. Praesent egestas leo in pede. Praesent blandit odio eu enim. Pellentesque sed dui ut augue blandit sodales. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Aliquam nibh. Mauris ac mauris sed pede pellentesque fermentum. Maecenas adipiscing ante non diam sodales hendrerit.


## Blok iqtiboslar

Blockquote elementi boshqa manbadan iqtibos keltirilgan kontentni anglatadi, optional ravishda `footer` yoki `cite` elementida keltirilgan manba bilan va zaruratga qarab inline o'zgartirishlar, masalan, izohlar va qisqartmalar bilan.

#### Attribution bo'lmagan blockquote

> Tiam, ad mint andaepu dandae nostion secatur sequo quae.
> **Eslatma**: Siz _Markdown sintaksisini_ blockquote ichida ishlatishingiz mumkin.

#### Attribution bilan blockquote

> Xotira almashish orqali emas, balki xotiralarni baham ko'rish orqali muloqot qiling.
>
> — <cite>Rob Pike[^1]</cite>

[^1]: Yuqoridagi iqtibos Rob Pike ning [ma'ruzasi](https://www.youtube.com/watch?v=PAAkCSZUG1c)dan olingan, Gopherfest, 2015-yil 18-noyabr.

## Jadvallar

Jadvallar asosiy Markdown spetsifikatsiyasining bir qismi emas, ammo Hugo ularni to'g'ridan-to'g'ri qo'llab-quvvatlaydi.

| Ism   | Yosh |
| ----- | ---- |
| Bob   | 27   |
| Alice | 23   |

#### Jadval ichidagi Inline Markdown

| Italik   | Qalin     | Kod    |
| -------- | --------- | ------ |
| _italik_ | **qalin** | `kod`  |

## Ro'yxat turlari

#### Tartibli ro'yxat

1. Birinchi element
2. Ikkinchi element
3. Uchinchi element

#### Tartibsiz ro'yxat

- Ro'yxat elementi
- Yana bir element
- Va yana bir element

#### Ichtaki tartibsiz ro'yxat

- Meva
  - Olma
  - Apelsin
  - Bananas
- Sut mahsulotlari
  - Sut
  - Pishloq

#### Ichtaki tartibli ro'yxat

1. Meva
    - Olma
    - Apelsin
    - Bananas
2. Sut mahsulotlari
    1. Sut
    2. Pishloq
3. Uchinchi element
    1. Birinchi subtur
    2. Ikkinchi subtur

## Boshqa elementlar — abbr, sub, sup, kbd, mark

<abbr title="Graphics Interchange Format">GIF</abbr> — bu bitmap rasm formati.

H<sub>2</sub>O

X<sup>n</sup> + Y<sup>n</sup> = Z<sup>n</sup>

Sessiyani tugatish uchun <kbd><kbd>CTRL</kbd>+<kbd>ALT</kbd>+<kbd>Delete</kbd></kbd> tugmalarini bosing.
