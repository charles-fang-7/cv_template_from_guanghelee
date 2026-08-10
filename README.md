# Cheng Fang — Personal Website

A responsive personal website for Cheng Fang, a PhD candidate in Materials Science at Shanghai Jiao Tong University.

## Website

The public site is available at:

**https://charles-fang-7.github.io/cv_template_from_guanghelee/**

## Local preview

```bash
cd /Users/orangecheng/Documents/primary_personal_website
python3 -m http.server 8000
```

Then open `http://localhost:8000` in a browser.

## Customize

- Edit `index.html` for the biography, contact link, and project descriptions.
- Edit `assets/css/main.css` for the visual design.
- Add a portrait as `assets/images/portrait.jpg` and a CV as `assets/docs/Cheng-Fang-CV.pdf` when they are ready.

### Media folders

- `assets/images/` — portrait and any future project images.
- `assets/docs/` — downloadable documents such as the CV.

After adding an asset, reference it from `index.html` with the same path, for example:

```html
<a href="assets/docs/Cheng-Fang-CV.pdf">Download CV</a>
```

## Deployment

The site is deployed automatically through GitHub Pages whenever the `master` branch changes.
