# Typography

## Headings

All HTML headings, `#` (h1) through `######` (h6) are available.

# h1. Heading 1

## h2. Heading 2

### h3. Heading 3

#### h4. Heading 4

##### h5. Heading 5

###### h6. Heading 6

## Body copy

Bootstrap’s global default `font-size` is **13px**, with a line-height of **19px**. This is applied to the `<body>` and all paragraphs. In addition, `<p>` (paragraphs) receive a bottom margin of half their line-height (10px by default).

Nullam quis risus eget urna mollis ornare vel eu leo. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Nullam id dolor id nibh ultricies vehicula.

Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec ullamcorper nulla non metus auctor fringilla. Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit. Donec ullamcorper nulla non metus auctor fringilla.

Maecenas sed diam eget risus varius blandit sit amet non magna. Donec id elit non mi porta gravida at eget metus. Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit.

```html
<p>...</p>
```

### Lead body copy

Make a paragraph stand out by adding `.lead`.

Vivamus sagittis lacus vel augue laoreet rutrum faucibus dolor auctor. Duis mollis, est non commodo luctus.

```html
<p class="lead">...</p>
```

## Emphasis

Make use of HTML’s default emphasis tags with lightweight styles.

```html
<small>
```

For de-emphasizing inline or blocks of text, use the small tag.

This line of text is meant to be treated as fine print.

```html
<p>
  <small>This line of text is meant to be treated as fine print.</small>
</p>
```

### Bold

For emphasizing a snippet of text with a heavier font-weight.

The following snippet of text is **rendered as bold text**.

```html
<strong>rendered as bold text</strong>
```

### Italics

For emphasizing a snippet of text with italics.

The following snippet of text is *rendered as italicized text*.

```html
<em>rendered as italicized text</em>
```

**Heads up!** Feel free to use `<b>` and `<i>` in HTML5. `<b>` is meant to highlight words or phrases without conveying additional importance while `<i>` is mostly for voice, technical terms, etc.

## Abbreviations

Stylized implemenation of HTML’s `<abbr>` element for abbreviations and acronyms to show the expanded version on hover. Abbreviations with a `title` attribute have a light dotted bottom border and a help cursor on hover, providing additional context on hover.

```html
<abbr>
```

For expanded text on long hover of an abbreviation, include the title attribute.

An abbreviation of the word attribute is attr.

##Addresses

Present contact information for the nearest ancestor or the entire body of work.

```html
<address>
```

Preserve formatting by ending all lines with `<br>`.

Twitter, Inc.795 Folsom Ave, Suite 600San Francisco, CA 94107P: (123) 456-7890
Full Namefirst.last@gmail.com

```html
<address>
  <strong>Twitter, Inc.</strong><br>
  795 Folsom Ave, Suite 600<br>
  San Francisco, CA 94107<br>
  <abbr title="Phone">P:</abbr> (123) 456-7890
</address>
```

```html
<address>
  <strong>Full Name</strong><br>
  <a href="mailto:#">first.last@gmail.com</a>
</address>
```

## Blockquotes

For quoting blocks of content from another source within your document.

> Default blockquote

Wrap `<blockquote>` around any HTML as the quote. For straight quotes we recommend a `<p>`.

> Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.

```html
<blockquote>
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.</p>
</blockquote>
```

### Blockquote options

Style and content changes for simple variations on a standard blockquote.

#### Naming a source

Add `<small>` tag for identifying the source. Wrap the name of the source work in `<cite>`.

> Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.
>
> Someone famous in Source Title

```html
<blockquote>
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.</p>
  <small>Someone famous <cite title="Source Title">Source Title</cite></small>
</blockquote>
```

#### Alternate displays

Use `.pull-right` for a floated, right-aligned blockquote.

```html
<blockquote class="pull-right">
  ...
</blockquote>
```

## Lists

### Unordered

A list of items in which the order does not explicitly matter.

* Lorem ipsum dolor sit amet
* Consectetur adipiscing elit
* Integer molestie lorem at massa
* Facilisis in pretium nisl aliquet
* Nulla volutpat aliquam velit
  * Phasellus iaculis neque
  * Purus sodales ultricies
  * Vestibulum laoreet porttitor sem
  * Ac tristique libero volutpat at
* Faucibus porta lacus fringilla vel
* Aenean sit amet erat nunc
* Eget porttitor lorem

### Ordered

A list of items in which the order does explicitly matter.

1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa
4. Facilisis in pretium nisl aliquet
5. Nulla volutpat aliquam velit
6. Faucibus porta lacus fringilla vel
7. Aenean sit amet erat nunc
8. Eget porttitor lorem

### Description

A list of terms with their associated descriptions.

Description lists:
  A description list is perfect for defining terms.
Euismod:
  Vestibulum id ligula porta felis euismod semper eget lacinia odio sem nec elit.
  Donec id elit non mi porta gravida at eget metus.
Malesuada porta:
  Etiam porta sem malesuada magna mollis euismod.

## Code

### Inline

Wrap inline snippets of code with `<code>`.

For example, `<section>` should be wrapped as inline.

```html
For example, <code><section></code> should be wrapped as inline.
```

## Images

Add classes to an <img> element to easily style images in any project.

![cat](http://placekitten.com/800/600)