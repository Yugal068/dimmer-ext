# dimmer-ext

Chrome extension that tracks reading time per tab

Small but I use it weekly.

## Getting started

```bash
# no build step needed
# chrome://extensions -> load unpacked -> select this folder
```

## Examples

```bash
# click the toolbar icon to see today's reading time
```

## What it does

- Popup shows today's total focus time
- Manifest V3, service worker based
- No remote calls, everything stays local
- Per-tab time persisted to chrome.storage

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   ├── dependabot.yml
│   └── pull_request_template.md
├── docs/
│   ├── configuration.md
│   └── development.md
├── examples/
│   └── quickstart.md
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
├── background.js
├── manifest.json
├── popup.html
└── popup.js
```

## Development

```bash
npm install
npm test
```

## License

MIT - see [LICENSE](LICENSE).
