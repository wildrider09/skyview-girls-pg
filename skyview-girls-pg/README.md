# SkyView Girls PG — Website

A single-page website for **SkyView Girls PG, Dehradun**, built on the free
[HTML5 UP "Read Only"](https://html5up.net/read-only) template (CCA 3.0 license)
and re-themed in sky-blue.

## Sections
About · Amenities · Rooms & Pricing · Gallery · Location (live Google Map) · Contact

---

## ✅ Before you go live — replace the placeholders

The site works as-is, but these values are **placeholders** you should update in `index.html`:

| What | Where | Current placeholder |
|------|-------|---------------------|
| Phone number | `tel:+910000000000` (appears 3×) | `+91 00000 00000` |
| WhatsApp number | `https://wa.me/910000000000` | `910000000000` (countrycode+number, no `+`) |
| Email | `info@skyviewgirlspg.com` | placeholder address |
| Full address | Contact + Location sections | "Dehradun, Uttarakhand" |
| Instagram / Facebook | sidebar `footer .icons` | generic links |
| Room prices | "Rooms & Pricing" section `.price` | ₹9,000 / ₹7,000 / ₹5,500 (indicative) |

### Replace the photos
The images in `images/` are **generated placeholders** (`.svg`). Swap them with real
photos (same names, or update the `src` in `index.html`). Recommended:

- `banner.svg` → wide building/exterior shot (~2160×700)
- `room-single.svg`, `room-double.svg`, `room-triple.svg` → room photos (~700×440)
- `gallery-*.svg` → dining / study / common-area photos
- `logo.svg` → your PG logo (square)

### Make the contact form actually send
A static site can't email on its own. To receive submissions, sign up at
[Formspree](https://formspree.io) (free tier) and set the form in the Contact
section to:

```html
<form method="POST" action="https://formspree.io/f/YOUR_FORM_ID">
```

---

## 🚀 Host on GitHub Pages

1. Create a new repository on GitHub (e.g. `skyview-girls-pg`).
2. From this folder:
   ```bash
   git init
   git add .
   git commit -m "Initial SkyView Girls PG website"
   git branch -M main
   git remote add origin https://github.com/<your-username>/skyview-girls-pg.git
   git push -u origin main
   ```
3. On GitHub: **Settings → Pages → Build and deployment**, set
   **Source = Deploy from a branch**, **Branch = `main` / `root`**, then **Save**.
4. Your site goes live at `https://<your-username>.github.io/skyview-girls-pg/`
   within a minute or two.

> Want it at `https://<your-username>.github.io/` instead? Name the repo
> `<your-username>.github.io` and push the same files.

### Custom domain (optional)
Add a `CNAME` file containing your domain (e.g. `skyviewgirlspg.com`) and configure
the DNS records as described in GitHub Pages → Custom domain.

---

## Credits
Template: [HTML5 UP](https://html5up.net) — "Read Only" by @ajlkn, CCA 3.0.
Please keep the HTML5 UP attribution in the footer per the license.
