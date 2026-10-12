# Timeline – looping parallax art preview

**Status:** temporary artwork/scrolling prototype, not historically final.

The game loads `assets/indus_pixel_atlas.b64` (a compact indexed PNG atlas encoded as plain Base64) and draws each image independently on the 320×180 game canvas with nearest-neighbor pixel scaling.

Atlas coordinates:
- Rows 0–7: source rectangles `(0, row*80, 240, 80)`
- Row 0: distant snowy mountains
- Row 1: rocky ridges
- Row 2: river-valley panorama
- Row 3: Harappan-style riverside city (illustrative, not archaeologically validated)
- Row 4: ruined settlement
- Row 5: forest/tree line
- Row 6: foreground vegetation
- Row 7: separately cropped clouds / sky details
- Traveler: source rectangle `(0,640,28,41)` – **approved/locked generic character design**

Layers move at different speeds. Ground, trees, city/ruins, mountains and clouds are visually repeating using a two-tile mirrored loop. Distant cloud groups also drift independently of player movement. The playable chronological journey loops at its ends during this **temporary preview**.

Original full-resolution assets and design lock: [Timeline Asset Library](https://drive.google.com/drive/folders/1k8DaRVq95MXZvPPiG39fnsgT5pY9BJvH).

The illustrated architecture, landscape placements, and chronology of visual transitions need a separate historical-accuracy review before final release. The core encounter logic, keyboard controls, on-canvas dialogue and journal are preserved.
