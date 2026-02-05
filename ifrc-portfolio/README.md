# IFRC Portfolio Registry

Enterprise Architecture portfolio management app for IFRC products, services, and applications.

## Quick Start (Local)

```bash
npm install
npm run dev
```

Open http://localhost:5173/ifrc-portfolio/

## Deploy to GitHub Pages

### One-time setup:

1. Create a new GitHub repo called `ifrc-portfolio`
2. Edit `package.json` — replace `YOUR_GITHUB_USERNAME` with your actual GitHub username
3. Edit `vite.config.js` — if your repo name is different, update the `base` path

### Push and deploy:

```bash
# Initialize git and push
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/ifrc-portfolio.git
git push -u origin main

# Deploy to GitHub Pages
npm run deploy
```

4. Go to your repo on GitHub → Settings → Pages
5. Under "Source", select **Deploy from a branch**
6. Select branch: **gh-pages** / folder: **/ (root)**
7. Click Save

Your app will be live at: `https://YOUR_USERNAME.github.io/ifrc-portfolio/`

## Features

- 📊 Table, Grid, and Dashboard views
- ✏️ Full CRUD (Create, Read, Update, Delete)
- 🔍 Filter by Category, Archetype, Strategy, Portfolio
- 📈 Charts: Pie (category/strategy), Radar (assessment scores), Bar (cost breakdown)
- ⬇️ CSV export
- 📝 User notes on each item
- 🎨 Dark theme with IFRC branding
