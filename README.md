# ⚡ APIForge — HTTP Testing Suite

A fully static, client-side HTTP testing tool combining the best features of HTTPBin, ReqBin, Beeceptor, APIBin, and APIdog.  
**No backend, no server, no signup — works directly from GitHub Pages.**

## 🚀 Deploy to GitHub Pages (3 steps)

```bash
# 1. Create a new GitHub repo (e.g. "apiforge")
# 2. Upload index.html to the repo root
# 3. Go to Settings → Pages → Source: Deploy from branch → main → / (root)
```

Your app will be live at:  
`https://<your-username>.github.io/<repo-name>/`

## ✨ Features

| Feature | Inspired By |
|---|---|
| 🔨 HTTP Request Builder (GET/POST/PUT/PATCH/DELETE/HEAD/OPTIONS) | ReqBin, APIdog |
| 📁 Request Collection (save & reload requests) | APIdog, Postman |
| 🎭 Mock Server (create fake endpoints, log hits) | Beeceptor |
| 🔍 Request Inspector (headers, body, JWT decoder, env info) | HTTPBin |
| ⚖️ JSON/Response Diff | APIBin |
| 🔐 Encode Tools (URL, Base64, JSON format, UUID, hashes) | Various |
| 📋 Request History (searchable, localStorage) | All |
| 🔑 Auth (Bearer, Basic, API Key) | APIdog |
| ⚙️ CORS Proxy support | HTTPBin workaround |
| 🌓 Dark theme, zero dependencies | Original |

## 🗂 File Structure

```
/
└── index.html    ← Entire app (single file, ~700 lines)
```

## ⚙️ How It Works

- **Pure static HTML/CSS/JS** — no Node, no build step, no dependencies
- **localStorage** stores your collection, history, and mock endpoints
- **CORS**: Requests are sent directly from the browser. Enable the CORS proxy in Settings for cross-origin APIs
- **Mock Server**: Simulated locally — intercepts calls client-side and returns your configured response
