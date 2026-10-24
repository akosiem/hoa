# Kasama HOA — Version 2

Static copy of the original table-based collection workbook from HOA App Planning.

## Open

Open `index.html` in a modern browser. No installation or build is required. Keep all four application files together:

- `index.html`: page shell and navigation
- `style.css`: responsive tables and printable statements
- `model.js`: fictional accounts, rates and calculations
- `app.js`: payment entry, statements, reports and browser saving

The app also works on ordinary static hosting without URL rewrite rules. Google Fonts are optional; without internet, the page uses local sans-serif fonts. The Version 1 comparison links open the original hosted prototype.

## Try it

1. Open **Enter payments** for October 2026.
2. For Elena Santos, enter PHP 75 in HOA and PHP 275 in maintenance.
3. The PHP 350 total reduces her PHP 525 balance to PHP 175.
4. Add another household's payment to try saving a batch, then review and save.
5. Open a household's SOA from the balance table, or inspect the payment register and monthly reports.
6. Select November to see monthly dues and credit carry-forward. Credits stay with their own fee type.

## Prototype limits

All accounts and billing rules are fictional demonstration data. The selectable months are September–November 2026. Payment dates must fall within the selected month. This is a practice workbook, not the finished Android application.

Entries save in browser local storage under `kasama-table-v2`, separately from Version 1. No login, synchronization or cloud backup is connected. Storage depends on browser and URL; copying or moving the files does not move saved entries. Direct-file storage support varies by browser. Use static hosting or a local static server if your browser cannot save from a file URL.

**Reset sample workbook** removes Version 2 practice entries after confirmation. Reports cover collections, not expenses or cash on hand. Statements are sample documents, not official receipts.

Source prototype: https://hoa-kasama-table-v2-37e34.happybell6.chatgpt.site
