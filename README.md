# Tap Tracker

A tiny installable web app (PWA). Tap the big button and it records the exact date and time, so you can track how often something happens.

- Multiple named trackers (e.g. "Headache", "Dog barked", "Fire alarm")
- Each tracker has its own color (TAP button, chart, header); change it with the color swatch
- Optional note on each tap (type it in the box under the button, then tap; edit it later with ✎)
- Bar chart of taps per day or month (Week, Month, Year, All time); tap a bar for its count
- History with time gaps between entries, plus total / today / average gap
- Undo, delete individual entries, export to CSV
- Works offline; data stays on your device (localStorage), nothing is sent anywhere
- Installs to your home screen

## Run it

No build step. Open `index.html`, or serve the folder:

```
python3 -m http.server 8000
```

## Host on GitHub Pages

1. Push these files to a GitHub repo.
2. Repo **Settings → Pages → Build and deployment**: Source = *Deploy from a branch*, Branch = `main` / `(root)`.
3. Visit `https://<your-username>.github.io/<repo-name>/`.

## Install on your phone

- **iPhone (Safari):** Share → Add to Home Screen
- **Android (Chrome):** menu → Install app

## Notes

Data is stored per browser/device. Use **Export CSV** to back it up. If you clear site data, entries are lost.

## License

MIT
