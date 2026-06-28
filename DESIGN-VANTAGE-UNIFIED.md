# Design Draft: Vantage as the Single Difficulty and Circumstance Tool

**Status:** Design decision — ready for implementation  
**Date:** 2026-06-27  
**Scope:** Retirement of the Stakes system; integration of circumstance and danger into the existing five-tier Vantage system; addition of a High Stakes declaration flag

---

## Summary of Change

The separate Stakes system (Low / Regular / High) is retired. Vantage now serves as the single tool for assessing both difficulty and fictional circumstances before an action roll. A lightweight High Stakes declaration flag replaces the mechanical function of High Stakes for moments where consequence severity genuinely needs to be elevated.

This reduces the GM's pre-roll assessment from two parallel systems to one unified question: **"What is your Vantage here?"**

---

## Why This Works

Stakes and Vantage were measuring overlapping things. Stakes asked "how dangerous is this situation?" Vantage asked "how favorable is your position?" In practice, a dangerous situation IS a situation where your position is less favorable — and a favorable situation IS one where circumstances actively help you succeed.

The merchant example illustrates this cleanly. A friendly merchant doesn't just lower the stakes of negotiation — they genuinely improve your position. They negotiate in good faith, volunteer useful information, and are predisposed to find a deal that works for both parties. That is Strong Vantage: circumstances actively working in your favor. An indifferent merchant is Standard. A hostile merchant actively trying to get the upper hand is Limited.

The fictional context — who this person is to you, what they want, how they're positioned — directly determines Vantage. Stakes as a separate concept is redundant because the fiction already captures it.

---

## The Five-Tier Vantage System as Circumstance Tool

Vantage already exists as a five-tier system. What changes is how GMs interpret and apply it — specifically, that **Strong and Limited Vantage now explicitly capture favorable and unfavorable circumstances**, not just capability and tools.

### The Adjudication Principle

The test for Strong vs Standard vs Limited is:

**"Do the circumstances actively help, actively hinder, or neither?"**

- Circumstances actively working in your favor → **Strong** (1-2 Boons)
- Circumstances neutral → **Standard** (no modifier)
- Circumstances actively working against you → **Limited** (1-2 Banes)

This applies to both capability-based positioning (do you have the right tools?) and circumstance-based positioning (is the fiction helping or hindering you?).

### Examples Across Both Dimensions

**Capability-based:**
- Champion with weapon in normal combat → Standard
- Champion without a weapon → Limited (1 Bane)
- Shadow with full kit picking a familiar lock → Strong (1 Boon)

**Circumstance-based:**
- Negotiating with a friendly merchant → Strong (they want to deal fairly)
- Negotiating with an indifferent merchant → Standard
- Negotiating with a hostile merchant trying to swindle you → Limited (1-2 Banes)

**Combined:**
- Champion without a weapon facing an armored knight in a cramped corridor → Limited (2 Banes — no weapon AND poor position)
- Shadow with full kit in their home territory, target is distracted → Strong (2 Boons — ideal tools AND favorable circumstances)

### The Existing Five Tiers Are Unchanged

Certain and Impossible remain exactly as defined. Strong and Limited now carry explicit circumstance meaning alongside their existing capability meaning. Standard remains the unmarked baseline.

---

## The High Stakes Flag

One genuine use case from the old Stakes system survives: moments where the GM needs to signal that consequences will be more severe than normal, regardless of Vantage.

This is handled by a **High Stakes declaration** — a brief statement made aloud during pre-roll framing. It is not a tier of Vantage. It is not a subsystem. It is a single sentence and a single mechanical effect.

### The Rule

> When the fiction demands consequences more severe than normal — a climactic confrontation, a life-or-death moment, a catastrophic potential failure — the GM declares High Stakes before the roll. Consequence Tier increases by 1 for this roll.

**Mechanical effect:** Consequence Tier +1

- Conflict → Major Consequence (instead of Minor)
- Setback → Severe Consequence (instead of Major)
- Disaster → Severe Consequence (already the ceiling; GM may describe it more devastatingly)

### How to Use It

The GM states it explicitly as part of pre-roll framing — not after the roll, not implied, but declared:

> "The dragon's attention is fully on you. **This is High Stakes** — if you stumble here, the consequences will be severe. What do you do?"

This serves two purposes: it gives players the information they need to make informed decisions about spending Momentum or invoking Traits before rolling, and it signals that this moment matters in a way that the fiction demands be felt mechanically.

### When to Use It

High Stakes should be **rare and reserved for moments the fiction clearly demands it.** It is not a routine modifier. Most rolls — even difficult ones, even dangerous ones — do not need it. Limited Vantage (Banes) already makes failure more likely. High Stakes is for when the cost of failure needs to be elevated beyond normal, not just the difficulty.

**Use High Stakes when:**
- Boss fights or climactic confrontations where standard Severe consequences feel insufficient
- Life-or-death moments where the fiction demands irreversible weight
- The single roll that determines whether the ritual completes, the bomb goes off, the ally survives

**Do not use High Stakes when:**
- The situation is dangerous but Limited Vantage already captures that danger
- You want consequences to feel dramatic — that's GM narration, not a mechanical modifier
- Every fight against a significant enemy — reserve it for truly exceptional moments

### Interaction with Vantage

High Stakes and Vantage are independent. A roll can be:

- Standard Vantage + High Stakes (normal difficulty, severe consequences — the classic "simple action at the worst moment")
- Limited Vantage + High Stakes (hard AND severe — the climactic boss fight)
- Strong Vantage + High Stakes (favorable position but the stakes are enormous — defusing a bomb with the right tools, but one wrong move ends everything)

The separation matters. A skilled character in a good position can still face High Stakes — their competence doesn't insulate them from the weight of the moment.

---

## What Replaces Stakes.md

The stakes.md standalone document is retired. Its content is distributed as follows:

| Content | New Home |
|---|---|
| The three-tier Stakes framework | Retired — replaced by Vantage + High Stakes flag |
| Communicating danger through fiction | GM Principles (Chapter 11 in redesign / Chapter 7 currently) |
| Consequence calibration guidance | Consequence Calibration Guide (Chapter 14 in redesign / Chapter 7 currently) |
| Stakes + Complications interaction | Vantage reference document (note that High Stakes and Complications are independent) |
| Worked examples | Appendix B in redesign / can be absorbed into Chapter 7 currently |

---

## Pre-Roll Framing Sequence

The GM's assessment before any action roll is now:

1. **Is a roll needed?** — Certain Vantage means no roll; success is automatic
2. **What is the Vantage?** — Sets Boon/Bane count based on capability and circumstances
3. **Any Complications?** — Sets outcome tier reduction from Challenge tags
4. **High Stakes?** — GM declares if Consequence Tier increases; stated aloud if yes
5. **Simple or complex?** — Immediate resolution or progress track

This is one fewer assessment than the previous sequence (which included a separate Stakes evaluation between steps 2 and 3). More importantly, steps 2 and the retired Stakes assessment are now unified — the GM asks one question ("what is the Vantage?") instead of two ("how hard is it?" and "how dangerous is it?").

---

## Vantage Reference Update

The Vantage reference document needs one addition to capture the circumstance dimension of Strong and Limited:

**Add under Strong Vantage:**
> Strong Vantage applies when circumstances actively work in your favor — not merely when they're non-hostile. A friendly NPC, ideal tools, superior position, or any fictional condition that genuinely helps you succeed warrants Strong Vantage.

**Add under Limited Vantage:**
> Limited Vantage applies when circumstances actively work against you — not merely when the task is challenging. A hostile NPC, missing tools, poor position, or any fictional condition that genuinely hinders your attempt warrants Limited Vantage.

**Add under Standard Vantage:**
> Standard Vantage is the neutral baseline. Circumstances neither help nor hinder. Most rolls are Standard.

---

## GM Cheat Sheet Update

**Remove:** The Stakes rows (Low / Regular / High with consequence adjustments)

**Add to pre-roll sequence block:**
> High Stakes (optional declaration): Consequence Tier +1. State aloud before the roll.

---

## Current Document Locations

Until the layout redesign is implemented, the following files need updating:

- **stakes.md** — Retire this file. Add a note at the top pointing to the Vantage reference and Chapter 7's Consequence Calibration Guide.
- **vantage.md** — Add the three paragraphs above (Strong, Limited, Standard circumstance language) and a brief section on the High Stakes flag.
- **Chapter 7 (GM Guide)** — Remove the Setting Stakes section. Add the High Stakes flag as a brief addition to the pre-roll framing guidance. Retain the Consequence Calibration Guide.
- **Chapter 4 (Action Resolution)** — Remove Stakes references from the GM Assesses step. Add High Stakes flag to the pre-roll framing sequence.
- **Chapter 2 (Core Mechanics)** — Remove Stakes from any introductory material if present.
- **GM Cheat Sheet** — Apply updates noted above.

---

## What Is Not Changing

- The five-tier Vantage system itself is unchanged
- Complications remain a separate post-roll outcome modifier
- The Consequence Calibration Guide remains in the GM chapter as practical guidance
- All existing Vantage examples and the Three Questions framework remain valid
- The Hint → Reveal → Strike pattern handles danger communication through fiction and is unaffected

---

## Benefits of This Change

**For GMs:**
- One unified assessment instead of two parallel systems
- Clearer adjudication principle ("do circumstances help or hinder?")
- Less pre-roll cognitive load
- High Stakes flag is simple and explicit

**For Players:**
- One fewer system to learn
- Clearer understanding of their position before rolling
- High Stakes declaration gives clear information for decision-making

**For the System:**
- Eliminates redundancy between Stakes and Vantage
- Maintains the power to elevate consequences when needed (High Stakes flag)
- Simpler without losing expressiveness
- Better aligns with fiction-first principles
