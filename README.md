# Irfan Yuksel — Web Developer Portfolio

A freelance web developer portfolio site, built as a static site with vanilla HTML/CSS/JS (no build step, no dependencies) so it deploys directly on GitHub Pages.

**Live site:** _add your GitHub Pages URL here after deployment_

## Structure

```
index.html                     Portfolio homepage
assets/css/style.css           Portfolio styles
assets/js/script.js            Portfolio nav/menu behavior
demos/dental-landing/          Sample local-business landing page (fictional "BrightSmile Dental")
demos/saas-landing/            Sample SaaS product landing page (fictional "Flowly")
```

Each demo is a fully self-contained sample project used to showcase landing page design and build quality — no real businesses are represented.

## Local preview

No build step required — just open `index.html` in a browser, or serve the folder locally:

```
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deployment

This site is deployed via **GitHub Pages** from the `main` branch (root). Any push to `main` updates the live site automatically.
