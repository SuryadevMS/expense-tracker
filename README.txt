PRIVATE EXPENSE TRACKER — UI REDESIGN

Upload index.html and sw.js to the ROOT of your existing GitHub Pages repository,
replacing the old files, then commit the changes.

This redesign preserves the existing IndexedDB database name/store, transaction
records, category list and import rules, date normalization, CSV export, JSON
backup/restore, and editing/deletion behaviour. It adds a saved light/dark theme
toggle and refreshes the responsive visual styling.

The service-worker cache was bumped to v3 so the updated interface can load.

IMPORTANT:
- Do not clear Safari website data.
- Do not change the GitHub Pages site URL or browser used for your existing data.
- Make a JSON backup before deploying if possible.
- After committing, wait for GitHub Pages to update, then fully close and reopen
  the installed app while online.
