# Archon - Reorganized Book Structure

**System Name:** Archon  
**Status:** Work in Progress  
**Started:** 2026-06-29  
**Based on:** [REORGANIZATION-PROPOSAL.md](../REORGANIZATION-PROPOSAL.md)

This folder contains the reorganized **Archon Core Rules** structured by **reader need** and **moment of use** rather than mechanic type.

---

## Directory Structure

```
reorganized/
├── part-0-before-you-play/     # Welcome + Core Loop (both players and GM)
├── part-1-the-rules/           # Complete mechanical system (everyone reads)
├── part-2-your-character/      # Character creation and advancement (players)
├── part-3-running-the-game/    # GM guidance and encounter design (GM reads once)
├── part-4-reference/           # Quick reference and at-table lookup (everyone)
└── part-5-appendices/          # Optional and supplementary content
```

---

## Reading Paths

### New Player
1. Part 0 (Before You Play)
2. Part 1 (The Rules) - Chapters 1-6
3. Part 2 (Your Character) - Chapters 7-8, your Calling, Spellcasting if relevant

### New GM
Read everything in order (Parts 0-3), use Part 4 at the table

### Mid-Session Reference
- Players: Part 4 (Vantage, Cheat Sheet)
- GM: GM Cheat Sheet → Part 4 → relevant Part 3 chapter

---

## Migration Status

### Part 0: Before You Play (Unnumbered - Introductory)
- [x] welcome.md - ✅ Complete
- [x] core-loop.md - ✅ Complete (with worked example)

### Part 1: The Rules (Chapters 1-6)
- [x] 01-the-action-roll.md - ✅ Complete (dice mechanics, outcomes, Boons/Banes, Edge, Expertise)
- [x] 02-taking-action.md - ✅ Complete (Actions, Approaches, Vantage, Potent Actions)
- [x] 03-consequences.md - ✅ Complete (consequence tiers, Complications, Progress Tracks)
- [x] 04-resilience.md - ✅ Complete (Stress, Conditions, Push Yourself, Assist)
- [x] 05-momentum.md - ✅ Complete (Momentum, Create an Opening, Invoke Your Drive)
- [x] 06-traits.md - ✅ Complete (Traits, Special Effects, adjudication)

### Part 2: Your Character (Chapters 7-10)
- [x] 07-character-creation.md - ✅ Complete (7-step process, Drive, Connections)
- [x] 08-advancement.md - ✅ Complete (levels, Approaches, Talents, Rank)
- [x] 09-callings.md - ✅ Complete (6 Callings, Core/Additional Talents, background questions)
- [x] 10-spellcasting.md - ✅ Complete (Spheres, Domains, magnitude, rituals)

### Part 3: Running the Game
- [ ] 11-gm-principles.md
- [ ] 12-gm-moves.md
- [ ] 13-challenges.md
- [ ] 14-running-scenes.md
- [ ] 15-combat.md
- [ ] 16-advancement-gm.md

### Part 4: Reference
- [ ] vantage-reference.md
- [ ] gm-cheat-sheet.md
- [ ] complication-tags.md
- [ ] condition-reference.md

### Part 5: Appendices
- [ ] appendix-a-design-notes.md
- [ ] appendix-b-examples.md
- [ ] appendix-c-challenge-builder.md
- [ ] appendix-d-character-sheet.md

---

## Key Principles

### Every Mechanic Has One Home
- **Resist Consequence** → Chapter 3 (Consequences)
- **Push Yourself / Assist** → Chapter 4 (Resilience)
- **Create an Opening** → Chapter 5 (Momentum)
- **Invoke Your Drive** → Chapter 5 (Momentum)
- **Secondary Effects** → Chapter 6 (Traits)
- **Potent Actions** → Chapter 2 (Taking Action)
- **Vantage & High Stakes** → Chapter 2 (brief) + Vantage Reference (Part 4)
- **Challenge Design** → Chapter 13 (Part 3)

All other references use cross-references, not duplication.

### No Rules in GM Principles
Chapter 11 (GM Principles) contains pure technique and guidance. All mechanical rules live in Part 1.

---

## Archived Documents

Planning docs that served their purpose during early migration are in `archive/`:
- MIGRATION-PLAN.md (content mapping, superseded by actual chapters)
- DRIFT-ANALYSIS.md (one-time audit, issues resolved)
- CHAPTER-2-DRIFT-CHECK.md (specific audit, resolved)
- IRONSWORN-COMPARISON.md (influenced early decisions, no longer actionable)
