# Finance Degree Apprenticeship Tracker

A live dashboard tracking **Level 6 degree apprenticeships** in finance at major UK
employers, auto-updated from GOV.UK three times a day (09:00 / 13:00 / 16:00 UK time)
by a GitHub Actions job, with optional Telegram alerts for new roles.

- `index.html` - about-me page (embeds the tracker)
- `tracker.html` - the live tracker
- `data.json` - current listings (rewritten by the scraper)
- `scrape.ps1` - the GOV.UK scraper (GitHub Actions runs it on a schedule)
- `assets/` - shared CSS + JS  `decks/` - portfolio PDFs

This is a standalone site - it contains finance only and links to nothing else.
Built with HTML/CSS/JavaScript + PowerShell, hosted on GitHub Pages.