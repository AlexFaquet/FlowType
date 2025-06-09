# GhostType

GhostType is a browser-based typing game. To run it locally, you need to serve the files with a local web server (opening the HTML file directly will not load the paragraphs).

## Quick Start

### 1. Clone or Download the Project

Make sure you have all the files:
- [`GhostType3.html`](GhostType3.html)
- [`paragraphs.json`](paragraphs.json)
- [`ambient.mp3`](ambient.mp3)

### 2. Start a Local Server

You can use Python or Node.js to serve the files.

#### Using Python 3

```sh
cd /path/to/GhostTypeGame
python3 -m http.server 8000
```

#### Using Node.js (http-server)

First, install http-server if you don't have it:

```sh
npm install -g http-server
```

Then run:

```sh
cd /path/to/GhostTypeGame
http-server -p 8000
```

### 3. Open in Your Browser

Go to [http://localhost:8000/GhostType3.html](http://localhost:8000/GhostType3.html) in your web browser.

## Notes

- Do **not** open `GhostType3.html` directly with `file://` — the game needs to fetch `paragraphs.json` via HTTP.
- If you add or change paragraphs, edit [`paragraphs.json`](paragraphs.json).
- For best experience, use a modern browser (Chrome, Firefox, Edge, Safari).

Enjoy playing GhostType!