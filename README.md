# atiafuture: AI impact horizon for Alaska travel, 2026 to 2032

A single-page report that maps how AI could change 12 Alaska travel sectors between now and 2032: when a change could become routine, how deep it could go, what to do first, and what to measure. It is the "take the full horizon home" page that the convention slides point to with a QR code.

Live address once published: **https://preig.github.io/atiafuture/**

Companion kit (practical tools, separate repo): https://preig.github.io/atiakit/

## What is on the page

- Main findings and four Alaska context figures, each with its source.
- The impact horizon chart: 12 numbered sectors, current position dots, dashed paths, planning ranges. Filters for sector, group, planning ranges, paths and a future window slider.
- Current situation and possible evolution for each sector (now, 2027-28, 2029-30, 2031-32, condition for progression).
- 12 sector cards with an expandable section of use cases, a worked example, a first pilot and the economics.
- Cross-cutting effects, verified developments, a 90-day plan with three starter pilots, method and limits, and 15 sources.
- Dark theme button, print or save as PDF (A4), works on phones and desktops.

All coordinates on the chart are analyst judgments. They are not adoption percentages or probabilities. The page says so on the chart and in the method section.

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole report. Styles, chart code and data are inside this one file. |
| `README.md` | This note. |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are. |

The page makes no outside requests: no web fonts, no images from other sites, no analytics, no cookies. Once loaded it works offline. Only the 15 source links (and the companion kit link) need an internet connection when clicked.

## Version 1.4 (10 October 2026), changes from version 1.3

- Removed all third-party branding: the logo and wordmark block, the brand stylesheet and its web-font import. The page now uses its own built-in theme (teal, green and gray band, matching the deck).
- Removed program and university references from the header and footer, and two internal workflow notes from the method section.
- New footer: version, assessment date, an independence note and the companion kit link.
- Replaced en and em dashes in visible text with "to", commas, colons or plain hyphens (for example "2026 to 2032", "depth 45 to 80", "2027-28").
- Chart tip, screen-reader labels and the future window slider now read "mid 2027" instead of "2027.5".
- Four phrases that said "must" now say "should" or "need to" (no sighting promises, no standing catch-allowance promises, cruise data agreements, fishing data before integration). The method section already labels these controls as recommendations, not legal mandates.
- Figures, sources, chart data and the assessment date (7 October 2026) are unchanged. On 10 October 2026 the 54.2% accommodation figure, the $3.9 billion / $5.6 billion 2022-23 model figures and the Booking.com 67% (n = 37,325, 33 markets) were checked against the linked sources and match.

## How to publish it as the repo `atiafuture`

The QR code on the slide points to `https://preig.github.io/atiafuture/`. That address works only after these steps.

### Option 1: GitHub website (no tools needed)

1. Sign in to GitHub as **preig**.
2. Click **New repository**. Name it exactly `atiafuture` (all lower case). Choose **Public**. Do not add a README from GitHub. Click **Create repository**.
3. On the new repo page, click **uploading an existing file**.
4. Drag in `index.html`, `README.md` and `.nojekyll` from this folder. (Windows hides files that start with a dot in some views; if you cannot drag `.nojekyll`, skip it. The page still works.)
5. Click **Commit changes**.
6. Go to **Settings**, then **Pages**. Under **Build and deployment**, set Source to **Deploy from a branch**, Branch to **main** and folder to **/ (root)**. Click **Save**.
7. Wait 1 to 10 minutes. Open https://preig.github.io/atiafuture/ and confirm the chart shows all 12 numbered sectors.

### Option 2: command line

Run these from inside this `atiafuture` folder (replace the path with where the folder sits on your computer):

```
cd "<path to>\github\atiafuture"
git init -b main
git add index.html README.md .nojekyll
git commit -m "Publish AI impact horizon v1.4"
git remote add origin https://github.com/preig/atiafuture.git
git push -u origin main
```

Then turn on Pages as in step 6 above.

## Check before 14 October

- Open the live address on a phone and on a laptop.
- Scan the QR code on the slide with a phone camera; it should open the same page.
- On the page: pick a sector, pick a group, press Reset, press Theme twice, expand one sector card.
- Press **Print / save PDF** once to make an offline PDF copy as a backup for the room.

## Updating later

Edit `index.html`, then upload it again (or commit and push). GitHub Pages republishes within a few minutes. Bump the version and date in the footer when the content changes. Revisit the ranges after the first measured operating season, a significant booking-platform change or a material failure, as the method section says.

Forecasts on this page are planning judgments, not measured outcomes, and not an official ATIA position or endorsement.
