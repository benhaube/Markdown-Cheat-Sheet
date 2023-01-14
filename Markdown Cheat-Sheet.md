# Heading 1
## Heading 2
### Heading 3
#### Heading 4 
##### Heading 5 
###### Heading 6

*italic text*
_italic text_

**bold text**
__bold text__

***bold and italic***
___bold and italic___

~~strike though text~~

>Block quote a group of text.
> 
> For a block quote with multiple paragrahps include a '>' on the blank line.
> > For nested code blocks use two '>>'.

## Links and Email Addresses

Insert a [link](https://www.google.com) and give it a name.
To turn a URL or email into a link without a name, enclose it in angle brackets.
	<https://www.google.com>
	<just-an@example.com>

Adding a link to a paragraph of text can make the text more difficult to read. There is a way to add a nested link to a paragraph while keeping the paragraph easy to read. Say I want to link to [Google][1] in a paragraph. This makes it much easier to read the contents of the paragraph because the URL is not getting in the way.

[1]: <https://www.google.com>

## Create an unordered list.
	* Item 1
	* Item 2
	* Item 3
		* Indented Item 1
		* Indented Item 2
	- Item 1
	- Item 2
	- Item 3
		- Indented Item 1
		- Indented Item 2
	+ Item 1
	+ Item 2
	+ Item 3
		+ Intented Item 1
		+ Indented Item 2

## Starting an unordered list with a number.
	* 1992\. A great Year!
	* I think 1993 was second best.

## Create and ordered list.
	1. Item 1
	2. Item 2
	3. Item 3
		1. Intented Item 1
		2. Indented Item 2
	4. Item 4 
o display a literal character that would otherwise be used to format text in a Markdown document, add a backslash (`\`) in front of the character.
## Code and Code Blocks 

Use `insert code here` to create a code block.

### To create a code block, indent every line of the block by at least 4 spaces or one tab

	<html>
		<head>
			<title
			</title>
		</head>

## Images

To add an image, add an exclamation mark (!), followed by alt text in brackets, and the path or URL to the image in parenteses. You can also add a title for the image in quotation marks after the URL or path to the image. 

![Tux, the Linux mascot.](/tux.png "Tux")

## Horizontal Rules
	To create a horizontal rule, use three or more asterisks (***), dashes (---), or underscores (___) on a line by themselves 

***
---
___
