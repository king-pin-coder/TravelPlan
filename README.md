# Karnataka Road Trip — Mobile Guide

Static, mobile-first travel guide for **13–19 December 2026**.

## Publish on GitHub Pages

1. Create a GitHub repository (e.g. `karnataka-road-trip`).
2. Upload **`index.html`** and **`.nojekyll`** to the repository root (branch `main`).
3. In **Settings → Pages**, set **Build and deployment → Source: Deploy from a branch**.
4. Choose **Branch: `main`**, **Folder: `/ (root)`**, and click **Save**.
5. Open `https://YOUR-USERNAME.github.io/karnataka-road-trip/` after GitHub publishes the site.

The page uses one embedded HTML file; no build tools or npm dependencies are required. Photos and guide text are embedded. Google Maps links require data/network (or compatible offline Maps setup).

## Mobile controls

- Swipe **date panel** left/right to change dates.
- Swipe **activity card** left/right to change activities; scroll vertically for details.
- **Today / Now** jumps to the planned activity for the current day/time (Asia/Kolkata). This is **schedule-based**, not GPS location or live traffic.
- Outside 13–19 December 2026, Today / Now opens a day-one/day-seven preview instead.
- No artificial swipe cooldown; one pointer-up triggers at most one change.
- Completed activities and reading position are stored in the browser's localStorage and do not sync between devices.

## Privacy

GitHub Pages is a public website. Anyone with the URL may view itinerary details, booked hotel names, and trip dates. No booking IDs or payment details are included here. Do not upload confirmations with personal information.
