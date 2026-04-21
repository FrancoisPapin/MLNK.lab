# MLKN.lab
MultiLayer Knowledge Network, Ideas Laboratory

# MultiLayer Interdisciplinarity Knowledge Network
### By François Papin · [LinkedIn](https://www.linkedin.com/in/francoispapin/)

> Interactive knowledge network maps synthesising the research state of the art  
> for 10 academic disciplines + a multi-level interdisciplinary map.

**License:** MIT · **Date:** April 21, 2026

---

## 📁 Files

| File | Description |
|------|-------------|
| `index.html` | Dashboard — landing page with links to all maps |
| `interdisciplinarity.html` | ★ Multi-level map (Layer A/B/C + Bridges) |
| `philosophy.html` | Discipline map — Philosophy |
| `cognitive_psychology.html` | Discipline map — Cognitive Psychology |
| `neuroscience.html` | Discipline map — Neuroscience |
| `education_science.html` | Discipline map — Education Science |
| `human_rights.html` | Discipline map — Human Rights |
| `environmental_science.html` | Discipline map — Environmental Science |
| `computer_science.html` | Discipline map — Computer Science |
| `sociology.html` | Discipline map — Sociology |
| `language_science.html` | Discipline map — Language Science |
| `systems_science.html` | Discipline map — Systems Science |
| `README.md` | This file |

---

## 🚀 GitHub Pages — Step by Step

### Step 1 — Create a GitHub Repository

1. Go to [github.com](https://github.com) → Sign in
2. Click **"+"** → **"New repository"**
3. Name it: `knowledge-networks` (or any name you like)
4. Set visibility: **Public** *(required for free GitHub Pages)*
5. Click **"Create repository"**

---

### Step 2 — Upload the Files

**Option A — Drag and drop (simplest):**

1. Open your repository on GitHub
2. Click **"Add file"** → **"Upload files"**
3. Drag **all 12 HTML files** + `README.md` into the upload area
4. Scroll down → write a commit message: `Add knowledge network maps`
5. Click **"Commit changes"**

**Option B — Git command line:**

```bash
# Clone your empty repo
git clone https://github.com/YOUR-USERNAME/knowledge-networks.git
cd knowledge-networks

# Copy all files into this folder, then:
git add .
git commit -m "Add Multi-level Interdisciplinarity Knowledge Network maps"
git push origin main
```

---

### Step 3 — Enable GitHub Pages

1. In your repository, click **"Settings"** (top menu)
2. In the left sidebar, click **"Pages"**
3. Under **"Source"**, select:
   - Branch: `main`
   - Folder: `/ (root)`
4. Click **"Save"**
5. Wait ~60 seconds, then refresh the page
6. GitHub will show: **"Your site is published at `https://YOUR-USERNAME.github.io/knowledge-networks/`"**

---

### Step 4 — Access Your Published Maps

Your maps will be live at:

```
https://YOUR-USERNAME.github.io/knowledge-networks/
https://YOUR-USERNAME.github.io/knowledge-networks/interdisciplinarity.html
https://YOUR-USERNAME.github.io/knowledge-networks/philosophy.html
https://YOUR-USERNAME.github.io/knowledge-networks/neuroscience.html
... (and so on for each discipline)
```

*Replace `YOUR-USERNAME` with your actual GitHub username.*

---

### Step 5 — Share the Link

Copy the URL and share on LinkedIn, in papers, or embed in websites.  
All maps work directly in any modern browser — no server required.

---

## ✏️ How to Update a Map

1. Edit the HTML file locally
2. Go to your GitHub repo → find the file → click the **pencil icon** to edit
3. Or use `git push` from the command line
4. Changes go live in ~30 seconds

---

## 📋 Optional: Custom Domain

If you have your own domain (e.g. `francoispapin.com`):

1. In **Settings → Pages**, enter your domain under **"Custom domain"**
2. Add a `CNAME` file in the repo root containing just your domain:
   ```
   francoispapin.com
   ```
3. Update your DNS: add a `CNAME` record pointing to `YOUR-USERNAME.github.io`

---

## 🔧 Technical Notes

- All maps are **self-contained HTML files** — no build step, no dependencies to install
- Visualizations use **D3.js v7** loaded from CDN (`d3js.org`)
- Fonts loaded from **Google Fonts** CDN
- All interactivity is pure JavaScript — works offline once cached
- Maps are **mobile-friendly** and **responsive**

---

## ⚖️ License

```
MIT License

Copyright (c) 2026 François Papin

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
```
