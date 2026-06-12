# Genesis

> *A story of becoming.*

An evolution / idle game built from a single narrative: the journey from one
spark of life in the void all the way to a **cosmic intelligence** capable of
creating new worlds. No build step, no dependencies — it's a single HTML file.

## Play

Open `index.html` in any modern browser. (Or serve it: `python3 -m http.server`
then visit `http://localhost:8000`.)

## How it works

- **Consume.** Tap the living organism (or press **Space**) to gather the era's
  resource. In the beginning there is only hunger.
- **Grow.** Spend that resource on **Traits** — generators that produce resource
  automatically. *Shift+click* to buy as many as you can afford.
- **Evolve.** Earn enough this era to cross the **Evolutionary Threshold**.
  Evolving resets your traits and resource, but permanently multiplies your
  **Evolution Drive** (×2.4) and click power (×2), and advances the story.
- **Become.** Climb all 11 eras, each with its own resource, visuals, and a
  chapter of the Genesis narrative:

  `The Void → First Cell → Multicellular → Predator → Titan → Awakening Mind →
  Tribe → Civilization → Planetary Mind → Interstellar Life → Cosmic Awakening`

## Features

- Living, morphing organism rendered on `<canvas>` that grows in complexity each era
- Drifting-matter starfield that shifts color with your evolutionary stage
- Auto-save to `localStorage` (+ capped offline progress at 50% efficiency)
- A **Codex** that records each chapter of the lineage as you unlock it
- Fully self-contained — one file, works offline

Begin in the void. End among the stars.
