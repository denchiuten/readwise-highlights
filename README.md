# readwise-highlights

An interactive 2D force-graph visualisation of my [Readwise](https://readwise.io) highlights, showing how ideas connect across books, articles, and other sources.

Built with [force-graph](https://github.com/vasturiano/force-graph). No server needed — just open `highlight-graph.html` in a browser.

## What it does

- Pulls highlights from Readwise and groups them by source
- Finds semantic connections between highlights from *different* sources
- Renders an interactive graph where you can explore clusters, hover to isolate, and click to read full highlights

## Navigation

- **Scroll** to zoom
- **Drag** to pan
- **Hover** a node to focus on its connections
- **Click** a node to open the sidebar with full text, notes, and cross-source links
- **Legend** (top right) filters by source
- **Esc** resets the view
