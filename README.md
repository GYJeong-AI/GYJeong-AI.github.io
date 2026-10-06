[![English — current language](docs/images/language-en-active.svg)](README.md) [![한국어](docs/images/language-ko-idle.svg)](README.ko.md)

# GY.JEONG

GY.JEONG's portfolio website showcasing web, app, and game projects.

- Website: [gyjeong-ai.github.io](https://gyjeong-ai.github.io/)
- Contact: [gyjeongai@gmail.com](mailto:gyjeongai@gmail.com)

## Files

- `index.html`: Page content, styles, and interactions
- `assets/images/`: WebP images used in project cards and detail views
- `og-image-v1.png`: Link preview image
- `robots.txt`, `sitemap.xml`: Search engine guidance
- `.nojekyll`: Disables Jekyll processing on GitHub Pages
- `app-ads.txt`: App advertising seller information
- `googlef8298d34093e4625.html`: Google Search Console ownership verification
- `motionsports-kart-v1.png`, `motionsports-tennis-v1.png`: Original images kept at the root for compatibility with existing links

## Editing and previewing

The site uses HTML, CSS, and JavaScript without a separate build tool. Edit the page in `index.html` and keep project images in `assets/images/`. When renaming an image, also check its `src`, `srcset`, and `data-full-src` paths.

Run `python3 -m http.server 8000` from the repository root, then open [localhost:8000](http://localhost:8000/) to preview the site. After making changes, check the mobile and desktop layouts and confirm that project detail images open correctly.

## Deployment

This is a static site served through GitHub Pages. Review changes before publishing them according to the repository's GitHub Pages deployment settings.

Keep the repository name and the root paths of `.nojekyll`, `app-ads.txt`, `googlef8298d34093e4625.html`, `robots.txt`, `sitemap.xml`, and `og-image-v1.png` unchanged to preserve the site URL and verification paths.
