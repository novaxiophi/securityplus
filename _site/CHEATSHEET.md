CHEATSHEET.md

# heading1 example
## heading2 example
### heading3 example
#### heading4 example
##### heading5 example
###### heading6 example

heading1
===
heading1
---
heading2
====
heading2
----

<h1>heading1</h1>
 <h2>heading2</h2>
 <h3>heading3</h3>
 <h4>heading4</h4>
 <h5>heading5</h5>
 <h6>heading6</h6>
 
 # heading

heading1
=====

heading2
=====

heading2
----

How to display markdown heading HTML text content
Sometimes, Documentation needs to include HTML tags contained in the headings tag.

<div> test content</div>
As per the above, an h3 tag contains a div tag. The HTML content needs to replace with encoding characters in the heading tag with markdown syntax.

### &lt;div&gt; test content &lt;div&gt;
How do you add a heading in Markdown?
There are three ways to create a heading in markdown

using hash # sign One way is to add hash # sign before heading string. hash sign count represents the subheading.
# heading1
## heading2
and so on
use equal or hyphen symbol another way is to add minimum three equal or hyphen symbols

heading1
===
heading1
---
and so on

use direct html heading tags Since markdown is parsed to html, so we can also use direct html heading tags such as h1,h2

<h1>heading1</h1>
How many headings are in a Markdown?
There are six type of heading tags in markdown, It specify count of hash symbols represents heading level. Generated html heading tags are h1,h2,h3,h4,h5,h5.


How do you add a subheading in Markdown?
Markdown heading tags are represented with hash symbol. For example, # with string represents heading tag(h1) and ‘##’ with string represents subheading tag(h2) hash symbol count represents sub heading tags

It uses two different syntaxes to create a header tag.

Structure enhanced text - setext syntax
structure true text - atx syntax
setext header styles syntax
setext syntax contains he

Heading Type	Rendered HTML	displayed on the browser

Heading one
==========

```HTML


Heading one

```| Heading one| | | |
```
# End

# Images

![alt text](image url "image Title")
<img src="image url" alt="alt text" title="image Title" />

How to add an image with a link
create an image with an anchor link like combining both images inline and inline links

 [![image alt text](image URL link)](anchor link)
[![image alt text](image url link)](anchor link)

It generates and displays an image.


<img src="image url" alt="alt text" title="image Title" width="150"/>


<img src="image url" alt="alt text" title="image Title" height="150"/>

# lists

* item 1
* Item 2
- Item 3
- Item 4
+ item 5
+ item 5

<ul>
    <li>item 1</li>
    <li>Item 2</li>
</ul>
<ul>
    <li>Item 3</li>
    <li>Item 4</li>
</ul>
<ul>
    <li>Item 5</li>
    <li>Item 6</li>
</ul>

1. Ordered list element one
2. Ordered list element two

<ol>
    <li>Ordered list element one</li>
    <li>Ordered list element two</li>
</ol>

# tables

|Header1 |Header2  | Header3|
--- | --- | ---|
|data1|data2|data3|
|data11|data12|data13|

<table>
   <thead>
      <tr>
         <th>Header1</th>
         <th>Header2</th>
         <th>Header3</th>
      </tr>
   </thead>
   <tbody>
      <tr>
         <td>data1</td>
         <td>data2</td>
         <td>data3</td>
      </tr>
      <tr>
         <td>data11</td>
         <td>data12</td>
         <td>data13</td>
      </tr>
   </tbody>
</table>

|Header1 |Header2  | Header3|
|--- | --- | ---|
|**bold style**| `code block`|data3|
|\|escape pipe|\`backtick|data13|


|Header1 |Header2  | Header3|
|:--- | ---: | :---:|
|Align left| Align right|center text|
|cell data1|cell data2|cell data3|

Markdown - Styles
This tutorial covers adding styles such as color font-weight and font-size to Markdown text content examples. It convers syntax and examples for plain html and CSS selector syntax..

Sometimes, Markdown content requires adding styles such as CSS attributes like color and font sizes, and weight attributes.

However, Natively Markdown does not support CSS styles, the same also does not work in the readme.md files in Github or any markdown parsers.

There are multiple ways to achieve this.


Then, How to apply the color text to markdown content?

How to Change Font, Foreground and ...

Pause

Unmute
Remaining Time -2:47


Fullscreen
How to Change Font, Foreground and Background Color in Notepad++
Markdown color styles content
color adds to markdown content in two ways

use inline HTML in markdown for styles
Since Markdown converted to HTML code. Most of the markdown parsers support HTML code.

So, Write inline HTML code in markdown content. Added span tag with inline styles for changing color, font-weight, and font size.


Below html coded added to markdown files(.md extension)

<span style="color:green;font-weight:700;font-size:20px">
    markdown color font styles
</span>
And output you can see on the browser is below.


markdown color font styles

Generated Output

<span style="color:green;font-weight:700;font-size:20px"> 
markdown color font styles
</span>
use CSS styles in markdown content
Another way using define CSS styles

Define CSS styles using selector as seen below
add content inside selector tags
<style>
red { color: red }
yellow { color: yellow }
</style>

<red> red color markdown text</red>
<yellow> red color markdown text</yellow>
Generated html


<p><red> red color markdown text</red>
<yellow> red color markdown text</yellow></p>
You can see the content styled in the browser as

red color markdown text red color markdown text

My Bold Text, in red color.{: style=“color: red; opacity: 0.80;” }

The above two ways work with almost all markdown parsers.

However, there are other ways we can do with different syntax with markdown content in Kramdown and Jekyll.