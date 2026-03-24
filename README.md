# DigiCraft Design – Portfolio Website

Portfolio of **Carla Reyes Vargas** — Web & UX Designer based in Raleigh, NC.  
Live at: [digicraft.design](https://digicraft.design)

---

## 📁 File Structure

```
digicraft-portfolio/
├── index.html              ← Homepage
├── about.html              ← About page
├── work.html               ← Work/projects listing
├── contact.html            ← Contact page
├── css/
│   └── style.css           ← All styles
├── img/
│   └── logo.png            ← Your logo (add this!)
└── projects/
    ├── community-food-bank.html
    ├── safedate-app.html
    ├── cozy-corner-bnb.html
    └── macon-county.html
```

---

## 🚀 How to Set Up on GitHub Pages

1. Create a new GitHub repository named `digicraft-portfolio` (or any name)
2. Upload all these files maintaining the folder structure
3. Go to **Settings → Pages**
4. Set Source to **"Deploy from a branch"** → `main` → `/ (root)`
5. Click Save — your site will be live at `https://yourusername.github.io/digicraft-portfolio`

## 🌐 Connect Your Custom Domain (digicraft.design)

### In GitHub Pages Settings:
1. Go to Settings → Pages → Custom domain
2. Type `digicraft.design` and click Save
3. GitHub will give you DNS records to add

### In Porkbun:
1. Log in → Your domain → DNS
2. Add these records:
   - **A record**: `@` → `185.199.108.153`
   - **A record**: `@` → `185.199.109.153`
   - **A record**: `@` → `185.199.110.153`
   - **A record**: `@` → `185.199.111.153`
   - **CNAME**: `www` → `yourusername.github.io`
3. Save and wait up to 48 hours

---

## ✏️ What You Need to Customize

### Replace placeholders marked with comments:
- `img/logo.png` — add your actual logo PNG (transparent background)
- Headshot image in hero and about sections
- Project screenshots in each `projects/*.html` file
- Figma embed URLs — get from Figma: Share → Get Embed Code
- Your actual email address (contact.html)
- Your LinkedIn URL (all pages)
- Your resume Google Drive PDF link (all nav bars)
- Your Formspree form ID (contact.html) — free at formspree.io

---

## 🎨 Brand Colors

| Variable      | Hex       | Use                    |
|---------------|-----------|------------------------|
| `--gold`      | `#d4a853` | Accent, CTAs, labels   |
| `--navy`      | `#1a2530` | Background             |
| `--navy-mid`  | `#2c3e50` | Secondary background   |
| `--navy-card` | `#233040` | Cards, panels          |
| `--teal`      | `#2e6b6b` | Intro band, accents    |
| `--green`     | `#5b8c5a` | Skill dots, tags       |

---

Built with plain HTML, CSS, and a little JavaScript. No frameworks needed. 🌱
