# Yutaka3DLab website

Official static website for Yutaka3DLab.

## Repository structure

```text
yutaka3dlab.github.io/
├── index.html
├── README.md
└── assets/
    ├── css/
    │   └── styles.css
    └── images/
        ├── brand/
        │   └── yutaka3dlab-logo.png
        └── products/
            ├── homepod-mini-mount.jpg
            ├── apple-tv-4k-mount.jpg
            └── router-mount.jpg
```

## Image naming convention

Use lowercase kebab-case:

`product-device-purpose-view.ext`

Examples:

- `homepod-mini-duplex-outlet-mount-front.jpg`
- `homepod-mini-plug-in-mount-installed.jpg`
- `apple-tv-4k-wall-mount-installed.jpg`
- `apple-tv-4k-wall-mount-kit.jpg`
- `router-wall-mount-front.jpg`
- `yutaka3dlab-logo.png`

### Rules

1. Lowercase only.
2. Use hyphens, never spaces or underscores.
3. Keep names descriptive but reasonably short.
4. Do not use generic names such as `image1.jpg`, `final2.png`, or `new-photo.jpg`.
5. Add a view/purpose suffix when useful: `front`, `side`, `installed`, `kit`, `detail`, `hero`.
6. Prefer `.jpg` for photographs and renders without transparency.
7. Prefer `.png` for logos or graphics that need transparency.
8. Prefer `.svg` for logos/icons if you have a clean vector source.

## Adding a new product image

1. Add the image to `assets/images/products/`.
2. Give it a descriptive kebab-case filename.
3. Reference the same path in `index.html`.
4. Commit and push.

## Notes

This version has no framework, external JavaScript library, or paid dependency.
It is designed to work directly on GitHub Pages.
