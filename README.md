# ASHFALL

*In war, no one wins.*

A complete, standalone, single-file narrative survival game inspired by **This War of Mine**.
No server, no internet, no libraries — one HTML file that runs by double-clicking.

## Play

1. Download [`index.html`](index.html)
2. Double-click it (Chrome / Firefox / Edge) — that's all.

Everything (graphics, audio, saving) happens locally in your browser:
- Charcoal, monochrome art drawn on Canvas 2D (red reserved for blood and fire)
- Characters: hand-coded 6-frame walking silhouettes in a cross-section shelter
- Day (grey, floating dust) / Night (dark blue, candle halo, linear rain)
- Ambient sound and effects synthesized with the Web Audio API (oscillators + noise)
- Autosave via `localStorage`

## How to survive

- **MORNING** — assign one task per survivor: rest, repair the house, search downstairs, craft tools, care for the wounded, stand guard.
- **DUSK** — supper, then the city knocks. Choices are immediate and **irreversible**.
- **NIGHT** — send one survivor to a location: abandoned house, hospital, checkpoint, or a family home that is not empty. Loot, witnesses, prices.
- **NEEDS** — health 0 = permanent death · hunger > 80 = illness · morale < 20 = depression.
- **THE STORY** — five threads: a hidden hospital with a moral price, a lost child, an informer next door, a missing sister, and the last train on day 30. Pull one thread and the others move.
- **ENDINGS** — more than one way out; more than one way to survive. Your decisions are recorded and read back to you.

## Characters

| Name | Age | Pre-war | Trait | Secret |
|------|-----|---------|-------|--------|
| Vera | 34 | Surgeon | doctor — hospitals are her ground | kept a boy's shoe after a kitchen-table amputation |
| Marko | 41 | Mechanic | deserter — checkpoints are his ground | crossed the river the night the bridge fell, left five men behind |
| Anya | 17 | Student | thief — houses are her ground | locked a pharmacist inside his pharmacy for insulin |

Playable 30–40 days, or until an ending. Death is forever; the game is not fair.
