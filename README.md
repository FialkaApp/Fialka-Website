# SecureChat Website

Official website for **SecureChat** — the end-to-end encrypted messenger that knows nothing about you.

🔗 **Live:** [devbot667.github.io/SecureChat-Website](https://devbot667.github.io/SecureChat-Website/)

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

- [SecureChat App](https://github.com/DevBot667/SecureChat) — The Android app

## License

[GPLv3](https://www.gnu.org/licenses/gpl-3.0.html)
