# Markdown Tabbed Editor

## Overview
This web application provides a dynamic and interactive way to view and edit Markdown content. It features a tabbed interface that allows users to seamlessly switch between a live rendered HTML preview and the original Markdown source code, ensuring both views remain synchronized.

## Features
*   **Tabbed Interface:** Easily switch between "HTML Output" and "Markdown Source" views using distinct tabs.
*   **Live Preview:** See your Markdown rendered as HTML in real-time.
*   **Source Editing:** Edit your Markdown directly in a dedicated source view.
*   **Synchronization:** Both the HTML output and Markdown source are kept in sync, reflecting the latest changes.

## Usage
1.  Open the `index.html` file in your web browser.
2.  Enter your Markdown content into the "Markdown Source" tab.
3.  Switch to the "HTML Output" tab to see the rendered HTML.
4.  Edit the Markdown in the "Markdown Source" tab, and the "HTML Output" will update automatically.

## Technical Details
This project utilizes basic HTML, CSS, and JavaScript. The core functionality is driven by JavaScript event listeners that capture changes in the Markdown input area (`#markdown-source`) and update the HTML output area (`#markdown-output`) using a Markdown parsing library (e.g., Marked.js, though not explicitly included in this minimal example, it's implied for full functionality). The tab switching is managed by simple DOM manipulation and CSS classes.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.