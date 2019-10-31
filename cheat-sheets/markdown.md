# Markdown Cheatsheet

This Markdown cheat sheet provides a quick overview of all the markdown syntax elements. It can't cover every edge case, so if you need mroe information about any of these elements, refer to the offical site.

## Table of Contents

- [Headers](#Headers)
- [Emphaisi](#emphasis)
- [Lists](#lists)
  - [Unordered List](#Unordered-Lists)
  - [Ordered List](#ordered-lists)
- [Links](#links)
- [Image](#image)
- [Inline Code and Syntax Highlighting](#Inline-Code-and-Syntax-Highlighting)
- [Blockquotes](#Blockquotes)
- [Task Lists](#task-lists)
- [Tables](#tables)


## Headers

You can use on `#` all the way up to `######` six for different levels of headings to structure your documents. Start lines with a `#` to create headings. Multiple `##` in a row denote smaller heading sizes

    # this is an level 1 header
    ## this is an level 2 header
    ###### this is an level 6 header

## Emphasis

- Italics: Use _Underscores_ or _Asterisks_
- BOLD: Use double **Underscores** or **Asterisks**
- Strikethrough uses two tildes: ~~test~~


    Italics: Use _Underscores_ or _Asterisks_
    BOLD: Use double **Underscores** or **Asterisks**
    Strikethrough uses to tildes: ~~test~~

## Lists

### Unordered Lists

Use *， +， - for unordered lists

* List 1

+ List 2

- List 3

      * List 1
      + List 2
      - List 3

### Ordered Lists

Use number with dots for ordered lists

1. List 1
2. List 2
   2.List 2.1


       1. List 1
       2. List 2
         2.1 List 
 
## Links

[Link to Google](https://www.google.com)

```
[Link to Google](https://www.google.com)
```

## Image

Similary to the links, simply add `!` to the `[Alt Text](URL)`

    ![Github Logo](/image/logo.png)
    Format: ![Alt Text](URL)

## Inline Code and Syntax Highlighting

Use `back-ticks` for the inline code

    Use `back-ticks` for the inline code

To create a code block, either indent each line by 4 spaces, or place 3 backtikcs on a line above and blew the code block

## Blockquotes

> the blockquote is used to indicate the quoation of a large section of text from another source

For example, this quote from the play Hamlet:

> To be, or not to be? That is the question.

```
> the blockquote is used to indicate the quoation of a section of text from another source

For example, this quote from the play Hamlet:
>To be, or not to be? That is the question.
```

## Task Lists

- [x] Task 1
- [ ] Task 2
- [ ] Task 3

```
- [x] Task 1
- [ ] Task 2
- [ ] Task 3
```

## Tables

You can create tables by assembling a list of words and dividing them with hyphens `-`(for the first row), and then separating each column with a pipe `|`:

| Fruit  | Price |
| :----: | :---: |
| Apple  |  \$1  |
| Lemon  |  \$5  |
| Orange |  \$5  |
| Banana | \$10  |

```
|Fruit | Price|
|:---: |:---: |
|Apple | $1   |
|Lemon | $5   |
|Orange| $5   |
|Banana| $10  |
```

**Note**: The outer pipes `|` are optional, and you don't need to make the raw Markdown line up rettily.
