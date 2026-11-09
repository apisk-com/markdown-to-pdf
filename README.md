# Markdown to PDF

Working code that converts Markdown to PDF. Each folder is one complete example: one language and tool, or one
problem. The [APISK tutorials](https://apisk.com/blog/) explain the code step
by step.

## Examples

| Folder | Language and tools | What it does | Tutorial |
|---|---|---|---|
| [nodejs-puppeteer](nodejs-puppeteer/) | Node.js, Express 5, markdown-it, highlight.js, Puppeteer | Markdown to PDF API: `POST /markdown` with print CSS and code highlighting; tests | [Markdown to PDF with Node.js: Build a Conversion API](https://apisk.com/blog/markdown-to-pdf-api/), 20 November 2026 |

Each folder runs on its own: open its `README.md` for the commands.

## Add an example

Examples for other languages and tools are welcome. Put each one in its own
folder. Name the folder `<language>-<tool>`, for example
`java-openhtmltopdf`, or name it after the problem that it solves. Add a
`test.sh` file that installs what the example needs on Ubuntu 24.04 and runs
its tests. The test workflow runs `test.sh` for each folder that a push or a
pull request changes.

## License

MIT. See [LICENSE](LICENSE).
