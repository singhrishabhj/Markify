# Tables in Markdown

Tables are used to organize and present data in a structured format. Markdown supports basic table formatting to help you display tabular data clearly.

## Syntax for Tables

To create a table, use pipes (`|`) to separate columns and hyphens (`-`) to create the table headers. Align columns by adjusting the placement of colons (`:`) in the separator line.

### Basic Table Syntax

```markdown
| Header 1 | Header 2 | Header 3 |
|----------|----------|----------|
| Row 1, Col 1 | Row 1, Col 2 | Row 1, Col 3 |
| Row 2, Col 1 | Row 2, Col 2 | Row 2, Col 3 |
```

### Example

```markdown
| Name    | Age | City      |
|---------|-----|-----------|
| Alice   | 30  | New York  |
| Bob     | 25  | Los Angeles |
| Charlie | 35  | Chicago   |
```

This will render as:

| Name    | Age | City       |
|---------|-----|------------|
| Alice   | 30  | New York   |
| Bob     | 25  | Los Angeles |
| Charlie | 35  | Chicago    |

### Aligning Columns

- **Left Alignment**: `:---` (default)
- **Center Alignment**: `:---:` 
- **Right Alignment**: `---:` 

### Example with Alignment

```markdown
| Name    | Age | City       |
|:--------|:---:|----------:|
| Alice   | 30  | New York  |
| Bob     | 25  | Los Angeles |
| Charlie | 35  | Chicago   |
```

This will render as:

| Name    | Age | City       |
|:--------|:---:|----------:|
| Alice   | 30  | New York  |
| Bob     | 25  | Los Angeles |
| Charlie | 35  | Chicago   |

## Usage Tips

- **Tables**: Ideal for organizing data, comparisons, and structured information.
- **Alignment**: Use alignment options to make the table easier to read and fit the content.
- **Readability**: Keep tables simple and avoid excessive complexity for clarity.

Tables in Markdown provide a straightforward way to present tabular data without needing complex formatting.

