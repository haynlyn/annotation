# Proposal 7: Dual-Channel Nonfiction Annotation — Softening Modifier Added

> Designed primarily for **nonfiction** reading. Fiction may warrant a separate or adapted system.

## Core Principle

**Highlights** encode your reaction to the author's content. **Underlines** modify that reaction — marking dissent, hedging, or action. **Stacked highlights** express compound meaning. The system is readable at a glance: color tells you *what*, type tells you *whose voice* and *what to do about it*.

---

## Color Semantics

### Evaluation Colors (stance axis)

| Color | Role |
|---|---|
| **Green** | Positive / beneficial — a callout that something is good |
| **Red** | Negative / dangerous — a callout that something is bad |

These are valence markers regardless of whether the author or the reader is making the call.

**Disagreement** is expressed by adding a contrasting underline:

| Combination | Meaning |
|---|---|
| Green highlight | "This is positive" |
| Red highlight | "This is negative — avoid" |
| Green highlight + red underline | "Presented as positive, I think it's wrong" |
| Red highlight + green underline | "Presented as negative, I think it's fine" |

**Hedging** is expressed by adding an orange underline:

| Combination | Meaning |
|---|---|
| Red highlight + orange underline | "Precaution — be careful, not absolute avoidance" |
| Green highlight + orange underline | "Promising, but not a sure thing" |

### Informational Colors (no stance required)

| Color | Role |
|---|---|
| **Blue** | Useful / interesting — worth knowing regardless of opinion |
| **Purple** | Novel / paradigm-shifting — changes how I think |
| **Orange** | Uncertainty — confusion, doubt, or "not yet understood" |
| **Yellow** | Premise / foundational assumption — the argument is built on this |
| **Grey** | Definition / term / reference — lookup-worthy material |

Orange covers the full uncertainty spectrum: "I can't follow this logic" and "I'm not convinced by this claim" are both epistemic uncertainty.

### Action Color

| Color | Role |
|---|---|
| **Magenta** | Call to action — I need to do something |

Magenta works across multiple types:

| Usage | Meaning |
|---|---|
| Magenta underline (beneath a highlight) | "Act on this content" |
| Magenta highlight | "Self-directed instruction tied to this location" |
| Magenta text | "Self-directed instruction, freeform" |

---

## Underline Roles (the modifier channel)

Underlines are limited to one per passage (they are opaque and share a layer). The full underline vocabulary:

| Underline Color | Role |
|---|---|
| **Green** (under red highlight) | Full dissent — "I disagree, this is actually fine" |
| **Red** (under green highlight) | Full dissent — "I disagree, this is actually wrong" |
| **Orange** (under any evaluation highlight) | Hedge / softener — "Not as extreme as the highlight suggests" |
| **Magenta** (under any highlight) | Action required — "I need to do something about this" |

### Severity Spectrum (negative example)

| Severity | Annotation |
|---|---|
| Full warning — avoid | Red highlight |
| Precaution — be careful | Red highlight + orange underline |
| Mild doubt about negativity | Red highlight + orange highlight (stacked) |
| Full disagreement — actually fine | Red highlight + green underline |

### Severity Spectrum (positive example)

| Severity | Annotation |
|---|---|
| Positive callout — good idea | Green highlight |
| Hedged positive — promising but unsure | Green highlight + orange underline |
| Mild doubt about positivity | Green highlight + orange highlight (stacked) |
| Full disagreement — actually wrong | Green highlight + red underline |

---

## Type Semantics

### Primary types

| Type | Role |
|---|---|
| **Highlight** | Default annotation — marks content and encodes reaction via color. Stackable for compound meaning. |
| **Underline** | Modifier channel — dissent, hedge, or action. Limited to one per passage. |
| **Box** | Preserves a block-level artifact — a figure, equation, paragraph, or diagram as a whole unit. Same color semantics as highlights; modifiers go in embedded comments. |

### Secondary types (limited use)

| Type | Role |
|---|---|
| **Text** | Freeform thought on the page. Primarily used with magenta for self-directed instructions. |
| **Freehand** | Spatial/structural marks — arrows, brackets, grouping. Edge cases only. |
| **Post-it** | Largely redundant — conflicts visually with comment indicators on other annotations. Avoid unless a distinct use emerges. |

---

## Reading the System at a Glance

| You see... | You infer... |
|---|---|
| Green highlight | "This is good" |
| Red highlight | "This is bad — avoid" |
| Red highlight + orange underline | "Precaution — be careful but not absolute" |
| Green highlight + orange underline | "Promising but not a sure thing" |
| Green highlight + red underline | "Presented as good, I say it's wrong" |
| Red highlight + green underline | "Presented as bad, I say it's fine" |
| Blue highlight | "Useful, no stance taken" |
| Purple highlight | "This shifted my thinking" |
| Orange highlight | "I don't follow this / uncertain" |
| Yellow highlight | "The argument rests on this premise" |
| Grey highlight | "Definition or reference term" |
| Any highlight + magenta underline | "I need to act on this" |
| Magenta highlight | "Instruction to myself at this location" |
| Colored box | "Preserve this artifact — color carries the same meaning as a highlight" |

---

## The Full Reading Lifecycle

1. **Orient** (yellow, grey) — identify premises, terms, definitions
2. **Encounter** (blue, purple, orange) — react to new information
3. **Judge** (green, red, orange underlines, cross-color underlines) — evaluate claims with nuance
4. **Act** (magenta underline / highlight / text) — flag what demands follow-up

---

## Open Questions

- How does this system adapt for fiction?
- What does Obsidian integration look like when exporting annotations with this schema?
- How are stacked/overlapping annotations reconciled when exported?
