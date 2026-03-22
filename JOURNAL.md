---
title: "Test Title"
start_date: "2026-3-21"
description: "This is an example description. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."
repository_url: "https://github.com/person20020/journals-site-test"
show_on_site: true
---

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

---

## Emphasis

Regular text, **bold text**, *italic text*, ***bold and italic***, ~~strikethrough~~, and `inline code`.

---

## Blockquotes

> Single-level blockquote.

> Nested blockquotes:
> > Level two.
> > > Level three.

> Multiline blockquote.
> Still the same quote.
>
> New paragraph inside blockquote.

---

## Lists

### Unordered

- Item one
- Item two
  - Nested item A
  - Nested item B
    - Deeply nested
- Item three

### Ordered

1. First
2. Second
   1. Nested first
   2. Nested second
3. Third

### Task List

- [x] Completed task
- [ ] Incomplete task
- [x] Another done
- [ ] Another todo

---

## Code

### Inline

Use `console.log("hello")` to print.

### Fenced — no language

```
plain text block
no syntax highlighting
```

### Fenced — Bash

```bash
#!/bin/bash
echo "Hello, world!"
for i in {1..5}; do
    echo "Line $i"
done
```

### Fenced — Python

```python
def greet(name: str) -> str:
    return f"Hello, {name}!"

if __name__ == "__main__":
    print(greet("world"))
```

### Fenced — JavaScript

```javascript
const fetchData = async (url) => {
    const response = await fetch(url);
    const data = await response.json();
    return data;
};
```

### Fenced — JSON

```json
{
    "name": "test",
    "version": "1.0.0",
    "tags": ["markdown", "test", "rendering"],
    "active": true,
    "count": 42
}
```

---

## Tables

### Basic

| Column A | Column B | Column C |
|----------|----------|----------|
| Cell 1   | Cell 2   | Cell 3   |
| Cell 4   | Cell 5   | Cell 6   |

### Alignment

| Left | Center | Right |
|:-----|:------:|------:|
| L    |   C    |     R |
| text | text   |  text |
| 1    |   2    |     3 |

---

## Links

[Basic link](https://example.com)

[Link with title](https://example.com "Example site")

<https://example.com> (autolink)

[Reference link][ref1]

[ref1]: https://example.com "Reference"

---

## Images

![Alt text placeholder](https://via.placeholder.com/400x200 "Placeholder image")

---

## Horizontal Rules

Three variants:

---

***

___

---

## Footnotes

Here is a sentence with a footnote.[^1]

Another sentence with a footnote.[^note]

[^1]: This is footnote number one.
[^note]: This is a named footnote.

---

## Definition Lists

Term one
:   Definition for term one.

Term two
:   First definition for term two.
:   Second definition for term two.

---

## Superscript & Subscript

Superscript: X^2^ or E=mc^2^

Subscript: H~2~O

---

## Highlight

==Highlighted text== (if supported)

---

## HTML Passthrough

<details>
<summary>Click to expand</summary>

Hidden content revealed on click.

</details>

<br>

<kbd>Ctrl</kbd> + <kbd>C</kbd> to copy.

---

## Escaping Special Characters

\*not italic\* \`not code\` \[not a link\]

Literal backslash: \\

---

## Long Content (Scroll / Overflow Test)

This paragraph is intentionally long to test how your renderer handles line wrapping and paragraph spacing. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

### Long Unbroken String (Overflow Test)

`averylongstringwithnospacestotestwhetheryourrendererapplieswordbreakproperlyorifitoverflowsthebounds`

### Wide Table (Horizontal Scroll Test)

| Col 1 | Col 2 | Col 3 | Col 4 | Col 5 | Col 6 | Col 7 | Col 8 |
|-------|-------|-------|-------|-------|-------|-------|-------|
| A     | B     | C     | D     | E     | F     | G     | H     |
| 1     | 2     | 3     | 4     | 5     | 6     | 7     | 8     |

---

## Emoji

:white_check_mark: :warning: :rocket: :tada: (if emoji shortcodes are supported)

Unicode emoji directly: ✅ ⚠️ 🚀 🎉

---

## Mixed Formatting Edge Cases

**Bold with `inline code` inside**

*Italic with [a link](https://example.com) inside*

> Blockquote with **bold**, *italic*, and `code` inside.

- List item with **bold** and *italic* and `code`
- List item with [a link](https://example.com)

| Cell with **bold** | Cell with *italic* | Cell with `code` |
|--------------------|--------------------|--------------------|
| normal             | normal             | normal             |
