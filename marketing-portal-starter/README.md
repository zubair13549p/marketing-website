# Marketing Management Portal — Starter Pack

A super-simple website you can open directly in your browser. Students enter their **College ID** to access a searchable list of **Marketing Management terms**.

> ⚠️ This is a beginner-friendly, **front-end only** project. It is good for a demo or class use. For real protection (so others cannot see data), you must add a backend (Phase 2).

---

## 📦 What's inside
- `index.html` — Login page
- `home.html` — Search page (only after login)
- `style.css` — Styles (design)
- `data.js` — Your terms (edit this to add many terms)
- `script.js` — Login + search logic
- `README.md` — This guide

---

## 🧰 Step 1 — Open the project
1. Install **VS Code** (https://code.visualstudio.com/)
2. Open VS Code → **File → Open Folder…** → choose this folder `marketing-portal-starter`
3. (Optional but recommended) Install the **Live Server** extension in VS Code.

---

## ▶️ Step 2 — Run the website
**Option A: With Live Server**  
- Right-click `index.html` → **Open with Live Server**  
- A browser tab opens — you are on the Login page.

**Option B: Without Live Server**  
- Just double-click `index.html` in your file explorer.

---

## 🔑 Step 3 — Try logging in
- Sample IDs allowed: `BBA101`, `BBA102`, `BBA103`, `BBA104`, `BBA105`
- Edit this list in `script.js` (the `validIds` array).

---

## 🔎 Step 4 — Search terms
- Go to the search page after login.
- Start typing (e.g., **AIDA**, **Segmentation**, **Brand**).
- It searches both the **term** and the **definition**.

Add or edit terms in `data.js`.  
Example:

```js
const terms = [
  { word: "AIDA", meaning: "Attention, Interest, Desire, Action — a classic model..." },
  // Add more here...
];
```

---

## ✏️ Step 5 — Customize
- Change the name and text in `index.html` and `home.html`.
- Adjust colors in `style.css`.
- Add more IDs in `script.js`.

---

## 🔐 Phase 2 — Real authentication (optional, later)
Front-end login can be bypassed by advanced users. For true protection:
- Make a backend (Node.js + Express) and a database (SQLite/MySQL).
- Store student IDs in the database and check on the server.
- Serve the data from the server (not from `data.js`).

If you want, I can give you a **Phase 2** starter later.

---

## 💡 Common fixes
- **Stuck on login page?** Your ID is not in `validIds` or you typed lower/upper case wrong.
- **Blank results?** You may have an empty search. Clear the box to show all terms.
- **Live Server not found?** Install the extension from VS Code marketplace.

---

Happy building! 🎉
