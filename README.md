# SQL Sandbox

A database workbench that runs SQLite entirely in your browser. No server, no install.

Open `index.html` in a browser (or host the folder on GitHub Pages).

- Explorer for tables and views, with row counts
- Multiple SQL tabs with syntax highlighting; Ctrl/⌘+Enter runs the query or the selection
- Editable table grids, a table designer, and column add/rename/drop
- Fake-data generator that respects foreign keys
- Import CSV, TSV, JSON, `.sql` scripts and `.sqlite`/`.db` files, or paste data
- Export the whole database as SQL
- Sample shop/company and library databases

Data is stored in IndexedDB in your browser, so it survives reloads but not clearing site data.
Loads SQL.js from cdnjs.
