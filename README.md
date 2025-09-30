# Campus Threads

A clean, beginner-friendly e‑commerce demo built with **HTML, CSS, and JavaScript**. 
It’s designed to be easy to read, easy to modify, and checklist‑friendly for typical college assignments.

## Features
- Semantic HTML (header/nav/main/section/aside/footer)
- Responsive layout (mobile‑first, CSS flex + grid)
- Accessible navigation (skip link, alt text, labels, aria‑attributes)
- Product catalog rendered from `assets/data/products.json`
- Search + category filter + sort
- Cart persisted in `localStorage` (add/remove/update quantities)
- Simple product detail pages (querystring `?id=...`)
- Contact form with basic client‑side validation (no backend required)
- Reusable components (header/footer) injected by JS for consistency
- Neatly organized file/folder structure with clear comments

## Folder Structure
```
ecommerce-site/
├─ index.html
├─ products.html
├─ product.html
├─ cart.html
├─ about.html
├─ contact.html
├─ 404.html
├─ README.md
└─ assets/
   ├─ css/
   │  └─ styles.css
   ├─ js/
   │  ├─ app.js
   │  ├─ router.js
   │  ├─ products.js
   │  ├─ cart.js
   │  └─ ui.js
   ├─ data/
   │  └─ products.json
   └─ img/
      ├─ logo.svg
      └─ placeholders/*.jpg
```

## How to Run Locally
1. Download this folder or the ZIP from ChatGPT.
2. Open `index.html` in your browser.

> If you double‑click and Chrome blocks local JSON fetching, use a simple local server:
- Python: `python -m http.server 8000` then visit http://localhost:8000
- VS Code: Install “Live Server”, open `index.html` with it.

## Deploy to GitHub Pages
1. Create a new repo on GitHub (e.g., `campus-threads`).
2. Upload all files in this folder to the repo (or drag/drop via GitHub UI).
3. In the repo, go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
5. Choose branch (usually `main`), and folder **/root** (if asked).
6. Click **Save**. Your site will be live in a minute at the URL shown there.

## Editing Tips
- Change the brand name and colors near the top of `assets/css/styles.css`.
- Update products in `assets/data/products.json` (name, price, description, image, category, rating).
- Logos and images are in `assets/img/`. Replace the logo SVG or placeholder photos as you like.
- All JS is heavily commented—search for `TODO:` markers to customize quickly.

---

© Campus Threads. For educational use.
