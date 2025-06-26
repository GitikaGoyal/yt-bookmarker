# 🎬 YT Bookmarker — Bookmark YouTube Video Timestamps with Ease

A lightweight Chrome extension that lets you save, view, and manage timestamp bookmarks directly on YouTube videos. Perfect for tutorials, lectures, and key video moments you want to revisit.

---

## 📌 Features

- ✅ Add bookmarks at the current timestamp via a button in the YouTube player
- 🕒 View all saved bookmarks in a clean popup
- ▶️ Click to instantly jump to saved moments
- ❌ Delete bookmarks with one click
- 🔁 Supports dynamic YouTube navigation (SPA)
- ☁️ Bookmarks are saved in Chrome's sync storage — persist across devices

---## 🚀 Installation

### From GitHub (Manual)
1. Clone or download this repo
2. Visit [`chrome://extensions`](chrome://extensions)
3. Enable **Developer Mode** (top right)
4. Click **Load unpacked** and select this project folder

---

## 🛠️ Tech Stack

- JavaScript (Vanilla)
- Chrome Extensions API (`storage`, `tabs`, `runtime`, `scripting`)
- DOM Manipulation
- Sync Storage
---

## ✅ Permissions Used

```json
"permissions": [
  "storage",
  "tabs",
  "activeTab"
],
"host_permissions": [
  "*://*.youtube.com/*"
]
```
---
## 📄 License

MIT License. Use freely with attribution.
