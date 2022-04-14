---
layout: post
title: "Markdwon Guide"
---

## Why I Post This

I have learned **Markdown language** for writing my blog on Github Pages, yes, which one you are reading right now! That's why I should post one page for Markdown guide.  
At first sight, I was amazed by this cool language, and then I thought I should learn it and write my own technical blog with it. Though it's token really long time to begin LOL.  
Anyway, we can start the main content from now.  
> All the techniques are from [Markdown Guide](https://markdownguide.org)  

-----

## Basic Syntax

### Heading

To create a heading, you have two ways:
1. Add number signs(#) in front of a word of phrase
2. Add == characters for heading level 1 or -- characters for heading level 2

```
# H1
## H2
### H3
```

```
H1
===
H2
---
```

For compatibility, you should know:
1. put a space between the number signs and the heading name
2. put blank lines before and after a heading

### Paragrap

To create paragraphs, use a blank line to separate one or more lines of text.

```
p1

p2
```

Unless the paragraph is in a list, don't indent paragraphs with spaces or tabs.

> If you need to indent paragraphs in the output, see the section on how to indent(tab).

To create a line break or new line(like HTML br tag), end a line with two or more spaces, and then type return.

```
This is the first line.  
And this is the second line.
```

### Emphasis

#### Bold

To bold text, add two asterisks or underscores before and after a word or phrase.

```
**bold text**
__bold text__
```

Markdown applications don’t agree on how to handle underscores in the middle of a word. Use asterisks to bold the middle of a word for emphasis.

Love**is**bold

```
Love**is**bold
```

#### Italic

To italicize text, add one asterisk or underscore before and after a word or phrase.  
To italicize the middle of a word for emphasis, add one asterisk without spaces around the letters like bold above.

A*cat*meow

```
*italicized text*
_italicized text_
A*cat*meow
```

#### Bold and Italic

To emphasize text with bold and italics at the same time, add three asterisks or underscores before and after a word or phrase.  
To bold and italicize the middle of a word for emphasis, add three asterisks without spaces around the letters.

***bold and italic***  
___bold and italic___  
bold***and***italic

```
***bold and italic***
___bold and italic___
bold***and***italic
```

### Blockquotes

To create a blockquote, add a > in front of a paragraph.  
For compatibility, put blank lines before and after blockquotes.

> blockquote

```
> blockquote
```

#### Blockquotes with Multiple Paragraphs

To create multiple paragraphs in blockquotes, add a > on the blank lines between the paragraphs.

> First paragraph
>
> Second paragraph

```
> First paragraph
>
> Second paragraph
```

#### Nested Blockquotes

Blockquotes can be nested.

> outter blockquote
>
>> Inner blockquote

```
> outter blockquote
>
>> Inner blockquote
```

#### Blockquotes with Other Elements

Blockquotes can contain other Markdown formatted elements.  
But **not all elements** can be used -- you'll need to experiment to see which ones work.

> ### Heading level 3 in blockquote
>
> - item 1
> - item 2

```
> ### Heading level 3 in blockquote
>
> - item 1
> - item 2
```

### Lists

#### Ordered List

To create an ordered list, add line items with numbers followed by periods. The numbers don't have to be in numerical order, but **the list sould start with the number one**.

1. First item
2. Second item
3. Third item

```
1. First item
2. Second item
3. Third item
```

#### unordered List

To create an unordered list, add dashes (-), asterisks (*), or plus signs (+) in front of line items. Indent one or more items to create a nested list.  
For compatibility, don’t mix and match delimiters in the same list — pick one and stick with it.

- First item
- Second item
- Third item
	- Indented item

```
- First item
- Second item
- Third item
	- Indented item
```

If you need to start an unordered list item with a number followed by a period, you can use a backslash (\) to escape the period.

- 1968\. A great year!

```
- 1968\. A great year!
```

#### Adding Elements in Lists

To add another element in a list while preserving the continuity of the list, indent the element four spaces or one tab.

- This is the first list item

    This is the paragraph element

- This is the second list item

```
- This is the first list item

    This is the paragraph element

- This is the second list item
```

Code blocks are normally indented four spaces or one tab. When they’re in a list, indent them eight spaces or two tabs.

1. list item 1

        <html>
            <head>
                <title>Title</title>
            </head>
        </html>

2. list item 2

```
1. list item 1

        <html>
            <head>
                <title>Title</title>
            </head>
        </html>

2. list item 2
```

### Code

```
`code`
```

### Horizontal Rule

```
---
```

### Link

```
[title](https://www.example.com)
```

### Image

```
![alt text](image.jpg)
```

## Extended Syntax

### Table

```
| Syntax | Description |
| ------ | ----------- |
| Header | Title |
|Paragraph| Text |
```

| Title | Description |
| --- | --- |
| item1 | m1 |
| item2 | m2 and ok |

### Fenced Code Block

While using code, you use a pair of backticks. As to code block, you should use triple pair of backticks.  

~~~
```
code in code block
```
~~~

### Footnote

Here's a sentence with a footnote. [^1]

```
Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.
```

[^1]: This is the footnote.

### Heading ID

### My Great Heading {#custom-id}

```
### My Great Heading {#custom-id}
```

### Definition List

```
term
: definition
```

### Strikethrough

The Result looks ~~like this~~.

```
The Result looks ~~like this~~.
```

### Task List

- [x] Be happy everday
- [ ] Kepp working out
- [ ] Finish Markdown Guide

```
- [x] Be happy everday
- [ ] Kepp working out
- [ ] Finish Markdown Guide
```

### Emoji

There are two ways to add emoji to Markdown files:
1. copy and paste the emoji into your Markdown-formatted text.
2. type emoji shortcodes.

#### Copyong and Pasting Emoji

In most cases, you can simply copy an emoji from a source like [Emojipedia](https://emojipedia.org) and paste it into your document.

> If you're using a static site generator, make sure you [encode HTML pages as UFT-8.](https://www.w3.org/International/tutorials/tutorial-char-enc/)

I am very happy here because I can copy and paste emoji here. 😃   

#### Using Emoji Shortcodes

**Some Markdown applications** allow you to insert emoji.  
Sorry, Jekyll's Markdown processor doesn't support emoji shortcodes, so I can't show you any example here. 😥(This sad face is pasted here!)

```
That is so funny! :joy:
```

### Highlight

**Some Markdown processors** allow you to highlight text.  
Alternatively, if your Markdown application supports HTML, you can use the **mark** HTML tag.   

I need to hightlight these <mark>very important words</mark>.

```
I need to hightlight these ==very important words==.
I need to hightlight these <mark>very important words</mark>.
```

### Subscript

**Some Markdown processors** allow you to use subscript.  
Alternatively, if your Markdown application supports HTML, you can use the **sub** HTML tag.   

H<sub>2</sub>O

```
H~2~O
H<sub>2</sub>O
```

### Superscript

**Some Markdown processors** allow you to use superscript.  
Alternatively, if your Markdown application supports HTML, you can use the **sup** HTML tag.  

x<sup>2</sup>

```
x^2^
x<sup>2</sup>
```

