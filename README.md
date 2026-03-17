# Evan Stratemeyer — Portfolio Site

## File Structure

```
/
├── index.html              ← Main homepage (single scroll)
├── css/
│   └── styles.css          ← All shared styles
├── js/
│   └── main.js             ← All shared scripts (scroll reveal, skill bars, nav)
├── assets/
│   └── images/             ← Drop your photos here
│       ├── dbf-1.jpg
│       ├── go-kart-1.jpg
│       └── ...
└── projects/
    ├── design-build-fly.html
    ├── tap-holder.html
    ├── go-kart.html
    ├── fpv-drone.html
    ├── rubiks-cube.html
    └── additional.html
```

## Adding Photos

1. Drop your photo into `assets/images/`
2. In the project page, replace the `.photo-placeholder` div with:

```html
<img src="../assets/images/your-photo.jpg" alt="Description" class="project-image">
```

## Deploying to GitHub Pages

1. Upload all files maintaining the folder structure above
2. The repo root should contain `index.html`
3. Enable GitHub Pages from Settings → Pages → Deploy from main branch
4. Site will be live at `https://yourusername.github.io`
