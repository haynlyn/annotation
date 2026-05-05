# Zotero Semantic Annotation System: Color and Type Heuristics for Structured Reading

## Color System

Colors encode the reader's evaluative relationship to the content. At a glance, color answers: *why did I annotate this?*

| Color | Concept | Description |
|-------|---------|-------------|
| **Red** | Warning (source) | The author explicitly warns against or flags something as dangerous/problematic |
| **Orange** | Warning (contrary to source) | I independently see a danger or problem the source does not acknowledge |
| **Green** | Good idea (source) | The author proposes or describes something I find valuable or correct |
| **Blue** | Good idea (contrary to source) | I see potential or insight here that the source does not recognize |
| **Yellow** | Precaution | Something to be careful about — softer than a warning, not necessarily to avoid |
| **Purple** | Counterintuitive | This surprised me or runs counter to expectations |
| **Gray** | Suspicious / verify later | I doubt the accuracy or validity of this; needs further verification |
| **Magenta** | Implement soon | Actionable — I should act on this in the near term |

**Design principle:** Red/orange pair as warning shades (source vs. reader). Green/blue pair as positive shades (source vs. reader). The source/reader axis distinguishes whether the judgment originates from the author or independently from the reader. Gray signals epistemic uncertainty (weaker than orange's confident disagreement). Magenta is visually distinct by design — it must stand out without opening a comment.

---

## Type System

Types encode the structural nature of the annotation. At a glance, type answers: *what am I marking?*

| Type | Use |
|------|-----|
| **Highlight** | The text itself is the artifact — preserving a passage verbatim |
| **Underline** | Precision targeting — a specific term or phrase within or alongside a passage |
| **Box** | Block-level unit — a paragraph, equation, figure, or self-contained structure worth preserving as an image |
| **Note** | A standalone personal thought, not anchored to specific text |
| **Text** | External addition — correction, translation, or elaboration inserted into the document |
| **Freehand** | Visual connection — arrows, circles, diagrams; non-verbal emphasis |

---

## Stacking

Types can stack. Combinations create compound meaning:

- **Highlight + Underline** → passage matters; this phrase specifically is the key term
- **Highlight + Note** → text matters; here is my reaction to it
- **Box + color** → preserve this block as an image; color carries the evaluative judgment

---

## Cross-referencing

Connections between annotations are not encoded in color or type. Links belong in comments or in Obsidian. The color at a second related annotation should reflect the reader's current evaluative stance — which may differ from the first, and that difference is itself informative.
