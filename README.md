# vscode-markdown-pdf-theme

A clean, modern, and documentation-focused stylesheet for the [Markdown PDF](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf) extension in Visual Studio Code.

Designed specifically for technical documentation, API specifications, and clean reports with polished typography, soft-gray inline code tags, clean table layouts, and subtle dividers.

You can see the here [Demo](./README.pdf)

---

## Features

- **Pill-style Inline Code**: Light gray background badges (`#f3f5f7`) with subtle rounding for better readability in API endpoints, parameters, and tokens.
- **Clean Bordered Tables**: Balanced padding, subtle gray borders, and soft header shading designed for structured technical specs.
- **High-contrast Headings**: Bold, readable headings (`#111827`) that create a clear visual hierarchy.
- **Subtle Dividers**: Replaces harsh horizontal rules with light, minimal borders.

---

## Installation

### 1. Clone the repository

Clone this repo to your local machine:

```bash
git clone https://github.com/jimmy-chiang/vscode-markdown-pdf-theme.git
```

Alternatively, download `style.css` directly into your workspace.

### 2. Configure VS Code

Open your VS Code `settings.json` (User or Workspace) and add the path to the stylesheet under `markdown-pdf.styles`:

```json
{
  "markdown-pdf.styles": [
    "/absolute/path/to/vscode-markdown-pdf-theme/markdown-pdf.css"
  ]
}
```
