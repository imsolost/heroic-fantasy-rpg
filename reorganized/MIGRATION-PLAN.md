# Migration Plan & Content Mapping

This document maps current content to new locations and tracks migration progress.

---

## Content Mapping: Current → New

### Current: 01-introduction.md
**Migrate to:**
- Part 0: welcome.md (orientation)
- Part 0: core-loop.md (quick start)
- Part 1: 01-rolling-dice.md (dice basics if not redundant)

---

### Current: 02-core-mechanics.md
**Split into:**
- Part 1: 01-rolling-dice.md (dice pool, outcomes, Boon/Bane, Edge, Expertise, probability)
- Part 1: 02-taking-action.md (Actions, Approaches, when to roll)
- Part 1: 05-momentum.md (Momentum earn/spend, cap)

**Rules to Extract:**
- Dice pool mechanics → Ch 1
- Four outcomes → Ch 1
- Boon/Bane sources and ±2d cap → Ch 1
- Edge definition → Ch 1
- Expertise definition → Ch 1
- Five Actions → Ch 2
- Five Approaches → Ch 2
- Momentum system → Ch 5

---

### Current: 03-characters.md
**Split into:**
- Part 2: 07-character-creation.md (creation process only)
- Part 2: 08-advancement.md (player-facing advancement)
- Part 4: 16-advancement-gm.md (when to award levels)
- Part 1: 06-traits.md (Trait mechanics)

**Rules to Extract:**
- Character creation steps → Part 2, Ch 7
- Starting arrays (3/2/1/1/0) → Part 2, Ch 7
- Trait system → Part 1, Ch 6
- Advancement table → Part 2, Ch 8
- Ranks (1-4) → Part 2, Ch 8
- When to Award Levels → Part 4, Ch 16

---

### Current: 04-action-resolution.md
**Split into:**
- Part 1: 01-rolling-dice.md (pool minimum)
- Part 1: 02-taking-action.md (resolution sequence, Vantage, Stakes)
- Part 1: 03-consequences.md (consequence tiers, Complications, tracks, Resist Consequence)

**Rules to Extract:**
- When to roll → Ch 2
- Vantage (4-tier) → Ch 2 (with cross-ref to Vantage Reference)
- Stakes → Ch 2 (with cross-ref to Stakes Reference)
- Resolution sequence → Ch 2
- Consequence framework → Ch 3
- Complication mechanics → Ch 3
- Progress tracks → Ch 3
- Impact Moves → Ch 3
- Resist Consequence → Ch 3

---

### Current: 05-resilience.md
**Migrate to:**
- Part 1: 04-resilience.md (with Push Yourself and Assist added)

**Rules to Add:**
- **Push Yourself** (canonical definition): mark 1 Stress for 1 Boon on your own roll
- **Assist** (canonical definition): mark 1 Stress for 1 Boon on an ally's roll

**Current Content:**
- Stress track (5 boxes)
- Conditions system
- Burdens
- Stress Overflow
- Taken Out
- Short Rest / Long Rest

---

### Current: 06-challenges.md
**Migrate to:**
- Part 4: 13-challenges.md (GM-facing design tools)

**Content to Clean:**
- Consolidate dragon stat block to one canonical version
- Remove repetition in examples
- Integrate Boss Design from 07-gm-guide.md
- Add Quick Challenge template

---

### Current: 07-gm-guide.md
**Split into:**
- Part 4: 11-gm-principles.md (pure technique, no rules)
- Part 4: 12-gm-moves.md (move taxonomy)
- Part 4: 13-challenges.md (Boss Design section)
- Part 4: 14-running-scenes.md (scene tools, Social Conflict canonical home)

**Rules to Extract:**
- GM Agendas → Ch 11
- GM Principles → Ch 11
- When to roll (cross-ref Ch 2) → Ch 11
- Action Scope → Ch 11
- Spotlight management → Ch 11
- Session structure → Ch 11
- Story Moves → Ch 12
- Suspense Moves → Ch 12
- Impact Moves → Ch 12
- Hint → Reveal → Strike → Ch 12
- Boss Design → Ch 13
- Investigation framework → Ch 14
- Social Conflict → Ch 14 (canonical home)
- Consequence Calibration → Ch 14
- Battlegrounds → Ch 14
- Clocks and Tracks → Ch 14
- Tangles (GM guidance) → Ch 14

---

### Current: 08-combat.md
**Migrate to:**
- Part 4: 15-combat.md (with Helping Allies as core, not optional)

**Content to Fix:**
- Integrate Helping Allies as core
- Define Seize Spotlight
- Fix Momentum accounting in example

---

### Current: 09-callings.md
**Migrate to:**
- Part 2: 09-callings.md (copy with fixes)

**Fixes Needed:**
- Add Push Yourself cross-references to all Talents that use it
- Fix typos
- Add Champion Talent differentiators

---

### Current: 10-spellcasting.md
**Migrate to:**
- Part 2: 10-spellcasting.md (with cleanup)

**Cleanup Needed:**
- Cut Summary section
- Cut duplicate Potent examples
- Fix rules drift (already done in current file?)

---

### Current: vantage.md
**Migrate to:**
- Part 3: vantage-reference.md (complete framework: 5-tier Vantage + High Stakes)
- Part 1: 02-taking-action.md (brief explanation with cross-ref to Reference)

**Note:** Current vantage.md includes both Vantage framework AND High Stakes (optional). Stakes system has been simplified—no longer separate Low/Regular/High Stakes scale. Just Vantage (5 tiers) + optional High Stakes flag.

---

### Current: gm-cheat-sheet.md
**Migrate to:**
- Part 3: gm-cheat-sheet.md (with gaps filled)

**Gaps to Fill:**
- Ensure all mechanics have entries
- Verify Consequence Selection Matrix is complete
- Add any missing quick-reference tables

---

### Current: appendix-a-design-notes.md
**Migrate to:**
- Part 5: appendix-a-design-notes.md (collect Design Notes from all chapters)

---

### Current: appendix-b-examples.md
**Migrate to:**
- Part 5: appendix-b-examples.md (consolidate ALL examples)

**Examples to Add:**
- Extended examples from all chapters
- Core resolution (full sequence)
- Combat (from Ch 8)
- Investigation scene (NEW)
- Social conflict (from Ch 7/Ch 14)
- Spellcasting (from Ch 10)
- Ritual (from Ch 10)

---

### Current: appendix-c-challenge-quick-reference.md
**Migrate to:**
- Part 5: appendix-c-challenge-builder.md (expand with templates)

---

## New Content to Write

### Part 0
1. **welcome.md** - Half page orientation (what kind of game, who it's for, what's distinctive)
2. **core-loop.md** - Two pages with six-step sequence + one worked example

### Part 1
1. **05-momentum.md** - NEW chapter consolidating scattered Momentum content
   - What Momentum represents
   - How to earn (Triumph, Build Momentum, Tangles)
   - The cap (2, raised to 3 by Talent)
   - Create an Opening (canonical definition)
   - Resist Consequence (cross-reference)
   - Tangles (defined here as optional)

### Part 5
1. **appendix-d-character-sheet.md** - Blank character sheet

---

## Migration Phases

### Phase 1: Foundation (Part 0 + Placeholders)
**Goal:** Create Part 0 and all placeholder files

**Tasks:**
1. Write welcome.md
2. Write core-loop.md
3. Create all chapter placeholder files with frontmatter
4. Set up cross-reference structure

**Estimated Time:** 2-3 hours

---

### Phase 2: Core Rules (Part 1)
**Goal:** Migrate and consolidate Part 1 (6 chapters)

**Priority Order:**
1. Chapter 1: Rolling Dice (foundation)
2. Chapter 5: Momentum (NEW, consolidates scattered content)
3. Chapter 2: Taking Action (builds on Ch 1)
4. Chapter 3: Consequences (builds on Ch 2)
5. Chapter 4: Resilience (standalone)
6. Chapter 6: Traits (standalone)

**Estimated Time:** 6-8 hours

---

### Phase 3: Character Content (Part 2)
**Goal:** Migrate Part 2 (4 chapters)

**Priority Order:**
1. Chapter 7: Character Creation (simplify to decision points)
2. Chapter 8: Advancement (extract from 03-characters.md)
3. Chapter 9: Callings (copy with fixes)
4. Chapter 10: Spellcasting (copy with cleanup)

**Estimated Time:** 3-4 hours

---

### Phase 4: Reference Layer (Part 3)
**Goal:** Create definitive at-table references

**Tasks:**
1. vantage-reference.md (copy from vantage.md, verify 5-tier)
2. stakes-reference.md (copy from stakes.md with fixes)
3. gm-cheat-sheet.md (copy with gaps filled)

**Estimated Time:** 1-2 hours

---

### Phase 5: GM Content (Part 4)
**Goal:** Migrate Part 4 (6 chapters)

**Priority Order:**
1. Chapter 11: GM Principles (extract technique from 07-gm-guide.md)
2. Chapter 12: GM Moves (extract from 07-gm-guide.md)
3. Chapter 13: Challenges (consolidate from 06-challenges.md + Boss Design)
4. Chapter 14: Running Scenes (extract from 07-gm-guide.md, add Social Conflict)
5. Chapter 15: Combat (copy from 08-combat.md with fixes)
6. Chapter 16: Advancement GM (extract from 03-characters.md + 07-gm-guide.md)

**Estimated Time:** 6-8 hours

---

### Phase 6: Appendices & Polish (Part 5)
**Goal:** Complete appendices and test reading paths

**Tasks:**
1. Consolidate Design Notes
2. Collect all examples into Appendix B
3. Build Quick Challenge Builder
4. Create character sheet
5. Cross-reference audit
6. Fresh reader testing

**Estimated Time:** 4-6 hours

---

## Total Estimated Time
**22-31 hours** spread across multiple sessions

---

## Success Criteria

### Structural
- [ ] Every mechanic has exactly one canonical home
- [ ] All cross-references are accurate and complete
- [ ] No duplicate rules text (only cross-references)
- [ ] Clear reading paths for players vs GMs
- [ ] Reference layer is scannable and definitive

### Content
- [ ] Part 0 Core Loop example is truly minimal
- [ ] Part 1 teaches the system progressively
- [ ] Part 2 guides character creation without mechanical detail
- [ ] Part 3 is usable mid-session
- [ ] Part 4 contains pure GM technique + tools

### Testing
- [ ] New player can read Part 0 + 1 + 2 and create character
- [ ] New GM can read everything and run first session
- [ ] Experienced player can find answers mid-session in Part 3
- [ ] GM can find scene/challenge tools in Part 4 without hunting

---

## Migration Strategy: Preserve Originals

**IMPORTANT:** Original files remain untouched during migration.

- All current documents stay in `/heroic-fantasy-rpg/` root directory
- New reorganized content goes in `/heroic-fantasy-rpg/reorganized/`
- Original files serve as reference to ensure complete content transfer
- Archive originals only AFTER verifying reorganized content is complete

### Migration Workflow

For each new chapter:
1. **Create** new file in appropriate `/reorganized/part-X/` folder
2. **Read** relevant source files from root directory
3. **Extract** content that belongs in this chapter
4. **Write** to new chapter file (with cross-references)
5. **Check** against source to verify nothing missed
6. **Mark** migration task as complete in this document
7. **Leave** original files untouched

### Verification Process

Before archiving originals:
1. Full content audit (all mechanics transferred)
2. Cross-reference completeness check
3. Fresh reader testing of new structure
4. Side-by-side comparison of old vs new for edge cases

## Risk Mitigation

### Content Loss
- Original files preserved untouched during migration
- Use git to track all changes in reorganized folder
- Review each migrated chapter against source files
- Checklist for each chapter: "All content from source accounted for?"

### Cross-Reference Maintenance
- Create master list of mechanics and their homes
- Use consistent cross-reference format: "See Chapter X: Title"
- Add cross-reference comments in source files

### Scope Creep
- Resist urge to rewrite during migration
- Focus on structure first, polish later
- Mark "NEEDS REWRITE" sections for Phase 6

### Testing Gaps
- Identify fresh readers early
- Prepare testing guide for readers
- Schedule testing time in Phase 6

