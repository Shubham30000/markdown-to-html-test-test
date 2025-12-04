# Markdown to HTML Converter

## Live Demo
[DEPLOYMENT_URL_PLACEHOLDER](DEPLOYMENT_URL_PLACEHOLDER)

## Overview
This project provides a simple, single-page web application designed to convert a local Markdown file (`input.md`) into richly formatted HTML. It leverages the `marked.js` library for efficient Markdown parsing and `highlight.js` for beautiful syntax highlighting within code blocks. The application is styled using Tailwind CSS, ensuring a clean and responsive user interface without any complex build steps. Just drop the files, and it works!

## Features
*   **Markdown to HTML Conversion:** Automatically reads and converts the content of `input.md` into standard HTML.
*   **Dynamic Rendering:** Markdown content is rendered directly into the page's DOM upon loading.
*   **Syntax Highlighting:** Integrates `highlight.js` to provide professional syntax highlighting for code blocks in various programming languages.
*   **Responsive Design:** Utilizes Tailwind CSS from a CDN for a mobile-first, responsive layout.
*   **Zero Build Setup:** No node modules, no compilers, just plain HTML, CSS, and JavaScript. Easily deployable as a static site.

## Technologies Used
*   **HTML5:** The core structure of the web page.
*   **CSS (Tailwind CSS via CDN):** For utility-first styling and responsive design.
*   **JavaScript:** For fetching, parsing, and rendering the Markdown content.
*   **`marked.js`:** A powerful Markdown parser and compiler.
*   **`highlight.js`:** A robust syntax highlighter for the web.

## Setup
To set up this project locally:
1.  **Clone or Download:** Get the project files ( `index.html`, `input.md`, `README.md`, `LICENSE` ).
2.  **Place `input.md`:** Ensure that the `input.md` file is in the same directory as `index.html`. This file contains the Markdown content that will be rendered.
3.  **Open `index.html`:** Simply open `index.html` in your preferred web browser.

That's it! The page will automatically fetch `input.md` and display its rendered HTML content.

## Usage
*   **View Markdown:** Open `index.html` in your browser to see the rendered content of `input.md`.
*   **Edit Content:** To change the displayed content, simply edit the `input.md` file using any text editor. Save your changes and refresh the browser.
*   **Add Code Blocks:** Include code blocks in `input.md` using standard Markdown fence syntax (e.g., ````javascript console.log("Hello, world!"); ````) to see `highlight.js` in action.

## Project Structure
```
.
├── index.html          # The main web page for rendering Markdown
├── input.md            # The Markdown content file to be rendered
├── README.md           # This project description
└── LICENSE             # Project license information
```

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.