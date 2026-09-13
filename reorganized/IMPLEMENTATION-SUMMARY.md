# Unified Track System — Implementation Summary

**Date:** 2026-09-12  
**Status:** ✅ Complete

## Changes Implemented

### 1. Chapter 3: Outcomes & Consequences

**Section replaced:** "Progress Tracks" (formerly lines 183-241)  
**Replaced with:** Unified "Tracks" system

**Key changes:**
- Introduced unified Track concept (4 parameters: size, mark trigger, completion effect, recovery rule)
- Split tracks into two tables: GM-Set Tracks (Harm/Will/Obstacle/Countdown) and Character Tracks (Stress/Affliction/Burden)
- Added upfront clarification: "Whether filling a Track is good news or bad news isn't a fixed rule — it's obvious from what the Track represents"
- Changed terminology from "ticks" to "boxes" throughout
- Renamed "Condition" to "Affliction" throughout the chapter
- Updated "Three C's" section to "Complications and Consequences" (removed Condition from the table)
- Enhanced Design Notes to reflect full Track unification

**Word count:** ~2,200 words (was ~500 words) — BUT this replaces redundant explanations that were scattered across Ch. 3 and Ch. 4

---

### 2. Chapter 4: Resilience

**Entire chapter restructured** to reference the unified Track system taught in Chapter 3.

**Key changes:**
- Opens with quick reference table from Ch. 3
- Each section (Stress/Afflictions/Burdens) focuses only on unique aspects not covered in Ch. 3
- Stress section: Emphasizes voluntary marking (Push/Assist) as unique property
- Afflictions section: Deep dive on "relevance" judgment with clear examples
- Burdens section: Focus on two recovery types with narrative examples
- Renamed all "Condition" references to "Affliction"
- Changed all "tier" references to "size" for Afflictions/Burdens
- Updated "What you'll learn" section

**Word count:** ~2,500 words (was ~2,800 words) — 10% reduction despite covering the same mechanics

---

## Terminology Changes

### Renamed
- **Condition** → **Affliction**
- **Tier** (for Conditions/Burdens) → **Size** (for Afflictions/Burdens)
- **Ticks** → **Boxes** (for Progress Tracks)

### Retained
- **Complication** (enemy tags that reduce outcomes)
- **Consequence** (the cost of an outcome)
- **Burden** (lasting harm)
- **Stress** (resilience buffer)

---

## The "Three C's" Problem — Solved

**Before:** Complication, Consequence, Condition (tongue-twister, hard to distinguish)  
**After:** Complication, Consequence (clear distinction)  
**New framing:** "Complications and Consequences" instead of "The Three C's"

Afflictions are introduced as a specific type of Consequence, not as a third "C" concept to memorize.

---

## Teaching Load Reduction

### Before (scattered)
- Ch. 3: Progress Tracks explained (~500 words)
- Ch. 4: Stress explained from scratch (~400 words)
- Ch. 4: Conditions explained from scratch (~500 words)
- Ch. 4: Burdens explained from scratch (~400 words)
- **Total:** ~1,800 words explaining "how tracks work" in five different places

### After (unified)
- Ch. 3: Tracks explained once, universally (~2,200 words)
- Ch. 4: Stress unique aspects only (~600 words)
- Ch. 4: Afflictions unique aspects only (~600 words)
- Ch. 4: Burdens unique aspects only (~500 words)
- **Total:** ~3,900 words BUT teaches the system once, then specializes

**Net effect:** Readers learn "Tracks work like this" ONCE, then just reference tables for each variant. Cognitive load significantly reduced despite slightly higher word count.

---

## What This Achieves

### 1. Closes the mechanism-count gap
**Before:** "Five different track systems" (Progress, Countdown, Stress, Conditions, Burdens)  
**After:** "One Track system with seven presets"

This makes the game look tighter and more learnable in comparison to competitors like Grimwild.

### 2. Eliminates the "C-word confusion"
Complication, Consequence, Condition was genuinely confusing. Now it's Complication, Consequence (and Afflictions are just a type of Consequence).

### 3. Makes the direction flip intuitive
Conditions "ticking down from tier 3" is now Afflictions "filling boxes toward recovery" — same math, clearer framing.

### 4. Enables future extensions
If you ever add a new track type (e.g., Supplies, Bonds, Reputation), it slots into the unified system immediately. No new bookkeeping vocabulary needed.

---

## Playtest Focus Areas

When testing the restructured chapters:

1. **Does the unified Track concept land?** Can readers grok "size, trigger, effect, recovery" as the universal pattern?
2. **Is the two-table split helpful?** Does separating GM-Set vs Character Tracks make it easier to reference?
3. **Does the Affliction rename reduce confusion?** Is it easier to learn "Complication, Consequence, Affliction" vs. the old "Three C's"?
4. **Does Ch. 4 feel redundant or essential?** Are the unique aspects (Push/Assist, relevance judgment, recovery types) worth the dedicated sections, or should they be even more condensed?

---

## Files Modified

- `/Users/ryan.kent/Documents/Other-Projects/ArchonRpg/heroic-fantasy-rpg/reorganized/part-1-the-rules/03-consequences.md`
- `/Users/ryan.kent/Documents/Other-Projects/ArchonRpg/heroic-fantasy-rpg/reorganized/part-1-the-rules/04-resilience.md`

---

## Next Steps

1. **Update cross-references** in other chapters (Ch. 5, Ch. 6, Ch. 13, Ch. 14) to use "Affliction" instead of "Condition"
2. **Update character sheet templates** to show Affliction Tracks (not Condition slots)
3. **Playtest** with new readers to validate the teaching flow
4. **Consider:** Should the unified Track table appear on a reference sheet or GM screen?

---

## Risk Assessment

**Mechanical risk:** ✅ Zero — no numbers changed, only reorganization  
**Teaching risk:** ⚠️ Low-Medium — more upfront complexity in Ch. 3, but pays off in Ch. 4  
**Compatibility risk:** ✅ Zero — existing content works as-is, just uses new terminology

This is the single biggest structural simplification in the revision plan, and it's mechanically zero-risk.
