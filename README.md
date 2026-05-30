# Portfolio

> Personal portfolio website — cybersecurity analyst, full-stack developer, and AI builder.

## What it does

Single-page portfolio website with sections for professional background, skills, projects, and contact information. Fully responsive, works on mobile and desktop, with a light/dark theme toggle.

## Sections

- **Hero** — name, title, and social links
- **About Me** — professional background and goals
- **Professional Experience** — work history with role details
- **Featured Projects** — selected projects with descriptions and links
- **Technical Skills** — languages, tools, and certifications
- **Education & Certifications** — degrees and professional certifications
- **Get In Touch** — contact links and social profiles

## Usage

Open `index.html` in any browser. No build step, no server, no dependencies.

```bash
git clone https://github.com/mamuaminu/portfolio.git
cd portfolio
open index.html
```

## Customization

Edit the HTML directly to update:
- Your name, title, and bio (in `index.html`)
- Social links (LinkedIn, GitHub, Twitter, etc.)
- Project descriptions and URLs
- Skills and certifications

## Theme Toggle

Click the sun/moon icon in the top-right to switch between light and dark mode. Theme preference is saved in localStorage.

## Deploy

**GitHub Pages:**
1. Push to a GitHub repo
2. Go to Settings → Pages
3. Select the branch (usually `main`) and `/ (root)`
4. Your site will be live at `https://yourusername.github.io/repo-name`

**Netlify:**
1. Drag and drop the folder onto netlify.com/drop
2. Done — SSL is automatic

**Vercel:**
```bash
npx vercel --prod
```

## Files

```
portfolio/
├── index.html   # Main page
├── styles.css   # All styles
├── script.js    # Theme toggle and interactions
└── README.md   # This file
```

---

By Muhammad Aminu Musa
