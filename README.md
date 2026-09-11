# focusfolio

Chrome extension that tracks reading time per tab

Small but I use it weekly.

## Features

- No remote calls, everything stays local
- Manifest V3, service worker based
- Per-tab time persisted to chrome.storage
- Popup shows today's total focus time

## Usage

```bash
# click the toolbar icon to see today's reading time
```

## Getting started

```bash
# no build step needed
# chrome://extensions -> load unpacked -> select this folder
```

## Project structure

```text
├── .github/
│   ├── workflows/
│   │   └── ci.yml
│   └── pull_request_template.md
├── docs/
│   ├── configuration.md
│   ├── development.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── scripts/
│   └── dev.sh
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── background.js
├── manifest.json
├── popup.html
└── popup.js
```

## Development

```bash
npm install
```

## License

MIT. Do whatever you want.
