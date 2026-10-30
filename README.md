# WardenClyffe Power & Light

A satirical website by **Wild Wipes Draws** about a fictional company finishing Nikola Tesla's Wardenclyffe Tower. Five pages (Home, Technology, Plans & Pricing, About, Investors) in a single `index.html`, with a disclaimer in the footer.

## Publish with GitHub Pages

1. Create a new repository on GitHub and upload everything in this folder (`index.html`, `images/`, `README.md`, `.nojekyll`).
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set Source to **Deploy from a branch**, pick `main` and `/ (root)`, and save.
4. Your site will be live at `https://<your-username>.github.io/<repo-name>/` in a minute or two.

To use your own domain or subdomain, add it under **Settings → Pages → Custom domain** and point a CNAME record at `<your-username>.github.io`.

## Changing photos

Photos live in `images/`. Replace a file with a new one using the **same name** and it shows up automatically:

| File | Where it appears |
|---|---|
| `home-hero.jpg` | Big banner at the top of Home (not added yet, shows a navy background until you add one) |
| `home-feature.jpg` | Home, "Residential service" section |
| `tower-feature.jpg` | Technology page |
| `plans-coverage.jpg` | Plans & Pricing, "Service area" |
| `history-archive.jpg` | About page |
| `board-1.gif`, `board-2.jpg`, `board-3.jpg` | Investors, Leadership portraits |

Using a different file type (like `.png`)? Update the matching path in the `PHOTOS` list near the bottom of `index.html`.

## Note

The contact form is for show only and does not send or store anything.
