# Shailee Foods Website

A clean, responsive static website for **Shailee Foods** — a food processing business in Vadodara specialising in vacuum packing and food dehydration.

## Pages

| File | Description |
|---|---|
| `index.html` | Home page — hero, services overview, why-us, CTA |
| `vacuum-packing.html` | Detail page for vacuum packing services |
| `dehydrating.html` | Detail page for food dehydration services |
| `contact.html` | Contact page with phone, address, form, and map |
| `styles.css` | All shared styles (responsive) |

---

## 🚀 Deploy to GitHub Pages (Step-by-Step)

### 1. Create a GitHub repository

1. Go to [https://github.com](https://github.com) and sign in (or create a free account).
2. Click the **+** icon (top right) → **New repository**.
3. Name it exactly: `shailee-foods` (or any name you like).
4. Keep it **Public**.
5. Do **not** add a README (we already have one).
6. Click **Create repository**.

---

### 2. Push the website files

Open a terminal in this folder and run the following commands one by one:

```bash
# Initialise git (only needed the very first time)
git init

# Add all files
git add .

# Commit
git commit -m "Initial website commit"

# Link to your GitHub repository (replace YOUR_USERNAME and REPO_NAME)
git remote add origin https://github.com/YOUR_USERNAME/shailee-foods.git

# Push to GitHub
git push -u origin main
```

> **Tip:** If your default branch is called `master` instead of `main`, replace `main` with `master` in the last command.

---

### 3. Enable GitHub Pages

1. On GitHub, open your repository.
2. Click **Settings** → scroll down to **Pages** (left sidebar).
3. Under **Source**, select **Deploy from a branch**.
4. Choose branch: **main** (or master) · folder: **/ (root)**.
5. Click **Save**.

GitHub will show a green banner with your live URL — typically:

```
https://YOUR_USERNAME.github.io/shailee-foods/
```

The site is usually live within **1–2 minutes**.

---

### 4. Updating the website later

Whenever you make changes, run:

```bash
git add .
git commit -m "Update website"
git push
```

GitHub Pages will automatically redeploy.

---

## Customisation Tips

- **Business name**: Search and replace `Shailee Foods` / `ShaileeFoods` across all files to change the brand name.
- **Phone number**: Currently `+91 93746 39925` — update in `index.html`, `vacuum-packing.html`, `dehydrating.html`, `contact.html`, and `styles.css` footer sections.
- **Address**: Update in all four HTML files in the footer `<address>` block.
- **Colours**: Edit the CSS variables at the top of `styles.css` (`:root` block).
