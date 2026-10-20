# Private Local Expense Tracker

A personal local-first PWA prototype. No login, backend, analytics or external database. Supports transactions, 11 categories, Need/Want/Saving, filters, monthly totals, CSV import/export and JSON backup/restore.

## Hosting and install
An installable Home Screen web app needs HTTPS. On Windows, create a GitHub repository and upload only `index.html`, `manifest.json`, `sw.js`, and `icon.svg`. Do NOT upload private CSV or JSON backup files. In repo Settings → Pages, publish from the `main` branch and root. Open the published HTTPS URL in Safari on iPhone → Share → Add to Home Screen. Open once online; then test offline mode.

## Import data
In app → Backup & import → Import CSV, select `Expenses_Google_Sheets_Refined.csv`. It accepts the refined export and uses New Category/Suggested Type when present. Unclear rows are marked REVIEW. Verify results before relying on totals.

## Backups
The app does not automatically sync to iCloud. Tap Download backup, then save the JSON file to Files → iCloud Drive. On a replacement phone, open the same app URL and restore the JSON backup. Restoring replaces local data; back up first. Browser storage can be erased, so keep regular backups in iCloud Drive and another location.
