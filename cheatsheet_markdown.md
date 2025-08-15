# Markdown Cheat Sheet

## 1. Headers
# H1 Header
## H2 Header
### H3 Header
#### H4 Header
##### H5 Header
###### H6 Header

---

## 2. Text Formatting
**Bold text**  
*Italic text*  
***Bold and italic***  
~~Strikethrough~~  
<sub>Subscript</sub> and <sup>Superscript</sup>  
`Inline code`

---

## 3. Lists

### Unordered list:
- Item 1
- Item 2
  - Sub-item 2.1
  - Sub-item 2.2
    - Nested item

### Ordered list:
1. First item
2. Second item
   1. Sub-item 2.1
   2. Sub-item 2.2

---

## 4. Links & Images

[Regular link](https://example.com)  
[Link with title](https://example.com "Hover text")

![Image alt text](https://via.placeholder.com/150)  
![Image with title](https://via.placeholder.com/150 "Hover text")

---

## 5. Blockquotes

> This is a blockquote.
> 
> It can span multiple lines.
>
> > Nested blockquote.

---

## 6. Code

### Inline code:
Use `backticks` for inline code.

### Code blocks (no language specified):
```
This is a code block
It can span multiple lines
```

### Syntax highlighting:
```python
def hello_world():
    print("Hello, world!")
```

```javascript
console.log("Hello, world!");
```

```bash
# A shell command
ls -la
```

---

## 7. Tables

| Column 1 | Column 2 | Column 3 |
|----------|----------|----------|
| Row 1    | Data     | More     |
| Row 2    | Data     | More     |

### Alignments:
| Left Align | Center Align | Right Align |
|:-----------|:------------:|------------:|
| Item 1     | Data         | Data        |
| Item 2     | Data         | Data        |

---

## 8. Checklists / Task Lists
- [x] Completed task
- [ ] Incomplete task
- [ ] Another task

---

## 9. Horizontal Rule
---
***
___

---

## 10. Footnotes
Here is a sentence with a footnote.[^1]  
[^1]: This is the footnote text.

---

## 11. Escaping Characters
\*This is not italic\*  
Use `\` before special characters to escape them.

---

## 12. HTML in Markdown
You can use raw HTML if supported:  
<b>Bold text</b>  
<i>Italic text</i>  
<br> (line break)

---

## 13. Collapsible Section (GitHub flavored)
<details>
<summary>Click to expand</summary>

Hidden content here!

</details>

