# Assets — Where to Place Images

This folder holds the images used by your GitHub profile README and your case-study repos. Add the files below, then reference them by relative path (e.g. `assets/banner.png`).

> No image assets ship with this profile repo by default — the portfolio's `/public` folder contains icons and `avatar.png`, but no project screenshots. You'll need to add screenshots yourself (see suggestions below).

---

## 📐 Recommended files &amp; placement

| File | Purpose | Recommended size | Notes |
| --- | --- | --- | --- |
| `banner.png` | GitHub profile banner (top of README) | 1280 × 320 px | Optional; keep it clean and on-brand |
| `avatar.png` | Profile photo | 400 × 400 px | Reuse from portfolio `/public/avatar.png` |
| `blaia-1.png` … | Blaia project screenshots | 1280 × 720 px (web) | Storefront, seller dashboard, checkout |
| `stemquiz-1.png` … | STEMQuiz screenshots | 1080 × 1920 px (mobile) | Quiz screen, leaderboard, admin panel |
| `my-mind-bestie-1.png` … | My Mind Bestie screenshots | mixed | Web, mobile, desktop surfaces |
| `obenan-1.png` … | Obenan screenshots | 1280 × 720 px | Dashboard, landing platform |
| `pedlar-1.png` … | Pedlar storefront screenshots | 1280 × 720 px | Creator storefront, product page |

---

## 🗂️ Where each image type goes

### GitHub profile banner
- File: `assets/banner.png`
- Reference it at the very top of the profile `README.md` if you want a header image.

### Project screenshots (web)
- Folder: `assets/` (or `assets/<project>/` if you have many)
- Use real captures from the live sites (Blaia, Obenan, Pedlar) at desktop width.

### App store screenshots (mobile)
- Folder: `assets/` (or `assets/<project>/`)
- Use the screenshots already published on the App Store / Google Play listings, or capture fresh ones from a device/simulator.
- Portrait orientation (e.g. 1080 × 1920) reads best for phone apps.

### Portfolio thumbnails
- Folder: `assets/thumbnails/`
- One small, consistent thumbnail per project (e.g. 600 × 400) for tables and cards.

### Case-study images
- For each public case-study repo, keep its own `assets/` folder.
- Reference them from that repo's README using the `project-readme-template.md` Screenshots section.

---

## ✅ Image guidelines

- **Compress** images (TileShot, Squoosh, or `sharp`) so the README loads fast.
- Use **PNG** for UI screenshots, **JPG** for photographic banners.
- Keep filenames lowercase-kebab-case: `blaia-checkout.png`.
- **Never include** images that expose secrets, private dashboards with real customer data, API keys, or confidential client information — blur or crop sensitive content first.
- Prefer screenshots of **publicly live** surfaces (your shipped App Store / Play / web pages) to stay on the safe side.
