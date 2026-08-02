# NiKami Labs — Website

Marketing / landing page for [NiKami Labs](https://nikamilabs.com) — an indie software studio building focused tools for traders, language learners, and card-game players.

## Products

| Product | Status | Stack | Description |
|---------|--------|-------|-------------|
| **BargBaz** | Live | Flutter · PWA · WebSocket | Persian card-game platform with online rooms, local network play, and solo practice |
| **VocabTrove** | Live | Flutter · Next.js · Supabase | Language-learning app with tap-to-look-up, flashcards, and spaced repetition |
| **Levera** | Beta | Python · FastAPI · Supabase | Margin trading simulator for Persian exchanges with live Wallex order books |

## Project Structure

```
.
├── index.html      # Single-page site
├── styles.css      # All styles
├── logos/          # SVG brand marks and product icons
└── screenshots/    # App screenshots used in the showcase section
```

## Development

This is a static HTML/CSS site — no build step required.

```bash
# Open locally
open index.html

# Or serve with any static server, e.g.:
npx serve .
```

## Deployment

The site is a single static page and can be deployed to any static host (Vercel, Netlify, GitHub Pages, etc.).

---

© NiKami Labs
