# 🍕 GUSTU — Dynamic QR Menu System

## الملفات / Files

| File | Purpose |
|------|---------|
| `index.html` | Customer menu (Arabic + English) |
| `menu.json` | All prices & items — **edit this to update menu** |
| `admin.html` | Admin panel to edit menu visually |
| `qr-setup.html` | QR code generator + GitHub setup guide |

## Setup in 5 minutes

1. Go to **github.com** → Sign up (free)
2. New repository → name: `gustu-menu` → Public → Create
3. Upload all 4 files
4. Settings → Pages → Source: `main` branch → Save
5. Your menu URL: `https://YOUR-USERNAME.github.io/gustu-menu/`
6. Open `qr-setup.html` → paste your URL → generate QR → print!

## Updating prices

**Option A (Visual):** Open `admin.html` → edit prices → Export JSON → copy to GitHub `menu.json`

**Option B (Direct):** Edit `menu.json` directly in GitHub → Commit → Done in 30 seconds

## Password
Admin panel default password: `gustu2024`
Change it in `admin.html` line: `const PASSWORD = 'gustu2024';`
