# Oak Park Barber Salon — GitHub Pages files

This version keeps the site-owned images inside the repository instead of hotlinking them from Hostinger or Pinterest.

## Folder structure

```text
index.html
assets/
  images/
    hero.jpg
    oak-park-logo.png
    storefront-sketch.webp
    gallery-01.webp ... gallery-08.webp
    image-fallback.svg
```

## Publish on GitHub Pages

1. Upload `index.html` and the entire `assets` folder to the same repository root.
2. In GitHub, open **Settings → Pages**.
3. Set the source to **Deploy from a branch**, select `main`, and choose `/ (root)`.
4. Do not rename only the image files without updating the matching paths in `index.html`.

The HTML uses relative paths such as `assets/images/gallery-01.webp`. Relative paths are important for project sites published at `username.github.io/repository-name/`.
