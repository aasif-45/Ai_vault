# AI Vault

AI Vault is a browser-based dashboard for saving, organizing, and opening AI tools from one place.

It is built as a single HTML file and stores data locally in the browser using `localStorage`.

## Features

- Add AI tools with just a URL
- Auto-detect tool name, category, and description
- Edit category manually if the detected one is not right
- Search tools quickly from the header
- Organize tools by category
- Drag and drop tools to reorder them
- Manage custom categories
- Keep saved data in the browser without a backend

## File

- `ai_manager.html` - Main app file

## How To Use

1. Open `ai_manager.html` in your browser.
2. Click `Add Tool`.
3. Paste the tool URL.
4. Let AI Vault auto-fill the details.
5. Adjust category or description if needed.
6. Save the tool.

## Storage

AI Vault stores tool data in the browser with `localStorage`.

That means:

- data stays available after refresh
- data is saved per browser/device
- clearing browser storage can remove saved tools

## Deploy

You can deploy this project easily with:

- GitHub Pages
- Netlify
- Vercel

For simple hosting, rename `ai_manager.html` to `index.html` or configure your host to serve it as the main page.

## GitHub Repo

Repository:

`https://github.com/aasif-45/Ai_vault`
