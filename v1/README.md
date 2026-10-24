# Kasama HOA — Version 1

Static copy of the original guided-screen prototype, preserved from HOA App Planning.

## Open

Double-click `index.html` in a modern browser. No installation or build is required. All page navigation uses URL hashes, so ordinary static hosting also works without rewrite rules.

Files:
- `index.html` — application shell
- `style.css` — responsive layout and print styles
- `app.js` — fictional records, navigation, payment flow, statements and reports

The stylesheet optionally loads DM Sans and Manrope from Google Fonts. Without internet it uses local sans-serif fonts; the app itself has no remote data dependency.

## Try it

1. Find Elena Santos in Households.
2. Record a PHP 350 payment using the default allocation.
3. Review and save. Her PHP 525 balance becomes PHP 175.
4. View the updated statement; use Print / PDF to print or save it.
5. Open Reports to export the selected month's collections as CSV.

Practice entries are stored under `kasama-demo-v1` in browser local storage. Reset demo restores the fictional records after confirmation. Storage belongs to the browser and URL; opening a different copy or hosting at another address does not transfer entries. Direct-file storage behavior varies by browser; use a local static server if saving is unavailable.

## Preserved prototype limits

- Fictional data only; no production accounts or real financial records.
- Fixed demonstration reporting date: 23 October 2026. Accepted payment dates: 1–23 October 2026.
- Default demonstration allocation pays HOA first, then maintenance. Fee-only payment options and unallocated advance credit are included; these are not approved HOA billing policies.
- Browser-only saving, with no login, cloud backup or synchronization.
- Statements are sample documents, not official receipts or collection notices.
- Reports show collections, not cash on hand; expenses and refunds are outside this version.

Source prototype: https://hoa-kasama-demo-37e34.happybell6.chatgpt.site

This local copy does not modify the hosted prototype or Version 2.
