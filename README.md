# Simple Markdown Tutorial

## Table of contents

* [General info](#general-info)
* [Technologies](#technologies)
* [Introduction](#intoduction)
* [Setup](#setup)
* [Syntax](#syntax)
* [Licence](#licence)

---

## General info
This is a tutorial that I have created to learn Markdown by myself. However, I came up with the idea of making a simple self-explaining file so everybody can learn from it too. I hope you enjoy it.

---

## Technologies
* Markdown

---

## Introduction
**Markdown** is a lightweight markup language designed by Aaron Swartz and John Gruber in 2004. It is used to provide simple and clear text documents using any editor.

![Markdown  Logo](https://markdown-here.com/img/icon256.png "Markdown Logo")

---

## Setup
As I have written in the **Introduction** section you can use almost any text editor however what is important is that the file has an ```.md``` extension. Nevertheless, I personally use [Visual Studio Code](https://code.visualstudio.com/) which is available for free with [Auto-Open Markdown Preview](hnw.vscode-auto-open-markdown-preview
) installed.

Also, remember when pushing the finished file to git it should be named ```README.md```

---

## Syntax

<!-- Comments -->
### Comments
The way you can comment your code:
```
<!-- Your Comment  --> 
```
In visual studio code shortcut for this is ```Ctrl + / ```.

---

<!-- Headings -->
### Headings
To make a heading you should use \# tag as well as your title. The number of tags corresponds to the size of headings. It is showed by the following example:

```
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```

Result:
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6


---
<!-- Italic and bold text -->
### Italic and bold text
There are two options to format text as italic or bold. The first option is by using ```*``` for italic and ```**``` for bold. For instance:
```
*Lorem* ipsum dolor sit amet.
```

```
**Lorem** ipsum dolor sit amet.
```
Result for italic font:

*Lorem* ipsum dolor sit amet.

Result for bold font:

**Lorem** ipsum dolor sit amet.



The second option is ```_``` and ```__```.It is just an alternative consisting of a change of the signs.
Both choices are good to depend on personal preferences. The only thing to consider is to remain consistent with your code.

---

<!-- Horizontal Rule -->
### Horizontal Rule
Necessery code:
```
---
```
or:

```
___
```
Result:

---

<!-- Strikethroughs -->
### Strikethroughs 

```~~sample text~~```

```
~~Lorem ipsum dolor~~ sit amet.
```

Result:

~~Lorem ipsum dolor~~ sit amet.

---

### Lists

Lists can be implemented as:
* Unordered lists
* Ordered lists

<!-- Unordered Lists -->
#### Unordered lists
Created with ```*``` for each list item:
```
* Item 1
* Item 2
* Item 3
```

<!-- Ordered Lists -->
#### Ordered lists
Created with **number** for each list item:
```
1. Item 1
2. Item 2
3. Item 3
```

<!-- Nested Lists -->
#### Nesting 
Achieved by the use of ```Tab``` on a list item, for example:
```
1. Item 1
    * Nested Item 1
2. Item 2
    * Nested Item 2
3. Item 3
    * Nested Item 3
```
---

<!-- Special Characters -->
### Special Characters

Ignore these with ```\``` before:
```
\*\*Lorem** ipsum \*dolor sit amet
```

---

<!-- Blockquotes -->
### Blockquotes
The ```>``` mark:
```
>Lorem ipsum dolor sit amet
```

>Lorem ipsum dolor sit amet

---

<!-- Links -->
### Links
Links require ```[]``` where you can insert name and ```()``` where the adress of domain is.

```
[Markdown Guide](https://www.markdownguide.org/)
```
[Markdown Guide](https://www.markdownguide.org/)

---

<!-- Images -->
### Images
The rule for images is similar to links but before the statement ```!``` is needed. Image from web implementation:
```
![Markdown  Logo](https://markdown-here.com/img/icon256.png)

```

Result:

![Markdown  Logo](https://markdown-here.com/img/icon256.png)



For image from file, image must be in the same directory or one directory far from the file.
```
![GitHub Logo](img/github.png)

```
Result:

![GitHub Logo](img/github.png)

---

<!-- Inline Code Block  -->
### Inline Code Blocks
Insert code with ``` `````` ```, as shown below:
```
```<a href="#" class="btn">Sign up</a>```
```

Result:
```<a href="#" class="btn">Sign up</a>```

---

## Specially for GitHub

<!-- Code Blocks -->
### Code Blocks



```c++
for (int i = 1; i < num; i++) {
    factorial*=i;
}
```

---

<!-- Task Lists -->
### Task lists
For task list use ``` []``` to make a box and x inside to check it.  
```
* [x] Task 1
* [x] Task 2
* [] Task 3
```

Result:
* [x] Shopping
* [x] Learning
* [] Cleaning

---

<!-- Tables -->
### Tables
Adding a table is easy. All you need to do is use ```|``` to separate columns bearing in mind that a number of columns in each row must be equal.

```
|Name|Email|
|-|-|
|Mateusz Polakiewicz|mateusz.polakiewicz.contact@gmail.com|
|James Smith|jamessmith@gmail.com|
```

Result:
|Name|Email|
|-|-|
|Mateusz Polakiewicz|mateusz.polakiewicz.contact@gmail.com|
|James Smith|jamessmith@gmail.com|

---

## Licence
Copyright MIT &copy; 2021 Mateusz Polakiewicz