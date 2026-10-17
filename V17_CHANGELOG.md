# ACS Website v17 Full

Fixed blank Project Search dropdowns when website is opened in Google Chrome from local files (file://). The project database is now embedded in assets/js/project-data.js and loaded before project-search.js, eliminating the browser restriction on fetching local JSON. Retains project-data.json for interoperability, and retains a fetch fallback. Works on GitHub Pages. Both EN and TH Projects updated. ZIP contains website files at archive root, ready for upload to GitHub root.
