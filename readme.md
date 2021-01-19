# ATX headings only

## paragraphs

paragraphs are separated by 2 newlines
a single newline continues the same paragraph

hard line breaks\
are added with a backslash

## lists

1. an ordered list starts with a number and a dot

- an unordered list starts with a hyphen

- for nested lists,
  - use 4 spaces or one tab

## codeblocks

codeblocks are always fenced in backticks, the first token on the same line following the opening backticks is parsed as `lang` the rest is an info string, parsed as `meta`

```lang info-string
code blocks are fenced in backticks
```

## inline

**strong** text is surrounded by 2 asterisks

_emphasis_ text is surrounded by 1 underline

`code` is wrapped in backticks

## thematic breaks

---

thematic breaks are three or more asterisks

## blockquotes

> quotes start with one of these
>
> > quotes can be nested

## links

links are text in square brackets followed by a url in parens:

[link text](https://url)

### autolinks

<mailto:auto@link>
<https://auto-link>
