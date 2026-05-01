# Portfolio Site

A production-grade personal portfolio website, single HTML file with embedded CSS and JavaScript.

**Design:** Technical founder aesthetic. Dark-first, warm amber accent. Editorial typography (Instrument Serif + Satoshi via CDN). Asymmetric project grid, scroll-reveal animations, dark/light mode toggle.

**Performance:**
- Single file: ~32KB minified
- No build step. Deploy anywhere.
- Fonts load via CDN (Google Fonts, Fontshare)
- Responsive: 375px → 1280px+
- WCAG AA contrast compliance
- Touch targets: 44x44px minimum
- Semantic HTML with proper a11y

**Features:**
- Sticky navigation with scroll indicator
- Hero with two-column layout (name/tagline left, bio right)
- Asymmetric projects grid (2x2 featured + 1x2 tall + regular cards + full-width)
- Editorial writing/notes section
- About with sidebar details
- Dark/light mode toggle (localStorage persistence)
- Smooth scroll, staggered animations, `prefers-reduced-motion` support

**To deploy:**
1. Download `index.html`
2. Push to GitHub Pages, Vercel, Netlify, or any static host
3. Done. No build, no dependencies.

**To customize:**
- Edit the `<h1>`, project cards, writing items, and contact links in the HTML
- Swap accent color: find `--color-accent: #e8a045` and change to your hex value
- Update fonts by changing the CDN links in `<head>`

Built for founders and builders. No templates. No fluff.
