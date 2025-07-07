# Email-Signature Copy Helper

Preview your HTML signature, then copy **either** the raw code **or** the fully rendered signature ready for pasting into Gmail, Outlook, or any rich-text field.

![image](https://github.com/user-attachments/assets/1c17a422-349b-4eff-adc3-5d6b9eb12bad)
![image](https://github.com/user-attachments/assets/4edcbd45-353c-4696-8b1e-29c4ad00d0bf)


---

## ✨ Why you might want this

* **Gmail quirks** – Gmail’s signature editor often strips styles or shows raw HTML when you paste.  
* **No extensions required** – Works offline, in any modern browser.  
* **One-click workflow** – Paste → *Copy Signature* → Ctrl + V inside Gmail → Done.  
* **Live preview** – Instantly verify that links, colours, and layout look right before you send your first email.

---

## 📦 Features

| Feature | What it does |
|---------|--------------|
| **Live preview** | Renders your HTML as you type/paste so you can sanity-check spacing, colours, links, etc. |
| **Copy Code** | Copies the raw HTML markup to the clipboard. |
| **Copy Signature** | Copies the rendered signature as rich HTML (Clipboard API + fallback) – pastes exactly as it looks. |
| **Lightweight** | Pure HTML + CSS + vanilla JS — no dependencies, < 8 KB minified. |

---

1. Paste your email signature HTML into the textarea.
2. Click **Copy Signature**.
3. In Gmail **Settings → Signature**, place your cursor in the editor and paste (Ctrl + V / Cmd + V).
4. Save changes. 🎉

---

## 🛠 Development

*All the logic lives in `index.html`.*
If you want to tweak styles or add features (dark-mode, drag-and-drop, etc.), edit that file and open a PR – contributions welcome!

---

## 📝 License

MIT © 2025 Gabriel Dalton – use freely, attribution appreciated but not required.
