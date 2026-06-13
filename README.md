# Genesis

> *A story of becoming.*

A living, kinetic evolution game built from a single narrative: the journey from
one spark of life to a cosmic intelligence. Single self-contained HTML file — no
build, no dependencies.

**▶ Play: https://barnickelus.github.io/new-genesis/**

## How to play

- **Tap anywhere** (or press **Space**) to send out a **shockwave** that consumes
  the matter it sweeps over. Every tap pops the food around it, throws off
  particles, and feeds your organism — *in the beginning there is only hunger.*
- **Hunt actively** to build a **combo** (up to ×6) that multiplies what you gain.
- **Buy Traits** from the dock at the bottom:
  - **Bigger Bite** — each mote is worth more
  - **Wider Reach** — your shockwave spreads farther
  - **Cilia** — tendrils that feed on nearby matter automatically (idle income)
  - **Rich Soup** — more, richer matter drifts in
- **Evolve** when the meter at the top fills. You spend your stored biomass to
  transform — keeping your trait levels and gaining a permanent **×3** to
  everything — and the whole world changes: a new creature, new colors, and a
  new chapter of the story.

## The eight eras

`Primordial Soup → First Cell → The Colony → The Predator → The Titan →
The Mind → Civilization → Cosmic Awakening`

Each has its own palette, matter, organism form, and a beat of the Genesis
narrative.

## Under the hood

- Single `index.html`, zero dependencies, works offline
- Fixed-timestep simulation loop with an accumulator (stable regardless of frame rate)
- Canvas world: drifting matter, expanding shockwaves, a particle system, and a
  breathing organism that grows and gains complexity each era
- Thin DOM HUD updated in place (no per-frame `innerHTML` churn)
- Procedural WebAudio sound (no audio files) with a mute toggle
- Auto-save to `localStorage`

The full source narrative lives as a comment at the top of `index.html`.
