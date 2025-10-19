## History Timeline (Local)

Minimal, serverless viewer/editor for a history timeline dataset.

### How to try it (1 minute)
1) Open `index.html` in your browser (Chrome/Edge recommended).
2) Click “Open lectures.json” and select a JSON file (e.g., `lectures.json`).
3) Scroll/drag to explore. Use search and tag pills to filter.
4) Click “Edit Mode”, then click a card to edit title/start/end/url/tags.
5) Click “Export JSON” to download your changes (e.g., `lectures_edited.json`).

Notes
- Edits are not auto-saved; export to persist changes.
- Use negative years for BCE (example: -1550).

### Files
- `index.html`: Main app (viewer + edit + export)
- `lectures.json`: Your dataset to load/edit
- `timeline.html`: Older static demo (optional)
- `bushwacker_videos.json`: Raw scrape archive (optional)
- `scarpper.ipynb`: WIP scraper for later automation (optional)

### Data format (per item)
```json
{
  "title": "...",
  "videoId": "...",
  "url": "https://youtu.be/...",
  "tags": ["lecture", "Europe"],
  "start": -800,
  "end": -323,
  "publishedAt": "2020-01-01T00:00:00Z"
}
```

### Share with a friend
- Send `index.html` and a JSON file (e.g., `lectures.json`).
- They open `index.html`, load the JSON via the button, make edits, and export a new JSON back to you.



