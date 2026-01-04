# FF Icon Extractor

FF Icon Extractor is a lightweight, frontend-only tool for scanning, previewing, and downloading Free Fire icon assets using sequential item IDs.

It is designed as a **utility tool**, not a consumer app — focused on correctness, clarity, and controlled behavior rather than flashy features.
 
---

## 🔧 What This Tool Does

- Select Free Fire server (Advance / Live)
- Choose OB version
- Pick an asset category
- Automatically scan sequential asset IDs
- Preview available assets in a grid
- Download individual assets securely
- Copy asset IDs with one click
- Clearly show context using a side heading (Category, OB, Server)

---

## ✅ Key Features

- Sequential ID scanning with automatic stop on missing assets
- Category-aware ID generation (normal and special formats)
- Clean, compact, mobile-friendly UI
- Secure-only download (Blob-based, no direct navigation)
- Copy ID functionality with cross-browser fallback
- Images are non-interactive (cannot be opened or dragged)
- No unnecessary features (search, bulk hacks, animations)

---

## 🔐 Security Model & Limitations

This is a **pure frontend application**.

### Important limitations:

- CDN URLs **cannot be fully hidden**
- Network requests are visible in browser developer tools
- Some mobile browsers may block secure downloads
- ZIP downloads and screenshots are not supported

### What is handled correctly:

- No direct navigation to CDN URLs
- Images cannot be clicked or opened
- No fallback that opens assets in a new tab
- No misleading or fake security claims

> **True URL hiding requires a backend proxy.**  
> This project intentionally avoids half-baked frontend hacks.

---

## 🧠 Design Philosophy

- Utility-first, not flashy
- Honest behavior over broken workarounds
- Minimal UI, minimal logic
- Frontend kept clean and backend-ready
- Easy to extend when a server is added

---

## 🛠️ Tech Stack

- HTML
- CSS
- Vanilla JavaScript
- No frameworks
- No build tools
- No external dependencies

---

## 🌐 Hosting

This project can be hosted on any static hosting platform:

- GitHub Pages (recommended)
- Netlify
- Cloudflare Pages

⚠️ Always access the site via **HTTPS**.  
Avoid opening the file locally using `file://` or `content://`.

---

## 🔮 Future Improvements (Optional)

Planned only if a backend is introduced:

- Backend download proxy (true URL hiding)
- ZIP download support
- Screenshot generation
- Improved mobile download reliability

---

## ⚠️ Disclaimer

All game icons and assets are the property of their respective owners (Garena).
This project does not distribute or claim ownership of any game assets.
Assets are loaded dynamically from public CDNs for educational and reference purposes only.

---

## 👤 Author

**Made by MK**

---

## 📌 Project Status

**v1 — Frontend Complete**  
Feature-frozen until a backend is added.
**v2 — Frontend Complete (Pattern-Based Scanning)
Asset scanning is pattern-based (supports multiple ID formats per category)
OB-aware logic implemented
Manual stop control added
UI and feature set finalized
No further frontend features planned
The project is feature-frozen until a backend is introduced
