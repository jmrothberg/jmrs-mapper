# JMR's Mapper

![JMR's Mapper — Wilmington, Vermont](vermont-preview.png)

A simple browser map for GPX tracks. The map opens on the Wilmington, Vermont area and does **not** load any tracks until you add a GPX file.

## Open it

From this folder:

```bash
python3 -m http.server 8765
```

Then open [http://127.0.0.1:8765/](http://127.0.0.1:8765/). You can also open `index.html` directly.

## How to use it

- **Add GPX files** — load one or more recordings. Each file is a group in the list
- **On / off** — uncheck a file, a track, or a segment to hide it
- **Regular map / Satellite** — basemap buttons
- **Color** (default) — click a line to select it and change its color
- **Split** — choose Split on the toolbar, then click where you want to split a segment. After the cut, the tool returns to Color so you can color each half. The split dots go away; you can choose Split again later
- **Name** — type a name in the list
- **Delete** — click **×**
- **Fit visible** — zoom to whatever is currently turned on (the map does not auto-zoom)

After you split a track, a track checkbox appears so you can hide that whole track or just one piece.

## Files

- `index.html` — the map app
- `vermont-track-2.1.gpx` — short OsmAnd recording (3 tracks)
- `2026-08-07_14-45_Fri.gpx` — longer OsmAnd recording
