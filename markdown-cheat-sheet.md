# Markdown Cheat Sheet

Thanks for visiting [The Markdown Guide](https://www.markdownguide.org)!

This Markdown cheat sheet provides a quick overview of all the Markdown syntax elements. It can’t cover every edge case, so if you need more information about any of these elements, refer to the reference guides for [basic syntax](https://www.markdownguide.org/basic-syntax) and [extended syntax](https://www.markdownguide.org/extended-syntax).

## Basic Syntax

These are the elements outlined in John Gruber’s original design document. All Markdown applications support these elements.

### Heading

# H1
## H2
### H3

### Bold

**bold text**

### Italic

*italicized text*

### Blockquote

> blockquote

### Ordered List

1. First item
2. Second item
3. Third item

### Unordered List

- First item
- Second item
- Third item

### Code

`code`

### Horizontal Rule

---

### Link

[title](https://www.example.com)

### Image

![alt text](image.jpg)

## Extended Syntax

These elements extend the basic syntax by adding additional features. Not all Markdown applications support these elements.

### Table

| Syntax | Description | Stuff |
| :---- | :----: | ----:|
| Header | Title | Stuff |
| Paragraph | Text | Stuffy Stuff Stuff |

| Syntax | Description | Stuff |
| ---- | ---- | ---- |
| Header | Title | Stuff |
| Paragraph | Text | Stuffy Stuff Stuff |

#### Formatting Text in Tables

You can format the text within tables. For example, you can add **links**, **code** (words or phrases in backticks (`) only, **not** code blocks), and **emphasis**.

You **cannot** add headings, blockquotes, lists, horizontal rules, images, or HTML tags.

#### Escaping Pipe Characters in Tables

You can display a pipe (|) character in a table by using its HTML character code (\&#124;).

### Fenced Code Block

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

### Footnote

Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.

### Heading ID

#### My Great Heading {#custom-id}

### Definition List

term
: definition

### Strikethrough

~~The world is flat.~~

### Task List

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media
