# Fialka Website

Official website for **Fialka** — the end-to-end encrypted messenger that knows nothing about you.

🔗 **Live:** [fialka.app](https://fialka.app/)

## Features

- **Homepage** — Animated hero, live AES-256-GCM encryption demo, 3D tilt cards, particle connections (Three.js), comparison table, Konami easter egg
- **How It Works** — 5-step interactive walkthrough of the Double Ratchet protocol with animated SVG illustrations
- **Changelog** — Auto-fetched from the app repo's CHANGELOG.md, parsed client-side with `marked`
- **Custom 404** — "Message lost in the void" with spiraling particles and live cipher text animation
- **FR/EN** — Full bilingual support with language switcher on every page

## Tech Stack

- [Astro](https://astro.build/) — Static site generator
- [Tailwind CSS 4](https://tailwindcss.com/) — Utility-first styling
- [Three.js](https://threejs.org/) — 3D particle effects
- [GSAP](https://gsap.com/) — Scroll-triggered animations
- [marked](https://marked.js.org/) — Markdown parsing for changelog

## SEO

- Sitemap (`@astrojs/sitemap`)
- `robots.txt`
- JSON-LD structured data
- Open Graph + Twitter Card meta tags
- OG image (1200×630)

## Development

```sh
npm install
npm run dev       # localhost:4321
npm run build     # static output in dist/
```

## Related

- [Fialka Android](https://github.com/FialkaApp/Fialka-Android) — The Android app
- [Fialka iOS](https://github.com/FialkaApp/Fialka-iOS) — The iOS app
- [FialkaApp](https://github.com/FialkaApp) — GitHub organization

## License

[GPLv3](https://www.gnu.org/licenses/gpl-3.0.html)
