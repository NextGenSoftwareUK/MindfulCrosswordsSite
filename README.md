# Mindful Crosswords

**Calm Your Mind, One Clue at a Time · OASIS Omniverse**

Mindful Crosswords is a crossword puzzle platform themed entirely around mindfulness, nature, spirituality and wellbeing. Every puzzle solved earns OASIS karma. Built on the NextGen Crosswords engine and integrated with the OASIS Omniverse.

## What is Mindful Crosswords?

- **Themed puzzles** — all clues and answers relate to mindfulness, meditation, nature, yoga, healing and consciousness
- **Daily puzzle** — a new mindfulness crossword every day
- **Difficulty levels** — from beginner (5×5 grids) to expert (21×21 full-size)
- **Karma rewards** — completing puzzles earns OASIS karma via the Web4 API
- **Accessibility** — designed for all ages, including older adults and those with cognitive differences

## Puzzle Themes

- Meditation and breathwork
- Healing modalities (Reiki, sound healing, crystals)
- Nature and ecology
- Philosophy and wisdom traditions
- OASIS Omniverse lore

## Tech Stack

| Layer | Detail |
|---|---|
| Front-end | Single-file `index.html` — inline CSS + vanilla JS |
| Puzzle Engine | Built on NextGen Crosswords |
| Fonts | Orbitron, Rajdhani, Share Tech Mono (Google Fonts) |
| OASIS API | `@oasisomniverse/web4-api@2.0.2` via esm.sh |
| Hosting | Static — any CDN or static host |

## Related

- [`NextGenCrosswordsSite`](../NextGenCrosswordsSite) — the core crossword engine this is built on

## Running Locally

```bash
npx serve .
# or
python -m http.server 8080
```

---

*Part of the [OASIS Omniverse](https://oasisomniverse.one) · Powered by NextGen Crosswords & OASIS Web4*
