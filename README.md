# Creov Canvas portfolio

Static portfolio site (no build step).

## Publish on GitHub Pages
1. Create a repository and upload everything in this folder (index.html, projects.json, images/).
2. Repository **Settings → Pages → Build and deployment → Deploy from a branch**, choose `main` and `/ (root)`.
3. Your site appears at `https://<username>.github.io/<repository>/`.

## Update content
Edit `projects.json` on GitHub (pencil icon) and commit:
- `site`: name, about, skills (max 6), portrait path, 5 categories, contact details.
- `projects`: add `{ "category": "Branding", "image": "images/my-file.jpg" }` for each work. Max 10 per category are shown.
- Upload the image files into the `images/` folder.

Changes go live about a minute after you commit.

## Notes
- The password Admin screen only works inside claude.ai. On GitHub, you edit `projects.json` instead; GitHub login is the admin protection.
- Navigation: mouse wheel, swipe, arrow keys, dots on the right.
