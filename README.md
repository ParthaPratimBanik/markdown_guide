# Contents:
* [Markdown Cheatsheet](#markdown-cheatsheet)
* [Markdown Basics (Github Docs)](#markdown-basics-github-docs)
* [Styling Text](#styling-text)
  - [Center](#center)
  - [Color](#color)
* [Styling Image](#styling-image)
  - [Center](#center-1)
* [Section or Content Link / Table of Contents](#section-or-content-link--table-of-contents)
## Markdown Cheatsheet
---
[Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

## Markdown Basics (Github Docs)
---
* [Basic formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
* [Organizing information with tables](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/organizing-information-with-tables)
* [Collapsed Section](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/organizing-information-with-collapsed-sections)
* [Creating and highlighting code blocks](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-and-highlighting-code-blocks)
* [Creating diagrams](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-diagrams)
* <u><b>[Writing Equation (Mathematical Expressions)](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)</b></u>
* [Autolinked References and URLs](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/autolinked-references-and-urls)
* [Attaching Files](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/attaching-files)
* [Creating a Permanent Link to Code Snippet](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-a-permanent-link-to-a-code-snippet)

## Styling Text:
---
### **Center**
* HTML/CSS style (inline style)
```
<p style="text-align: center;">text_content</p>
```
> <p style="text-align: center;">text_content</p>
* Github Flavoured
```
<p align="center">text_content</p>
```
> <p align="center">text_content</p>
```
<center>text_content</center>
```
> <center>text_content</center>

### **Color**
```
<span style="color:blue">some *blue* text</span>
```
> <span style="color:blue">some *blue* text</span>

## Styling Image
---
### Center
* HTML style
```
<p align="center">
    <img src="images/markdown.jpg" 
        alt="markdown image"
        width="720" 
        height="360" 
        style="display: block; margin: 0 auto"
      />
/p>
```
> <p align="center"> <img src="images/markdown.jpg" alt="markdown image" width="540" height="360" style="display: block; margin: 0 auto"/>


## Section or Content Link / Table of Contents
---
```
[Chapter-1](#chapter-1)
[Chapter-2](#chapter-2)
[Chapter-3](#chapter-3)
```

>[Chapter-1](#chapter-1)\
>[Chapter-2](#chapter-2)\
>[Chapter-3](#chapter-3)
>## Chapter-1
>.......... _text content of chapter 1_ .............
>## Chapter-2
>.......... _text content of chapter 2_ .............
>## Chapter-3
>.......... _text content of chapter 3_ .............