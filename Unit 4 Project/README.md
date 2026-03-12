# BIOL 101 – Personal Webpage Project
## Setup & Deployment Guide

---

## Step 1 — Customize Your Files

### In `index.html`, find and replace:
| Find | Replace with |
|------|-------------|
| `Your Name` | Your actual name (appears in nav logo, hero, and footer) |
| `Your<br /><em>Name</em>` | Your first and last name split however you like |
| `[Your University]` | Your school name |
| The bio paragraph | Your own personal bio |
| `unit1_project.html`, etc. | The actual filenames of your class HTML projects |
| Card titles and descriptions | Descriptions of your actual projects |

---

## Step 2 — Add Your Photo

1. Get a photo of yourself (JPG or PNG works best)
2. Rename it **`profile.jpg`**
3. Place it in the **`img/`** folder
4. The webpage will automatically display it

The image placeholder text will disappear once a real image loads.

---

## Step 3 — Add Your Class Projects

Copy your previous HTML project files into a `projects/` folder:

```
mywebpage/
  index.html
  css/
    style.css
  img/
    profile.jpg
  projects/
    unit1_project.html    ← your actual project files
    unit2_project.html
    unit3_project.html
```

Then update the `href` links in `index.html` to match your filenames.

---

## Step 4 — Deploy to GitHub Pages

1. **Create a GitHub account** at https://github.com  
   *(Use a professional username — it appears in your URL!)*

2. **Create a new repository** named exactly:
   ```
   yourusername.github.io
   ```
   - Set it to **Public**
   - Do NOT initialize with a README (or you'll need to merge)

3. **Upload your files**:
   - Click "uploading an existing file" on the repo page
   - Drag and drop your entire `mywebpage/` folder contents  
     *(Make sure `index.html` is at the **root** of the repo, not inside a subfolder)*

4. **Enable GitHub Pages** (usually automatic for `username.github.io` repos):
   - Go to repo **Settings → Pages**
   - Source: **Deploy from branch → main → / (root)**
   - Click Save

5. **Visit your site** at:
   ```
   https://yourusername.github.io
   ```
   *(It may take 1–2 minutes to go live after uploading)*

---

## Checklist — Project Requirements

- [ ] Hosted on a real server (GitHub Pages) ✓
- [ ] Built with HTML + CSS files you created ✓  
- [ ] Profile picture scaled to appropriate size ✓
- [ ] Header (your name) and short bio ✓
- [ ] Navigation bar with a logo ✓
- [ ] At least two nav menu items (About, Portfolio) ✓
- [ ] Portfolio menu item with links to class projects ✓

---

## File Structure Reference

```
mywebpage/               ← upload ALL of this to GitHub root
├── index.html           ← main page (GitHub looks for this)
├── css/
│   └── style.css        ← all styling
├── img/
│   └── profile.jpg      ← your photo
└── projects/
    ├── unit1_project.html
    ├── unit2_project.html
    └── unit3_project.html
```
