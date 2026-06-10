# ☕ a small question

A tiny single-page site for asking someone out, the only correct way — with a **No button that runs away**.

## What it does

1. **The question** — "Will you go on a date with Ashish?" The Yes button works. The No button dodges your cursor (or your thumb on mobile), shrinks with every attempt, gets progressively more judgmental, and eventually gives up and becomes a second Yes button.
2. **Pick the vibe** — Coffee ☕ / Drinks 🍸 / Sushi 🍣 / Ramen 🍜, each with a tasting note.
3. **It's a date** — a receipt-style ticket with their pick, and a button that opens WhatsApp with the choice pre-filled, so the answer lands straight in chat.

## Tech

- One HTML file. Vanilla JS, plain CSS, no frameworks, no build step.
- Google Fonts: Fraunces + Karla.
- Confetti included. `prefers-reduced-motion` respected.

## Run it

Open `index.html` in a browser. That's it.

## Deploy (GitHub Pages)

1. Push this repo with the file named `index.html`.
2. Repo **Settings → Pages → Deploy from branch** → `main`, root folder.
3. Send the link. Wait.

## Customize

All knobs are near the top of the `<script>` in `index.html`:

- `PHONE` — WhatsApp number (country code, no `+`)
- `noTexts` — the No button's escalating protest lines
- The four `.card` divs — swap in your own date options

## Disclaimer

Not responsible for outcomes. The button only removes "no" as an option — charm not included.
