#READ ME

## Basic HTML
- `<!DOCTYPE html>` (doctype)
- `html`
- `head`
- `body`

## Head-related
- `meta` (self-closing)
  - used for `charset="UTF-8"` attribute/value
  - can be used for [many other purposes](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta)
- `link` (self-closing)
  - used to include external resources (i.e. css)
- `script`
  - used to include scripts (i.e. javascript)
- `title`

## Anchor
- `a`
  - frequently used with `href` attribute to create hyperlinks

## Header (h) tags
- `h1`
- `h2`
- `h3`
- `h4`
- `h5`
- `h6`

## Paragraphs
- `p`

## Emphasis
- `em` (emphasis)
- `strong` (strong emphasis)

## Subscript & Superscript
- `sub`
- `sup`

## Lists
- `ul` (unordered list)
- `ol` (ordered list)
- `li` (list item)
- `dl` (definition list)
- `dt` (defnition term)
- `dd` (definition)

## Abbreviation
- `abbr` (be sure to use `title` attribute)

## Quotes
- `blockquote`
- `q`
- can use `cite` attribute to include a URL

## Highlighting
- `mark`

## Addresses
- `address`
- `br` (self-closing, use for address; sparingly otherwise)
- only for site owner, not *any* address

## Insert & Delete
- `ins`
- `del`
- remember to style `ins` using css

## Small text
- `small`
- appropriate for 'legal' text, copyright info in footer

## Computer Input/Output
- `code` (code sample)
- `kbd` (keyboard input)
- `samp` (computer output)

## Date & Time
- `time`
- remember to use `datetime` attribute
- datetime should be formatted: `YYYY-MM-DD HH:MM` (i.e. 2015-01-28 18:00)

## Simple Tables
- `table`
- `tr` (table row)
- `th` (table header)
- `td` (table data cell)

## Complex Tables
- in addition to the tags above
- `caption` (table caption)
- `colgroup` (column grouping)
- `col` (column)
- `thead` (table head)
- `tbody` (table body)
- `tfoot` (table footer)

## Multimedia, Images & Graphics
- `audio`
- `img` (self-closing)
- `figure`
- `figcaption` (caption for `figure`)
- `map` (imagemap)
- `area` (clickable area in an `map`; self-closing)
- `video`
- `source` (specifices media source for `audio`, `video`)
- `track` (provideds metadata for `audio`, `video`)

## Structural
- `header`
- `nav`
- `main`
- `section`
- `article`
- `aside`
- `footer`

## Other
- `cite` (citation of a creative work)
- `data` (machine-readable content)
- utilizes `value` attribute
- `dfn` (a term to be defined)
- `var` (variables in mathematical expressions)

## Generic
These tags have no meaning but are acceptable to use (if necessary) when applying CSS or Javascript.
- `div` (block element)
- `span` (inline element)


## DO NOT USE
Do not use the following tags as they are *presentational* and provided no context. Their default styles can be applied using CSS.
- `b`
- `hr`
- `i`
- `s`
- `u`

## Complete Reference
- [Mozilla Developers Network: HTML element reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
