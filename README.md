# TICKET — Pre-Trade Checklist & Trigger Log

A single-page trading discipline tool. Built for the habit of writing notes like *"watch BTC for a strong weekly close above 65000"* — so those notes actually resurface before you trade, instead of sitting forgotten in a notebook.

**Live demo:** _[TICKET](https://hj503x.github.io/Ticket/)_

## What it does

- **Checklist** — general items to tick off before every trade (session overlap, news check, HTF trend, etc.)
- **Watchlist** — structured price/condition alerts you're tracking: asset, level, direction (above/below), timeframe, and the exact condition (e.g. "strong candle close"). Status cycles through Watching → Triggered → Invalidated, and sorts itself so active watches stay on top.
- **Trigger Rules** — IF / THEN playbook entries for recurring market behavior (e.g. liquidity sweeps, volume spikes).

All three are tagged by category (pair, session, or setup type) and filterable with one tap.

## Extras

- Dark / light theme toggle (remembers your choice, defaults to system preference)
- Sticky jump-nav between sections, auto-highlights as you scroll
- Export/Import your data as a JSON backup file
- Two-tap delete confirmation so nothing gets removed by accident
- Fully responsive — built mobile-first, works the same on desktop

## Tech

Plain HTML, CSS, and JavaScript. No build step, no dependencies, no backend. Data is stored in your browser's `localStorage` — nothing leaves your device.

## Running it

Just open `index.html` in a browser, or deploy it for free with GitHub Pages:

1. Upload `index.html` to this repo
2. Go to **Settings → Pages**
3. Set branch to `main`, folder to `/root`, and save
4. Your live link appears at `https://<your-username>.github.io/<repo-name>/`

## Notes

Data is local to whatever browser/device you're using — export a backup (JSON) periodically if you use it across multiple devices, then import it on the other one.
