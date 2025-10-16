# Markdown Previewer

## Description

This project is a simple, static web application that converts Markdown text into HTML in real-time. It provides a clean and intuitive interface for users to write or paste Markdown code and instantly see the rendered output.  The application is fully self-contained, requiring no external dependencies, and is designed to be deployed as a static website.  It also supports syntax highlighting for code blocks within the markdown, using a simplified and self-contained version of highlight.js.

## Features

-   **Real-time Preview:** As you type or paste Markdown into the input area, the HTML output is updated immediately.
-   **Markdown Support:** Supports common Markdown syntax elements, including headings, lists, emphasis (bold and italic), links, images and code blocks.
-   **Code Syntax Highlighting:** Code blocks are automatically highlighted for better readability.
-   **Responsive Design:** The application adapts to different screen sizes, providing a good user experience on both desktop and mobile devices.
-   **Self-Contained:**  No external dependencies or build steps are required. All necessary CSS and JavaScript are embedded directly into the HTML file.
-   **Modern Design:** Clean and visually appealing design.
-   **Vanilla JavaScript:**  Built using only vanilla JavaScript, no external frameworks needed.

## How to Use

1.  Open the `index.html` file in your web browser.
2.  Type or paste Markdown code into the text area.
3.  The rendered HTML output will appear in the `markdown-output` section below the text area.

## Technologies Used

-   HTML
-   CSS (embedded)
-   JavaScript (embedded)
-   [Marked.js](https://github.com/markedjs/marked) (minimal implementation)
-   [Highlight.js](https://highlightjs.org/) (minimal implementation)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.