# InteractiveAvatar — Project Page

Project page for **InteractiveAvatar: Real-Time Streaming Video Generation for
Consistent and Intent-Aware Avatars** (ECCV 2026).

- Paper: https://arxiv.org/abs/2606.22905
- page: https://caiguijiang.github.io/authors/quanyuesong/

## Structure

```
.
├── index.html            # the single-page site
├── static/
│   ├── css/index.css     # styles
│   └── js/index.js       # BibTeX copy button
├── assets/               # figures & videos (see assets/README.md)
└── .nojekyll             # serve files as-is on GitHub Pages
```

## Local preview

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy (GitHub Pages)

Pages is served from the `main` branch root. After pushing, the site is
available at `https://caiguijiang.github.io/authors/quanyuesong/`.

## Editing

- Replace figure images in `assets/` with your own exports.
- Update author affiliations and the Code link (marked with `EDIT:` comments).