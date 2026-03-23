# GraphGuard - Hugo Static Site

This is the Hugo static site for GraphGuard, a premium fish finder screen protector brand.

## Prerequisites

- [Hugo](https://gohugo.io/installation/) (Extended version recommended)

## Project Structure

- `data/products.json`: Contains all product data (prices, features, compatibility).
- `content/`: Markdown files for pages (About, Installation, Compatibility, Products).
- `layouts/`: HTML templates for rendering the site.
- `static/css/`: CSS styling.
- `hugo.toml`: Site configuration.

## How to Run Locally

1. Open a terminal in the `graphguard` directory.
2. Run the Hugo development server:
   ```bash
   hugo server -D
   ```
3. Open your browser to `http://localhost:1313`.

## How to Build for Production

1. Open a terminal in the `graphguard` directory.
2. Run the build command:
   ```bash
   hugo
   ```
3. The compiled static site will be generated in the `public/` directory. You can upload the contents of this directory to any static hosting provider (e.g., AWS S3, Netlify, Vercel, GitHub Pages).

## Placeholders

The site uses several placeholders that need to be replaced before launch:
- `[PRODUCT_IMAGE_HELIX_7]`, etc.: Replace with actual product images in `static/images/` and update the templates.
- `[YOUTUBE_INSTALL_VIDEO]`: Replace with actual YouTube embed iframes.
- `[INSTALL_STEP_1]`, etc.: Replace with actual installation step photos.
- `[AMAZON_URL_HELIX_7]`, etc.: Replace with actual Amazon product URLs in `data/products.json`.
