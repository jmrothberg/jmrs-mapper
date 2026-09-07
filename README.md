# JMR's Mapper

![JMR's Mapper — Wilmington, Vermont](vermont-preview.png)

A simple browser map for GPX tracks. The map opens on the Wilmington, Vermont area and does **not** load any tracks until you add a GPX file.

## Open it

On iPhone or any browser: [https://jmrothberg.github.io/jmrs-mapper/](https://jmrothberg.github.io/jmrs-mapper/)

From this folder:

```bash
python3 -m http.server 8765
```

Then open [http://127.0.0.1:8765/](http://127.0.0.1:8765/). You can also open `index.html` directly.

## How to use it

- **Add GPX files** — load one or more recordings. Each file is a group in the list
- **Example tracks** — tap a sample (Goose Neck, Vermont tracks 1–3 and 2.1) if you have no GPX of your own
- **On / off** — uncheck a file, a track, or a segment to hide it
- **Regular map / Satellite** — basemap buttons
- **Color** (default) — click a line to select it and change its color
- **Split** — choose Split on the toolbar, then click the start and the end of the piece you want. That cuts the segment into the part before, the part between, and the part after. You can tap the dots or the line. After the cut, the tool returns to Color. Choose Split again for another cut
- **Name** — type a name in the list
- **Delete** — click **×**
- **Show names on map** — puts each segment’s name next to the line
- **Line style** — Normal, Thin, Dashed, or Thin dashed on any segment
- **Save map** — downloads one GPX with every segment, color, name, line style, and map view. Opening that file later restores it. It also remembers the map in this browser
- **Fit visible** — zoom to whatever is currently turned on
- A GPX outside the default Wilmington area moves the map to that track

Works on iPhone and iPad: the tools sit in a bottom panel you can collapse with ▾. Add this page to the Home Screen for a full-screen app.

After you split a track, a track checkbox appears so you can hide that whole track or just one piece.

## Files

- `index.html` — the map app
- `goose neck 2026-09-06_12-26_Sun.gpx` — Goose Neck example
- `vermont track 1 2026-08-07_14-55_Fri.gpx` — Vermont track 1 example
- `vermont track 2 2026-08-10_16-26_Mon.gpx` — Vermont track 2 example
- `vermont track 2.1 2026-08-10_17-46_Mon.gpx` — Vermont track 2.1 example
- `vermont track 3 2026-09-05_11-30_Sat.gpx` — Vermont track 3 example
- `vermont-track-2.1.gpx` — short OsmAnd recording (3 tracks)
- `2026-08-07_14-45_Fri.gpx` — longer OsmAnd recording
