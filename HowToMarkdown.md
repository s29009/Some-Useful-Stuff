# How To Markdown 
### This explains in simple terms how to write simple markdown files, so that our documentation can be easily accessible within github repository.
## Contents
- [Headers](#headers)
- [New Lines](#new-lines)
- [Bold and Italics](#bold-and-italics)
- [Lists](#lists)
  - [Unordered Lists](#unordered-lists)
  - [Ordered Lists](#ordered-lists)
- [Links](#links)
  - [Simple Links](#simple-links)
  - [Images](#images)
- [Codeblocks](#codeblocks)
- [Blockquotes](#blockquotes)
- [Horizontal Rules](#horizontal-rules)
- [More Information](#more-information)

## Headers
To write headers you use "#"
The more #s you use the smaller the header.
For example, "How To Markdown" at the top of this file uses one #, whereas the "Headers" subheader uses two.

## New Lines
To add a new line, simply use html breakline character: \<br>.

## Bold and Italics
To use bold and italics you use "*" <br>
\*\*Hi\*\* is bold (**Hi**) <br>
\*Hi\* is in italics (*Hi*)

## Lists
For both lists, when you want to go into a sublist/nested list (whatever you want to call it), you simply use an indentation. <br>
It will look as follows: <br>
- Item1
- Item2
  - SubItem2a
  - SubItem2b
- Item3

**After** the list you want to add an **empty line** in the markdown file or else the text that follows will be added to the last point of the list <br>
(literally just press enter twice, not \<br>).
If you want multiple lines for a point in the list, you can use the breakline character, and it will look like this: <br>
- Item1
- Item2 <br> More Item2
- Item3

### Unordered Lists
To make a list you use "-"
It is important to add a space after the - or it will not work.
This text: <br>
\- Item1 <br>
\- Item2 <br>
\- Item3 <br><br>
Will look like this:
- Item1
- Item2
- Item3

If you want your unordered list to start with a number simply use a backslash ("\") before the fullstop, <br>
Like this: <br>
\- 123\.

### Ordered Lists
If you want to make list that is ordered you use numbers like this: <br>
\1. Item1 <br>
\2. Item2 <br>
\3. Item3 <br><br>
And it will look like this:
1. Item1
2. Item2
3. Item3

For ordered lists you don't have to use ascending numbers (1, 2, 3) as it will be auto generated. <br>
\1. Item1 <br>
\2. Item2 <br>
\3. Item3 <br><br>

\1. Item1 <br>
\1. Item2 <br>
\1. Item3 <br><br>

Will look the same. (When using github to edit the numbers are automatically ascending when you type, so it doesn't matter)

## Links

### Simple Links
To add a simple link to the markdown file you use square and normal brackets as follows:<br>
\[Text to show in markdown file]\(link to go to)
### Images
To insert an image into a markdown file you need to have host it somewhere first. For this purpose there will be an images folder made in the documentation folder. 
After you have hosted it copy the link to it (I suggest the permalink as it won't change) and then use the standard link template, but with an exclamation mark in front. <br>
Like this: <br>
!\[image name]\(image link)

## Codeblocks
Codeblocks work by using the backtick (" \` ") symbol. <br>
You should add it before and after the codeblock, like this: <br>
\` code goes here \` <br>
and it will look like this: <br>
`code goes here`

If for some reason your code contains backticks, you can use two of them to still have backticks in your code: <br>
\`\` code \`goes\` here\`\`
and this will look as follows: <br>
`` code `goes` here ``

## Blockquotes
Blockquotes look like this: <br>
> Hi

To make one simply use the ">" character like in a list. It should look like this: <br>
\> This is a block quote.
You can also stack block quotes onto each other: <br>
> Quote a
> Quote b
> > Quote c

> Quote d

This is done by adding another > after the first one (" > > "). <br>
It is important that you add an empty line after a blockquote (in the markdown itself, not a \<br>) or the next lines will also be in the blockquote (same as in lists).
Also similarly to lists, the breakline works in blockquotes.

## Horizontal Rules
Horizontal rules can be used to split up text. There are three rules you can use: <br>
\***  (asterisks)<br>
\--- (dashes)<br>
\___ (underscores)<br>
For each of the rules you need 3 of the above characters.<br>
The rules look like the following:<br><br>
asterisks

***

asterisks
<br><br>
dashes

---

dashes
<br><br>
underscores

___

underscores<br><br>

If you do not use an empty line (like when ending a list) then instead of a horizontal rule, you will end up with a heading.

## More Information
For more information on markdown look at markdown guide: <br>
[Markdown Guide](https://www.markdownguide.org/)<br>
All the things from "Basic Synax" are already here, but "Extended Syntax" are not, so if there is something you need that isn't here, it probably is there.