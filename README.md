# SkyView Girls PG — Website

A single-page website for **SkyView Girls PG, Dehradun**, built on the free
[HTML5 UP "Read Only"](https://html5up.net/read-only) template (CCA 3.0 license).

**Sections:** About · Why Us · Amenities · Rooms & Pricing · Gallery · Reviews ·
Location (live Google Map) · FAQ · Contact, plus a floating WhatsApp "Book a Visit" button.

---

## 🎨 Change the theme colour (one line)

The whole site's accent colour is driven by a single CSS variable. Open
`assets/css/custom.css` and edit `--accent` near the top:

```css
:root {
    --accent: #6d28d9;        /* primary brand colour  */
    --accent-dark: #581cae;   /* darker shade (hovers)  */
    --accent-soft: rgba(109, 40, 217, 0.08);
}
```

Ready-to-use palettes (set `--accent` / `--accent-dark`):

| Colour | `--accent` | `--accent-dark` |
|--------|-----------|-----------------|
| Violet (current) | `#6d28d9` | `#581cae` |
| Teal | `#0f9488` | `#0a6e66` |
| Rose / berry | `#c2185b` | `#8e133f` |
| Emerald green | `#10916d` | `#0b6e52` |
| Sky blue (original) | `#2f8fd0` | `#2273ad` |

> If you change the colour, also update two spots so browser UI/link previews match:
> 1. `<meta name="theme-color" content="#6d28d9" />` in `index.html`
> 2. `--accent-soft` (use the same RGB as `--accent`).

The template's accent was previously hard-coded as `#2f8fd0` throughout
`assets/css/main.css`; those are now `var(--accent)`, so you never edit `main.css`.

---

## ✅ Before you go live — checklist

1. **Replace the sample reviews** in the *Reviews* section with **genuine** feedback
   from your real residents/parents. (They're clearly marked as samples.)
2. **Replace the photos** in `images/` with your own real photos (keep the same
   file names, or update the `src` in `index.html`).
3. **Set your real web address.** Several SEO tags use `https://skyviewgirlspg.com/`
   as a placeholder. If you host somewhere else (e.g. GitHub Pages), update the URL in:
   - `index.html` → `<link rel="canonical">`, the `og:url` / `og:image` / `twitter:image` tags, and the JSON-LD `url`/`image`/`logo`.
   - `robots.txt` → the `Sitemap:` line.
   - `sitemap.xml` → the `<loc>` value.
4. **Contact details** shown on the page: phone `+91 99970 84777`, email
   `skyviewgirlspg@gmail.com`. Confirm these are correct.
5. **Contact form delivery:** the form posts via [FormSubmit](https://formsubmit.co)
   to `abhisgg1997@gmail.com`. On the first real submission you'll get a one-time
   email to activate it. If you'd rather receive enquiries at
   `skyviewgirlspg@gmail.com`, change the `action="https://formsubmit.co/…"` address
   in the Contact section (you'll re-confirm via that mailbox).

---

## 🔎 SEO & sharing (already set up)

- Descriptive `<title>` + meta description and local keywords (Dehradun).
- **Open Graph + Twitter cards** → rich previews when the link is shared on
  WhatsApp, Facebook, Instagram, X, etc. (uses `images/hero.jpg`).
- **JSON-LD `LodgingBusiness` structured data** → helps Google understand this as a
  local PG/accommodation (name, address, geo, phone, amenities, price range).
- `robots.txt` + `sitemap.xml` for crawlers.
- Geo meta tags for Dehradun, Uttarakhand.
- Favicon from `images/logo.svg`.
- Below-the-fold images use `loading="lazy"` for faster load.

> On-page SEO only takes you part of the way. For real local traffic, also create a
> free **Google Business Profile** for the PG, add real photos, and collect genuine
> Google reviews — that's what drives "near me" searches.

---

## 🚀 Host on GitHub Pages

1. Create a new repository on GitHub (e.g. `skyview-girls-pg`).
2. From this folder:
   ```bash
   git add .
   git commit -m "Re-theme, add reviews/FAQ, SEO and safety improvements"
   git branch -M main
   git remote add origin https://github.com/<your-username>/skyview-girls-pg.git
   git push -u origin main
   ```
3. On GitHub: **Settings → Pages → Build and deployment**, set
   **Source = Deploy from a branch**, **Branch = `main` / `root`**, then **Save**.
4. Your site goes live at `https://<your-username>.github.io/skyview-girls-pg/`
   within a minute or two. (Remember to update the URLs in step 3 of the checklist above.)

### Custom domain (optional)
Add a `CNAME` file containing your domain (e.g. `skyviewgirlspg.com`) and configure
the DNS records as described in GitHub Pages → Custom domain.

---

## Credits
Template: [HTML5 UP](https://html5up.net) — "Read Only" by @ajlkn, CCA 3.0.
Please keep the HTML5 UP attribution in the footer per the license.
