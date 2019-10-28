<!-- ---
title: Markdown Cheatsheet
author: Fania Raczinski
date: 2019-10-28
... -->

# Markdown Cheatsheet


## Text

```
# This is an <h1> tag
## This is an <h2> tag
###### This is an <h6> tag
```

*This text will be italic*  
_This will also be italic_  
**This text will be bold**  
__This will also be bold__  
*You **can** combine them*

```
*This text will be italic*  
_This will also be italic_  
**This text will be bold**  
__This will also be bold__  
*You **can** combine them*
```


As Grace Hopper said:
> I’ve always been more interested
> in the future than in the past.

```
As Grace Hopper said:  

> I’ve always been more interested
> in the future than in the past.
```


Strikethrough ~~text~~ here.

```
Strikethrough ~~text~~ here.
```


http://github.com - automatic!

[GitHub](http://github.com)

[CEMstudentexperience@dmu.ac.uk](mailto:CEMstudentexperience@dmu.ac.uk)

```
http://github.com - automatic!

[GitHub](http://github.com)

[CEMstudentexperience@dmu.ac.uk](mailto:CEMstudentexperience@dmu.ac.uk)
```


## Images

![DMU logo](imgs/DMU-Logo-768x329.png)

![cat](imgs/technokitten.jpg)

```
![alt](absolute url)
![alt](relative url)
```


## Tables

|                          |                                |
|:-------------------------|-------------------------------:|
| Module Name:             | **Multimedia III**             | 
| Module Code:             | **TECH3015**                   |
| Title of Assessment:     | **Coursework 1**               |
| This coursework item is: | **Summative / ~~Formative~~**  |

```
|                          |                                |
|:-------------------------|-------------------------------:|
| Module Name:             | **Multimedia III**             | 
| Module Code:             | **TECH3015**                   |
| Title of Assessment:     | **Coursework 1**               |
| This coursework item is: | **Summative / ~~Formative~~**  |
```

or

First Header     | Second Header
---------------- | -------------
Content cell 1   | Content cell 2
Content column 1 | Content column 2

```
First Header     | Second Header
---------------- | -------------
Content cell 1   | Content cell 2
Content column 1 | Content column 2
```


## Lists

- Item 1
- Item 2
  * Item 2a
  * Item 2b
- Item 3

```
- Item 1
- Item 2
  * Item 2a
  * Item 2b
- Item 3
```

1. Item 1
2. Item 2
3. Item 3
  - Item 3a
  - Item 3b
4. Item 4

```
1. Item 1
2. Item 2
3. Item 3
  * Item 3a
  * Item 3b
4. Item 4
```

- [x] this is a complete item
- [ ] this is an incomplete item
- [x] @mentions, #refs, [links](),
**formatting**, and <del>tags</del>
supported

```
- [x] this is a complete item
- [ ] this is an incomplete item
- [x] @mentions, #refs, [links](),
**formatting**, and <del>tags</del>
supported
```


## Multi Markdown


### Citations

This is a statement that should be attributed to
its source[p. 23][#Doe:2006].

And following is the description of the reference to be
used in the bibliography.

[#Doe:2006]: John Doe. *Some Big Fancy Book*.  Vanity Press, 2006.

```
This is a statement that should be attributed to
its source[p. 23][#Doe:2006].

And following is the description of the reference to be
used in the bibliography.

[#Doe:2006]: John Doe. *Some Big Fancy Book*.  Vanity Press, 2006.
```