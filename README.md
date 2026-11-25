# PolyRun Studio

**Code Without Borders — Made by HAN**

PolyRun is a browser-based coding playground with a Monaco editor, multiple project files, dark/light appearance, syntax checks, formatting, standard input, output, and local previews.

## Languages and tools that run locally

These run on the user's device inside the browser; PolyRun does not send source code to a remote code-execution API:

- **Python** — executed with Pyodide (WebAssembly).
- **JavaScript** — executed in a sandboxed browser frame.
- **TypeScript** — transpiled in the browser, then executed in the JavaScript sandbox.

Local browser tools (not standalone programming-language runtimes):

- **HTML** — rendered in the preview frame.
- **CSS** — applied to an HTML preview.
- **JSON** — parsed, validated, and formatted.

## Editor-only languages

C, C++, Java, C#, Go, Rust, PHP, Ruby, and Bash can be edited and syntax-highlighted, but this version does not execute them. They are not sent to an online runner.

## Run PolyRun

1. Download or clone this repository.
2. Open `index.html` in a modern browser, or publish it with GitHub Pages.
3. Keep an internet connection available on first load for Monaco Editor, Pyodide, and the TypeScript compiler. After the runtime libraries are downloaded, supported code executes locally in the browser.

**Important:** "Local execution" means code runs in the browser on the user's device. The supporting editor/runtime libraries are downloaded from CDNs. It is not a fully offline application. Browser security restrictions and device memory/performance still apply.

## Publish with GitHub Pages

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch **main** and folder **/(root)**, then save.
4. After deployment, the site will be available at:

   `https://iknowb4ll.github.io/PolyRun/`

## Current limitations

- The syntax assistant checks a limited set of common mistakes; it is not a full compiler or AI repair system.
- Formatting depends on the language formatter available in Monaco.
- Long-running or infinite JavaScript tasks are stopped after a short time limit. Python execution does not yet have a hard timeout.
- HTML/CSS preview is sandboxed and may not support every browser API.
- C, C++, Java, C#, Go, Rust, PHP, Ruby, and Bash need separate browser-compatible runtimes before PolyRun can execute them locally.

## Credits

Created by **HAN**.
