# Markdown to HTML

## Overview

Convert Markdown files to HTML using a Python script.

## Requirements

- Ubuntu 18.04 LTS, Python 3.7+
- First line of scripts: `#!/usr/bin/python3`
- Follow PEP 8 style
- Executable files
- Documented modules
- Code should not execute on import

## Tasks

### 0. Basic Script

Create `markdown2html.py` to convert Markdown to HTML.

### 1. Headings

Convert Markdown headings (`#` to `######`) to HTML headings (`<h1>` to `<h6>`).

### 2. Unordered Lists

Convert `- Item` syntax to `<ul><li>Item</li></ul>`.

### 3. Ordered Lists

Convert `* Item` syntax to `<ol><li>Item</li></ol>`.

### 4. Paragraphs

Convert simple text and paragraphs to `<p>text</p>`.

### 5. Bold and Emphasis

Convert `**bold**` to `<b>bold</b>` and `__emphasis__` to `<em>emphasis</em>`.

### 6. Custom Parsing

- `[[text]]` to MD5 hash
- `((text))` to remove 'c' (case insensitive)

## Repository

- **GitHub:** `alx-frontend-for-fun`
- **File:** `markdown2html.py`

