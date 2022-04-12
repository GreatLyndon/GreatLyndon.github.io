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

### Bold

```
**bold text**
```

### Italic

```
*italicized text*
```

### Blockquote

```
> blockquote
```

### Ordered List

```
1. First item
2. Second item
3. Third item
```

### unordered List

```
- First item
- Second item
- Third item
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
