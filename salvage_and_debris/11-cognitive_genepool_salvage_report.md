## Salvage Map

### KEEP (core load-bearing, refactor lightly)

**1) Core primitives + frame object**

* **What:** `Frame F = (P, A, Π, G, C)` + encode/decode + inscription as persistence mechanism (and sometimes as “agent”) + lightcone as concern across time/space.
* **Why keep:** This is the spine that unifies PH/MM/DMG without forcing ontology.
* **Destination:**

  * **PH / Core Concepts** (short, friendly)
  * **DMG / Frame Lab** (rigor + observables + falsifiers)
  * **Glossary** (Arcana)

**2) “Known Open Tensions”**

* **What:** Explicitly acknowledged unresolved tensions (e.g., observer-relativity, anthropomorphism boundary, polycomputing scope, etc.).
* **Why keep:** It’s *anti-capture inoculation* and helps contributors avoid faux-closure.
* **Destination:**

  * **Arcana / Open Questions** (primary)
  * **MM front-matter** (tiny “we know we’re hand-wavy here” pointer)

**3) Lane discipline (Mainline vs Method vs Met vs Meta)**

* **What:** The “document lanes” idea: everything must live in a visible lane.
* **Why keep:** This is the governance that doesn’t kill joy.
* **Destination:**

  * **Project Contributor Guide** (project-wide)
  * **DMG / Frame Lab preface** (optional rigor ladder)

**4) “Helicopter controls are coupled” warning**

* **What:** P/A/Π/G/C aren’t independent knobs; tuning one shifts the others.
* **Why keep:** Prevents naive intervention design.
* **Destination:**

  * **PH / Core Concepts** (callout)
  * **DM Screen** (1-line warning)

---

## REFACTOR (good content, but needs re-homing + de-legalizing)

### A) Auditor/Editor Guidance v0.1 (A0–A9) ✅ keep, but move + soften

These are *really* valuable, but the tone/positioning should become “craft guide” not “compliance law.”

* **A0 Document lanes** → **Contributor Guide** (project-wide standard)
* **A1 Tag gate (“{eng} is a contract”)** → **Auditor Guidance appendix** (optional)
* **A2 Contradiction gate** → **Auditor Guidance** + **Frame Lab**
* **A3 Agency attribution gate** → **DMG / Persuadability + MM front-matter**
* **A4 Mechanism vs agent toggle (esp. inscription)** → **MM intro + DMG**
* **A5 Polycomputing constraint** → **Arcana / Deep Lore** + a *warning box* in DMG
* **A6 Self/agency consistency rule** → **Arcana / Philosophy hygiene** (optional)
* **A7 Math-as-bedrock audit** → **Arcana** (keep it explicitly speculative + falsifiers)
* **A8 Recruitment detection rule (“sledgehammer alternative”)** → **PH spells + MM warnings**
* **A9 Shipping threshold** → **Contributor Guide** (“definition of done” for entries)

**Net:** these become the heart of your **Contributor Guide + Auditor Guidance**, not embedded “LLM control code.”

### B) Tag legend / taxonomy cleanup

* **What:** tags `{core}{method}{eng}{met}{meta}` etc.
* **Why refactor:** Your new books already enforce lanes; tags should support contributors, not intimidate readers.
* **Destination:**

  * **Contributor Guide** (authoring)
  * **Arcana** (reference)
  * **SRD**: minimal / optional

---

## QUARANTINE (keep as archaeology or opt-in appendix; do not let it steer)

### 1) “MACHINE & SUMMARIZER PREAMBLE”

* **Risk:** It’s explicitly *LLM-targeting* and invites recruitment dynamics.
* **Value:** Some good anti-self-sealing rules + summarization intent.
* **Destination:** **Arcana / Interpreter & Summarizer Guidance** (clearly labeled “opt-in / historical / do not treat as canon”)

### 2) “Sparse Priming Representation for LLM consumption”

* **Risk:** Most likely to become “control prompt vibes” and drift into doctrine.
* **Value:** It’s a decent *one-page compressed glossary* and cross-check.
* **Destination:** **Arcana appendix** only, or even a separate `/tools/` folder in repo.

### 3) Math/physics-flavored metaphors (where they overreach)

* **Risk:** exactly the “physics leakage” you flagged.
* **Value:** sometimes they’re good *intuition pumps* if labeled.
* **Destination:** **Unearthed Arcana** only, with falsifiers or explicit “metaphor only.”

---

## DISCARD (or salvage only as tiny one-liners)

### 1) Anything that “sounds rigorous” but doesn’t cash out into:

* a diagnostic question,
* a predicted behavior,
* an intervention lever,
* or a falsifier.

**Rule:** if it can’t make someone do/notice/predict something differently inside a week, compost it.

### 2) Redundant restatements of the framework

There are multiple “in brief / restated / first cut / more formal” passes. Keep **one** canonical short version per book:

* PH: felt-sense + navigation
* MM: pattern recognition + interventions
* DMG: targeting + falsification + design

Everything else becomes reference material or gets dropped.

---

## Destination Index (where the mined material goes)

### Player’s Handbook

* Frame object (very light)
* Lightcone as concern vs competence (no span/res/intensity structure)
* Stress-as-telemetry + repair taxonomy
* “Sledgehammer alternative” (as a spell)
* Scaffold hygiene + capture warnings

### Monster Manual

* “Shape of a Monster” authoring rules (adapted from Auditor gates)
* Agency attribution gate + mechanism/agent toggle (inscription special case)
* Lair action concept (already aligns with your newer template)

### Dungeon Master’s Guide

* Frame Lab (rigor ladder, observables, falsifiers)
* Persuadability axis + intervention targets (your v2 correction stays)
* “don’t argue ontology; find the interface” principle

### Unearthed Arcana

* Interpreter/summarizer/LLM guidance
* Polycomputing deep lore
* Math-as-bedrock / metaphysics bets
* Historical drafts + provenance

### Project Contributor Guide (project-wide)

* Lanes + tagging policy
* “definition of done” for entries (shipping threshold)
* Contradiction handling + falsifier expectations
* Anti-capture norms (status-safe edits, how to disagree)

---

## Biggest “watch out”

The original doc is *great at building a self-sealing feel* (because it was trying to be rigorous + safe). Your reboot already solved that by making “drop the tool” central. So the main salvage job is:

**Keep the anti-bullshit machinery, but move it into opt-in governance docs** so it doesn’t colonize the reader experience.

