# Reorganization Project Status

**Started:** 2026-06-29  
**Target Completion:** TBD  
**Status:** Planning Complete → Ready for Implementation

---

## Project Overview

**Goal:** Reorganize the entire rulebook by reader need and moment of use, eliminating rules drift and creating clear reading paths.

**Strategy:** Preserve all original files during migration. New content goes in `/reorganized/`. Archive originals only after verification.

**Estimated Effort:** 22-31 hours across multiple sessions

---

## Deliverables

### Primary Deliverables
- [ ] **Quick Start Guide** (10 pages, standalone PDF)
- [ ] **Part 0: Before You Play** (Welcome + Core Loop)
- [ ] **Part 1: The Rules** (6 chapters)
- [ ] **Part 2: Your Character** (4 chapters)
- [ ] **Part 3: Reference** (3 documents)
- [ ] **Part 4: Running the Game** (6 chapters)
- [ ] **Part 5: Appendices** (4 appendices)

### Supporting Deliverables
- [x] Reorganization proposal (REORGANIZATION-PROPOSAL.md)
- [x] Migration plan (MIGRATION-PLAN.md)
- [x] Ironsworn comparison (IRONSWORN-COMPARISON.md)
- [x] Quick Start outline (QUICKSTART-OUTLINE.md)
- [x] Project tracking (this document)

---

## Progress Tracking

### Phase 0: Planning ✅ COMPLETE
- [x] Review reorganization proposal
- [x] Analyze Ironsworn layout
- [x] Create folder structure
- [x] Write migration plan
- [x] Outline Quick Start Guide
- [x] Define project scope

**Completed:** 2026-06-29

---

### Phase 1: Quick Start Guide (3-4 hours)
**Status:** ✅ DRAFT COMPLETE (2026-06-29)
**Priority:** High (standalone deliverable)

- [x] Write page 1 (What Is This Game?)
- [x] Write pages 2-3 (Core Loop with example)
- [x] Write page 4 (Character Creation)
- [x] Write page 5 (How to Roll Dice)
- [x] Write page 6 (The Five Actions)
- [x] Write page 7 (Consequences and Resilience)
- [x] Write page 8 (Momentum and Traits)
- [x] Write page 9 (For the GM)
- [x] Write page 10 (What's Next)
- [ ] Create visual designs (dice pools, flowcharts)
- [ ] Test with new players
- [ ] Iterate based on feedback
- [ ] Finalize as PDF

**Status:** Content complete, needs visual design and playtesting

**Dependencies:** None (can be done in parallel with other work)

---

### Phase 2: Part 0 - Before You Play (1-2 hours)
**Status:** ✅ COMPLETE (2026-06-29)
**Priority:** High (required for reading flow)

#### 01-welcome.md
- [x] Half-page orientation (what kind of game, who it's for, what's distinctive)
- [x] No rules, pure orientation
- [x] What You Need section
- [x] How to Use This Book section
- [x] "What Does Play Feel Like?" section

#### 02-core-loop.md
- [x] Six-step sequence
- [x] Complete worked example (Shadow crossing courtyard)
- [x] Shows shape of how a session works
- [x] Minimal mechanical detail (just the loop)
- [x] Key principles illustrated
- [x] Variations on the loop

**Status:** Both documents complete and ready for Part 1

**Dependencies:** Can reference Quick Start for consistency

---

### Phase 3: Part 1 - The Rules (6-8 hours)
**Status:** Not Started  
**Priority:** High (core content)

#### 01-the-action-roll.md
- [x] What an Action Roll is and when to make one
- [x] Building dice pool (Approach + Boons - Banes)
- [x] Four outcomes (Triumph/Success/Conflict/Setback)
- [x] Boon and Bane sources and ±2d cap
- [x] Edge definition and usage
- [x] Expertise definition (Setback → Conflict)
- [x] Pool minimum (0d = 2d take lowest)
- [x] Complete Action Roll sequence
- [x] Probability tables

**Source files:** 02-core-mechanics.md, 04-action-resolution.md

**Status:** ✅ Complete (2026-06-29)

#### 02-taking-action.md
- [ ] Five Actions with Primary Effects
- [ ] Five Approaches
- [ ] How Actions and Approaches combine
- [ ] Vantage (brief, cross-ref to Part 3)
- [ ] Stakes (brief, cross-ref to Part 3)
- [ ] When to roll vs when to say yes
- [ ] Complete resolution sequence

**Source files:** 02-core-mechanics.md, 04-action-resolution.md, vantage.md

#### 03-consequences.md
- [ ] Consequence tiers (Minor/Major/Severe/Disaster)
- [ ] How Complications reduce outcomes
- [ ] How Stakes modify consequence tiers
- [ ] Five specific Action outcomes
- [ ] Progress tracks (Harm, Will, Obstacle, Countdown)
- [ ] Enemy actions and Impact Moves
- [ ] Resist Consequence (canonical definition)

**Source files:** 04-action-resolution.md, 05-resilience.md

#### 04-resilience.md
- [ ] Stress track (5 boxes)
- [ ] Conditions (naming, tiers, Bane, clearing)
- [ ] Burdens (difference from Conditions, recovery)
- [ ] Stress Overflow (Burden or Taken Out choice)
- [ ] Taken Out (what it means, recovery)
- [ ] **Push Yourself** (canonical definition)
- [ ] **Assist** (canonical definition)
- [ ] Short Rest and Long Rest

**Source files:** 05-resilience.md + ADD Push Yourself and Assist

#### 05-momentum.md (NEW CHAPTER)
- [ ] What Momentum represents
- [ ] How to earn (Triumph, Build Momentum, Tangles)
- [ ] The cap (2, raised to 3 by Talent)
- [ ] Create an Opening (canonical definition)
- [ ] Resist Consequence (cross-reference to Ch 3)
- [ ] Tangles (defined as optional)

**Source files:** 02-core-mechanics.md, 04-action-resolution.md (scattered references)

#### 06-traits.md
- [ ] What Traits are and what they do
- [ ] Three Trait types (Origin, Profession, Personal)
- [ ] When to invoke (Conflict or better, narratively relevant)
- [ ] Three Special Effects (Greater Effect, Secondary Effect, Build Momentum)
- [ ] Secondary Effect framework (Defy variations)
- [ ] Trait breadth guidance
- [ ] One Trait per roll rule

**Source files:** 02-core-mechanics.md, 03-characters.md

**Dependencies:** Chapters build on each other (do in sequence 1→6)

---

### Phase 4: Part 2 - Your Character (3-4 hours)
**Status:** Not Started  
**Priority:** Medium (players need after Part 1)

#### 07-character-creation.md
- [ ] Choose Approaches (3/2/1/1/0)
- [ ] Write three Traits
- [ ] Choose Calling
- [ ] Choose 2 additional Talents
- [ ] Record starting stats

**Source files:** 03-characters.md

#### 08-advancement.md
- [ ] Advancement table (levels 1-10)
- [ ] Approach increases and caps
- [ ] Talent acquisition
- [ ] Rank thresholds (1-4)
- [ ] Four Ranks with descriptions
- [ ] Talent retraining
- [ ] Cross-Calling Talents
- [ ] Re-Skinning Talents

**Source files:** 03-characters.md

#### 09-callings.md
- [ ] Copy from current 09-callings.md
- [ ] Fix typos
- [ ] Add Push Yourself cross-references
- [ ] Add Champion Talent differentiators
- [ ] Verify all Talents present

**Source files:** 09-callings.md

#### 10-spellcasting.md
- [ ] Copy from current 10-spellcasting.md
- [ ] Cut Summary section
- [ ] Cut duplicate Potent examples
- [ ] Verify rules drift fixes applied
- [ ] Ensure all magic systems covered

**Source files:** 10-spellcasting.md

**Dependencies:** Part 1 complete (cross-references)

---

### Phase 5: Part 3 - Reference (1-2 hours)
**Status:** Not Started  
**Priority:** Medium (at-table tools)

#### vantage-reference.md
- [ ] Copy from vantage.md (complete document)
- [ ] Verify 5-tier system (Certain/Strong/Standard/Limited/Impossible)
- [ ] Include High Stakes section (optional climactic flag)
- [ ] Complete framework with examples
- [ ] Decision process for GMs
- [ ] Vantage and Expertise interaction
- [ ] Vantage and Conditions interaction
- [ ] Common pitfalls

**Source files:** vantage.md

**Note:** Stakes system simplified—no separate stakes-reference.md. High Stakes now integrated into Vantage framework.

#### gm-cheat-sheet.md
- [ ] Copy from gm-cheat-sheet.md
- [ ] Fill all gaps
- [ ] Verify completeness
- [ ] Add visual elements if needed
- [ ] Ensure all mechanics referenced

**Source files:** gm-cheat-sheet.md

**Dependencies:** Part 1 complete (references core rules)

---

### Phase 6: Part 4 - Running the Game (6-8 hours)
**Status:** Not Started  
**Priority:** Medium (GM-only content)

#### 11-gm-principles.md
- [ ] GM Agendas (three)
- [ ] GM Principles (technique only)
- [ ] When to roll vs say yes
- [ ] Action Scope
- [ ] Spotlight management
- [ ] Failure is not a wall
- [ ] Session structure
- [ ] Final Advice
- [ ] NO rules restatement

**Source files:** 07-gm-guide.md (extract technique, remove rules)

#### 12-gm-moves.md
- [ ] Story Moves
- [ ] Suspense Moves
- [ ] Impact Moves
- [ ] When to use each (Decision Matrix)
- [ ] Hint → Reveal → Strike
- [ ] Common mistakes

**Source files:** 07-gm-guide.md

#### 13-challenges.md
- [ ] What Challenges are
- [ ] Rank vs CR
- [ ] Complication tags (all eight)
- [ ] Bypassing and removing Complications
- [ ] Progress tracks design guidance
- [ ] Challenge Moves
- [ ] Group Challenges
- [ ] Challenge Design Matrix
- [ ] Worked examples (consolidated)
- [ ] Boss Design (from 07-gm-guide.md)
- [ ] Quick Challenge template

**Source files:** 06-challenges.md, 07-gm-guide.md (Boss Design)

#### 14-running-scenes.md
- [ ] Investigation framework
- [ ] **Social Conflict** (canonical home)
- [ ] Consequence Calibration Guide
- [ ] Battlegrounds (Features and Threats)
- [ ] Clocks and Tracks
- [ ] Tangles (GM guidance)
- [ ] Complex Scene Structure

**Source files:** 07-gm-guide.md

#### 15-combat.md
- [ ] Turn structure (spotlight rotation)
- [ ] Zones and Positioning
- [ ] Combat Maneuvers
- [ ] Helping Allies (as core, not optional)
- [ ] Define Seize Spotlight
- [ ] Threat Pool (optional)
- [ ] Epic Foe Abilities (optional)
- [ ] Extended Combat Example (fix Momentum accounting)

**Source files:** 08-combat.md

#### 16-advancement-gm.md
- [ ] When to Award Levels
- [ ] Suggested pacing by campaign length
- [ ] Rank transition guidance
- [ ] Managing power curve

**Source files:** 03-characters.md, 07-gm-guide.md

**Dependencies:** Parts 1-3 complete (heavy cross-referencing)

---

### Phase 7: Part 5 - Appendices (4-6 hours)
**Status:** Not Started  
**Priority:** Low (supplementary content)

#### appendix-a-design-notes.md
- [ ] Copy from appendix-a-design-notes.md
- [ ] Collect Design Notes from all chapters
- [ ] Organize by topic
- [ ] Add inspirations and acknowledgments

**Source files:** appendix-a-design-notes.md + scattered Design Notes sections

#### appendix-b-examples.md
- [ ] Core resolution (full sequence)
- [ ] Combat (from Chapter 8)
- [ ] Investigation scene (NEW)
- [ ] Social conflict (from Chapter 7/14)
- [ ] Spellcasting (from Chapter 10)
- [ ] Ritual (from Chapter 10)
- [ ] Consolidate all scattered examples

**Source files:** All chapters (extract examples)

#### appendix-c-challenge-builder.md
- [ ] Copy from appendix-c-challenge-quick-reference.md
- [ ] One-page format
- [ ] Pick CR → Rank → Complications → Moves
- [ ] Common Challenge templates

**Source files:** appendix-c-challenge-quick-reference.md

#### appendix-d-character-sheet.md
- [ ] Blank character sheet
- [ ] Optional: fillable PDF version

**Source files:** NEW (create from current sheet)

**Dependencies:** All other content complete (examples from everywhere)

---

### Phase 8: Polish & Verification (4-6 hours)
**Status:** Not Started  
**Priority:** High (quality assurance)

#### Cross-Reference Audit
- [ ] Verify all cross-references are accurate
- [ ] Check chapter numbers in links
- [ ] Ensure consistent cross-reference format
- [ ] Test that all references point to existing content

#### Content Completeness
- [ ] Compare each new chapter to source files
- [ ] Verify no mechanics lost
- [ ] Check all edge cases transferred
- [ ] Ensure Design Notes captured

#### Reading Path Testing
- [ ] Test: New player can create character from Parts 0-2
- [ ] Test: New GM can run first session from Parts 0-1 + Ch 11
- [ ] Test: Mid-session lookup works in Part 3
- [ ] Test: GM scene tools accessible in Part 4

#### Visual Design
- [ ] Add flowcharts to Part 3
- [ ] Add diagrams where helpful
- [ ] Ensure consistent formatting
- [ ] Create any missing visual aids

#### Fresh Reader Testing
- [ ] Recruit 2-3 new players
- [ ] Have them read Quick Start + create character
- [ ] Observe pain points and confusion
- [ ] Iterate based on feedback

**Dependencies:** All content complete

---

## Current Status: PLANNING COMPLETE ✅

### Completed Work
- Reorganization proposal reviewed and refined
- Ironsworn comparison completed
- Migration plan documented
- Quick Start outlined
- Folder structure created
- Preservation strategy defined

### Ready to Begin
**Next immediate task:** Choose between:
1. Start with Quick Start Guide (standalone, high value)
2. Start with Part 0 (foundational for main book)
3. Start with Part 1, Chapter 1 (proof of concept for migration)

**Recommendation:** Start with **Quick Start Guide** because:
- Standalone deliverable (immediate value)
- Tests the "overview approach" before diving into detail
- Can be used for playtesting while main book is in progress
- Informs Part 0 content (overlap in purpose)

---

## Risk Register

### High Risk
- **Content loss during migration** → Mitigated by preserving originals
- **Cross-reference errors** → Mitigated by audit phase
- **Scope creep** → Mitigated by strict phase boundaries

### Medium Risk
- **Migration timeline longer than estimated** → Acceptable, quality over speed
- **Structure doesn't work for readers** → Mitigated by fresh reader testing

### Low Risk
- **Original files need updates during migration** → Make in both places
- **Discover missing mechanics** → Capture in reorganized version

---

## Success Metrics

### Structural Success
- ✅ Every mechanic has exactly one canonical home
- ✅ No duplicate rules text (only cross-references)
- ✅ Clear reading paths for players vs GMs
- ✅ Reference layer is scannable and definitive

### User Success
- ✅ New player can create character in 20 minutes
- ✅ New GM can run first session after reading Quick Start + Part 1
- ✅ Mid-session lookup takes < 30 seconds (Part 3)
- ✅ No rules contradictions between chapters

### Quality Success
- ✅ All edge cases preserved from originals
- ✅ Fresh readers understand without prior RPG knowledge
- ✅ Visual design aids comprehension
- ✅ Cross-references are accurate and complete

---

## Notes & Decisions

### 2026-06-29
- Decided to preserve original files during migration
- Quick Start Guide will be 10 pages (Ironsworn-inspired)
- Part 1 will have 6 chapters (added Momentum chapter)
- Reference layer (Part 3) separated from teaching layer (Part 1)
- Examples consolidated to Appendix B

### Open Questions
1. Should Momentum move to Chapter 4 instead of 5? (before Resilience)
2. Should Vantage/Stakes be combined into one reference doc?
3. Should Part 3 include quick-reference tables extracted from Part 1?
4. When to archive original files? (After Phase 8 verification)

---

## Timeline Estimate

**Total Estimated Hours:** 22-31 hours

**Breakdown:**
- Phase 1 (Quick Start): 3-4 hours
- Phase 2 (Part 0): 1-2 hours
- Phase 3 (Part 1): 6-8 hours
- Phase 4 (Part 2): 3-4 hours
- Phase 5 (Part 3): 1-2 hours
- Phase 6 (Part 4): 6-8 hours
- Phase 7 (Part 5): 4-6 hours
- Phase 8 (Polish): 4-6 hours

**Working at 2 hours/session:** 11-15 sessions  
**Working at 4 hours/session:** 6-8 sessions

**Realistic Completion:** 2-4 weeks at steady pace

