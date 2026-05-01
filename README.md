# Harshini Reddy — Personal Portfolio

Interactive portfolio site showcasing my journey from IoT hardware projects in Hyderabad to AI-driven data systems at UMass Lowell.

**Live:** [harshinireddy2204.github.io/portfolio](https://harshinireddy2204.github.io/portfolio)

## Tech

- Pure HTML/CSS/JS — no build step, no frameworks, no dependencies
- Scroll-triggered fade-in animations via Intersection Observer
- Responsive (mobile nav, fluid typography)
- Dark editorial design with amber accent

## Local Preview

Just open `index.html` in your browser. Or use VS Code Live Server:

```
cd C:\Users\harsh\portfolio
code .
# Right-click index.html → "Open with Live Server"
```

## Deploy to GitHub Pages (Free Hosting)

### 1. Create the repo on GitHub

Go to [github.com/new](https://github.com/new) and create a repo called `portfolio` (public).

### 2. Push from your local folder

```bash
cd C:\Users\harsh\portfolio
git init
git add .
git commit -m "Initial portfolio"
git branch -M main
git remote add origin https://github.com/harshinireddy2204/portfolio.git
git push -u origin main
```

### 3. Enable GitHub Pages

1. Go to your repo → **Settings** → **Pages**
2. Under "Source", select **Deploy from a branch**
3. Branch: `main`, Folder: `/ (root)`
4. Click **Save**
5. Wait ~1 minute — your site will be live at:

```
https://harshinireddy2204.github.io/portfolio
```

### 4. Add to LinkedIn

Copy the live URL and paste it in your LinkedIn **Featured** section or **Website** field in your profile.

## File Structure

```
portfolio/
├── index.html          ← The entire site (single file)
├── assets/
│   └── profile.png     ← Your LinkedIn photo
├── .gitignore
└── README.md
```

## Customization

Everything is in `index.html`:
- **Content**: Edit the HTML directly — all text, links, and project descriptions are inline
- **Colors**: Change CSS variables at the top (`:root` block)
- **Photo**: Replace `assets/profile.png`
- **LinkedIn URL**: Search for `linkedin.com` in the file and update if needed

## Photo Note

The profile photo is loaded from `assets/profile.png`. Before pushing to GitHub, copy your photo:

```bash
copy "C:\Users\harsh\OneDrive\Pictures\LinkedIN.png" "C:\Users\harsh\portfolio\assets\profile.png"
```