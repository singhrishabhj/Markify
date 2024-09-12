# **Markdown Cheat Sheet**

## **Basic Syntax**

### **Headings**

```markdown
# H1
## H2
### H3
#### H4
##### H5
###### H6
```

### **Emphasis**

- **Bold**: `**text**` or `__text__`
- *Italic*: `*text*` or `_text_`
- ***Bold and Italic***: `***text***` or `___text___`

### **Lists**

- **Unordered List**:
  ```markdown
  - Item 1
  - Item 2
    - Subitem 1
    - Subitem 2
  ```

- **Ordered List**:
  ```markdown
  1. Item 1
  2. Item 2
     1. Subitem 1
     2. Subitem 2
  ```

### **Links**

- **Inline Link**: `[Link Text](http://example.com)`
- **Reference Link**: 
  ```markdown
  [Link Text][1]

  [1]: http://example.com
  ```

### **Images**

- **Inline Image**: `![Alt Text](http://example.com/image.jpg)`
- **Reference Image**: 
  ```markdown
  ![Alt Text][1]

  [1]: http://example.com/image.jpg
  ```

### **Code**

- **Inline Code**: `` `code` ``
- **Code Block**:
  ```markdown
  ```language
  code
  ```
  ```

### **Blockquotes**

```markdown
> This is a blockquote.
> 
> This is a continuation of the blockquote.
```

### **Horizontal Rules**

```markdown
---
```

---

## **Advanced Syntax**

### **Tables**

```markdown
| Header 1 | Header 2 |
|----------|----------|
| Row 1    | Row 1    |
| Row 2    | Row 2    |
```

### **Task Lists**

```markdown
- [x] Task 1
- [ ] Task 2
  - [ ] Subtask 2.1
  - [x] Subtask 2.2
```

### **Footnotes**

```markdown
Here's a sentence with a footnote[^1].

[^1]: This is the footnote text.
```

### **Definition Lists** (Not supported in standard Markdown)

```markdown
Term 1
: Definition 1

Term 2
: Definition 2
```

### **Mathematics** (Requires specific renderer)

```markdown
Inline math: \( a^2 + b^2 = c^2 \)

Block math:
\[ \int_{0}^{\infty} x^2 \, dx \]
```

---

## **Common Extensions**

### **HTML**

You can include raw HTML for custom styling:

```markdown
<p>This is an HTML paragraph.</p>
```

### **Custom Attributes**

Some platforms allow custom attributes, like custom classes or IDs:

```markdown
<div class="custom-class" id="custom-id">
  Content here
</div>
```
