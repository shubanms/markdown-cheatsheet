# Text styles


Using markdown syntax, we can change texts’ styles, including bold, italic, blockquotes, monospaced, underlined, strike-through, boxed, subscript, and superscript.


We can use two asterisks (`**`), underscores (`_ _`), or an HTML tag `<strong>` to make the text bold. To make the text italic, we can use one asterisk (`*`), underscore (`_`), or an HTML tag `<em>`. Also, we can make the text bold and italic at the same time.

```
Bold
**The quick brown fox jumps over the lazy dog.**
__The quick brown fox jumps over the lazy dog.__
<strong>The quick brown fox jumps over the lazy dog.</strong>
Italic
*The quick brown fox jumps over the lazy dog.*
_The quick brown fox jumps over the lazy dog._
<em>The quick brown fox jumps over the lazy dog.</em>
Bold and Italic
**_The quick brown fox jumps over the lazy dog._**
<strong><em>The quick brown fox jumps over the lazy dog.</em></strong>
```

Let’s see how it looks on GitHub.

**The quick brown fox jumps over the lazy dog.**
__The quick brown fox jumps over the lazy dog.__
<strong>The quick brown fox jumps over the lazy dog.</strong>
Italic
*The quick brown fox jumps over the lazy dog.*
_The quick brown fox jumps over the lazy dog._
<em>The quick brown fox jumps over the lazy dog.</em>
Bold and Italic
**_The quick brown fox jumps over the lazy dog._**
<strong><em>The quick brown fox jumps over the lazy dog.</em></strong>

To create a blockquote, we can use the greater than sign `>`. We can create a single-line or multi-line blockquote. Also, blockquote inside a blockquote. We can add other text styles inside a blockquote, such as bold or italic text styles.

```
Blockquotes
> The quick brown fox jumps over the lazy dog.

> The quick brown fox jumps over the lazy dog.
> 
> The quick brown fox jumps over the lazy dog.
> 
> The quick brown fox jumps over the lazy dog.

> The quick brown fox jumps over the lazy dog.
>> The quick brown fox jumps over the lazy dog.
>>> The quick brown fox jumps over the lazy dog.

> **The quick brown fox** *jumps over the lazy dog.*
```

Let’s see how it looks on GitHub.

> The quick brown fox jumps over the lazy dog.

> The quick brown fox jumps over the lazy dog.
> 
> The quick brown fox jumps over the lazy dog.
> 
> The quick brown fox jumps over the lazy dog.

> The quick brown fox jumps over the lazy dog.
>> The quick brown fox jumps over the lazy dog.
>>> The quick brown fox jumps over the lazy dog.

> **The quick brown fox** *jumps over the lazy dog.*

We can achieve monospaced and underlined styles using HTML tags `<samp>` and `<ins>`. For a strike-through style, we can use two tilda sign `~~`.

```
Monospaced
<samp>The quick brown fox jumps over the lazy dog.</samp>

Underlined
<ins>The quick brown fox jumps over the lazy dog.</ins>

Strike-through
~~The quick brown fox jumps over the lazy dog.~~
```

Let’s see how it looks on GitHub.

Monospaced
<samp>The quick brown fox jumps over the lazy dog.</samp>

Underlined
<ins>The quick brown fox jumps over the lazy dog.</ins>

Strike-through
~~The quick brown fox jumps over the lazy dog.~~

We can use an HTML `<table>` tag to create a box.

```
Boxed
<table><tr><td>The quick brown fox jumps over the lazy dog.</td></tr></table>
```

Let’s see how it looks on GitHub.

<table><tr><td>The quick brown fox jumps over the lazy dog.</td></tr></table>

We can achieve subscript and superscript styles using HTML tags `<sub>` and `<sup>`. It is useful when you’re writing a mathematical formula.

```
2 <sup>53-1</sup> and -2 <sup>53-1</sup>
```

Let’s see how it looks on GitHub.

2 <sup>53-1</sup> and -2 <sup>53-1</sup>

```
Subscript <sub>The quick brown fox jumps over the lazy dog.</sub>
Superscript <sup>The quick brown fox jumps over the lazy dog.</sup>
```

Let’s see how it looks on GitHub.

Subscript <sub>The quick brown fox jumps over the lazy dog.</sub>
Superscript <sup>The quick brown fox jumps over the lazy dog.</sup>