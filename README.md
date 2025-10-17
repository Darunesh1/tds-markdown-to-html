# Markdown to HTML Converter

## Overview

This project is a simple web application that converts Markdown content into HTML. It leverages the `marked.js` library for efficient Markdown parsing and `highlight.js` for syntax highlighting of code blocks. The output is rendered within a designated HTML element, and the entire application is styled using Bootstrap 5 for a clean and responsive user interface.

## Features

*   **Markdown to HTML Conversion:** Dynamically converts Markdown text into well-formatted HTML.
*   **Code Block Syntax Highlighting:** Integrates `highlight.js` to provide syntax highlighting for code snippets.
*   **Bootstrap 5 Styling:** Utilizes Bootstrap 5 for a modern, responsive, and visually appealing user interface.
*   **Client-Side Rendering:** All conversion and rendering happen directly in the user's browser.

## Usage

1.  **Clone the repository:**
    ```bash
    git clone <repository-url>
    cd markdown-to-html
    ```
2.  **Open `index.html`:** Open the `index.html` file in your web browser.
3.  **Input Markdown:** The application will display an area where you can paste or type your Markdown content.
4.  **View HTML Output:** As you type or paste Markdown, the corresponding HTML will be rendered in the designated output area.

## Technical Details

The `index.html` file serves as the main entry point. It includes links to Bootstrap 5 CSS and JavaScript, `marked.js` for Markdown parsing, and `highlight.js` for syntax highlighting. The JavaScript code within the HTML file listens for changes in the Markdown input area, processes the Markdown using `marked.js`, and updates the `#markdown-output` div with the generated HTML. `highlight.js` is then called to apply syntax highlighting to any code blocks within the output.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.