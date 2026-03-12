# Khursheed Alam Portfolio

## Preview while coding with Codex

This project is a static site (`index.html` + `style.css` + `script.js`), so the quickest live preview is a local HTTP server.

### 1) Start a local server

From the repo root:

```bash
python3 -m http.server 4173
```

Then open:

- `http://127.0.0.1:4173`

### 2) Fast refresh loop

- Keep the server running in one terminal.
- Edit files in another terminal/editor.
- Refresh the browser after each save.

### 3) Optional: capture a preview screenshot in Codex browser tooling

Use the browser tool to open the local URL and save an artifact screenshot after your changes.

### Troubleshooting

- If you get a blank page, confirm you started the server from the repository root.
- If styles/scripts do not update, force-refresh the page (`Ctrl+Shift+R` / `Cmd+Shift+R`).
- If port `4173` is busy, use another port:

```bash
python3 -m http.server 8080
```

Then open `http://127.0.0.1:8080`.
