# readmeter

MV3 extension playground: page reading-time estimator

Built for my own use; public in case it helps someone.

## Getting started

```bash
# no build step needed
# chrome://extensions -> load unpacked -> select this folder
```

## Highlights

- Manifest V3, service worker based
- Per-tab time persisted to chrome.storage
- No remote calls, everything stays local
- Popup shows today's total focus time

## How to use

```bash
# click the toolbar icon to see today's reading time
```

## Project structure

```text
├── .github/
│   ├── workflows/
│   │   └── ci.yml
│   └── pull_request_template.md
├── docs/
│   ├── faq.md
│   ├── roadmap.md
│   └── usage.md
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── SECURITY.md
├── background.js
├── manifest.json
├── popup.html
└── popup.js
```
