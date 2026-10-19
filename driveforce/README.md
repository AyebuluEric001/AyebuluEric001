# DriveForce Rider Website

Single-file responsive marketing page (`index.html`) for the DriveForce rider app.

## Before launch
Edit the `CONFIG` object at the top of the script in `index.html`:
- `stores.googlePlay`, `stores.appStore`: real store URLs (blank = button shows a "not configured" message)
- `links.login`, `links.signup`, `links.privacy`, `links.terms`: real routes / pages
- `rating`: confirm the 5.0 / 20+ reviews figure from the design reference, or set to `null`

Draft FAQ answers (registration fee, service areas, delivery issues) are flagged `draft: true` in `FAQS` and need confirmed policy text.
Illustrations (hand, ID card, rider) are CSS/SVG approximations; replace with real assets if available.
