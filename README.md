# JMR's Mapper

A simple browser map for GPX tracks. Load a recording, split it into named colored segments, and switch between a regular map and satellite.

GPX files in this folder:

- `vermont-track-2.1.gpx` — OsmAnd export with 3 short tracks (40 points)
- `2026-08-07_14-45_Fri.gpx` — longer OsmAnd recording (3 tracks, about 1,300 points). Use **Add GPX files** to load it.

## Open it

From this folder:

```bash
python3 -m http.server 8765
```

Then open [http://127.0.0.1:8765/](http://127.0.0.1:8765/).

You can also open `index.html` directly. The GPX is embedded in the page so tracks still load.

## How to use it

- **Regular map / Satellite** — buttons in the top-left panel
- **Select a track** — click a line. Dots appear on its GPS points
- **Split** — click that same selected line where you want to cut it. The new piece is named `… b` so you can rename it
- **Name** — type in the text box next to the piece
- **Color** — use the color square, or the swatches that appear when you click it
- **Delete** — click **×** on a piece
- **Add GPX files** — drop in more recordings; they are added to the map, not replaced

## Files

- `index.html` — the map app
- `vermont-track-2.1.gpx` — the included Vermont recording
