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
├── part-3-reference/           # Quick reference and at-table lookup (everyone)
├── part-4-running-the-game/    # GM-only content
└── part-5-appendices/          # Optional and supplementary content
```

---

## Reading Paths

### New Player
1. Part 0 (Before You Play)
2. Part 1 (The Rules) - Chapters 1-6
3. Part 2 (Your Character) - Chapter 7-8, your Calling, Spellcasting if relevant

### New GM
Read everything in order (Parts 0-4)

### Mid-Session Reference
- Players: Part 3 (Vantage, Stakes, Cheat Sheet)
- GM: GM Cheat Sheet → Part 3 → relevant Part 4 chapter

---

## Migration Status

### Part 0: Before You Play
- [x] 01-welcome.md - ✅ Complete
- [x] 02-core-loop.md - ✅ Complete (with worked example)

### Part 1: The Rules
- [x] 01-the-action-roll.md - ✅ Complete (dice mechanics, outcomes, Boons/Banes, Edge, Expertise)
- [ ] 02-taking-action.md - Migrate from 02-core-mechanics.md + 04-action-resolution.md + vantage.md
- [ ] 03-consequences.md - Migrate from 04-action-resolution.md + 05-resilience.md
- [ ] 04-resilience.md - Migrate from 05-resilience.md (Push Yourself and Assist canonical home)
- [ ] 05-momentum.md - NEW (consolidate from scattered references)
- [ ] 06-traits.md - Migrate from 03-characters.md + 02-core-mechanics.md

### Part 2: Your Character
- [ ] 07-character-creation.md - Migrate from 03-characters.md
- [ ] 08-advancement.md - Migrate from 03-characters.md
- [ ] 09-callings.md - Copy from 09-callings.md (with fixes)
- [ ] 10-spellcasting.md - Copy from 10-spellcasting.md (with cleanup)

### Part 3: Reference
- [ ] vantage-reference.md - Copy from vantage.md (5-tier Vantage + High Stakes)
- [ ] gm-cheat-sheet.md - Copy from gm-cheat-sheet.md (with gaps filled)

**Note:** Stakes system simplified—no separate stakes-reference.md. High Stakes is now an optional flag within Vantage framework.

### Part 4: Running the Game
- [ ] 11-gm-principles.md - Migrate from 07-gm-guide.md (technique only, no rules)
- [ ] 12-gm-moves.md - Extract from 07-gm-guide.md
- [ ] 13-challenges.md - Migrate from 06-challenges.md (consolidate examples)
- [ ] 14-running-scenes.md - Migrate from 07-gm-guide.md (scene tools)
- [ ] 15-combat.md - Migrate from 08-combat.md
- [ ] 16-advancement-gm.md - Migrate from 03-characters.md + 07-gm-guide.md

### Part 5: Appendices
- [ ] appendix-a-design-notes.md - Copy from appendix-a-design-notes.md
- [ ] appendix-b-examples.md - Consolidate examples from all chapters
- [ ] appendix-c-challenge-builder.md - Migrate from appendix-c-challenge-quick-reference.md
- [ ] appendix-d-character-sheet.md - NEW

---

## Key Principles

### Every Mechanic Has One Home
- **Resist Consequence** → Chapter 3 (Consequences)
- **Push Yourself** → Chapter 4 (Resilience)
- **Assist** → Chapter 4 (Resilience)
- **Create an Opening** → Chapter 5 (Momentum)
- **Tangles** → Chapter 5 (rules) + Chapter 14 (GM guidance)
- **Secondary Effects** → Chapter 6 (Traits)
- **Seize Spotlight** → Chapter 15 (Combat)
- **When to Award Levels** → Chapter 16 (Advancement GM)
- **Social Conflict** → Chapter 14 (Running Scenes)
- **Boss Design** → Chapter 13 (Challenges)
- **Vantage & High Stakes** → Vantage Reference (Part 3)

All other references use cross-references, not duplication.

### No Rules in GM Principles
Chapter 11 (GM Principles) contains pure technique and guidance. All mechanical rules live in Part 1.

### Examples Separated
Extended examples move to Appendix B. Rules chapters get shorter and more scannable.

---

## Implementation Notes

### Phase 1: Create New Structure
1. ✅ Create directory structure
2. Write Part 0 content (Welcome + Core Loop)
3. Create placeholder files for all chapters

### Phase 2: Migrate Core Rules (Part 1)
1. Extract dice mechanics into Chapter 1
2. Consolidate action resolution into Chapter 2
3. Build new Momentum chapter (Chapter 5)
4. Clean up cross-references

### Phase 3: Migrate Character Content (Part 2)
1. Simplify character creation to decision points only
2. Split advancement into player and GM sections
3. Fix Callings typos and Push Yourself references
4. Clean up Spellcasting duplication

### Phase 4: Build Reference Layer (Part 3)
1. Copy and format Vantage/Stakes/Cheat Sheet
2. Add missing content to Cheat Sheet
3. Ensure all references are definitive

### Phase 5: Migrate GM Content (Part 4)
1. Extract technique from rules in GM Guide
2. Give GM Moves their own chapter
3. Consolidate Challenge examples
4. Build Scene Running chapter from scattered content

### Phase 6: Polish
1. Consolidate examples into Appendix B
2. Complete Design Notes
3. Build Quick Challenge Builder
4. Test reading paths with fresh readers

---

## Review Feedback Summary

### Strengths
- Clear design philosophy (reader need vs mechanic type)
- Addresses root causes of rules drift
- Eliminates duplication structurally
- Separate reading paths for players/GMs

### Suggested Improvements
1. **Part 1 density**: Consider extracting quick-reference tables to Part 3
2. **Chapter 2 scope**: Potentially split Actions/Approaches from Vantage/Stakes
3. **Momentum placement**: Consider moving before Traits (Ch 4 instead of Ch 5)
4. **Spellcasting scope**: Flag more prominently as "Spellcasters only"
5. **Core Loop example**: Ensure it's truly minimal (not comprehensive)

### Implementation Risks
- Large scope (multi-session effort)
- Content loss during migration
- Cross-reference maintenance burden
- Needs fresh reader testing

---

## Migration Workflow

**Preservation Strategy:** Original files in `/heroic-fantasy-rpg/` remain untouched during migration. New content goes in `/reorganized/`. Archive originals only after complete verification.

## Next Steps

1. Create Quick Start Guide (10 pages, standalone document)
2. Write Part 0 content (Welcome + Core Loop example)
3. Create placeholder files for all chapters
4. Begin migration with Chapter 1 (Rolling Dice) as proof of concept
5. Review proof of concept before continuing
6. Continue migration in phases (see MIGRATION-PLAN.md)
7. Verify all content transferred before archiving originals

---

## Questions for Review

1. Should Momentum move to Chapter 4 (before Resilience)?
2. Should Vantage/Stakes be combined into one reference doc?
3. Should Part 3 include quick-reference tables extracted from Part 1?
4. Should Spellcasting move to Part 4 with player summary in Part 2?

