# TODO & Future Work

## High Priority

### Example Accuracy Audit
**Estimated Effort:** Medium

Review all examples for mechanical accuracy following September 2026 simplification (removed Assist, baseline Push Yourself, Resist Consequence).

**Status:** Phase 1 & 2 complete ✅

**Phase 1 Complete (Critical fixes):**
- ✅ Quick Start Guide — Fixed Battleborn talent, Stress Track description, and "Use Stress to" section
- ✅ Chapter 12 — Fixed "Enemy's turn in combat" to clarify enemies act through Consequences or by spending Suspense

**Phase 2 Complete (Core Rules review):**
- ✅ Chapters 1-2 — All inline examples verified correct
- ✅ Chapter 4 (Resilience) — Push Yourself correctly defined as formal game term, limited to once per action roll
- ✅ Chapter 6 (Traits) — All Special Effect examples verified correct
- ✅ Talents Draft — Terminology verified correct (uses "Push Yourself" as formal game term)

**Phase 3 Next (Later Chapters):**
- Part 2 (Ch. 7-10) review (some already updated in September)
- Part 3 (Ch. 13-15) review for GM-facing examples
- Part 4 (Reference) review

**Full audit:** See `design-docs/example-accuracy-audit.md`

---

### Session in Play (Extended Example)
**Estimated Effort:** Large

Create a comprehensive example showing how different scene types flow together in actual gameplay. Demonstrates the system in action for new GMs and players transitioning from other systems.

**Scene Types to Include:**
1. **Exploration** — Navigating dangerous terrain, discovering clues, overcoming environmental obstacles
2. **Social Conflict** — Negotiating with NPCs, Will Tracks, Talk vs Clash distinction
3. **Investigation** — Using Sense and Know to solve mysteries
4. **Combat** — Full tactical encounter with Complications, Challenge Moves, zones, movement
5. **Downtime** — Short/Long Rests, recovering Stress/Conditions

**Key Elements to Showcase:**
- GM telegraphing Vantage and Stakes before rolls
- When to call for rolls vs. when to just narrate
- How Momentum flows between scenes
- How Stress/Conditions carry forward
- Scene transitions and pacing
- Player agency and creative problem-solving

**Location:** Part 4 (Reference) or Appendix

---

### Part 4: Reference Materials
**Estimated Effort:** Large

Build out the reference section for mid-session lookup:
- GM Cheat Sheet (action resolution flow, Consequence calibration, Suspense moves)
- Player Quick Reference (Action Roll steps, Special Effects, Momentum spends — must include the 2d-take-lowest rule for 0-or-negative pools, which is rare enough that tables re-look it up every time)
- Challenge Quick Reference (Track Sizes, Complication Tags, Challenge Moves)
- Condition Reference (all standard Conditions with effects and tick-down rules)
- Sage Theorem Table (7 Spheres × 9 Operations grid, sparsely filled with the ~30 named example theorems — fast scanning aid for theorem selection and Arcane Formula improvisation)

---

## Medium Priority

### Investigation Challenge Example
**Estimated Effort:** Small

Mostly covered by the Corrupt Magistrate example (Ch. 13) — social boss with nested Obstacle track and Countdown. Remaining gap: a pure investigation set-piece (Sense/Know clue-gathering as the primary track). Low priority now; consider for Part 5 extended examples instead.

---

### Scene-Long Debuff Counter-Play
**Estimated Effort:** Small

Add GM guidance for handling scene-long debuffs against boss enemies to prevent "land one debuff, coast to victory."

**Suggested approaches:**
- Boss spends turn dramatically breaking the effect (costs Suspense)
- Impact Move: "Dragon's rage burns through your curse" (remove debuff + create danger)
- Multi-Phase: each phase sheds active debuffs
- Weaken from scene-long to "2 relevant Action Rolls remaining"

**Location:** Ch. 13 (Challenge design) or Ch. 15 (boss encounters)

---

### Default to Stress
**Estimated Effort:** Small

Add a one-liner to Consequence calibration guidance: when in doubt about what Consequence to impose, default to Stress. It's the simplest, most reversible option and keeps play moving.

**Location:** Ch. 12 (GM Moves, Consequence Severity section)

---

### Talent Completion
**Estimated Effort:** Medium

Finalize talents-draft.md:
- Review new Talents (Risk/Reward, Defensive, Tactical, Mobility, Knowledge, Social, Offensive)
- Assign to Callings and integrate into Ch. 9
- Ensure mobility Talents (Charge, Skirmisher, Fleet of Foot, Juggernaut) interact cleanly with movement rules

---

## Low Priority / Polish

### Consider Renaming "Complication" (Backburner)
The Three C's (Complication/Consequence/Condition) share a phonetic shape and collide at the table. Complication is the best rename target — it's our most idiosyncratic usage (most games use "complication" for narrative fallout, forcing constant capitalization-policing) and only touches stat blocks. Requirement: the new word must work for enemies, obstacles, AND environments (not "Defense"). Best candidate so far: **Hindrance** ("each Hindrance reduces your outcome by 1 tier"; "the vault door's Complex Hindrance"). Runner-up: Hurdle. Decide before any published material exists — this is the last cheap window.

### Index / Glossary
Convert KEYWORDS.md into a proper glossary appendix with brief definitions for each term.

### Appendix: Design Notes
Consolidate design rationale into an optional appendix for interested readers.

---

## Completed

### September 2026
- **Core Simplification** — Removed baseline Push Yourself and Resist Consequence. Push Yourself now Talent-only activation (formal game term, once per action roll). Assist removed, Create an Opening works for self or allies.
- **Assist Reintroduction (Sept 14)** — Reintroduced Assist as subsection of Create an Opening with constraints: fictional positioning required + shared risk (helper faces same consequence). Differentiates safe self-buff from committed ally support.
- **Defy Expansion (Sept 14)** — Expanded Defy section in Ch. 2 with detailed explanations of all intent effects (Mark Obstacle, Seize Control, Take Something, Create Advantage, Change Environment, Resist/Endure). Added full support toolkit overview in Ch. 5. Moved Teamwork section from Ch. 4 to Ch. 5.
- **Buff Tracks Formalization (Sept 15)** — Formalized Buff mechanic as Character Tracks (parallel to Afflictions). Buffs grant +1 Boon OR fictional positioning, tick down through use (Buff 2 default, Buff 3 with Greater Effect). Resolves duration vagueness and improves tracking clarity. Environmental advantages remain narrative. Clarified Affliction asymmetry: PCs get -1 Bane, enemies grant +1 Boon to attackers.
- **Potent Actions & Trait Merge (Sept 15)** — Simplified Potent Actions by merging with Trait system. Potent now grants free Trait Effect (Enhanced/Additional/Build Momentum) without needing relevant Trait. If Trait also applies, pick two different effects. Dropped Edge+1 (use Momentum for that). Renamed Greater→Enhanced, Secondary→Additional for clarity. See design-docs/potent-actions-trait-merge.md.
- **Track System Unification** — Unified all six track types (Progress, Countdown, Stress, Affliction, Burden, Buff) under one concept with 4 parameters. Renamed Condition → Affliction.
- **Momentum Economy** — Added session reset (start each session at full Momentum). Cap remains at 2 (or 3 with Talent). Analysis showed Build Momentum creates self-sustaining economy without need for cap increase.
- **Potent Actions Consolidation** — Ch. 2 remains canonical home with full explanation. Ch. 9 already condensed (brief pointer + design note). Ch. 10 condensed further (removed repeated scale dimensions explanation, kept magic-specific examples table).
- **Example Accuracy Audit** — Phase 1 & 2 complete. Fixed Quick Start Guide and Ch. 12. Verified core rules chapters accurate.

### July 2026
- **Keyword Capitalization Audit** — Consistent capitalization of Action Roll, Consequence, Track, etc. across all chapters. Updated KEYWORDS.md glossary.
- **Movement Rules Revision** — Movement table, Vantage-based cost for Near+acting, Difficult Terrain, hazard movement, mobility Talents
- **Cross-Manuscript Consistency Review** — Fixed rules drift, terminology (Enhanced Effect, Vantage for positioning, Cinematic Actions, Persistent Burden), reduced repetition, corrected cross-references
- **Rank → Scale Rename** — Full rename across manuscript, removed CR
- **Linked Challenges** — Added pattern to Ch. 13

### June 2026
- **Book Reorganization** — Full restructure into 5 Parts (Before You Play / The Rules / Your Character / Running the Game / Reference)
- **Quick Start Guide** — Complete 8-page quick-start for new players and GMs
- **Vantage 5-Tier System** — Certain/Strong/Standard/Limited/Impossible
- **Potency Framework** — Unified Potent Spells with general Potency
- **Suspense Economy** — Redesigned GM resource (earn by giving, spend for moves)
- **Enhanced Effect** — Parent category with Greater Effect and Broad Effect sub-options
- **Secondary Effect** — Free Defy action on Trait invocation
- **Spotlight Management** — Ch. 12 with full guidance
- **Chapter 10 Spellcasting** — Comprehensive revision and cleanup
