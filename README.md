# madievs.github.io
My personal website and CV


markdown
# 1. Headings
Use 1 to 6 `#` symbols followed by a space to create headings.
# Heading 1 (Largest)
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6 (Smallest)

---

# 2. Text Styling
Emphasize text with bold, italics, strikethrough, or script tags.

*This text is italic* (or _this_)
**This text is bold** (or __this__)
***This text is both bold and italic***
~~This text is strikethrough~~

Superscript: <sup>text</sup>
Subscript: <sub>text</sub>
Underline: <ins>text</ins>

---

# 3. Lists
Create ordered, unordered, or task-oriented lists.

### Unordered List
- Item 1
* Item 2
+ Item 3
  - Indented sub-item (use 2 or 4 spaces)

### Ordered List
1. First item
2. Second item
   1. Sub-item 1
   2. Sub-item 2

### Task Lists (Checkboxes)
- [x] Completed task
- [ ] Incomplete task

---

# 4. Links and Images
Add anchors, web URLs, or media directly to your documentation.

### Links
[Visit GitHub Docs](https://docs.github.com)
[Inline Link with Hover Title](https://www.google.com "Google's Homepage")
Automatic URL conversion: https://github.com

### Images
![Alt Text for Image](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

---

# 5. Code and Syntax Highlighting
Use backticks to format code lines or full blocks.

### Inline Code
Use `git status` to see pending changes.

### Block Code (With Language Shorthand)
```python
def say_hello():
    print("Hello from GitHub Markdown!")
```

### Raw Plain Text Block
```text
This block will ignore code syntax coloring.
```

---

# 6. Quotes and Alerts
Call out important notices or cite outside text.

### Blockquotes
> This is a standard blockquote.
> > Nested blockquote level 2.

### GFM Alerts
> [!NOTE]
> Useful information users should know.

> [!TIP]
> Helpful advice to do things better.

> [!IMPORTANT]
> Crucial information necessary for success.

> [!WARNING]
> Critical content demanding immediate attention.

> [!CAUTION]
> Negative consequences of an action.

---

# 7. Tables
Organize structured metrics or properties into scannable grids.

| Header 1     | Header 2         | Centered Header | Right-Aligned |
| :----------- | :--------------- | :-------------: | ------------: |
| Left-aligned | Default column   | Center text     | \$100.00       |
| Row 2 item   | More text        | Text            | \$50.50        |

---

# 8. Mentions, Issues, and Colors
Leverage native GitHub integrations inside your text.

- Tag a contributor: @username
- Reference an Issue or Pull Request: #123
- Render a live color chip block: `#FF5733`

---

# 9. Miscellaneous and Escaping
Add horizontal rules, line breaks, or bypass Markdown rules.

### Horizontal Line
---

### Line Break
Use the standard HTML line break element<br>to jump down a single line.

### Escaping Formatting Characters
To print a markdown character as literal text instead of styling it, use a backslash `\` before it:
\*This text will have literal asterisks\* and will not be italicized.
