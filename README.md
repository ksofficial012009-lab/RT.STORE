# RT.Gamer.P — GitHub Pages Deployment Guide

## 📁 Project Structure

```
rt-gamer-p/
├── index.html          ← Main page (never rename this)
├── README.md           ← This file
└── assets/
    ├── style.css       ← All styles
    ├── app.js          ← All JavaScript
    └── qr.png          ← Payment QR code image
```

## 🚀 Deploy to GitHub Pages

1. Create a new GitHub repository (e.g. `rt-gamer-p`)
2. Upload **all files** keeping the folder structure above
3. Go to **Settings → Pages**
4. Set Source to **Deploy from a branch → main → / (root)**
5. Click **Save** — your site will be live at:
   `https://YOUR-USERNAME.github.io/rt-gamer-p/`

## 🔄 Updating Assets (No Code Changes Needed)

| Task | What to do |
|------|-----------|
| **Change QR code** | Replace `assets/qr.png` with your new QR image — keep the filename `qr.png` |
| **Change prices** | Edit `index.html` — search for `₹35`, `₹45`, `₹65`, `₹149` |
| **Change features** | Edit the `<ul class="features">` lists in `index.html` |
| **Change voice text** | Edit `VOICE_TEXT` in `assets/app.js` |
| **Change styles/colors** | Edit CSS variables at the top of `assets/style.css` |

## 📱 Responsive Breakpoints

| Screen | Layout |
|--------|--------|
| Mobile (< 480px) | 1 column |
| Tablet (640–1023px) | 2 columns |
| Desktop (≥ 1024px) | 4 columns |
