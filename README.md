# baludaghanshyam.org

Static website for **Shree Swaminarayan Vatsalya Dham, Kaliyana** — a charitable trust
running Anna Daan, elderly care (Vrudhashram) and Bal Sanskar seva.

## Structure

Single-page static site. No build step.

| File | Purpose |
| --- | --- |
| `index.html` | The entire site (Tailwind via CDN, Font Awesome, Google Fonts) |
| `logo.jpg` | Trust crest — used as nav logo, footer logo and favicon |
| `baludaGhanshyam.jpg` | Standing murti, Legacy section main frame |
| `baludaGhanshyam_small.jpg` | Murti darshan close-up, Legacy section offset frame |

## Local preview

Any static server works, e.g.:

```bash
npx --yes serve .
```

## Known follow-ups

- Most photography is hotlinked Unsplash / Wikimedia stock. Several URLs have already
  gone 404 once. Replace with real photographs of the trust's seva and host them in-repo.
- Donation section is a placeholder — Razorpay / UPI gateway not yet integrated.
- Footer copyright still reads 2023.
