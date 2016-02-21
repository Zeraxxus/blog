+++
author = "Bjarne Kristensen"
date = "2016-02-21T14:39:42+01:00"
description = "This is just a small test page to show the different markdown possibilities"
tags = ["markdown", "test"]
title = "Markdown Test"

+++
# Header

## Header

### Header 

#### Header

##### Header

###### Header
```
# Header

## Header

### Header 

#### Header

##### Header

###### Header
```

- - -
### Emphasising text

**bold**

*italic* and _italic_  

***italic bold*** and **_italic bold_**  

~~Strikethrough~~  

```
**bold**

*italic* and _italic_  

***italic bold*** and **_italic bold_**  

~~Strikethrough~~  
```

- - -
### Numbered List
1. Item
2. Item
   1. Item
   2. Item
3. Item
   * Item
   * Item
4. Item

```
1. Item
2. Item
   1. Item
   2. Item
3. Item
   * Item
   * Item
4. Item
```

- - -
### Unordered list
* Item
* Item
  1. Item
  2. Item
- Item
  * Item
  * Item
- Item
+ Item
+ Item

```
* Item
* Item
  1. Item
  2. Item
- Item
  * Item
  * Item
- Item
+ Item
+ Item
```

- - -
### Block quote

> This is just a sample to see how block quotes look.  
> And it seems just fine and easy.  
> <br>
> And an emty line above, but will not show.  

```
> This is just a sample to see how block quotes look.  
> And it seems just fine and easy.  
> <br>
> And an emty line above, but will not show.  
```

- - -
### Horizontal line
- - -
```
- - -
```

- - -
### Code block

```
C:\_ singlelinecode.exe
```

```
void FancyAlert(char* word) {
  if(word) {
    printf("%s is fancy!", word);
  }
}
```

code is displayed using three grave accents &#96; or tildes &#126; before and after the code, like this:

~~~
```
void FancyAlert(char* word) {
  if(word) {
    printf("%s is fancy!", word);
  }
}
```
~~~

or 

```
~~~
void FancyAlert(char* word) {
  if(word) {
    printf("%s is fancy!", word);
  }
}
~~~
```

- - -
### Links

My website <http://www.zeraxxus.dk>

My website [www.zeraxxus.dk](http://www.zeraxxus.dk)

My website [www.zeraxxus.dk](http://www.zeraxxus.dk "www.zeraxxus.dk")

Not my email <name@email.com>

```
My website <http://www.zeraxxus.dk>

My website [www.zeraxxus.dk](http://www.zeraxxus.dk)

My website [www.zeraxxus.dk](http://www.zeraxxus.dk "www.zeraxxus.dk")

Not my email <name@email.com>
```

- - -
### Images

![Open Source keyhole logo](https://opensource.org/files/osi_keyhole_300X300_90ppi_0.png "Open Source")

```
![Open Source keyhole logo](https://opensource.org/files/osi_keyhole_300X300_90ppi_0.png "Open Source")
```

- - -
### Youtube
{{< youtube Iwmwa3c0hUA >}}
<br>
youtube embeds are inserted via hugo macros like this:

&#123;&#123;&#60; youtube Iwmwa3c0hUA &#62;&#125;&#125;

- - -
### Footnotes
This text really needs a footnote.[^1] This text might need some footnoting as well with a link to a website.[^2]

[^1]: Footnote 1 text.
[^2]: [Footnote 2 link](http://www.zeraxxus.dk)

Footnotes are made like this:  
`This text really needs a footnote.[^1] This text might need some footnoting as well with a link to a website.[^2]`

`[^1]: Footnote 1 text.`  
`[^2]: [Footnote 2 link](http://www.zeraxxus.dk)`


- - -
### Tables

Good Food | Bad Food
--- | ---
Fruits | Candy
Carrots | Potato Chips
Beans | Meat

First Name | Last Name | Score
--- | --- | ---
Jane | Smith | 780
John | Smith | 640
Jack | Johnson | 540
Sue | Johnson | 350

```
Good Food | Bad Food
--- | ---
Fruits | Candy
Carrots | Potato Chips
Beans | Meat

First Name | Last Name | Score
--- | --- | ---
Jane | Smith | 780
John | Smith | 640
Jack | Johnson | 540
Sue | Johnson | 350
```