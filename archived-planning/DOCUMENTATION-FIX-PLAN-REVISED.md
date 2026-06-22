# Documentation Fix Plan - Heroic Fantasy RPG (REVISED)

**Generated:** 2026-06-20  
**Review Status:** 16 files reviewed, issues re-evaluated based on design clarifications  
**Estimated Effort:** 15-20 hours total

---

## Executive Summary

The comprehensive review identified **clarity and consistency issues** rather than fundamental system errors. The core mechanics are sound, but documentation needs:

1. **Clarification sections** for intentional design choices (Action vs Effect, Tier vs Rank)
2. **Actual fixes** for genuine errors (invalid Approach reference, undefined magical schools)
3. **Consistency improvements** (add missing mechanics to overviews, eliminate redundancy)
4. **Structural polish** (reorganize scattered content, standardize formatting)

**Key Insight:** Many "errors" identified in initial review were actually correct design that needs better explanation, not fixing.

---

## Clarifications from Designer

### What's Actually Correct (Not Errors):

✅ **Action Names:** Defy, Clash, Talk, Sense, Know are the correct Action names  
✅ **Primary Effects:** Overcome, Harm, Influence, Assess, Recall are mechanical outcomes  
✅ **Tier vs Rank:** Intentionally distinct concepts that don't map 1:1  
✅ **Disaster:** Confirmed edge case (Setback reduced further by Complications)  
✅ **Callings:** Vanguard and Hunter are valid; Wanderer is on hold

### What Needs Actual Fixing:

❌ **Invalid "Wits" Approach** in spellcasting chapter  
❌ **Missing Expertise** in overview files  
❌ **Missing Complication tags** in overview files  
❌ **Undefined magical schools** (Biomancy, Wardcraft, Shadowmancy)  
❌ **Extensive redundancy** (duplicate content across chapters)  
❌ **Unclear context** for key mechanics

---

## Phase 1: Add Critical Clarifications (Week 1)
**Goal:** Explain intentional design choices to prevent confusion  
**Estimated Time:** 3-4 hours  
**Files Affected:** 4 files

### 1.1 Add "Action vs Effect" Clarification

**Problem:** Players and reviewers confused by two names for each action (Defy vs Overcome, etc.)

**Root Cause:** The distinction between **Action** (player-facing verb) and **Primary Effect** (mechanical outcome) serves a design purpose but isn't explained.

**Add to Chapter 1 (01-introduction.md) after line 32:**

```markdown
---

### Understanding Actions and Effects

Each of the 5 Actions has two names:

**Action Name** (what you say at the table):
- "I **Defy** the dragon's flames"
- "I **Clash** with the knight"
- "I **Talk** to the guard"

**Primary Effect** (mechanical result in the rules):
- Defy → **Overcome** (mark Progress track)
- Clash → **Harm** (mark Harm/Will track)
- Talk → **Influence** (mark Will track)
- Sense → **Assess** (ask questions)
- Know → **Recall** (GM tells you + clarifying question)

**Why both names?** Action names are evocative player verbs. Primary Effects describe what mechanically happens when you succeed. Use Action names during play; Primary Effects are reference terms in the rules.

**Example:**
> **Player:** "I Clash with the troll!"
> **GM:** "Roll Clash + Daring."
> **[Player rolls Conflict]**
> **GM:** "You succeed—the Clash's Primary Effect is Harm, so mark 1 tick on the troll's Harm track. But you also take a Minor Consequence..."

Throughout this rulebook, you'll see both terms. Just remember: **Actions are what you do, Effects are what happens.**

---
```

**Add to Chapter 2 (02-core-mechanics.md) before line 29:**

```markdown
## Actions and Effects

When you take an action, you name the **Action** (Defy, Clash, Talk, Sense, Know). Each Action has a **Primary Effect**—the mechanical outcome when you succeed:

| Action | Primary Effect | What It Does |
|--------|----------------|--------------|
| **Defy** | Overcome | Mark Obstacle track OR automatically overcome simple barriers |
| **Clash** | Harm | Mark Harm or Will track OR defeat weaker foes outright |
| **Talk** | Influence | Mark Will track OR convince lesser NPCs automatically |
| **Sense** | Assess | Ask 2 questions (1 on Conflict) |
| **Know** | Recall | GM tells you something + you ask 1 clarifying question |

**Use Action names at the table** ("I Defy the trap", "I Sense for ambushes"). Primary Effects appear in the rules to describe what mechanically happens.

---
```

**Action Items:**
- [ ] Add "Understanding Actions and Effects" to 01-introduction.md (after line 32)
- [ ] Add Actions and Effects table to 02-core-mechanics.md (before line 29)
- [ ] Add brief note to README.md overview (line 15): "(Actions have Primary Effects—see Chapter 1)"

---

### 1.2 Add "Tier vs Rank" Clarification

**Problem:** Tier (Challenge difficulty) and Rank (PC narrative genre) appear to conflict, but they're intentionally different scales.

**Root Cause:** The distinction serves important design goals (Tier 4 Goblin King for Rank 1 heroes, Tier 1 minions for Rank 3 heroes) but isn't explained.

**Add to Chapter 6 (06-challenges.md) after line 23:**

```markdown
---

## Tier vs Rank: Two Different Scales

**Tier** and **Rank** measure different things and **don't map 1:1 by design**.

### Tier (Challenge Difficulty)

**Tier measures how mechanically difficult** a Challenge is to overcome:
- **Tier 0:** Trivial threats (untrained bandits, giant rats)
- **Tier 1:** Competent opposition (veteran soldiers, dire wolves)
- **Tier 2:** Formidable foes (elite knights, young dragons)
- **Tier 3:** Legendary threats (ancient dragons, master assassins)
- **Tier 4+:** World-ending entities (demon lords, gods, primordial forces)

Tier determines:
- How many Complications the Challenge has (0-3+)
- How long Progress tracks are (2-10+ ticks)
- How much HP/resistance it has

### Rank (PC Narrative Genre)

**Rank measures what genre of fantasy** the PCs are experiencing:
- **Rank 1 (Local Heroes):** Grounded fantasy, realistic struggle
- **Rank 2 (Seasoned Adventurers):** Heroic fantasy, peak mortals
- **Rank 3 (Regional Legends):** Mythic fantasy, superhuman feats
- **Rank 4 (Mythic Heroes):** Demigod fantasy, world-shaping

Rank determines:
- What scale of actions you can attempt (narrative permission)
- What genre tone the campaign operates in
- What kinds of stories make sense

### Why They Don't Match

**Tier and Rank serve different purposes and intentionally don't correspond 1:1.**

**Example: Tier 4, Rank 1 (The Goblin King)**
- **Tier 4:** Mechanically tough boss fight (long Harm track, 3 Complications, hits hard)
- **Rank 1:** For starting heroes in grounded fantasy
- **Result:** Climactic campaign finale where scrappy local heroes face their greatest threat

**Example: Tier 1, Rank 3 (Demon Spawn Minions)**
- **Tier 1:** Mechanically easy (short track, 0-1 Complications)
- **Rank 3:** Legendary heroes cutting through hordes
- **Result:** Regional legends mowing down demon army minions (narratively impressive, mechanically trivial)

### Designing Challenges

**Don't match Tier to Rank.** Instead:

1. **Pick Tier based on desired difficulty:**
   - Easy fight? → Tier 0-1
   - Balanced encounter? → Tier 2
   - Boss fight? → Tier 3-4+

2. **Use Rank for narrative scope:**
   - Rank 1: Village-scale threats (bandits, local monsters)
   - Rank 2: City-scale threats (conspiracies, regional beasts)
   - Rank 3: Nation-scale threats (armies, legendary monsters)
   - Rank 4: World-scale threats (apocalyptic forces)

**A Rank 4 party can face:**
- Tier 0-1 minions (mowing through armies)
- Tier 2 elites (worthy opponents)
- Tier 3-4 bosses (climactic battles)
- Tier 5+ god-tier entities (world-ending threats)

The key: **Tier = mechanical challenge, Rank = narrative genre**. Use them together to create the right difficulty AND story tone.

---
```

**Add to advancement.md after line 147:**

```markdown
**Note on Rank vs Tier:** Your character's Rank (1-4) represents narrative genre and scale, not mechanical power. You can face Tier 4 threats at Rank 1 (tough boss fights) or Tier 1 threats at Rank 4 (minions). See Chapter 6: Challenges for the distinction between Rank (narrative permission) and Tier (mechanical difficulty).

---
```

**Action Items:**
- [ ] Add "Tier vs Rank" section to 06-challenges.md (after line 23)
- [ ] Add note to advancement.md (after line 147)
- [ ] Update README.md line 11 to note distinction: "Progress track-based (Tier = difficulty, Rank = genre)"

---

### 1.3 Clarify Disaster as Edge Case

**Problem:** Disaster appears as a 5th outcome in multiple files, creating confusion about whether it's part of the core system.

**Root Cause:** Disaster is an edge case (Setback reduced further by Complications), but it's presented inconsistently—sometimes as a full outcome tier, sometimes as a note.

**Fix README.md (line 70):**

**Current:**
```markdown
- **Setback** (all 1-3) — Failure with consequences
- **Conflict** (any 4-5) — Success with consequence (GM makes soft Impact Move)
- **Success** (any 6) — Clean success
- **Triumph** (two+ 6s) — Heroic success (gain Momentum, ignore Complications)
```

**Change to:**
```markdown
- **Setback** (all 1-3) — Failure with Major Consequence (GM makes hard Impact Move)
- **Conflict** (any 4-5) — Success with Minor Consequence (GM makes soft Impact Move)
- **Success** (any 6) — Clean success
- **Triumph** (two+ 6s) — Heroic success (gain Momentum, ignore Complications)

**Edge Case - Disaster:** If a Setback is reduced even further by Complications (rare), it becomes a **Disaster** (Severe Consequence: Taken Out, Burden, catastrophic failure). See Chapter 4 for details.
```

**Update 02-core-mechanics.md (line 309):**

**Current:**
```markdown
Setback can be pushed further into **Disaster** (Severe Consequence)
```

**Change to:**
```markdown
### Disaster (Edge Case)

When **multiple Complications** reduce an outcome past Setback, it becomes **Disaster** (Severe Consequence). This is rare—it requires rolling Setback AND having 2+ Complications, OR rolling Success/Conflict and having 3+ Complications.

**Disaster represents catastrophic failure:**
- Taken Out (unconscious, captured, removed from scene)
- Gain a Burden (persistent Condition)
- Objective fails completely with lasting consequences

**GM Discretion:** Disaster is optional. If it feels too punishing, cap outcomes at Setback and apply a harsh Major Consequence instead.

**Example:**
> Kael attacks an Ancient Dragon (3 Complications: Resilient, Warded, Legendary).
> - Rolls Success (6)
> - Complications reduce: Success → Conflict → Setback → **Disaster**
> - GM: "Your blade shatters against its scales. Mark a Burden: Weapon Shattered 2. You're disarmed and staggered—the dragon's counterattack sends you flying..."

See Chapter 4 for Disaster Impact Moves.
```

**Update 04-action-resolution.md (line 804 header):**

**Current:**
```markdown
## Disaster
```

**Change to:**
```markdown
## Disaster (Edge Case / Optional)

Disaster occurs when outcomes are reduced **below Setback** by Complications. This is rare and represents catastrophic failure.

**When Disaster Happens:**
- Multiple Complications stack to reduce outcome past Setback
- Example: Success with 3 Complications → Disaster
- Example: Setback with 2+ Complications → Disaster

**GM Discretion:** Disaster is an optional edge case. If it feels too punishing for your table, simply cap outcomes at Setback and apply the harshest possible Major Consequence instead.
```

**Action Items:**
- [ ] Update README.md line 70 to clarify Disaster as edge case
- [ ] Rewrite Disaster section in 02-core-mechanics.md (line 309)
- [ ] Update 04-action-resolution.md header (line 804) to mark as edge case/optional

---

### 1.4 Update Calling List in Rules Summary

**Problem:** Rules summary lists Wanderer (on hold) instead of Vanguard/Hunter (valid).

**Fix:** Simple update to rules summary and any cross-references.

**Files to Update:**
- Rules summary document (if separate)
- README.md line 11 (if Callings mentioned)
- Any chapter introductions that list Callings

**Update to:**
```markdown
**Callings:** Champion, Vanguard, Shadow, Hunter, Sage (Specialist/Generalist), Mystic
```

**Action Items:**
- [ ] Update Calling list in rules summary
- [ ] Search for "Wanderer" references: `grep -r "Wanderer" heroic-fantasy-rpg/*.md`
- [ ] Remove or mark as "(future content)" any Wanderer mentions

---

## Phase 2: Fix Actual Errors (Week 1-2)
**Goal:** Correct genuine mechanical and terminology errors  
**Estimated Time:** 2-3 hours  
**Files Affected:** 3 files

### 2.1 Fix Invalid "Wits" Approach Reference ⚠️ CRITICAL

**Problem:** `10-spellcasting.md` line 541 uses "Wits" which is not a valid Approach.

**File:** `10-spellcasting.md`  
**Line:** 541

**Current Text:**
```markdown
**Dispelling Magic:** Defy + Wits/Spirit to unravel
```

**Fix:**
```markdown
**Dispelling Magic:** Defy + Spirit to unravel (or + Cunning if using analytical counterspell techniques)
```

**Rationale:**
- **Spirit:** Willpower-based dispelling (forcing magic to bend)
- **Cunning:** Analytical counterspelling (finding logical flaws)
- Both fit the fiction better than the non-existent "Wits"

**Action Items:**
- [ ] Update line 541 in `10-spellcasting.md`
- [ ] Search for any other "Wits" references: `grep -r "Wits" heroic-fantasy-rpg/`
- [ ] If other instances found, replace with appropriate valid Approaches

---

### 2.2 Remove or Define Undefined Magical Schools

**Problem:** `10-spellcasting.md` references magical schools not defined in the Seven Spheres system.

**Undefined Terms:**
- **Biomancy** (line 433) - "Healing domain, Biomancy, Life magic"
- **Wardcraft** (lines 514, 540) - "Divination, Wardcraft", "Wardcraft, Abjuration"
- **Shadowmancy** (line 403) - "Shadowmancy or Illusion"
- **Abjuration** (line 540) - "Wardcraft, Abjuration"

**File:** `10-spellcasting.md`

**DECISION REQUIRED:** Are these:
- **A)** Alternative names for existing Spheres (if so, create a mapping table)
- **B)** Examples of spell "trappings" (cosmetic flavoring, not mechanical)
- **C)** Outdated terms that should be replaced with the Seven Spheres

**Option A: Map to Existing Spheres**

Add after the Seven Spheres section (line 184):
```markdown
### Alternative Magical Terminology

Different cultures and traditions use different names for the Seven Spheres. Here are common alternatives:

| Common Name | Alternative Names |
|-------------|-------------------|
| **Body** | Biomancy, Flesh-craft, Vitalism, Life magic |
| **Mind** | Enchantment, Thought-weaving, Psychomancy |
| **Space** | Translocation, Dimension-craft, Portal magic |
| **Time** | Chronomancy, Temporal magic |
| **Elements** | Evocation, Elemental-craft, Destruction magic |
| **Force** | Abjuration, Wardcraft, Shielding, Protection magic |
| **Matter** | Transmutation, Alchemy, Shape-craft |

**General Terms:**
- **Shadowmancy:** Usually Mind (illusions) or Elements (darkness manipulation)
- **Divination:** Usually Mind (reading thoughts) or Time (glimpsing future)

Use whatever terminology fits your setting—mechanically, they all work the same as the Seven Spheres.
```

**Option B: Mark as Trappings**

Replace references with:
- Line 433: "Healing domain, Life sphere, etc."
- Line 403: "Shadow illusions or Mind illusions"
- Lines 514, 540: "Force sphere (wards, barriers, protection)"

**Option C: Replace with Seven Spheres**

Simple find/replace:
- Biomancy → Body
- Wardcraft/Abjuration → Force
- Shadowmancy → Mind or Elements

**Recommendation:** **Option A** - Adds richness, acknowledges different magical traditions, maintains flexibility.

**Action Items:**
- [ ] **DECIDE:** Option A, B, or C
- [ ] Implement chosen solution in `10-spellcasting.md`
- [ ] Search for other undefined magical terms: `grep -r "mancy\|craft" 10-spellcasting.md`

---

### 2.3 Fix Arcane Formula Frequency Inconsistency

**Problem:** Sage's Arcane Formula states "once/scene" in Quick Reference but main text doesn't specify this.

**File:** `09-callings.md`  
**Locations:** Line 129-130 (main text), Line 227 (Quick Reference)

**DECISION REQUIRED:** Is Arcane Formula:
- **A)** Unlimited uses (just costs 1 Stress each time)
- **B)** Once per scene (as Quick Reference states)

**If Option A (Unlimited):**
- Line 227: Remove "once/scene" from Quick Reference
- Line 129-130: Clarify "You may use this as many times per scene as you can afford the Stress cost"

**If Option B (Once per scene):**
- Line 129-130: Add "**Once per scene**, you may..." to main text

**Recommendation:** Check with playtest data—is unlimited too powerful? If so, keep once/scene and update main text.

**Action Items:**
- [ ] **DECIDE:** Unlimited or once/scene?
- [ ] Update either main text or Quick Reference to match
- [ ] Add frequency limit prominently if choosing once/scene

---

## Phase 3: Add Missing Core Mechanics (Week 2)
**Goal:** Fill gaps in overview chapters  
**Estimated Time:** 4-5 hours  
**Files Affected:** 4 files

### 3.1 Add Expertise Mechanic to Overview Files

**Problem:** Expertise (converts Setback→Conflict within domain) is core mechanic but barely mentioned in overview chapters.

**Files to Update:**

**A. README.md**
- **Location:** After line 62 (Momentum section)
- **Add:**
```markdown
### Expertise

Characters with **Expertise** in a domain (e.g., Heavy Blades, Stealth, your chosen magical Sphere) convert **Setback → Conflict** outcomes when acting within that domain.

**You still succeed, but at a cost.** Expertise represents mastery—you don't fail, but difficult situations still extract a price.

**Example:** A master swordsman with Expertise: Heavy Blades rolls Setback against an armored foe. Expertise converts it to Conflict—the attack lands (mark Harm track) but costs Stress.

*(See Chapter 3: Characters for full Expertise rules)*
```

**B. 01-introduction.md**
- **Location:** After line 87 (end of Traits section)
- **Add:**
```markdown
**Expertise:** Some Talents grant Expertise in a specific domain (e.g., "Expertise: Stealth and Thievery" or "Expertise: Your Chosen Sphere"). When you act within your Expertise and roll Setback, the outcome becomes Conflict instead. You succeed, but still face consequences—representing how your mastery pulls victory from failure.
```

**C. 02-core-mechanics.md**
- **Location:** After line 213 (Pool Calculations section)
- **Add full Expertise section:**
```markdown
---

## Expertise

**Expertise** represents mastery in a specific domain. When you take an action within your Expertise domain and your final outcome (after applying all Complications) would be **Setback**, the outcome becomes **Conflict** instead.

### Key Mechanics

**Expertise applies AFTER Complications:**
- Roll dice → determine raw outcome
- Apply Complications (reduce outcome tiers)
- **If final outcome is Setback AND action is within Expertise domain: convert to Conflict**

**Expertise does NOT:**
- Protect against Disaster outcomes (only converts Setback)
- Reduce Consequence severity (you still mark same Stress/Conditions)
- Add Edge or negate Complications

**Expertise converts failure → success, but success at a cost.**

### Common Expertise Domains

**Combat:**
- Heavy Blades (greatswords, longswords, axes)
- Light Weapons (daggers, rapiers, shortswords)
- Archery (bows, crossbows)
- Unarmed Combat (brawling, martial arts)

**Subterfuge:**
- Stealth and Deception (sneaking, lying, disguises)
- Thievery (lockpicking, pickpocketing, traps)

**Social:**
- Persuasion and Diplomacy
- Intimidation and Threats
- Performance and Entertainment

**Magic:**
- Your chosen Sphere (Sage Specialist only)
- Specific spell domains (Mystic depending on patron)

**Other:**
- Wilderness Survival (tracking, foraging, animal handling)
- Scholarship (research, languages, lore)

### Example in Play

> **Kael (Champion with Expertise: Heavy Blades)** attacks an armored knight with 2 Complications (Resilient, Heavily Armored).
>
> **Roll:** Kael rolls 3d6 (Daring 3) → highest die is 6 (Success)
>
> **Apply Complications:**
> - 2 Complications reduce outcome by 2 tiers
> - Success → Conflict → Setback
>
> **Expertise Converts:**
> - Setback → Conflict (Kael's mastery with heavy blades pulls victory from failure)
>
> **Result:** Conflict outcome
> - **Primary Effect:** Mark 1 Harm on knight's track (Kael's blade finds a gap in the armor)
> - **Consequence:** Minor (mark 1 Stress from the jarring impact against heavy plate)
>
> **GM:** "Your greatsword slams into the knight's pauldron with a ringing clang. You feel the impact travel up your arms (mark 1 Stress), but your years of training let you redirect the force—your blade slides down and catches him in the exposed joint. The knight staggers back (mark 1 Harm)."

Without Expertise, this would have been Setback (failure + Major Consequence). Expertise converted it to Conflict (success + Minor Consequence).

*(See Chapter 3 for Expertise Talents)*

---
```

**Action Items:**
- [ ] Add Expertise to README.md (after line 62)
- [ ] Add Expertise to 01-introduction.md (after line 87)
- [ ] Add full Expertise section to 02-core-mechanics.md (after line 213)

---

### 3.2 Add Complication Tags to Overview Files

**Problem:** The 9 Complication tags aren't mentioned in overview sections, leaving new players without context.

**Files to Update:**

**A. README.md (lines 64-76)**

**Current:**
```markdown
**Complications** reduce outcome by -1 tier (Triumph → Success → Conflict → Setback → Disaster)
- Unlimited stacking
- Source: Challenge Complications (enemy defenses)
- Negate with: Act with Potency (ignore 1), Talents, Triumph

**Triumph ignores all Complications.**
```

**Replace with:**
```markdown
**Complications** reduce outcome by -1 tier each (Success → Conflict → Setback → Disaster)
- Source: Challenge Complications (enemy defensive abilities)
- Negate with: Act with Potency (ignore 1), Talents, Triumph
- Unlimited stacking

**Common Complication Tags:**

Challenges have **Complication tags** that describe when they apply:

**Defensive Tags** (hinder attacks):
- **Resilient** — Hinders actions that try to harm, damage, or destroy (tough armor, thick hide)
- **Warded** — Hinders magical attacks and effects (magic resistance, protective wards)
- **Elusive** — Hinders attacks, physical or magical (dodge, parry, supernatural evasion)

**Perception Tags** (hinder detection/deception):
- **Stealthy** — Hinders attempts to detect, track, or perceive (natural camouflage, supernatural concealment)
- **Alert** — Hinders stealth, ambush, or deception attempts (keen senses, paranoia, magical awareness)

**Mental Tags** (hinder social/mental actions):
- **Resolute** — Hinders persuasion, intimidation, or mental influence (strong will, fanaticism, mind shields)
- **Complex** — Hinders attempts to solve, unlock, or understand (intricate locks, arcane puzzles, alien logic)

**Special Tags** (modify consequences or stack):
- **Deadly** — Increases Consequence severity by 1 tier when you fail (venomous, brutal, savage)
- **Legendary** — Reduces outcome by 2 tiers instead of 1 (counts as 2 Complications)

**Triumph ignores all Complications.**

*(See Chapter 6: Challenges for complete Complication system)*
```

**B. 01-introduction.md (after line 50)**

**After first Complication mention, add:**
```markdown
Challenges have **Complication tags** that describe their defenses and when they apply:
- **Resilient** (hard to damage), **Elusive** (hard to hit), **Alert** (hard to deceive)
- **Warded** (magically protected), **Resolute** (strong-willed), **Deadly** (dangerous when you fail)
- **Legendary** (counts as 2 Complications), **Complex** (hard to solve), **Stealthy** (hard to detect)

*(See Chapter 6: Challenges for complete tag descriptions)*
```

**Action Items:**
- [ ] Expand README.md Complications section (lines 64-76) with tag list
- [ ] Add Complication tags overview to 01-introduction.md (after line 50)

---

## Phase 4: Structural Improvements (Week 2-3)
**Goal:** Eliminate redundancy, improve organization  
**Estimated Time:** 6-8 hours  
**Files Affected:** 8 files

### 4.1 Consolidate Duplicate Content

**Problem:** Key concepts explained 2-3 times within same files.

**A. 04-action-resolution.md - Triumph Explanations**

**Locations:** Lines 167-174, 177-188, 1029-1033 (explained three times)

**Fix:**
- **Keep:** Lines 167-174 (first comprehensive explanation)
- **Delete:** Lines 177-188 (redundant prose)
- **Keep:** Lines 1029-1033 (Quick Reference - but convert to table format, not prose)

**B. 04-action-resolution.md - Progress Tracks**

**Locations:** Lines 437-492 (detailed), Lines 770-801 (duplicate)

**Fix:**
- **Keep:** Lines 437-492 (main comprehensive section)
- **Delete:** Lines 770-801 (duplicate explanation)
- **Add:** Cross-reference at line 770: "*(See Progress Tracks section, line 437 for complete rules)*"

**C. 07-gm-guide.md - Soft/Hard Moves**

**Locations:** Lines 33-59 (Telegraph danger), Lines 100-151 (GM Moves section)

**Fix:**
- **Keep:** Lines 33-59 (Telegraph danger, then follow through)
- **Streamline:** Lines 100-151 - remove redundant definition of Soft/Hard, keep only the three-tier categorization (Suspense/Impact/Challenge)
- **Change line 100 to:** "GM Moves fall into three categories (see 'Telegraph danger, then follow through' above for Soft vs Hard distinction):"

**D. advancement.md - Progression Summaries**

**Locations:** Lines 7-20 (Level Progression Table), Lines 24-48 (Power Curve Summary), Lines 494-512 (Quick Reference)

**Fix:**
- **Expand:** Level Progression Table (lines 7-20) to include Power Curve details in additional columns
- **Delete:** Power Curve Summary section (lines 24-48) entirely
- **Keep:** Quick Reference (lines 494-512) but as compact formulas only

**Enhanced Level Progression Table:**
```markdown
| Level | Approaches | Talents | Traits | Rank | Gain | Notes |
|-------|------------|---------|--------|------|------|-------|
| **1** | 3/2/1/1/0 (7 pts) | 2 | 3 | 1 | **Start** | Choose Calling (Core + 1 secondary Talent) |
| **2** | +1 → 8 pts | 3 | 3 | 1 | +1 Approach (cap 2), +1 Talent | Broaden competencies |
| **3** | +1 → 9 pts | 3 | 3 | 1 | +1 Approach (cap 3) | |
| **4** | +1 → 10 pts | 4 | 3 | **2** | **Rank 2**, +1 Approach (cap 4), +1 Talent | **Seasoned Adventurers** |
| **5** | 10 pts | 4 | 4 | 2 | +1 Trait | |
| **6** | +1 → 11 pts | 5 | 4 | 2 | +1 Approach (cap 2), +1 Talent | |
| **7** | +1 → 12 pts | 6 | 4 | **3** | **Rank 3**, +1 Approach (cap 3), +1 Talent | **Regional Legends** |
| **8** | +1 → 13 pts | 7 | 4 | 3 | +1 Approach (cap 4), +1 Talent | Specialize primary |
| **9** | +1 → 14 pts | 7 | 4 | 3 | +1 Approach (cap 5) | **Legendary Approach** |
| **10** | 14 pts | 8 | 5 | **4** | **Rank 4**, +1 Trait, +1 Talent | **Mythic Heroes** |
```

**E. README.md - Build Momentum**

**Locations:** Lines 49, 56, 66-68 (explained three times identically)

**Fix:**
- **Keep:** Line 49 (under Traits Special Effects - first mention)
- **Line 56:** Change to "- **Build Momentum (Trait)** — See Traits section above"
- **Delete:** Lines 66-68 (third explanation)

**F. 05-resilience.md - Edge/Bane Cap**

**Locations:** Lines 65-69 (detailed), 125-127 (example), 257 (mentioned again)

**Fix:**
- **Keep:** Lines 65-69 (main explanation with mechanics)
- **Line 125-127:** Simplify to "*(±2d cap applies - see line 65)*"
- **Line 257:** Change to "*(Remember the ±2d cap from all sources)*"

**Action Items:**
- [ ] Consolidate Triumph explanations (04-action-resolution.md)
- [ ] Merge duplicate Progress Tracks sections (04-action-resolution.md)
- [ ] Streamline Soft/Hard Move explanations (07-gm-guide.md)
- [ ] Consolidate progression summaries (advancement.md)
- [ ] Remove duplicate Build Momentum explanations (README.md)
- [ ] Remove duplicate Edge/Bane cap explanations (05-resilience.md)

---

### 4.2 Reorganize GM Guide Structure

**Problem:** Related content scattered across the chapter.

**File:** `07-gm-guide.md`

**Current Order:**
1. GM Principles (9-31)
2. Telegraph danger (33-59)
3. GM Moves (79-158)
4. Vigilance (160-199)
5. Spotlight (202-231)
6. Pacing Combat (360-383)
7. Threat Pool (385-400)
8. Session Structure (427-449)
9. Challenges (452-494)
10. Battlegrounds (525-550)
11. Tangles (554-590)
12. Clocks & Tracks (593-616)

**Proposed Reorganization:**

**1. Foundation (Lines 9-158)**
- GM Principles (9-31) ✓ keep
- GM Moves Framework (consolidate 33-158):
  - Telegraph danger basics (33-59) ✓ keep
  - Three Tiers (Suspense/Impact/Challenge) (79-158) ✓ streamline
  - Vigilance pattern (160-199) → **move here** (specific application of Soft/Hard Moves)

**2. Running Sessions (Lines 200-450)**
- Session Structure (427-449) → **move up here** (comes before specific techniques)
- Spotlight Management (202-231) ✓ keep position
- Pacing Combat (360-383) → **move here** (session-level pacing)

**3. Structured Scene Tools (Lines 450-620)**
- Challenges (452-494) ✓ keep
- Battlegrounds (525-550) ✓ keep
- Clocks & Tracks (593-616) ✓ keep

**4. Optional Mechanics (Lines 385-590)**
- Threat Pool (385-400) → **move here** (group optionals)
- Tangles (554-590) → **move here** (group optionals)

**New Order:**
1. **GM Foundation**
   - GM Principles
   - GM Moves (Telegraph danger + Three Tiers + Vigilance)
2. **Running Sessions**
   - Session Structure
   - Spotlight Management
   - Pacing Combat
3. **Structured Scene Tools**
   - Challenges
   - Battlegrounds
   - Clocks & Tracks
4. **Optional Mechanics**
   - Threat Pool
   - Tangles

**Benefits:**
- Foundation grouped logically
- Session/pacing guidance together
- Optional mechanics clearly separated
- Related tools grouped

**Action Items:**
- [ ] Reorganize 07-gm-guide.md sections
- [ ] Update internal cross-references after move
- [ ] Add section headers to delineate the four groups

---

### 4.3 Simplify Complex Procedures

**A. Stress Overflow (05-resilience.md lines 96-106)**

**Current:** Nested rules with exception mid-flow

**Rewrite as clear steps:**

```markdown
## Stress Overflow

When you would mark Stress but your Stress Track is completely full:

### Step 1: Check for Resist Consequence (Optional)

If you have Momentum available, you may spend 1 Momentum to **Resist Consequence** before applying overflow. Roll Defy to reduce or avoid the incoming Consequence (see Resist Consequence section).

If you successfully resist and reduce the Consequence below what would cause overflow, you avoid the overflow entirely.

### Step 2: Choose Your Path

If overflow still applies after any Resist attempt, you must choose one:

#### Option A: Take a Burden

**Gain a persistent Burden** (Condition that doesn't clear on short rest):
- The Burden's tier matches the incoming Consequence:
  - **Minor Consequence** → **Burden 1**
  - **Major Consequence** → **Burden 2**
  - **Severe Consequence** → **Burden 3**
- Your Stress Track remains full
- You stay in the scene

**Special Case:** If you already have a Burden with the same name, it refreshes to whichever tier is higher (existing or new).

**Example:**
> Kael has a full Stress Track and takes 2 Stress from a hard hit (Major Consequence). He chooses to take a Burden instead of being Taken Out. He gains **Wounded 2** and stays in the fight.

#### Option B: Be Taken Out

**You're removed from the scene:**
- Clear your entire Stress Track (back to 0)
- You're unconscious, captured, or otherwise incapacitated
- The GM narrates what happens and how you exit
- You cannot act again until the scene ends

**Example:**
> Mira has a full Stress Track and takes 1 Stress from a minor wound (Minor Consequence). Rather than take Wounded 1, she lets herself be Taken Out—she collapses from exhaustion and blood loss, unconscious at the scene's edge.

### When It Matters

Stress Overflow is a critical decision point:
- **Take a Burden:** Stay in the fight, but suffer a persistent debuff (doesn't clear on short rest)
- **Be Taken Out:** Remove yourself from danger, clear Stress, but lose agency for this scene

Choose based on the situation—sometimes being Taken Out is the smart choice.
```

**B. Secondary Effects (04-action-resolution.md lines 348-434)**

**Current:** 86 lines mixing categories, rules, and GM guidance

**Fix:** Add clear subsection headers

```markdown
## Secondary Effects (from Traits)

When you invoke a Trait on Conflict or higher, you gain one **Special Effect**:
- **Greater Effect** (double progress, extra questions)
- **Secondary Effect** (inflict Condition, affect multiple targets, take something)
- **Build Momentum** (grant 1 Momentum to self or ally)

Choose the Special Effect AFTER rolling but BEFORE the GM describes consequences.

---

### Core Categories

**[Lines 353-372 - Keep as-is with header]**

---

### Inflicting Conditions on Enemies

When you choose **Secondary Effect: Inflict Condition**, you can impose a Condition on an enemy you've successfully affected with your action.

**[Lines 376-405 - Keep as-is with header]**

---

### GM Guidance: Adjudicating Secondary Effects

Secondary Effects should feel meaningful but not overwhelming. Here's how to adjudicate them at the table:

**[Lines 407-434 - Keep as-is with header]**

---
```

**Action Items:**
- [ ] Rewrite Stress Overflow as clear numbered steps (05-resilience.md lines 96-106)
- [ ] Add subsection headers to Secondary Effects (04-action-resolution.md lines 348-434)

---

## Phase 5: Clarity & Polish (Week 3-4)
**Goal:** Final clarity improvements and formatting  
**Estimated Time:** 3-4 hours  
**Files Affected:** 6 files

### 5.1 Introduction Timing Fixes

**File:** `01-introduction.md`

**A. Add Edge/Bane Cap Earlier**
- **Current:** Line 70 (late mention)
- **Fix:** Add to line 46 when first introduced

**Line 46 current:**
```markdown
**Edge/Bane:** Situational advantages (Edge) or complications (Bane) add or remove d6 from your pool before rolling. These cancel each other 1:1.
```

**Change to:**
```markdown
**Edge/Bane:** Situational advantages (Edge) or complications (Bane) add or remove d6 from your pool before rolling **(cap: ±2d after canceling)**. Edge and Bane cancel each other 1:1 first, then apply the cap.
```

**B. Clarify Assess Questions**
- **Line 31:** "Ask specific questions"
- **Fix:** "Ask 2 questions (1 question on Conflict)"

**C. Add Recall Clarifying Question**
- **Line 32:** "GM tells you something useful"
- **Fix:** "GM tells you something useful + you ask 1 clarifying question"

**D. Clarify Act with Potency**
- **Line 59:** Currently ambiguous if all three effects apply
- **Fix:** "**Choose one:** gain 1 Edge (+1d), ignore 1 Complication, OR enable an extraordinary feat"

**E. Lead Conditions with Fiction**
- **Lines 68-74:** Currently mechanics-first
- **Fix:** Start with narrative: "**Conditions** are temporary impairments (Wounded, Frightened, Poisoned, etc.) that hinder your actions. Each Condition applies 1 Bane..."

**Action Items:**
- [ ] Add Edge/Bane cap to line 46
- [ ] Clarify Assess questions (line 31)
- [ ] Add clarifying question to Recall (line 32)
- [ ] Clarify Act with Potency as choose-one (line 59)
- [ ] Rewrite Conditions opening (lines 68-74) to lead with fiction

---

### 5.2 Define Terms Before Using

**A. Define "Track" and "Mark" (01-introduction.md before line 27)**

**Add before action descriptions:**
```markdown
### Progress Tracks

Extended challenges use **Progress Tracks**—a series of boxes (usually 4-8) representing obstacles, enemy endurance, or social resistance:

**Three Track Types:**
- **Harm Track:** Physical damage to enemies/obstacles
- **Will Track:** Social/mental resistance
- **Obstacle Track:** Environmental or situational challenges

When you succeed at certain actions, you **mark** (fill in) ticks on the appropriate track. When the track fills completely, you overcome the challenge.

**Example:**
> A heavily armored knight has a Harm track with 6 ticks: [ ][ ][ ][ ][ ][ ]
> Each time you successfully Clash with him, you mark 1-2 ticks.
> When all 6 are filled, he's defeated.

*(See Chapter 4 for complete track rules)*
```

**B. Define "Primary Effect" (02-core-mechanics.md before line 38)**

**Add before first use:**
```markdown
### Primary Effects

Each Action has a **Primary Effect**—what it accomplishes when you succeed. Primary Effects are automatic and free; you don't need to spend Momentum or invoke Traits to get them.

**Example:** When you successfully Clash with an enemy, the Primary Effect is **Harm**—you mark their Harm track. You get this even on a basic Conflict outcome with no Traits involved.

*(Actions and their Primary Effects are detailed below)*
```

**Action Items:**
- [ ] Add track/mark definitions to 01-introduction.md (before line 27)
- [ ] Add Primary Effect definition to 02-core-mechanics.md (before line 38)

---

### 5.3 Standardize Quick Reference Sections

**Problem:** Quick Reference sections repeat prose instead of being pure reference.

**Files to Update:**
- `02-core-mechanics.md` lines 313-345
- `04-action-resolution.md` lines 1008-1058
- `challenge-creation.md` lines 1300-1638

**Approach:** Convert to table/formula format only, remove explanatory prose

**Example Transformation:**

**Before (prose repeat):**
```markdown
**Conflict (any 4-5)** — You succeed at your Primary Effect but suffer a Minor Consequence. The GM makes a soft Impact Move: mark 1 Stress, lose position, or introduce a complication.
```

**After (table format):**
```markdown
| Outcome | Roll | Primary Effect | Consequence |
|---------|------|----------------|-------------|
| **Conflict** | Any 4-5 | Yes | Minor (soft Impact Move) |
```

**Action Items:**
- [ ] Convert 02-core-mechanics.md Quick Reference (lines 313-345) to tables
- [ ] Convert 04-action-resolution.md Quick Reference (lines 1008-1058) to tables
- [ ] Convert challenge-creation.md Quick Reference (lines 1300-1638) to formulas only

---

### 5.4 Add Cross-References

**A. First Complication Mention**
- `01-introduction.md` line 50: Add "*(see Chapter 6 for Complication tags)*"
- `02-core-mechanics.md` line 123: Add "*(Chapter 6 for complete system)*"

**B. First Track Mention**
- `01-introduction.md` line 27: Add "*(tracks detailed in Chapter 4)*"
- `02-core-mechanics.md` line 38: Add "*(see Chapter 4 for track rules)*"

**C. Momentum Cap Talent**
- `03-characters.md` line 137: "Cap: 2 *(increased to 3 via Relentless Talent)*"

**D. Expertise Reference**
- `02-core-mechanics.md` line 203: "*(see Expertise section, line [X])*"

**Action Items:**
- [ ] Add Complication cross-references to 01-introduction, 02-core-mechanics
- [ ] Add track cross-references to 01-introduction, 02-core-mechanics
- [ ] Add Momentum cap talent reference to 03-characters
- [ ] Add Expertise cross-reference to 02-core-mechanics

---

### 5.5 Minor Terminology Consistency

**A. Standardize "Progress track"**
- **Decision:** Use "Progress track" as generic term
- **Keep:** Specific names (Harm track, Will track, Obstacle track)
- **Files:** README.md, 01-introduction.md, 02-core-mechanics.md
- **Find/Replace:** Generic "track" mentions → "Progress track"

**B. Capitalize "Burden" Consistently**
- **File:** 05-resilience.md
- **Rule:** Always capitalize when referring to game term
- **Check:** `grep -i "burden" 05-resilience.md` and fix inconsistencies

**C. Verify "Hinders" Consistency**
- **All Complication tags use "hinders" not "blocks" or "prevents"**
- **Already correct per review**, but verify: `grep -r "blocks\|prevents" heroic-fantasy-rpg/*.md`

**Action Items:**
- [ ] Standardize "Progress track" terminology across overview files
- [ ] Capitalize "Burden" consistently in 05-resilience.md
- [ ] Verify "hinders" usage in all Complication descriptions

---

## Verification Checklist

After completing all phases:

### Terminology Verification
```bash
# Check for "Wits" (should only be valid Approaches)
grep -r "Wits" heroic-fantasy-rpg/*.md

# Check for undefined magical schools
grep -r "Biomancy\|Wardcraft\|Shadowmancy\|Abjuration" 10-spellcasting.md

# Check for "blocks" (should be "hinders")
grep -r "blocks\|blocking" heroic-fantasy-rpg/*.md | grep -i complication

# Check for Wanderer references (on hold)
grep -r "Wanderer" heroic-fantasy-rpg/*.md
```

### Clarity Verification
```bash
# Check Action vs Effect clarity exists
grep -r "Understanding Actions and Effects" heroic-fantasy-rpg/*.md

# Check Tier vs Rank clarification exists
grep -r "Tier vs Rank" heroic-fantasy-rpg/*.md

# Check Disaster framed as edge case
grep -r "Disaster (Edge Case\|Optional)" heroic-fantasy-rpg/*.md
```

### Structural Verification
```bash
# Find remaining duplicate content
grep -r "Build Momentum" heroic-fantasy-rpg/*.md | wc -l  # Should be minimal

# Check Quick Reference sections use tables
grep -A 5 "^## Quick Reference" heroic-fantasy-rpg/*.md | grep "^|"  # Should see tables
```

---

## Success Criteria

**Phase 1 Complete (Clarifications):**
- [ ] Action vs Effect distinction explained in 3 files (README, 01-intro, 02-core)
- [ ] Tier vs Rank distinction explained in 2 files (06-challenges, advancement)
- [ ] Disaster clearly marked as edge case/optional in 3 files
- [ ] Calling list updated (no Wanderer, yes Vanguard/Hunter)

**Phase 2 Complete (Fix Errors):**
- [ ] No "Wits" Approach references remain
- [ ] Undefined magical schools resolved (mapped, removed, or marked as trappings)
- [ ] Arcane Formula frequency clarified (once/scene or unlimited)

**Phase 3 Complete (Add Missing Mechanics):**
- [ ] Expertise explained in README, 01-intro, 02-core
- [ ] Complication tags listed in README, 01-intro
- [ ] All overview files include core mechanics

**Phase 4 Complete (Structure):**
- [ ] No duplicate Triumph/Progress Tracks/Soft-Hard Move explanations within files
- [ ] GM Guide reorganized logically (Foundation → Sessions → Tools → Optional)
- [ ] Stress Overflow rewritten as clear steps
- [ ] Secondary Effects has clear subsections

**Phase 5 Complete (Polish):**
- [ ] Edge/Bane cap mentioned when first introduced (01-intro line 46)
- [ ] Tracks and Primary Effect defined before use
- [ ] Quick Reference sections use tables, not prose
- [ ] Cross-references added throughout
- [ ] Terminology consistent (Progress track, Burden, hinders)

---

## Estimated Timeline

**Week 1 (Phases 1-2):** 5-7 hours
- **Day 1:** Add Action vs Effect + Tier vs Rank clarifications (2-3 hours)
- **Day 2:** Clarify Disaster, update Calling list, fix Wits (1 hour)
- **Day 3:** Resolve undefined magical schools, Arcane Formula frequency (2-3 hours)

**Week 2 (Phase 3):** 4-5 hours
- **Day 4-5:** Add Expertise to overview files (2-3 hours)
- **Day 6:** Add Complication tags to overview files (2 hours)

**Week 3 (Phase 4):** 6-8 hours
- **Day 7-8:** Consolidate duplicate content (3-4 hours)
- **Day 9:** Reorganize GM Guide structure (2-3 hours)
- **Day 10:** Simplify complex procedures (1 hour)

**Week 4 (Phase 5):** 3-4 hours
- **Day 11:** Introduction timing fixes (1 hour)
- **Day 12:** Define terms before using (1 hour)
- **Day 13:** Standardize Quick References + cross-references (1 hour)
- **Day 14:** Terminology consistency pass + verification (1 hour)

**Total:** 18-24 hours over 3-4 weeks

---

## Decisions Needed Before Starting

Please review and decide:

1. **Undefined Magical Schools (Section 2.2):**
   - **Option A:** Map to Seven Spheres with alternative names table *(recommended)*
   - **Option B:** Mark as cosmetic "trappings" only
   - **Option C:** Replace with Seven Sphere names

2. **Arcane Formula Frequency (Section 2.3):**
   - **Option A:** Unlimited uses (costs 1 Stress each)
   - **Option B:** Once per scene (as Quick Reference states)

3. **Scope:**
   - Approve all 5 phases and begin?
   - Start with Phases 1-2 only and reassess?
   - Modify the plan first?

---

## Implementation Notes

1. **Backup First:** `git checkout -b documentation-clarity-2026-06`

2. **Work in Order:** Clarifications → Fixes → Additions → Structure → Polish

3. **Test After Each Phase:** Read through affected sections to ensure changes flow naturally

4. **Commit Frequently:** Descriptive messages (e.g., "Add Action vs Effect clarification to overview files")

5. **Line Numbers Will Shift:** After Phase 4 reorganization, line numbers in later phases become approximate—work from section headers instead

6. **This Is Enhancement, Not Repair:** Frame changes as "clarity improvements" not "error fixes" (the system works, it just needs better explanation)

---

**End of Revised Fix Plan**
