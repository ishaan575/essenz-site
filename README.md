# Essenz Static Storefront

This is a zero-build static website for Essenz. It can be deployed for free because it only needs:

- `index.html`
- `styles.css`

## Local Preview

Run:

```bash
node server.mjs
```

Then open:

```text
http://127.0.0.1:4173
```

## Free Deployment Options

### GitHub Pages

1. Create a GitHub repository.
2. Upload `index.html` and `styles.css`.
3. Go to repository Settings > Pages.
4. Set the source to the main branch and root folder.
5. GitHub will provide a free `github.io` URL.

### Netlify

1. Go to Netlify and choose "Add new site".
2. Drag this folder into the deploy screen.
3. Netlify will publish it with a free URL.

### Cloudflare Pages

1. Create a Cloudflare Pages project.
2. Connect the GitHub repository.
3. Use no build command.
4. Set the output directory to `/`.

## Notes

The product images and product links currently point to `https://essenz.group/`, so this static site can work as a polished front page while the current WooCommerce store continues handling product detail pages and checkout.
