# Proposal 9: Nonfiction Annotation — Channel Architecture and Color Semantics

> Designed primarily for **nonfiction** reading. Fiction may warrant a separate or adapted system.

## Core Principle

**Highlights** encode your reaction to the author's content. **Underlines** modify that reaction — marking dissent, hedging, or action. **Stacked highlights** express compound meaning. The system is readable at a glance: color tells you *what*, type tells you *whose voice* and *what to do about it*.

---

## Core Architecture

The annotation system operates on two independent channels. Each channel carries distinct meaning; their combination produces compound annotations.

---

## Channel 1: The Primary Channel (Highlights and Boxes)

Highlights and boxes encode the **nature of the content being marked**. Color answers: *what kind of thing is this?*

This channel is subdivided into three groups:

### Evaluation Colors
These assign a valence — good or bad — to the content.

| Color | Role |
|---|---|
| **Green** | Positive — a callout that something is good or beneficial |
| **Red** | Negative — a callout that something is bad or dangerous |

### Informational Colors
These characterize the content without taking a stance.

| Color | Role |
|---|---|
| **Yellow** | Neutral assertion or structural claim — neither a tip nor a warning |
| **Blue** | Useful or interesting — worth knowing regardless of opinion |
| **Purple** | Novel or paradigm-shifting — changes how I think |
| **Orange** | Uncertainty — I don't follow this, or I'm not yet convinced |
| **Grey** | Definition, term, or reference — lookup-worthy material |

### Action Color

| Color | Role |
|---|---|
| **Magenta** | Directive — I need to do something |

---

## Channel 2: The Modifier Channel (Underlines)

Underlines **modify the primary annotation**. They do not stand alone as the primary signal — they operate on top of a highlight. Color answers: *how does my stance differ from or extend the highlight?*

One underline per passage (they share a layer and are opaque).

| Underline Color | Role |
|---|---|
| **Red** | Dissent — I disagree with the highlighted claim |
| **Green** | Dissent — I disagree with the highlighted claim (counter-valence to red base) |
| **Orange** | Hedge — not as strong as the highlight suggests; soften the reading |
| **Magenta** | Action — I need to act on this content |

Dissent underlines can apply to **any** highlight color — evaluation or informational. A red or green underline beneath a yellow, blue, grey, or purple highlight expresses disagreement with a neutral or structural claim.

---

## Channel Interaction

The two channels are independent but compose. The primary channel describes the content; the modifier channel describes the reader's response or action relative to it. Neither channel is required — a highlight alone is a complete annotation. An underline alone is not.
