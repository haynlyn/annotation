# Proposal 6: Dual-Channel Nonfiction Annotation — Stacked Highlights for Severity

> Designed primarily for **nonfiction** reading. Fiction may warrant a separate or adapted system.

## Core Principle

**Highlights** encode your reaction to the author's content. **Underlines** modify that reaction — marking dissent or action. **Stacked highlights** express severity or uncertainty layered onto a primary judgment. The system is readable at a glance: color tells you *what*, type tells you *whose voice* and *what to do about it*.

---

## Color Semantics

### Evaluation Colors (stance axis)

| Color | Role |
|---|---|
| **Green** | Positive / beneficial content |
| **Red** | Negative / dangerous content |

A green or red highlight alone notes the **author's framing**. It does not necessarily imply emphatic agreement — it means "the author presents this as positive/negative, and I'm noting it."

**Disagreement** is expressed by adding a contrasting underline:

| Combination | Meaning |
|---|---|
| Green highlight | "Author presents this as positive" |
| Red highlight | "Author presents this as negative" |
| Green highlight + red underline | "Author says positive, I think it's wrong" |
| Red highlight + green underline | "Author says negative, I think it's fine" |

**Mild doubt** is expressed by stacking an orange highlight:

| Combination | Meaning |
|---|---|
| Green highlight + orange highlight | "Author says positive, I'm uncertain — not fully convinced" |
| Red highlight + orange highlight | "Author says negative, I'm uncertain — maybe it's not that bad?" |

This creates a severity spectrum for disagreement:

| Severity | Annotation |
|---|---|
| Noting the author's stance | Green or red highlight alone |
| Mild doubt | Green/red highlight + orange highlight |
| Confident disagreement | Green/red highlight + red/green underline |
| Urgent disagreement requiring action | Green/red highlight + red/green underline + magenta underline |

> **Note:** Double underlines are not possible — they exist on the same layer and are opaque. Only one underline per passage. When both dissent and action must be expressed, use stacked highlights for the evaluative layer (green + red highlight) and reserve the underline for magenta (action). Alternatively, action intent can live in a comment on the dissent underline.

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

## Type Semantics

### Primary types

| Type | Role |
|---|---|
| **Highlight** | Default annotation — marks content and encodes reaction via color. Can be stacked for compound meaning. |
| **Underline** | Modifier channel — dissent (green/red contrast) or action (magenta). Limited to one per passage. |
| **Box** | Preserves a block-level artifact — a figure, equation, paragraph, or diagram as a whole unit. Same color semantics as highlights; underlines are unavailable, so dissent/action intent goes in embedded comments. |

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
| Green highlight | "Author presents this as positive" |
| Red highlight | "Author presents this as negative/dangerous" |
| Green highlight + orange highlight | "Author says good, I have doubts" |
| Green highlight + red underline | "Author says good, I think it's wrong" |
| Red highlight + green underline | "Author says bad, I think it's fine" |
| Blue highlight | "Useful, no stance taken" |
| Purple highlight | "This shifted my thinking" |
| Orange highlight (standalone) | "I don't follow this / uncertain" |
| Yellow highlight | "The argument rests on this premise" |
| Grey highlight | "Definition or reference term" |
| Any highlight + magenta underline | "I need to act on this" |
| Magenta highlight | "Instruction to myself at this location" |
| Colored box | "Preserve this artifact — color carries the same meaning as a highlight" |

---

## The Full Reading Lifecycle

1. **Orient** (yellow, grey) — identify premises, terms, definitions
2. **Encounter** (blue, purple, orange) — react to new information
3. **Judge** (green, red, orange stacks, cross-color underlines) — evaluate claims
4. **Act** (magenta underline / highlight / text) — flag what demands follow-up

---

## Open Questions

- How does this system adapt for fiction?
- What does Obsidian integration look like when exporting annotations with this schema?
- How are stacked/overlapping annotations reconciled when exported (two annotation entries for the same text)?
