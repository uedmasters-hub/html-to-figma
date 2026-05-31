# HTML to Figma

A Chrome Extension that captures any webpage's HTML and CSS and imports it into Figma as fully editable native layers — frames, text nodes, fills, borders, shadows, and corner radii.

## How It Works

1. Visit any webpage in Chrome
2. Click the HTML to Figma extension icon
3. Choose capture mode: Full page, Visible area, or CSS selector
4. Click "Capture & Copy to Clipboard"
5. Open Figma → run the HTML to Figma plugin → Paste and Import

## Features

- Full page capture
- CSS selector mode (capture specific elements)
- Editable text nodes with font family, size, weight, color
- Fills, borders, shadows, corner radii preserved
- One-click clipboard workflow

## Privacy Policy

**Last updated: June 2026**

HTML to Figma is committed to protecting your privacy.

### Data Collection
This extension does **not** collect, store, transmit, or share any personal data or user information of any kind.

### How It Works Locally
- All HTML and CSS capture happens entirely on your local device
- Captured data is copied only to your local clipboard
- No data is sent to any external server or third party
- No analytics, tracking, or telemetry of any kind

### Permissions Used
- **activeTab** — reads the current tab's DOM and styles locally only
- **scripting** — injects content script locally to traverse the DOM
- **clipboardWrite** — copies captured JSON to your local clipboard
- **storage** — temporarily stores data locally between extension components
- **host_permissions** — enables capture on any user-chosen webpage; no data leaves the device

### Contact
For any privacy questions, open an issue on this repository.
