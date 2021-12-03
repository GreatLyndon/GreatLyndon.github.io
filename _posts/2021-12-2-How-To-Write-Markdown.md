---
layout: post
title: How To Write Markdown
---

All things in this post come from:  [Markdown Guide](https://markdownguide.org)  

# What you will learn in this post?

The basic syntax and extended syntax of Markdown  

# What is Markdown?

Ummmm, good question, but I won't talk about thing like this here.  
If you want to know them, just click the link on the top of this post, thanks. :)  

So, right now, let just start!  

---

# Basic Syntax

---

## Heading

```
# Heading level 1

## Heading level 2

### Heading level 3

Heading level1
===

Heading level2
---
```
# Heading level 1

## Heading level 2

### Heading level 3

Heading level 1
===

Heading level 2
---

1. It has total 6 different sizes of the first kind of headings, 1 to 6, and 2 of the second kind.
2. You should also put blank lines before and after a heading for compatibility.

---

## Paragraphs

```
p1

p2
```

p1

p2

1. To create paragraphs, use a blank line to separate one or more lines of text.
2. Unless the paragraph is in a list, don’t indent paragraphs with spaces or tabs.

---

## Line Breaks

```
Before line breaks  
After line breaks
```

To create a line break, end a line with two or more spaces, and then type return.

---

## Bold

```
**bold text**

__bold text__

a**B**c
```

**bold text**  
__bold text__  
a**B**c  

 Markdown applications don’t agree on how to handle underscores in the middle of a word. For compatibility, use asterisks to bold the middle of a word for emphasis.

---

## Italic

```
*italicized text*

_italicized text_

a*B*c
```

*italicized text*  
_italicized text_  
a*B*c  

For compatibility, use asterisks to italicize the middle of a word for emphasis.

---

## Bold and Italic

```
This text is ***really important***

This text is ___really important___

This text is __*really important*__

This text is _**really important**_

This text is **_really important_**

a***B***c
```

This text is ***really important***  
This text is **_really important_**  
This text is *__really important__*  
This text is ___really important___  
This text is __*really important*__  
This text is _**really important**_  
a***B***c  

For compatibility, use asterisks to bold and italicize the middle of a word for emphasis.

---

## Blockquotes

```
> Dorothy followed her through many of the beautiful rooms in her castle.
```

> Dorothy followed her through many of the beautiful rooms in her castle.

---

## Nested Blockquotes

```
> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
```

> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

---

## Blockquotes with Other Elements

```
> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>  *Everything* is going according to **plan**.
```

> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>  *Everything* is going according to **plan**.

Blockquotes can contain other Markdown formatted elements. Not all elements can be used — you’ll need to experiment to see which ones work.  
For compatibility, put blank lines before and after blockquotes.  

---

## Ordered List

```
1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item
4. Fourth item
```

1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item
4. Fourth item

To create an ordered list, add line items with numbers followed by periods. The numbers don’t have to be in numerical order, but the list should start with the number one.  

---

## Unordered List

```
- First item
- Second item
- Third item
   * Indented item
   * Indented item
      + Deepest item
      + Deepest item
- Fourth item
- 1968\. A great year!
```

- First item
- Second item
- Third item
   * Indented item
   * Indented item
      + Deepest item
      + Deepest item
- Fourth item
- 1968\. A great year!

1. To create an unordered list, add dashes, asterisks, or plus signs in front of line items.
2. Indent one or more items to create a nested list.
3. If you need to start an unordered list item with a number followed by a period, you can use a backslash to escape the period.
4. For compatibility, don’t mix and match delimiters in the same list — pick one and stick with it.

---

## Adding Elements in Lists

### Paragraphs

To add another element in a list while preserving the continuity of the list, indent the element ***four spaces*** or one tab, as shown in the following examples.  

```
* This is the first list item.
* Here's the second list item.

    I need to add another paragraph below the second list item.

* And here's the third list item.
```

* This is the first list item.
* Here's the second list item.

    I need to add another paragraph below the second list item.

* And here's the third list item.

### Blockquotes

```
* This is the first list item.
* Here's the second list item.

    > A blockquote would look great below the second list item.

* And here's the third list item.
```

* This is the first list item.
* Here's the second list item.

    > A blockquote would look great below the second list item.

* And here's the third list item.

### Code Blocks

```
1. Open the file.
2. Find the following code block on line 21:

        <html>
          <head>
            <title>Test</title>
          </head>

3. Update the title to match the name of your website.
```

1. Open the file.
2. Find the following code block on line 21:

        <html>
          <head>
            <title>Test</title>
          </head>

3. Update the title to match the name of your website.

Code blocks are normally indented four spaces or one tab. When they’re in a list, indent them eight spaces or two tabs.  

### Images

```
1. Open the file containing the Linux mascot.
2. Marvel at its beauty.

    ![Tux, the Linux mascot](/assets/images/tux.png)

3. Close the file.
```

### Lists

```
1. First item
2. Second item
3. Third item
    - Indented item
    - Indented item
4. Fourth item
```

1. First item
2. Second item
3. Third item
    - Indented item
    - Indented item
4. Fourth item

---

## Code

```
`<p>Hellow world!</div>`
```

`<p>Hellow world!</div>`  

To denote a word or phrase as code, enclose it in backticks

### Escaping Backticks

```
``Use `code` in your Markdown file.``
```

``Use `code` in your Markdown file.``

If the word or phrase you want to denote as code includes one or more backticks, you can escape it by enclosing the word or phrase in double backticks  

### Code Blocks

__This is Markdown:__

```
    <html>
        <head>
        </head>
    </html>
```

__This is output:__

	<html>
	  <head>
	  </head>
	</html>

To create code blocks:  
- indent every line of the block by at least four spaces or one tab
- wrap your code blocks in triple backticks

# Horizontal Rules

```
***

---

_________
```

The rendered output of all three looks identical:  

***

1. To create a horizontal rule, use three or more asterisks, dashes, or underscores on a line by themselves
2. For compatibility, put blank lines before and after horizontal rules

---

## Links

### Adding Titles

```
[Google](https://www.google.com "You are hoving over Google!")
```

[Google](https://www.google.com "You are hoving over Google!")  

To add a title, enclose it in parentheses after the URL. This will appear as a tooltip when the user hovers over the link.  

### URLs and Email Addresses

```
<https://www.markdownguide.org>
<fake@example.com>
```

<https://www.markdownguide.org>  
<fake@example.com>  

To quickly turn a URL or email address into a link, enclose it in angle brackets  

### Formatting Links

```
I love supporting the **[EFF](https://eff.org)**.
This is the *[Markdown Guide](https://www.markdownguide.org)*.
See the section on [`code`](#code).
```

I love supporting the **[EFF](https://eff.org)**.  
This is the *[Markdown Guide](https://www.markdownguide.org)*.  
See the section on [`code`](#code).  

1. To emphasize links, add asterisks before and after the brackets and parentheses.
2. To denote links as code, add backticks in the brackets.

### Reference-style Links

Reference-style links are a special kind of link that make URLs easier to display and read in Markdown  
Reference-style links are constructed in two parts: the part you keep inline with your text and the part you store somewhere else in the file to keep the text easy to read  

#### Formatting the First Part of the Link

The first part of a reference-style link is formatted with two sets of brackets. The first set of brackets surrounds the text that should appear linked. The second set of brackets displays a label used to point to the link you’re storing elsewhere in your document.  

```
[hobbit-hole][1]
```

#### Formatting the Second Part of the Link

The second part of a reference-style link is formatted with the following attributes:  

1. The label, in brackets, followed immediately by a colon and at least one space
2. The URL for the link, which you can optionally enclose in angle brackets
3. The optional title for the link, which you can enclose in double quotes, single quotes, or parentheses

You can place this second part of the link anywhere in your Markdown document  

```
[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles"
```

#### An Example

```
In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
eat: it was a [hobbit-hole][1], and that means comfort.

[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"
```

In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
eat: it was a [hobbit-hole][1], and that means comfort.   

[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"  

### Caveat

Markdown applications don’t agree on how to handle spaces in the middle of a URL  
For compatibility, try to URL encode any spaces with %20  

## Image
