# Rahul Bajaj — CV Website

A single self-contained HTML file. Everything — styles, scripts, the world map, and
all photos — lives inside `index.html` itself. There is no separate images folder;
photos are embedded directly in the file.

## Updating the site

Edit `index.html` directly:
- The `roles` array holds the career timeline
- The `rawRows` array holds the skills/treemap data
- To swap a photo, re-embed it as base64 and replace the matching `data:image/jpeg;base64,...` string

Commit and push (or re-upload) the updated `index.html` — that's the only file that matters.

## Local preview

Just open `index.html` directly in a browser — no build step, no server required.
