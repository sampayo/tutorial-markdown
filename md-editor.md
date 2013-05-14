# Markdown tutorial with HTML code and syntax examples

[Markdown](http://daringfireball.net/projects/markdown/) helps you to write simple, fast documentation or blog posts.  
It is not replacing all HTML tags nor HTML itself but it helps to make writing for web so much faster !

**Following tutorial has this format:**

1. description
2. Markdown syntax
3. HTML code
4. HTML result as shown in browser


## Heading:

Markdown

	# Heading 1
	## Heading 2
	### Heading 3
	#### Heading 4
	##### Heading 5
	###### Heading 6

HTML

	<h1>Heading 1</h1>
	<h2>Heading 2</h2>
	<h3>Heading 3</h3>
	<h4>Heading 4</h4>
	<h5>Heading 5</h5>
	<h6>Heading 6</h6>

Result

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6



## Paragraph:
Markdown
	
	Any text on new separate line forms a paragraph.

	It is really easy !

HTML

	<p>Any text on new separate line forms a paragraph.</p>
	<p>It is really easy !</p>

Result

	Any text on new separate line forms a paragraph.
	It is really easy !

## Line breaks

When you do want to insert a `<br />` break tag using Markdown, you end a line with two or more spaces, then type return.

## Bold text:

You can use: asterisks and underscores `* and _`

Markdown

	**This is bold text**

HTML

	<strong>This is bold text</strong>

Result

**This is bold text**

## Emphasis:

You can use: asterisks and underscores `* and _`

Markdown

	*This is emphasis text.*

HTML

	<em>This is emphasis text.</em>

Result

*This is emphasis text.*

## Unordered list

You can use: asterisks, pluses, and hyphens (*, +, and -).

Markdown

	* A
	* B
	* C

HTML

	<ul>
		<li>A</li>
		<li>B</li>
		<li>C</li>
	</ul>


Result

* A
* B
* C

## Ordered list

You can use: number with `DOT .` at the end + actual text.

Markdown

	1. A
	2. B
	3. C

HTML

	<ol>
		<li>A</li>
		<li>B</li>
		<li>C</li>
	</ol>

Result

1. A
2. B
3. C

> And this is blockquote. Fonts, color schemes, layouts and stylesheets are all 100% customizable so you can turn MarkdownPad into your perfect editor.


## Links

Links are super easy too. Bear in mind this syntax `[TEXT OF LINK](ACTUAL HYPERLINK "TITLE IS OPTIONAL")`  
Look at examples below.

Markdown

	[Daring Fireball](http://daringfireball.net/projects/markdown/)
	[Daring Fireball](http://daringfireball.net/projects/markdown/ "Markdown syntax")

HTML

	<a href="http://daringfireball.net/projects/markdown/">Markdown project</a>
	<a href="http://daringfireball.net/projects/markdown/" title="Markdown syntax !">Markdown link with title</a>

Result

[Markdown project](http://daringfireball.net/projects/markdown/)  
[Markdown link with title](http://daringfireball.net/projects/markdown/ "Markdown syntax !")	

## Automatic links

Are you feeling lazy or like to be super fast ? Then use `angle brackets < >` to generate automatic links !  
Your link will be used and turned into a clickable text.

Markdown

	<http://daringfireball.net/projects/markdown/>

HTML

	<a href="http://daringfireball.net/projects/markdown/">http://daringfireball.net/projects/markdown/</a>

Result

<http://daringfireball.net/projects/markdown/>

## Image:

Syntax is similar to links above.

`![alt text](http://www.w3.org/html/logo/badge/html5-badge-h-solo.png "title")`

![alt text](http://www.w3.org/html/logo/badge/html5-badge-h-solo.png "Link")

## Code

You can display code by wrapping it in **grave accent** = HTML Entity Code: `&#96;` = ASCII Character: &#96;



Markdown

&#96;alert("Hi there");&#96;

HTML

	<code>alert("Hi there");</code>

Result

This is some text with code ... `alert("Hi there");` ... and some text at the end.

## Blockquotes

So you have some text you want to quote and put in a block ? No problem.

Markdown

	> Lorem ipsum

HTML

	<blockquote>Lorem ipsum</blockquote>

Result

> Lorem ipsum

## Backslash escapes

In order to escape special characters use `backslash \` to generate literal characters.  
Following characters otherwise have special meaning in Markdown syntax:

	\   backslash
	`   backtick
	*   asterisk
	_   underscore
	{}  curly braces
	[]  square brackets
	()  parentheses
	#   hash mark
	+   plus sign
	-   minus sign (hyphen)
	.   dot
	!   exclamation mark

## Horizontal rules

You can create horizontal rule tag `<hr />` by typing three asterisks on a line.

Markdown

	***

HTML

	<hr />

Result
***

### How to run and display Markdown

Running Markdown in your browser is a bit tricky but there is help !

1. Chrome extension: [Markdown Preview](https://chrome.google.com/webstore/detail/markdown-preview/jmchmkecamhbiokiopfpnfgbidieafmd)
2. Editor for **Windows**: [MarkdownPad](http://markdownpad.com/)
3. Editor for **Mac**: [Mou](http://mouapp.com/)

### Summary

This was basic tutorial, hope it helped you. If you want all the details and info use links below.  
Thank you **John Gruber**:

1. <http://daringfireball.net/projects/markdown/basics>
2. <http://daringfireball.net/projects/markdown/syntax>