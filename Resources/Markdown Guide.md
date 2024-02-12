# Markdown Guide

## Headings

# Heading 1
`# Heading 1`
## Heading 2
`## Heading 2`
### Heading 3
`### Heading 3`
#### Heading 4
`#### Heading 4`
##### Heading 5
`##### Heading 5`
###### Heading 6
`###### Heading 6`

## Text Styling

| Style                   | Syntax               | Example                                                                   |
| ----------------------- | -------------------- | ------------------------------------------------------------------------- |
| Bold                    | `** **` or `__ __`   | **Bold text**                                                             |
| Italic                  | `* *` or `_ _`       | *Italicised text*                                                         |
| Bold with nested italic | `** **` and `_ _`    | **Bold with _italicised_ text**                                           |
| Bold and italic         | `*** ***`            | ***Bold and italicised text***                                            |
| Strikethrough           | `~~ ~~`              | ~~Striked text~~                                                          |
| Subscript               | `<sub> </sub>`       | <sub>Subscript</sub> text                                                 |
| Superscript             | `<sup> </sup> `      | <sup>Superscript</sup> text                                               |
| Links                   | `[Link text](URL)`   | [Example Link](https://github.com/British-Columbia/Legislative-Assembly/) |

---
> Quoted text

`> Quoted text`

---

`Code line`

\`Code line\`

---

```
Code box
```

\`\`\`Code box\`\`\`

## Lists
### Unordered lists
- Item 1
* Item 2
+ Item 3
```
- Item 1
* Item 2
+ Item 3
```
### Ordered lists
1. Item 1
2. Item 2
3. Item 3

### Nested lists
1. Item 1
   - Nested item 1
      - Nested item 2

## New line/paragraph
Paragraph 1
<!-- Leave a space between the two paragraphs -->
Paragraph 2

```
Paragraph 1

Paragraph 2
```

## Tables

| Column Heading | Column Heading |
| -------------- | -------------- |
| Cell Contents  | Cell Contents  |
| Cell Contents  | Cell Contents  |

```
| Column Heading | Column Heading |
| -------------- | -------------- |
| Cell Contents  | Cell Contents  |
| Cell Contents  | Cell Contents  |
```
> [!NOTE]
> Note you do not need to make them all align but it is helpful for visualising whilst writing. But, you must have at least three hyphens in each column of the header row.

| Left-aligned  | Centre-aligned | Right-aligned |
| :------------ | :------------: | ------------: |
| Cell Contents | Cell Contents  | Cell Contents |
| Cell Contents | Cell Contents  | Cell Contents |

```
| Left-aligned  | Centre-aligned | Right-aligned |
| :------------ | :------------: | ------------: |
| Cell Contents | Cell Contents  | Cell Contents |
| Cell Contents | Cell Contents  | Cell Contents |
```

## Collapsed sections
<details>
<summary>Collapsed section</summary>
Contents
</details>

```
<details>
<summary>Collapsed section</summary>
Contents
</details>
```

## Aligning text
<div align="center">
Centre-aligned text
</div>

<div align="right">
Right-aligned text
</div>

```
<div align="center">
Centre-aligned text
</div>

<div align="right">
Right-aligned text
</div>
```

## Horizontal lines
<hr/>

> [!IMPORTANT]
> Type `hr/` inside angle brackets `<>`.

## Footnotes
Footnote with singular line[^1].

Footnote with multiple lines[^2].

[^1]: Footnote reference.
[^2]: Footnote reference.
  Add two spaces to indicate second line.

```
Footnote with singular line[^1].

Footnote with multiple lines[^2].

[^1]: Footnote reference.
[^2]: Footnote reference.
  Add two spaces to indicate second line.
```

## Ignoring markdown
Ignore \*this\* markdown.

`Ignore \*this\* markdown.`
