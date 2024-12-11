# Markdown Cheatsheet

## What is Markdown?

Markdown is a lightweight markup language that you can use to add formatting elements to plaintext text documents.

## Basic Syntax

These are the elements outlined in John Gruber’s original design document. All Markdown applications support these elements.

## 1. Headings

```markdown
# H1

## H2

### H3

#### H4

##### H5

###### H6

Alternatively, for H1 and H2, an underline-ish style:

# Alt-H1
----
## Alt-H2
====
```

## 2. Emphasis

```markdown
_Italic_ or _Italic_
**Bold** or **Bold**
**_Bold and Italic_**
```

Example:

_Italic_ or _Italic_

**Bold** or **Bold**

**_Bold and Italic_**

## 3. Lists

### Unordered List

```markdown
- Item 1
- Item 2
  - Subitem 2.1
  - Subitem 2.2
```

Example:

- Item 1
- Item 2
  - Subitem 2.1
  - Subitem 2.2

### Ordered List

```markdown
1. First
2. Second
   1. Subitem 2.1
   2. Subitem 2.2
```

Example:

1. First
2. Second
   1. Subitem 2.1
   2. Subitem 2.2

## 4. Links

```markdown
[Markdown Guide](https://www.markdownguide.org)
```

Example:

[Markdown Guide](https://www.markdownguide.org)

## 5. Images

```markdown
![alt text](https://www.markdownguide.org/assets/images/tux.png)
```

Example:

![alt text](https://www.markdownguide.org/assets/images/tux.png)

## 6. Code

- **Inline Code**

```markdown
`code snippet`
```

Example:

`print("Hello, World!")`

- **Code Block**

```markdown

```

Example:

```javascript
function greet() {
    console.log("Hello, World!");
}
```

## 7. Blockquotes

```markdown
> This is a blockquote.
```

Example:

> This is a blockquote.

## 8. Horizontal Line

```markdown
---
```

Example:

---

## 9. Tables

```markdown
| Header 1 | Header 2 | Header 3 |
| -------- | -------- | -------- |
| Row 1    | Data 1   | Data 1   |
| Row 2    | Data 2   | Data 2   |
```

Example:

| Header 1 | Header 2 | Header 3 |
| -------- | -------- | -------- |
| Row 1    | Data 1   | Data 1   |
| Row 2    | Data 2   | Data 2   |

## 10. Task Lists

```markdown
- [x] Task 1
- [ ] Task 2
- [ ] Task 3
```

Example:

- [x] Task 1
- [ ] Task 2
- [ ] Task 3

## 11. Escaping Characters

Use `\` to escape special characters.

```markdown
\*Not Italic\*
```

Example:

\*Not Italic\*

## 12. Extended GitHub Markdown

These elements extend the basic syntax by adding additional features. Not all Markdown applications support these elements.

- **Syntax Highlighting**

Use language name after triple backticks.

````markdown
```javascript
console.log("Hello, World!");
```
````

Example:

````markdown
```javascript
console.log("Hello, World!");
````

- **Footnotes**

```markdown
Here is a footnote reference[^1].

[^1]: This is the footnote.
```

Example:

```markdown
Here is a footnote reference[^1].

[^1]: This is the footnote.

1. This is the footnote. ↩︎
```

- **Strikethrough**

```markdown
~~Strikethrough~~
```

Example:

~~Strikethrough~~

## 13. Emoji

```markdown
:smile: :+1: :heart:
```

Example:

:smile: :+1: :heart:

## 14. GFM (GitHub Flavored Markdown)

- **Checklists**

```markdown
- [x] Item 1
- [ ] Item 2
```

Example:

- [x] Item 1
- [ ] Item 2

- **Mentioning Users**

```markdown
@username
```

Example: @tanmaypatil

- **Referencing Issues**

```markdown
#123
```

Example: #123

- **Add Custom Notes**

```markdown
> **Note:** This is important.
> **Warning:** Be cautious.
```

Example:
> **Note:** This is important.
> **Warning:** Be cautious.

- **Highlight**

```markdown
I need to highlight these ==very important words==.
```

Example:
I need to highlight these ==very important words==.

- **Subscript**

```md
H~2~O
```

Example: H~2~O

- **Superscript**
  
```md
X^2^
```

Example: X^2^

- **Plain text**
  
End a line with two spaces to start a new paragraph.

- **Latex Equation**
  
Surround text with a single dollar sign to make it a LaTeX equation

```md
$e^{\pi i} + 1 = 0$
```

Example: $e^{\pi i} + 1 = 0$

This Markdown cheatsheet covers the basics and some advanced features commonly used on GitHub.

:|-----------------:|----------------:|-----------------:|---------------:|---------------:|
