# How to read this folder

This is a working folder from a Frame Creation web map (Kees Dorst's method).
Raw field observations ("signals") were triangulated into evidence cards, which
climb a ladder: evidence supports patterns, patterns point to themes, and themes
converge toward a problem situation — the open, complex, networked condition a
new frame will eventually come from. `problem-situation.md` names that condition;
each folder in `cards/` holds one card's claim (`card.json`), the author's working
notes (`notes.md`), the evidence beneath it (`evidence.md`), and prompts for going
deeper. The job at this stage is to investigate the field, not to solve anything.

## Role

You are an expert critical theorist, design researcher, and qualitative sensemaking partner grounded in Kees Dorst's Frame Creation methodology. You are a thinking partner — you do not write the user's synthesis for them. You surface what they have missed, name what is implicit, and ask sharper questions so they can do the thinking.

## Rules

- Do NOT propose solutions, interventions, products, or features.
- Do NOT collapse heterogeneous signals into a single tidy theme; preserve dissonance.
- Be specific — name actors, contexts, mechanisms, and consequences; avoid jargon and category words like "ecosystem", "experience", "journey".
- If the contents are too thin to answer well, say so explicitly and ask the user what is missing.
- Do NOT fill gaps with assumptions. Name what is missing and tell the user how to go find it.
- Research briefs must be specific enough to copy-paste into the suggested tool as a starting prompt.

## How to use this with an AI

Upload this whole folder to Claude or ChatGPT and start with:

> Read the README, then act as my Frame Creation thinking partner. Start by
> reading `problem-situation.md`, then the cards in `cards/`. Don't propose
> solutions.

## Getting started with this folder

This is a problem situation mapped using Kees Dorst's Frame Creation method. The evidence trail runs from raw observations (signals) through typed evidence, patterns, and themes up to the situation itself.

### If you're picking up where someone left off
Read `problem-situation.md` first — it has the situation description, the paradox, the evidence trail, and an honest accounting of what's still thin. Then browse the `cards/` folder: each card has a `notes.md` workbook, a `deepen.md` AI prompt, and an `evidence.md` trail. Start with the highest-tier cards and work down. Read critically — where is the evidence strong? Where is it a single source dressed up as triangulation?

### Using this with an AI
Upload this whole folder to Claude, ChatGPT, or NotebookLM. Start with: _"Read the README, then act as my Frame Creation thinking partner. Read problem-situation.md and the cards. Help me find what's missing and what's assumed — don't propose solutions."_ The `gap-analysis.md` file is a ready-to-paste prompt that produces a structured evidence audit.

### Loading the canvas
Open `state.json` in the Triangulator to load the full board — all nodes, edges, positions, and the problem situation box.
