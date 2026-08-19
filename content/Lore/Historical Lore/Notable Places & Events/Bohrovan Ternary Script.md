---
tags:
  - type/concept
  - era/bohrovan
  - era/waning
  - region/dyradia-wide
  - audience/table
  - status/canon
aliases:
  - Bohrovan Script
  - The Ternary Script
  - Bohrovan Notation
---

# Bohrovan Ternary Script

The base-3, line-runic writing system [[Bohrova]] used to encode his research. Anyone can copy it; only those who understand ternary logic can read it. Predates the Fracture, survives in fragments.

> *"Reality is not binary. It is ternary."* — the principle the script enforces

---

## Origin & Mystery

The script's origins are uncertain. Possibilities scholars argue:

- A pre-existing notation Bohrova rediscovered
- A Dyra-influenced script he translated into mortal use
- His own invention, built on ternary logic

What's agreed: he used it to keep his research **encoded, not encrypted** — readable to anyone who understood the underlying logic, unintelligible to anyone who didn't. The Church hated it. Fragments survived because they could not be selectively erased without losing the substrate they were carved into.

---

## Core Logic

Each glyph is built from **three fixed axes**:

- Vertical `|`
- Diagonal right `/`
- Diagonal left `\`

Each axis has **three states**:

- **0** — Empty (no stroke)
- **1** — Short (half-length stroke)
- **2** — Long (full-length stroke)

**3³ = 27 glyphs.**

All strokes originate from a top anchor point and extend downward only. Short strokes are always exactly half the length of long strokes — sharing the same anchor, making them visually distinct and copy-safe.

Internal notation (DM-side): `(V, /, \)` triples.

---

## The 27-Glyph Table

### 🔹 Null / Spacer

| Index | (V,/,\) | Function |
| --- | --- | --- |
| 0 | (0,0,0) | Null / Spacer / Silence / Zero |

Used for word breaks, line breaks, empty markers, the number zero.

### 🔹 Vowels (vertical-favoring, "open")

| Index | (V,/,\) | Letter |
| --- | --- | --- |
| 1 | (1,0,0) | A |
| 2 | (2,0,0) | E |
| 3 | (1,1,0) | I |
| 4 | (2,1,0) | O |
| 5 | (1,2,0) | U |
| 6 | (2,2,0) | Y |

### 🔹 Soft Consonants (one diagonal + vertical)

| Index | (V,/,\) | Letter |
| --- | --- | --- |
| 7 | (0,1,0) | L |
| 8 | (0,2,0) | R |
| 9 | (1,0,1) | M |
| 10 | (2,0,1) | N |
| 11 | (1,0,2) | S |
| 12 | (2,0,2) | H |

Flowing, adaptable — used in names and poetry.

### 🔹 Hard Consonants (vertical + diagonal combinations)

| Index | (V,/,\) | Letter |
| --- | --- | --- |
| 13 | (1,1,1) | D |
| 14 | (2,1,1) | T |
| 15 | (1,2,1) | K |
| 16 | (2,2,1) | G |
| 17 | (1,1,2) | B |
| 18 | (2,1,2) | P |

Constructed, stable.

### 🔹 Complex / Rare Consonants (dense, slightly ominous)

| Index | (V,/,\) | Letter |
| --- | --- | --- |
| 19 | (1,2,2) | Z |
| 20 | (2,2,2) | X |
| 21 | (0,1,1) | F |
| 22 | (0,2,1) | V |
| 23 | (0,1,2) | C |
| 24 | (0,2,2) | J |

### 🔹 Terminal / Power Glyphs

| Index | (V,/,\) | Function |
| --- | --- | --- |
| 25 | (1,0,0) + overline | Q (used in proper names, seals, Interstice references) |
| 26 | (2,0,0) + break | **Mark of Emphasis / Seal** — used for wards, finality, ritual closures |

---

## Numbers

Numbers use the **same 27 glyphs**. Meaning is inferred from context and grouping:

- Single glyph = 0–26
- Strings of glyphs = larger base-3 positional numbers
- Read left to right, highest order first

A player seeing a wall of repeating glyphs senses *"this is structured and mathematical"* without needing to decode it.

---

## Writing Rules

- **Never rotate glyphs** in normal text (rotation reserved for ritual states — see "Future Layers" below)
- **Stroke order does not matter** — only presence and length
- **Spacing matters** — cramped glyphs imply corruption or hasty copying
- **Clean glyphs imply intact knowledge**
- **Reading order within a glyph:** Vertical → `/` → `\` (logical order, not necessarily how the eye scans)

---

## Visualization & Mental Model

Ternary is easy to *understand* but hard to *see* until the glyph has a consistent skeleton. Once you have the skeleton, the strokes become as visual as a barcode.

### The Anchor Skeleton

Picture every glyph as a single **top anchor point** with **three axes** radiating downward:

```
       •  ← anchor
      /|\
     / | \
    \  |  /
```

Those three axes are the three trits (`V`, `/`, `\`). So every glyph is *"a 3-trit number, drawn."*

That's your visual anchor — literally.

### Each axis has 3 states

For each axis you choose:

- **0** — empty (no mark on that axis)
- **1** — short (a half-stroke from the anchor)
- **2** — long (a full-stroke from the anchor)

A single-axis preview:

```
0:   (nothing drawn)
1:   short stroke
2:   long stroke   (≈ twice the length of short)
```

You don't have to measure — your hand learns it the way it learns dot vs dash.

### The "ternary barcode" trick

When you can't picture a glyph, don't picture the whole glyph — picture it as a 3-row **status list**:

```
V axis: 0 / 1 / 2
/ axis: 0 / 1 / 2
\ axis: 0 / 1 / 2
```

Then translate each number into (none / short / long). It's literally a ternary barcode.

### Drawing order (helps consistency)

To prevent "wait, which axis was which?":

- Drop the anchor point first
- Add axes in fixed order: **V → / → \** (same as the canonical notation)
- Length first, then move to the next axis

### Why 3 axes × 3 states = 27 is *the right size*

3³ = 27 glyphs — exactly enough for **1 spacer + 26 letters**, no wasted symbols, no overflow. The system is mathematically self-justifying, which is part of why Bohrova chose it: the alphabet *can't* be argued with.

---

## Post-Fracture Corruption

The Fracture damaged not just the world but the script itself. Post-Fracture inscriptions often show:

- Missing strokes
- Uneven lengths
- Broken anchors
- Cramped spacing

Players notice this *before* they can read it. Damaged text is its own narrative signal.

---

## How Players Encounter This

This script should appear as:

- Marginal notes in ruins
- Labels on Interstice devices
- Titles carved above sealed doors
- Repeated glyphs near dangerous areas
- Short phrases on ancient tools

**Never paragraphs at first.** The principle is **recognition before comprehension** — players should feel the script as a presence long before they can decode it.

---

## Future Layers (Not Active Yet)

When ready, the script can be extended with:

- **Overlines / underlines** — meaning shifts
- **Rotated glyphs** — ritual states
- **Broken strokes** — corruption or decay markers
- **Incomplete glyphs** — Fracture damage signals
- **Syntax rules** for words and phrases
- **Interstice-only glyph variants**

These are deliberately *not* part of the canonical foundation. They're earned additions, introduced when the campaign benefits from them.

---

## Cross-References

- [[Bohrova]] — the script's author or rediscoverer
- [[The Interstice]] — where Interstice-era notation appears
- [[The Academic Awakening]] — the intellectual movement this script informed and recorded
- [[The Fracture]] — the event that corrupted later inscriptions
- [[The Dyra]] — possible ultimate origin of the underlying ternary logic
