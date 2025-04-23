# Drum Notation Renderer

# A high-performance, real-time drum notation rendering engine, optimized for playback sync and grid-based sequencing

---

## Purpose

- **Real-time playback sync:** Full alignment with grid-based sequencers and playback engines like Tone.js.
- **Instrument-level clarity:** Supports Kick, Snare, Hi-Hat, Toms, Ride, Crash, and more — with proper drum notation symbols.
- **Low overhead:** SVG-based, mutation-driven rendering. React is orchestration-only, not in the render loop.
- **Exportable:** Native SVG output (printable, scalable).
- **Future integration with LilyPond for sheet music export.**

---

## Features

- High-performance SVG rendering
- Sync with external playhead (`currentColumn`, `currentBar`)
- Supports time signature and subdivision
- Instrument mapping by row
- Playhead highlighting (non-reactive mutation, sub-16ms frame targets)
- Optional export as SVG file (planned)
- Future LilyPond-based printable sheet export (planned)

---

## Installation

This package is not yet published to NPM.
