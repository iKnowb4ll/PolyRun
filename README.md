# PolyRun Studio

**Code Without Borders — Made by HAN**

PolyRun is a browser-based coding playground with a Monaco editor, multiple project files, dark/light appearance, multilingual interface labels, syntax checks, formatting, standard input, output, and HTML preview.

## Run locally

1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. Keep an internet connection available for Monaco Editor, Pyodide, and online execution.

## Publish with GitHub Pages

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch **main** and folder **/(root)**, then save.
4. After deployment, the site will be available at:

   `https://iknowb4ll.github.io/PolyRun/`

## Supported runtimes

- Browser: HTML preview, JavaScript, JSON validation
- In-browser Python: Pyodide (downloaded on first run)
- Online runner: selected languages through the public Piston API, subject to service availability and rate limits

Not every language/version is guaranteed to run. Remote execution requires an internet connection and depends on the external runner's supported runtimes.

## Syntax assistant

The built-in checker detects a limited set of common issues and offers safe suggestions for selected cases. It is not a full compiler or AI repair system; always run and test your code.

## Credits

Created by **HAN**.