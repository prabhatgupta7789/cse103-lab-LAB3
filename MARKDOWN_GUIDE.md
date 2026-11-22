cd ~/cse103_lab/LAB3/my_first_repo
cat << 'EOF' > MARKDOWN_GUIDE.md
# Heading 1 (largest)

## Heading 2

### Heading 3

**Bold text** *Italic text* ~~Strikethrough~~

Unordered list:
- Item A
- Item B
  - Nested item B1

Ordered list:
1. First step
2. Second step

Inline code: `print("Hello")`

Fenced code block:
```python
def greet(name):
    return f"Hello, {name}!"

Hyperlink: GitHubTable:Column 1Column 2Column 3LeftCentreRightprintf '\nTable:\n| Column 1 | Column 2 | Column 3 |\n|----------|:--------:|----------:|\n| Left | Centre | Right |\n' >> MARKDOWN_GUIDE.md



Blockquote:
> An important note or reference goes here.

Horizontal divider:
---
