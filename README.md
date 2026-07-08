# diogoccprado.github.io

Personal robotics portfolio site, deployed via [GitHub Pages](https://pages.github.com/).

## Structure

```
diogoccprado.github.io/
├── index.html                              # Main portfolio page
├── styles.css                              # Site styles
├── README.md                               # This file
└── GITHUB_PROFILE_PORTFOLIO_CHECKLIST.md   # Portfolio setup checklist
```

## Edit

1. Update project cards in `index.html` as repos are renamed or new media is added.
2. Fill in TODO placeholders: LinkedIn, email, CV, coursework links, project images.
3. Keep copy conservative — no invented metrics or claims.

## Deploy

### First-time setup

```bash
cd ~/diogoccprado.github.io
git init
git add .
git commit -m "Initial portfolio site scaffold"
git branch -M main
git remote add origin git@github.com:diogoccprado/diogoccprado.github.io.git
git push -u origin main
```

GitHub Pages serves `index.html` from the `main` branch automatically for a repo named `username.github.io`.

### Updates

```bash
git add index.html styles.css
git commit -m "Update portfolio content"
git push
```

## Local preview

```bash
cd ~/diogoccprado.github.io
python3 -m http.server 8080
# Open http://localhost:8080
```

## Related repos

- Profile README: `~/diogoccprado`
- Project repos: see `GITHUB_PROFILE_PORTFOLIO_CHECKLIST.md`
