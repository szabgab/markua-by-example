{sample: true, id: introduction}
# Introduction

This book includes examples using [Markua](https://leanpub.com/markua).
I am using this as a playground to see how to add elements to my books. This also makes it easier to to ask questions and submit bug-reports where something does not work out. The source of this book can be found [in GitHub](https://github.com/szabgab/markua-by-example).
If you'd like to support my effort to make Markua more accessible, you can purchase this book, or any of my [other book](https://leanpub.com/u/szabgab), or you can [support me on Patreon](https://www.patreon.com/szabgab).

## How to use this book?

While looking at the book compare it with the source [in GitHub](https://github.com/szabgab/markua-by-example) to see what generates each secion.


## Notes

I am writing this book in plain text file using the Markua format. The Webhook in GitHub configure to autopublish the book, so every time I push out some changes the book is published with a minute or so.


## Table

### A table

Copied from [the Markua specification](https://leanpub.com/markua/read#tables)

{type: table}
|============|============|============|
| Header A   | Header B   | Header C   |
|============|============|============|
| Content A1 | Content B1 | Content C1 |
|------------|------------|------------|
| Content A2 | Content B2 | Content C2 |
|============|============|============|
| Footer A   | Footer B   | Footer C   |
|============|============|============|


### Table without footer

{type: table}
|============|============|============|
| Header A   | Header B   | Header C   |
|============|============|============|
| Content A1 | Content B1 | Content C1 |
|------------|------------|------------|
| Content A2 | Content B2 | Content C2 |
|============|============|============|

### A missing external table 

![](tbl/some_table.tbl)

### An existing external table 

![](tbl/first.tbl)

It is located at `manuscript/resources/tbl/first.tbl`.

## Images

### Missing image

![](img/some_image.png)


## Verbatim text

As I understand, [the spec indicates](https://leanpub.com/markua/read#code) that line-numbers default to `false` however in LeabPub it seems to be dependent on the `theme` that you can configure in `https://leanpub.com/YOUR-BOOK/theme`. All 3 default themes have `line-numbers` set to `true`, but you can create a custom theme and set the `line-numbers` to default to `false`.

```
first line
second line
```

The End
