# Markdown Test Page

This page demonstrates various Markdown features supported by myst-parser.

## Basic Markdown Features

### Lists

**Unordered List:**
- Item 1
- Item 2
  - Nested item 2.1
  - Nested item 2.2
- Item 3

**Ordered List:**
1. First item
2. Second item
3. Third item

### Text Formatting

This is **bold text** and this is *italic text*. You can also use ~~strikethrough~~.

Here's a `code snippet` in a sentence.

### Links and Images

Here's a [link to the getting started guide](getting-started).

![Alt text](https://via.placeholder.com/300x200 "Optional title")

### Code Blocks

**Python:**
```python
def greet(name):
    """Greet someone by name."""
    return f"Hello, {name}!"

result = greet("StaffHub")
print(result)
```

**JavaScript:**
```javascript
function calculateTotal(shifts) {
    return shifts.reduce((total, shift) => {
        return total + shift.hours;
    }, 0);
}
```

**JSON:**
```json
{
    "user": {
        "id": 1,
        "name": "John Doe",
        "role": "Manager"
    }
}
```

## MyST-Specific Features

### Admonitions

```{note}
This is a note admonition. Useful for providing additional information.
```

```{warning}
This is a warning admonition. Use it for important cautions.
```

```{tip}
This is a tip admonition. Great for helpful hints!
```

```{important}
This is an important admonition. Use for critical information.
```

### Definition Lists

Term 1
: Definition for term 1

Term 2
: Definition for term 2
: Another definition for term 2

### Tables

| Feature | Status | Notes |
|---------|--------|-------|
| Scheduling | ✅ Active | Available to all users |
| Reporting | ✅ Active | Requires manager role |
| API Access | 🚧 In Progress | Coming soon |

### Block Quotes

> This is a block quote. It can span multiple lines
> and is useful for highlighting important information
> or quoting other sources.

### Math (if enabled)

Inline math: $E = mc^2$

Block math:
$$
\int_{-\infty}^{\infty} e^{-x^2} dx = \sqrt{\pi}
$$

### Directives

```{code-block} python
:linenos:
:emphasize-lines: 2,4

def example():
    print("This line is emphasized")
    x = 10
    print(f"This line is also emphasized: {x}")
```

### Cross-References

You can reference other documents:
- [Getting Started Guide](getting-started)
- [User Management](features/user-management)
- [FAQ](faq)

### Task Lists

- [x] Install myst-parser
- [x] Create sample markdown file
- [ ] Test on Read the Docs
- [ ] Customize content

### Horizontal Rule

---

This is content after a horizontal rule.

## Combining Features

You can combine multiple features:

```{note}
**Tip:** Use markdown for quick documentation updates. It's easier to write than RST for many people.

Check out the [API Reference](api-reference) for more details.
```

---

*This markdown file tests various myst-parser features. If you can see this rendered correctly, myst-parser is working!*

