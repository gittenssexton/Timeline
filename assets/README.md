# Timeline Game - Pixel-Art Parallax Assets

These game-ready assets were optimized from the user's approved, AI-generated Timeline asset library. Original full-resolution versions and design references remain in Google Drive (Timeline Game / ASSET_LIBRARY_2026-10-12).

- traveler.png: approved gender-neutral traveler design; preserve clothing, hair, satchel, palette and silhouette in later animation frames.
- cloud.png and wisps.png: independent animated/depth cloud elements.
- mountains.png and valley.png: distant and mid-distance landscape backdrops.
- city.png: stylized brick settlement/riverfront environment (not a vetted archaeological reconstruction; avoid treating decorative towers, arches, or waterfront features as evidence).
- forest.png, reeds.png: vegetation/foreground scenery.
- ruins.png: aged settlement layers (stylized art).

The assets remain independent PNGs and the loop is a temporary *visual demonstration*, not evidence that a historical era cyclically repeats. Keep scenery parallax code in the game; do not concatenate these into a static mural. Source assets were cropped, resized with nearest-neighbor resampling, and palette reduced; the full-resolution files are preserved in Drive.

## Ten Harappan NPCs — Prototype 007

- `harappan_npcs.png`: one 640×64 transparent sprite atlas; 10 columns of 64×64, left-to-right ordered by `atlas_index` 0–9.
- `harappan_npcs.json`: names, dialogue, approximate date windows and screen-space game coordinates, visual references, and uncertainties.
- Source images preserved in [Timeline shared Drive NPC folder](https://drive.google.com/drive/folders/1Ie5LzOvKXa8SHh1g1UW3MHwLC_0gqOi1).
- Fictional people and game dialogue; not historically attested names, spoken words, or certain apparel reconstructions. Harappan writing remains undeciphered. Artistic draped clothing and accessories should be treated as provisional.
- **NPC interaction**: players must overlap the exact world-space marker to see the prompt and speak. Do not tie target distance to a different parallax speed.
- **Timeline** extended left to c. 2650 BCE for the Mature Harappan cities, while preserving later settlement and pastoral encounters. Temporary map loop remains a gameplay preview only.
