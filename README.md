# Markdown to HTML Renderer

![Project Status: Live](https://img.shields.io/badge/Status-Live-brightgreen.svg)

## 🚀 Live Demo

Experience the application live here:

### [**https://Shubham30000.github.io/markdown-to-html-test-test/**](https://Shubham30000.github.io/markdown-to-html-test-test/)

## 📋 Overview

This project provides a simple, static web page designed to convert Markdown content into rendered HTML. It dynamically processes an `input.md` file, displaying its HTML output in a designated area, complete with professional syntax highlighting for code blocks. It serves as a straightforward example of client-side Markdown rendering.

## ✨ Features

*   **Markdown to HTML Conversion**: Seamlessly converts Markdown syntax to valid HTML.
*   **Dynamic Rendering**: Automatically renders content from `input.md` on page load.
*   **Code Block Syntax Highlighting**: Enhances readability of code snippets using `highlight.js`.
*   **Static Page Deployment**: Easily deployable as a static website without server-side dependencies.

## 🛠️ Technologies Used

*   **HTML5**: For structuring the web content.
*   **JavaScript**: Powers the client-side conversion and rendering logic.
*   **[marked.js](https://marked.js.org/)**: A powerful Markdown parser and compiler for the browser.
*   **[highlight.js](https://highlightjs.org/)**: A robust syntax highlighter for various programming languages, loaded directly from a CDN.

## 📦 Setup

To get a local copy up and running, follow these simple steps.

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/Shubham30000/markdown-to-html-test-test.git
    ```
2.  **Navigate to the project directory**:
    ```bash
    cd markdown-to-html-test-test
    ```
3.  **Open `index.html`**: Simply open the `index.html` file in your preferred web browser.

## 💡 Usage

Using the Markdown to HTML Renderer is straightforward:

1.  Open the live demo link provided above, or open `index.html` locally in your web browser.
2.  The application will automatically load the content from `input.md`.
3.  The Markdown content will be converted to HTML and displayed in the `#markdown-output` section, with all code blocks properly syntax-highlighted.
4.  To change the rendered content, simply modify the `input.md` file in the project directory.

## 📁 Project Structure

*   `index.html`: The main HTML file that serves as the entry point for the application, including the necessary scripts and output area.
*   `input.md`: The Markdown file whose content is processed and rendered into HTML.
*   `script.js`: (Assumed) Contains the JavaScript logic to fetch `input.md`, parse it with `marked.js`, insert into `index.html`, and initialize `highlight.js`.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.