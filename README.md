# diogoccprado.github.io

Static personal portfolio for Diogo Prado, focused on robotics software, perception,
localization, mapping, control, and robot learning.

The public site target is:

```text
https://diogoccprado.github.io
```

## Structure

```text
diogoccprado.github.io/
├── index.html
├── styles.css
├── assets/
│   └── README.md
├── README.md
└── GITHUB_PROFILE_PORTFOLIO_CHECKLIST.md
```

## Run Locally

Because this site has no build step, you can open `index.html` directly in a
browser.

For a local server preview:

```bash
cd ~/diogoccprado.github.io
python3 -m http.server 8080
```

Then open:

```text
http://localhost:8080
```

## Edit Content

- Update text, links, publications, and project cards in `index.html`.
- Update colors, spacing, typography, grids, and placeholders in `styles.css`.
- Keep claims conservative and avoid adding metrics, awards, or affiliations unless
  they are documented.
- Keep repository links explicit so they are easy to audit later.

## Add Images

Place images in `assets/`. The CSS already looks for these filenames:

- `assets/profile.jpg`
- `assets/argus-preview.jpg`
- `assets/hovercraft-preview.jpg`
- `assets/robocup-preview.jpg`
- `assets/lidar-calibration-preview.jpg`
- `assets/go2-preview.jpg`
- `assets/aerial-mapping-preview.jpg`
- `assets/genai-preview.jpg`

If an image is missing, the page shows a dark blue placeholder instead of a broken
image icon.

## Deploy

GitHub Pages serves `index.html` from the root of the `main` branch for a repository
named `diogoccprado.github.io`.

To publish updates:

```bash
cd ~/diogoccprado.github.io
git status
git add index.html styles.css README.md assets/README.md
git commit -m "Redesign robotics portfolio site"
git push
```

Do not push until the page has been reviewed locally.

## TODOs

- Add real profile photo at `assets/profile.jpg`.
- Add project screenshots and robot photos in `assets/`.
- Add LinkedIn URL.
- Add contact email or obfuscated email.
- Add CV / resume PDF, for example `assets/Diogo-Prado-CV.pdf`.
- Replace TODO project page, paper, notes, and private repo links as they become
  public.
