# Buggy Project Repository 🛑

Welcome to this repository! This README is intentionally structured with Markdown syntax errors, broken code snippets, and formatting issues to test how GitHub parsers, linters, or extensions handle malformed documentation.

---

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation) -> [Broken Link](#non-existent-section)
- [Usage](#usage)
- [Issues & Bugs](#issues--bugs)
TestTestTEst
---

## Introduction
This project is designed specifically for testing parser resilience against invalid Markdown formatting.

> [!NOTE]
> This blockquote uses an invalid alert syntax or unclosed formatting **bold text without closing asterisk.

---

## Installation

Run the following command to install dependencies:

```bash
git clone https://github.com/example/buggy-repo.git
cd buggy-repo
npm install --save-dev broken-package@latest
# Unclosed code block below:
```

```python
def unclosed_function():
    print("This python block is missing its closing backticks
    
print("Missing backticks above")
```

---

## Usage

Here is how you use the broken features:

1. First step of the list.
3. Out of order list item (should be 2).
   * Unmatched sub-list indentation.
- Mixed bullet types causing parsing errors.

---

## Broken Tables & HTML

| Header 1 | Header 2 | Header 3
| :--- | :--: | ---:
| Row 1 Col 1 | Row 1 Col 2 | Row 1 Col 3 | Extra Column
| Row 2 Col 1 | Row 2 Col 2 |

<div align="center">
  <h3>Unclosed HTML tag alert
  <p>This paragraph contains broken HTML attributes <a href="http://example.com" target="_blank">broken link</a>
</div>

---

## Code Snippet with Syntax Errors

```javascript
function testError() {
    console.log("Missing closing parenthesis;
    let x = [1, 2, 3;
    return x
}
```

---

## Footer
End of file without proper newline or closing markers.
