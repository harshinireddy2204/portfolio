# Harshini Reddy | Personal Portfolio

Interactive portfolio showcasing my work across data engineering, AI systems, and IoT hardware.

**Live:** [harshinireddy2204.github.io/portfolio](https://harshinireddy2204.github.io/portfolio)

## Tech

Pure HTML/CSS/JS. No build step, no frameworks, no dependencies. Scroll triggered fade-in animations via Intersection Observer. Responsive with mobile nav and fluid typography.

## Local Preview

Open `index.html` in your browser. Or use VS Code Live Server:

```
cd C:\Users\harsh\portfolio
code .
```
Right-click index.html and select "Open with Live Server".

## Deploy to GitHub Pages (Free)

### 1. Create the repo

Go to [github.com/new](https://github.com/new) and create a public repo called `portfolio`.

### 2. Push

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

1. Go to your repo, then Settings, then Pages
2. Under Source, select Deploy from a branch
3. Branch: `main`, Folder: `/ (root)`
4. Click Save
5. Your site will be live in about a minute at:

```
https://harshinireddy2204.github.io/portfolio
```

### 4. Add to LinkedIn

Copy the URL and paste it in your LinkedIn Featured section or Website field.

## File Structure

```
portfolio/
├── index.html
├── assets/
│   └── profile.png
├── .gitignore
└── README.md
```

## Photo Setup

Before pushing, copy your photo into the repo:

```bash
copy "C:\Users\harsh\OneDrive\Pictures\LinkedIN.png" "C:\Users\harsh\portfolio\assets\profile.png"
```

## Customization

Everything lives in `index.html`. Edit text directly. Colors are in the `:root` CSS variables at the top.