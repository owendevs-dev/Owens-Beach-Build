# Owens Beach Build — Personal fitness PWA

A mobile-first, offline-capable fitness tracker. No account, analytics, external API, or cloud backend. Entries are stored in the browser's localStorage on the device. Export JSON backups regularly. Clearing website data or switching browsers/devices can erase local entries.

## Start locally

From this folder, run `python3 -m http.server 8080` and open http://localhost:8080 on a computer. On iPhone, host the folder on an HTTPS static site (e.g. GitHub Pages or Netlify), open the URL in Safari, then Share → Add to Home Screen. Opening index.html directly from Files is not a reliable PWA install or offline experience. The service worker requires HTTPS or localhost.

## Included

- Daily dashboard with persistent checkboxes, nutrition, weight, steps, water, sleep, and notes
- Four resistance-band training templates, with per-exercise sets/reps/resistance logging and daily completion
- Weekly progress, weight trend and adherence summaries
- No-blender protein recipe ideas and snack-friendly meal suggestions
- Editable goals and JSON export/import backup
- Local-only privacy and offline cache after first successful load

## Limitations

No cloud sync, push reminders, barcode scanning, HealthKit integration, or clinician-guided calorie calculation. Food macros are manually entered. Weight trend is observational. Checkbox completion is not a substitute for logging actual intake. App is a starter implementation and should be tested on your target device before relying on it as the only copy of your records.
