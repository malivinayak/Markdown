<h1>Markdown</h1>
Markdown is an easy-to-read, easy-to-write language for formatting plain text. You can use Markdown syntax, along with some additional HTML tags, to format your writing on GitHub, in places like repository READMEs and comments on pull requests and issues.

<h2>Table of Contents</h2>

- [Badge](#badge)
- [Checkbox](#checkbox)
- [Emoji](#emoji)
- [Foldable Text](#foldable-text)
- [Footnotes or References](#footnotes-references)
- [Heading](#heading)
- [Link](#link)
  - [Link to specific part of page](#link-to-specific-part-of-page)
  - [Link to file in same repository](#link-to-file-in-same-repository)
  - [Link to other url](#link-to-other-url)
- [List](#list)
- [Math in Markdown](#math-in-markdown)
- [Nested Block](#nested-block)
- [References](#footnotes-references)
- [Text Style](#text-style)
- [Table](#table)

<!-- --------------------------------------------------------------------- -->
## Badge

<!-- --------------------------------------------------------------------- -->
## Checkbox

<table>

<tr>

* Simple Checkbox
</tr>

<tr>
<td align="center"> Markup Code</td> 
<td align="center"> Result </td>
</tr>

<tr>
<td> 

```markup
- [x] A completed task
- [ ] An uncompleted task
```

</td>

<td>

- [x] A completed task
- [ ] An uncompleted task

</td>
</tr>

</table>


<table>

<tr>

* Nested Checkbox
</tr>

<tr>
<td align="center"> Markup Code</td> 
<td align="center"> Result </td>
</tr>

<tr>
<td> 

```markup
- [ ] An uncompleted task
  - [ ] A subtask
```

</td>

<td>

- [ ] An uncompleted task
  - [ ] A subtask

</td>
</tr>

</table>

<!-- --------------------------------------------------------------------- -->
## Emoji
* [Reference Link](https://www.webfx.com/tools/emoji-cheat-sheet/)

<!-- --------------------------------------------------------------------- -->
## Foldable Text

<!-- --------------------------------------------------------------------- -->
## Footnotes References
 A marker in the text that will become a superscript number; a footnote definition that will be placed in a list of footnotes at the end of the document. A footnote looks like this:

<table>

<tr>
</tr>

<tr>
<td align="center"> <b>Markup Code</b> </td> 
<td align="center"> <b>Result</b> </td>
</tr>

<tr>
<td> 

```markup
This is a footnote.[^1]

[^1]: the footnote text.
```
</td>

<td>

This is a footnote.[^1]

[^1]: the footnote text.

</td>
</tr>

</table>

Note: The `the footnote text.` will be appear at end of the file

<!-- --------------------------------------------------------------------- -->
## Heading

<table>

<tr></tr>

<tr>
<td align="center"> Markup Code  &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp; </td> 
<td align="center"> Result  &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp; </td>
</tr>

<!-- Heading 1 Source Code -->
<tr>
<td> 

```markup
# Heading 1 
```
```markup
Heading 1 
==========
```

</td>

<td>

# Heading 1

</td>
</tr>

<tr></tr>

<!-- Heading 2 Source Code -->
<tr>
<td> 

```markup
## Heading 2 
```
```markup
Heading 2 
-----------
```

</td>

<td>

Heading 2
----------
</td>
</tr>

<tr></tr>

<!-- Heading 3 Source Code -->
<tr>
<td> 

```markup
### Heading 3 
```
</td>

<td>

### Heading 3 
</td>
</tr>

<tr></tr>

<!-- Heading 4 Source Code -->
<tr>
<td> 

```markup
#### Heading 4 
```
</td>

<td>

#### Heading 4
</td>
</tr>

</table>

<!-- --------------------------------------------------------------------- -->
## Link

### Link to specific part of page

### Link to file in same repository

### Link to other url

<!-- --------------------------------------------------------------------- -->
## List

1. An unordered list can be created by preceding one or more lines of text with a hyphen (-), an asterisk (*), or a plus sign (+).
1. An ordered list can be created using numbers (1., 2., 3., and so on) or letters (a., b., c., and so on) followed by a period.
    - You can use `1` for each list item, and the numbers will be automatically generated for you
1. To create a nested list, indent the line(s) with a tab or four white spaces.
1. To create a task list, begin list items with a hyphen and a space, followed by [ ]. To mark a task as complete, use [x].

<table>

<tr></tr>
<tr>
<td align="center"> <b>Markup Code</b> </td> 
<td align="center"> <b>Result</b> </td>
</tr>

<tr>
<td> 

<b>An unordered list<b>
```md
- item 1
- item 2
- item 3
```
</td>

<td>

- item 1
- item 2
- item 3

</td>
</tr>

<tr></tr>
<tr>
<td> 

<b>An ordered list<b>
```md
1. item 1
1. item 2
1. item 3
```
</td>

<td>

1. item 1
1. item 2
1. item 3

</td>
</tr>

<tr></tr>
<tr>
<td> 

<b>Nested list<b>
```md
1. First list item
   - First nested list item
     - Second nested list item
```
</td>

<td>

1. First list item
   - First nested list item
     - Second nested list item

</td>

<tr></tr>
<tr>
<td> 

<b>Task list<b>
```md
- [x] Task 1 Completed 
- [ ] Task 2
  - [ ] Sub-task for Task 2
- [ ] Task 3
```
</td>

<td>

- [x] Task 1 Completed 
- [ ] Task 2
  - [ ] Sub-task for Task 2
- [ ] Task 3

</td>
</tr>
</tr>
</table>

<!-- --------------------------------------------------------------------- -->
## Math in Markdown

<table>

<tr></tr>
<tr>
<td align="center"> <b>Markup Code</b> </td> 
<td align="center"> <b>Result</b> </td>
</tr>

<tr>
<td> 

Fraction like `4/5`
```html
<sup>4</sup>&frasl;<sub>5</sub>
```
</td>

<td>

<sup>4</sup>&frasl;<sub>5</sub>
</td>
</tr>

<tr></tr>
<tr>
<td> 

Not Equal to
```html
$a \ne 0$
$a \ne b$
```
</td>

<td>

$a \ne 0$

$a \ne b$
</td>
</tr>

<tr></tr>
<tr>
<td> 

```html
$(ax^2 + bx + c = 0)$
```
</td>

<td>

$(ax^2 + bx + c = 0)$
</td>
</tr>
</table>

<!-- --------------------------------------------------------------------- -->
## Nested Block

<!-- --------------------------------------------------------------------- -->
## Text Style

<table>

<tr>
<td align="center"> <h3>Markup Code</h3> </td> 
<td align="center"> <h3>Style</h3> </td>
</tr>

<tr>
<td> 

```markup
Common text
```
</td>
<td>

Common text
</td>
</tr>

<tr>
<td> 

```markup
_Emphasized text_
```
```markup
*Emphasized text*
```
</td>
<td>

_Emphasized text_
</td>
</tr>

<tr>
<td> 

```markup
~~Strikethrough text~~
```
</td>
<td>

~~Strikethrough text~~
</td>
</tr>

<tr>
<td> 

```markup
__Strong text__
```
```markup
**Strong text**
```
</td>
<td>

__Strong/Bold text__
</td>
</tr>

<tr>
<td> 

```markup
___Strong emphasized text___
```
```markup
***Strong emphasized text***
```
</td>
<td>

___Strong emphasized text___
</td>
</tr>

<tr>
<td> 

````markup
```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
````

</td>
<td>

```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
</td>
</tr>

<tr>
<td> 

```html
<p align="left"> Center Alligned Text </p>
<p align="center"> Center Alligned Text </p>
<p align="right"> Center Alligned Text </p>
```
</td>
<td>

* <p align="left"> Center Alligned Text </p>
* <p align="center"> Center Alligned Text </p>
* <p align="right"> Center Alligned Text </p>
</td>
</tr>

</table>

<!-- --------------------------------------------------------------------- -->
## Table

<table>

<tr></tr>

<tr>
<td align="center"> Markup Code to create Table</td> 
<td align="center"> Result </td>
</tr>

<!-- Format 1 -->
<tr>
<td> 

```markup
First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell
```

</td>

<td>

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

</td>
</tr>

<tr></tr>
<!-- Format 2 -->
 
<tr>
<td> 

```markup
Left Header | Right Header | Center Header
| :--- | ---: | :---:
Content Cell  | Content Cell | Content Cell
Content Cell  | Content Cell | Content Cell
```

</td>

<td>

Left Header | Right Header | Center Header
| :--- | ---: | :---:
Content Cell  | Content Cell | Content Cell
Content Cell  | Content Cell | Content Cell

</td>
</tr>

<tr></tr>
<!-- Format 3 -->
<tr>
<td>

<p align='center'>Using HTML Syntax</p>

```html
<table>
  <tr>
    <td align="center"> <b>Column 1 Heading</b> </td> 
    <td align="center"> <b>Column 2 Heading</b> </td>
  </tr>

  <tr>
    <td> Colmn 1 Row 1 </td>
    <td> Colmn 2 Row 1 </td>
  </tr>

  <tr>
    <td> Colmn 1 Row 2 </td>
    <td> Colmn 2 Row 2 </td>
  </tr>
</table>
```
</td>

<td>
<table>
  <tr>
    <td align="center"> <b>Column 1 Heading</b> </td> 
    <td align="center"> <b>Column 2 Heading</b> </td>
  </tr>

  <tr>
    <td> Colmn 1 Row 1 </td>
    <td> Colmn 2 Row 1 </td>
  </tr>

  <tr>
    <td> Colmn 1 Row 2 </td>
    <td> Colmn 2 Row 2 </td>
  </tr>
</table>
</td>
</tr>
</table>

<!-- --------------------------------------------------------------------- -->
## License

| | |
| ---- | ------------------------------------ |
| <p align="center"> <img src="https://user-images.githubusercontent.com/66154908/175827109-a9f2f54a-f63e-4e07-bd83-a1f760246b56.png" width="80%"></img> | ![](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square) <br> This project is licensed under MIT License (c) 2022 Vinayak Mali, Inc. For more information, read the [LICENSE](./LICENCE) file.  <img width=2300/> |
   

