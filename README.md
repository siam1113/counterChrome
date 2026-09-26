# Counter Chrome Extension

A Chrome browser extension that counts clicks on a page and keeps a separate, running count for each website you visit.

## How it works

The extension listens for clicks on the current page and stores a click count per website, so each site's count is tracked independently.

## Project structure

- `manifest.json` — Chrome extension manifest
- `background.js` — background script that manages counts
- `content.js` — script injected into pages to detect clicks
- `index.html` / `index.js` / `index.css` — the extension's popup UI

## Installation

Load the extension in Chrome via `chrome://extensions` → "Load unpacked" and select this folder.
