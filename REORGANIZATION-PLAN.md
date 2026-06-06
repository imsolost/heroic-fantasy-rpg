# File Reorganization Plan

## Goals
1. Clear reading order (numbered chapters)
2. Remove duplication
3. Each topic covered in ONE authoritative place
4. Separate core rules from GM advice from optional appendices

## New Structure

### Core Chapters (01-08)

**01-introduction.md** ✅ DONE
- What is this game
- Core concepts overview
- Quick start example
- What's next

**02-core-mechanics.md** ⏳ TODO
- Source: resolution.md (dice mechanics, probability) + core-foundations.md (Actions, Approaches, Outcomes)
- Dice pool method (Xd6, highest die)
- Five Actions (Primary Effects)
- Five Approaches (ratings 0-5)
- Four Outcomes (Setback/Conflict/Success/Triumph)
- Edge & Bane system
- Probability tables
- Advancement structure

**03-characters.md** ⏳ TODO
- Source: traits-complications-challenges.md (Traits section) + scattered character creation content
- Character creation process
- Traits (definition, invocation, Special Effects)
- Talents (examples, design principles)
- Advancement

**04-action-resolution.md** ⏳ TODO
- Source: action-roll.md (mostly keep as-is, minor cleanup)
- Complete Action Roll procedure
- Track types (Obstacle, Harm, Accord)
- Momentum spends during rolls
- Resist Consequence mechanics
- Impact Moves

**05-resilience.md** ⏳ TODO
- Source: stress-conditions.md (THE authoritative doc, keep as-is, just rename)
- Stress Track (5 boxes, overflow)
- Conditions (named, tiers, Banes)
- Burdens (persistent)
- Recovery (short/long rest)
- Taken Out

**06-challenges.md** ⏳ TODO
- Source: traits-complications-challenges.md (Challenges section)
- Challenge structure (Traits, Consequence Moves, recovery)
- Complications system
- Creating enemies
- Boss design patterns

**07-gm-guide.md** ✅ KEEP AS-IS (already well-organized)
- Source: gm-guidance.md (just rename)
- GM Agendas & Principles
- GM Moves (Story/Suspense/Impact)
- Difficulty setting
- Spotlight management

**08-combat.md** ⏳ TODO (minor cleanup)
- Source: combat-design.md (mostly keep, remove duplication)
- Combat flow
- Enemy design
- Tactical considerations
- Quick reference

### Appendices

**appendix-a-design-notes.md** ⏳ TODO
- Source: design-notes.md (just rename, optional reading)

**appendix-b-examples.md** ⏳ TODO
- Source: examples-stress-conditions.md (just rename, optional reading)

## Files to Remove After Merge

- ❌ core-foundations.md (split into 02/03/05)
- ❌ resolution.md (merge into 02)
- ❌ traits-complications-challenges.md (split into 03/06)
- ❌ gm-guidance.md (renamed to 07)
- ❌ action-roll.md (renamed to 04)
- ❌ stress-conditions.md (renamed to 05)
- ❌ combat-design.md (renamed to 08)
- ❌ design-notes.md (renamed to appendix-a)
- ❌ examples-stress-conditions.md (renamed to appendix-b)

## Execution Order

1. ✅ Create 01-introduction.md
2. ⏳ Create 02-core-mechanics.md (merge resolution.md + parts of core-foundations.md)
3. ⏳ Create 03-characters.md (Traits from traits-complications-challenges.md)
4. ⏳ Rename action-roll.md → 04-action-resolution.md (minor edits)
5. ⏳ Rename stress-conditions.md → 05-resilience.md (keep as-is)
6. ⏳ Create 06-challenges.md (Challenges from traits-complications-challenges.md)
7. ⏳ Rename gm-guidance.md → 07-gm-guide.md (keep as-is)
8. ⏳ Rename combat-design.md → 08-combat.md (minor cleanup)
9. ⏳ Rename design-notes.md → appendix-a-design-notes.md
10. ⏳ Rename examples-stress-conditions.md → appendix-b-examples.md
11. ⏳ Update README.md with new structure
12. ⏳ Remove old files
13. ⏳ Commit and push

## Status

✅ **COMPLETE** — All files reorganized and old files moved to old-ideas/

All chapters created, appendices renamed, README updated, old files archived.
