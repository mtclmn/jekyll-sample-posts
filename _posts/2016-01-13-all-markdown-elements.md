---
layout: post
title:  "All Markdown Elements"
date:   2016-01-13 08:20:18 -0400
categories: jekyll testing markdown
---

# Markdown Test

Here are a bunch of Markdown elements altogether on one page! Use it to style your own elements.

## Overview

Completely **synergize** resource taxing relationships via premier *niche markets*. Professionally cultivate one-to-one customer service with robust ideas. Dynamically innovate resource-leveling customer service for state of the art customer service.

## Syntax

#### Strong and Emphasize

**strong** or __strong__

*emphasize* or _emphasize_

**Sometimes I want a lot of text to be bold.
Like, seriously, a _LOT_ of text**

## Blockquotes

> Right angle brackets &gt; are used for block quotes.

## Links and Email

An email <example@example.com> link.

Simple inline link <https://google.com>, another inline link [Acme Link Co](http://google.com), one more inline link with title [Generic Link Place](http://google.com "a title goes here").

A [reference style][id] link. Input id, then anywhere in the doc, define the link with corresponding id:

[id]: http://google.com "A reference link to Google"

Titles ( or called tool tips ) in the links are optional.

## Images

![Image FPO](/assets/fpo.jpg)

## Code

{% highlight ruby %}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}

{% highlight ruby linenos %}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}

#### Fenced Code Blocks

Start with a line containing 3 or more backticks, and ends with the first line with the same number of backticks:

```
Fenced code blocks are like Stardard Markdown’s regular code
blocks, except that they’re not indented and instead rely on
a start and end fence lines to delimit the code block.
```

## Lists

###  Ordered Lists

1. Ordered list item
2. Ordered list item
3. Ordered list item

### Unordered Lists

* Unordered list item
* Unordered list item
* Unordered list item

- Unordered list item
- Unordered list item
- Unordered list item

#### Hard Linebreak

End a line with two or more spaces will create a hard linebreak, called `<br />` in HTML. ( Control + Return )
Above line ended with 2 spaces.

#### Horizontal Rules

***

---

- - - -

#### Headers

Setext-style:

This is H1
==========

This is H2
----------

atx-style:

# This is H1
## This is H2
### This is H3
#### This is H4
##### This is H5
###### This is H6

### Extra Syntax

#### Footnotes

Footnotes work mostly like reference-style links. A footnote is made of two things: a marker in the text that will become a superscript number; a footnote definition that will be placed in a list of footnotes at the end of the document. A footnote looks like this:

That's some text with a footnote.[^1]

[^1]: And that's the footnote.

#### Strikethrough

Wrap with 2 tilde characters:

~~Strikethrough~~
