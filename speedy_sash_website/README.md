# Speedy Sash Website

A simple static website designed for GitHub Pages. No backend required.

## 1. Add your main image
Put your image in `images/` and replace the placeholder `<div>` in `index.html` with:

```html
<img src="images/your-image.jpg" alt="Speedy Sash" />
```

You can also use a PNG or WebP.

## 2. Add your Google Form
In Google Forms:
1. Open the form.
2. Click Send.
3. Select the Embed (`<>`) option.
4. Copy the iframe's `src` URL.
5. In `index.html`, replace `YOUR_GOOGLE_FORM_EMBED_URL` with that URL.

## 3. Add Instagram
Find this line in `index.html`:

```html
<a class="instagram-button" href="#" ...>
```

Replace `#` with your Instagram profile URL.

## 4. Add gallery photos
Replace the four placeholder files in `images/` with your own files named:
- gallery-1.svg
- gallery-2.svg
- gallery-3.svg
- gallery-4.svg

Or change the filenames in `index.html`.

The gallery opens images in a simple full-screen lightbox.

## 5. Publish with GitHub Pages
Create a GitHub repository, upload the files, then enable GitHub Pages under:
Settings → Pages → Deploy from a branch → main → /(root).

For a custom domain, add it under the same Pages settings.
