````markdown
# Markdown to HTML Converter 📝➡️📄

This project is a simple web-based Markdown to HTML Converter. It uses JavaScript to parse and convert Markdown syntax into clean, readable HTML. The interface provides three main areas: Markdown input, raw HTML output, and a live HTML preview.

## 🚀 Features

- Converts:
  - Headings (`#`, `##`, `###`)
  - Bold (`**bold**` or `__bold__`)
  - Italics (`*italic*` or `_italic_`)
  - Images (`![alt-text](src)`)
  - Links (`[text](url)`)
  - Blockquotes (`> quote`)
- Displays:
  - Raw converted HTML
  - Rendered HTML preview
- Responsive and easy-to-use interface

## 📂 Project Structure

```bash
markdown-to-html-converter/
├── index.html        # Main HTML file
├── styles.css        # Stylesheet for layout and design
└── script.js         # JavaScript logic for Markdown conversion
```

## 🔧 How It Works

1. User types Markdown text into a `<textarea>`.
2. JavaScript reads this input and uses regular expressions to:

   * Identify Markdown syntax
   * Convert it into valid HTML elements
3. Output is displayed in two areas:

   * `#html-output`: shows raw HTML
   * `#preview`: renders the HTML visually

## 🧠 Supported Markdown Syntax

| Markdown Input           | Output HTML                      |
| ------------------------ | -------------------------------- |
| `# Heading 1`            | `<h1>Heading 1</h1>`             |
| `## Heading 2`           | `<h2>Heading 2</h2>`             |
| `### Heading 3`          | `<h3>Heading 3</h3>`             |
| `**bold**` or `__bold__` | `<strong>bold</strong>`          |
| `*italic*` or `_italic_` | `<em>italic</em>`                |
| `![alt](src)`            | `<img alt="alt" src="src">`      |
| `[text](url)`            | `<a href="url">text</a>`         |
| `> quote`                | `<blockquote>quote</blockquote>` |

## 🛠️ How to Run Locally

1. Clone the repository:

``bash
git clone https://github.com/yourusername/markdown-to-html-converter.git
cd markdown-to-html-converter
``

2. Open `index.html` in your browser.

> ✅ No server required. Everything runs client-side.

## ✨ Future Enhancements

* Add support for lists, code blocks, and inline code
* Syntax highlighting for code
* Toggle between dark/light mode
* Download rendered HTML

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

Made with ❤️ by \Jordan Leturgez

```
