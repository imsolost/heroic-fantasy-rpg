# Documentation Fix Plan - Heroic Fantasy RPG

**Generated:** 2026-06-20  
**Review Status:** 16 files reviewed, 212 issues identified (18 critical)  
**Estimated Effort:** 21-30 hours total

---

## Executive Summary

The comprehensive review identified **5 critical system-breaking issues** that prevent accurate gameplay:

1. ❌ **Outdated action terminology** in character creation and resilience chapters
2. ❌ **Tier vs Rank confusion** creating two competing power systems
3. ❌ **"Disaster" phantom outcome** contradicting the 4-outcome system
4. ❌ **Invalid "Wits" Approach** reference in spellcasting
5. ❌ **Calling list mismatch** between files and stated rules

Additionally, significant **redundancy** (duplicate content in 8+ locations) and **clarity issues** (missing context, confusing explanations) reduce usability.

**Recommendation:** Fix in 4 phases over 4 weeks, ensuring playability after Phase 1.

---

## Phase 1: Critical System Fixes (Week 1)
**Goal:** Make documentation mechanically accurate and playable  
**Estimated Time:** 4-6 hours  
**Files Affected:** 6 files

### 1.1 Action Terminology - Global Replacement ⚠️ CRITICAL

**Problem:** Two files use outdated action names throughout examples and mechanics.

**Files to Fix:**
- `03-characters.md` (15+ instances)
- `05-resilience.md` (4 instances)

**Find and Replace (case-sensitive):**
```
Defy   → Overcome  (but keep "Defy" when it's the Approach choice in outcomes)
Clash  → Harm
Talk   → Influence
Sense  → Assess
Know   → Recall
```

**Specific Locations:**

**03-characters.md:**
- Lines 178, 183, 185, 192 (Trait examples)
- Lines 220, 225, 252, 253, 254 (Talent mechanics)
- Lines 297, 305, 317, 318, 320 (Expertise section)
- Line 340 (Build Momentum example)

**05-resilience.md:**
- Line 74: "Blinded doesn't affect recalling lore (Know)" → "(Recall)"
- Line 75: "Restrained doesn't affect examining your surroundings (Sense)" → "(Assess)"
- Line 76: Keep "Defy" (correct usage)
- Line 78: "using Know to recall trivia" → "using Recall to recall trivia"

**Verification:** Search for remaining instances: `grep -r "Know\|Sense\|Clash\|Talk" --include="*.md"`

---

### 1.2 Tier vs Rank Decision ⚠️ CRITICAL

**Problem:** Challenge and combat chapters use **Tier 0-4** (5 numerical levels), but rules state **4 Ranks** with narrative names.

**DECISION REQUIRED:** Choose one approach:

#### Option A: Keep Tier 0-4 for Enemies, Clarify Mapping to PC Ranks

**Pros:** 
- Less rewriting required (mostly adding clarification)
- Tier as enemy power rating is intuitive
- PC Ranks remain narrative (genre-focused)

**Cons:**
- Two parallel systems to track

**Changes Needed:**
1. Add mapping table to `06-challenges.md` after line 23:
```markdown
## Enemy Tiers and PC Ranks

| Enemy Tier | Typical PC Rank | Description |
|------------|-----------------|-------------|
| **Tier 0** | Rank 1 | Minor threats (bandits, giant rats, common guards) |
| **Tier 1** | Rank 1-2 | Competent enemies (veteran soldiers, dangerous beasts) |
| **Tier 2** | Rank 2-3 | Formidable foes (elite knights, young dragons, master assassins) |
| **Tier 3** | Rank 3-4 | Legendary threats (ancient dragons, demon lords, archmages) |
| **Tier 4** | Rank 4 | World-ending (gods, primordial forces, apocalyptic entities) |
```

2. Update all Tier references to include PC Rank context:
   - `06-challenges.md` lines 589-594: Add "PC Rank" column to Challenge Tiers table
   - `08-combat.md` lines 303-308: Add note "Enemy Tiers vs PC Ranks - see Chapter 6"

#### Option B: Replace Tier 0-4 with PC Rank Names Throughout

**Pros:**
- Single unified power system
- Reinforces "Rank as genre" theme
- Clearer for players

**Cons:**
- Extensive rewriting (20+ tables/sections)
- Loses granularity (5 tiers → 4 ranks)

**Changes Needed:**
1. Replace all instances in `06-challenges.md`:
   - Lines 589-594, 649-654, 686-696, 874-880, 1305-1320 (all tables)
   - Lines 151-180, 405-410 (Tier 4 boss examples)
   - Line 507, 1310 (Tier 0 references)

2. Replace in `08-combat.md`:
   - Lines 303-308, 326 (Enemy Quick Reference)

3. Update terminology: "Tier 2 enemy" → "Rank 2 threat" or "Regional Legend-tier enemy"

**Recommendation:** **Option A** - Easier to implement, preserves existing structure, adds needed clarification.

**Action Items:**
- [ ] **DECIDE:** Option A or Option B
- [ ] If Option A: Add mapping table and PC Rank columns to challenge tables
- [ ] If Option B: Execute find/replace across `06-challenges.md` and `08-combat.md`

---

### 1.3 Remove or Integrate "Disaster" Outcome ⚠️ CRITICAL

**Problem:** Multiple files reference "Disaster" as a 5th outcome, contradicting the stated 4-outcome system (Triumph/Success/Conflict/Setback).

**Files Affected:**
- `README.md` line 70
- `02-core-mechanics.md` line 309
- `04-action-resolution.md` lines 108-110, 207, 232-240, 804-841

**DECISION REQUIRED:** Is Disaster a real outcome or an edge case?

#### Option A: Remove Disaster Entirely

**If:** Disaster is just a severe Setback, not a separate outcome tier.

**Changes:**
1. `README.md` line 70: Change "Triumph → Success → Conflict → Setback → Disaster" to "Triumph → Success → Conflict → Setback"
2. `02-core-mechanics.md` line 309: Delete "Setback can be pushed further into **Disaster**"
3. `04-action-resolution.md`:
   - Delete entire Disaster section (lines 804-841)
   - Lines 108-110, 207, 232-240: Replace "or Disaster" with "severe Setback"

#### Option B: Keep Disaster as Optional Edge Case

**If:** Disaster represents extreme failures when multiple Complications stack.

**Changes:**
1. Add to `02-core-mechanics.md` after line 123:
```markdown
### Disaster (Optional Edge Case)

When **multiple Complications** reduce a Success/Conflict down past Setback, the outcome becomes **Disaster** (Severe Consequence). This represents catastrophic failure.

**Example:** You attack an enemy with 3 Complications. You roll Success, but 3 Complications reduce it: Success → Conflict → Setback → Disaster.

Disaster is **optional** - GMs can cap at Setback if Disaster feels too punishing.
```

2. Update references to clarify optional status:
   - `README.md` line 70: Add note "(optional: Disaster)"
   - `04-action-resolution.md` line 804: Change header to "### Disaster (Optional)"

**Recommendation:** **Option B** - Keeps existing content, adds clarity about when/why Disaster applies.

**Action Items:**
- [ ] **DECIDE:** Remove Disaster (Option A) or keep as optional (Option B)
- [ ] Execute changes across all 4 affected files

---

### 1.4 Fix Invalid "Wits" Approach Reference ⚠️ CRITICAL

**Problem:** `10-spellcasting.md` line 541 uses "Wits" which is not a valid Approach.

**File:** `10-spellcasting.md`  
**Line:** 541

**Current Text:**
```markdown
**Dispelling Magic:** Defy + Wits/Spirit to unravel
```

**Fix:**
Determine correct Approach based on fiction:
- If analytical/clever dispelling: "Defy + Cunning"
- If willpower-based dispelling: "Defy + Spirit"
- If both are valid: "Defy + Cunning or Spirit (depending on approach)"

**Recommended Change:**
```markdown
**Dispelling Magic:** Defy + Spirit to unravel (or Cunning if using analytical counterspell techniques)
```

**Action Items:**
- [ ] Update line 541 in `10-spellcasting.md`
- [ ] Search for any other "Wits" references: `grep -r "Wits" heroic-fantasy-rpg/`

---

### 1.5 Resolve Calling List Discrepancy ⚠️ CRITICAL

**Problem:** `09-callings.md` includes **Vanguard** and **Hunter** callings, but stated rules list only: Champion, Sage (Specialist/Generalist), Mystic, Shadow, **Wanderer**.

**File:** `09-callings.md`

**DECISION REQUIRED:** Which is correct?

#### Option A: Vanguard and Hunter Are Valid (Update Rules List)

**If:** The document reflects current design, rules summary is outdated.

**Changes:**
- Update rules summary to list 6 Callings: Champion, Vanguard, Shadow, Hunter, Sage, Mystic
- Remove Wanderer from rules list (appears obsolete)

#### Option B: Wanderer Is Valid (Update 09-callings.md)

**If:** Wanderer is the correct 5th calling, Vanguard/Hunter are outdated.

**Changes:**
- Add Wanderer section to `09-callings.md`
- Remove or mark Vanguard and Hunter as deprecated
- Update all cross-references in other chapters

**Recommendation:** **Option A** - The detailed calling implementations in `09-callings.md` suggest Vanguard/Hunter are current design. Wanderer likely an old concept.

**Action Items:**
- [ ] **DECIDE:** Option A or Option B
- [ ] If Option A: Update rules summary, confirm no "Wanderer" references remain
- [ ] If Option B: Add Wanderer to 09-callings.md, remove Vanguard/Hunter

---

## Phase 2: Structural Consolidation (Week 2)
**Goal:** Eliminate redundancy, add missing core mechanics  
**Estimated Time:** 8-12 hours  
**Files Affected:** 8 files

### 2.1 Add Missing Expertise Mechanic to Core Files

**Problem:** Expertise (converts Setback→Conflict within domain) is barely mentioned in overview/core chapters.

**Files to Update:**

**A. README.md**
- **Location:** After line 62 (Momentum section)
- **Add:**
```markdown
### Expertise

Characters with **Expertise** in a domain convert **Setback → Conflict** outcomes when acting within that domain. You still succeed with consequences, but you don't fail.

**Example:** A master swordsman with Expertise: Heavy Blades rolls Setback against an armored foe. Expertise converts it to Conflict—the attack lands (mark Harm) but at a cost (mark Stress).

*(See Chapter 3: Characters for full Expertise rules)*
```

**B. 01-introduction.md**
- **Location:** After line 87 (Traits section)
- **Add:**
```markdown
**Expertise:** Some Talents grant Expertise in a domain (e.g., "Expertise: Stealth and Thievery"). When you act within your Expertise domain and roll Setback, the outcome becomes Conflict instead. This represents your mastery—you succeed even under pressure, though it may cost you.
```

**C. 02-core-mechanics.md**
- **Location:** After line 213 (Pool Calculations section)
- **Add full Expertise section:**
```markdown
## Expertise

**Expertise** represents mastery in a specific domain. When you take an action within your Expertise and your final outcome (after applying all Complications) would be **Setback**, the outcome becomes **Conflict** instead.

**Key Points:**
- Expertise applies AFTER Complications reduce outcome (see Resolution Order Algorithm, Chapter 4)
- Expertise does NOT protect against Disaster outcomes
- Expertise does NOT reduce Consequence severity—you still mark the same Stress/Conditions
- Expertise converts failure → success, but at a cost

**Example Expertise Domains:**
- Heavy Blades (combat with greatswords, longswords)
- Stealth and Deception (sneaking, lying, disguises)
- Your chosen Sphere (Sage Specialist only)
- Healing magic (Mystic with Healing domain)

**Example:**
> Kael (Expertise: Heavy Blades) attacks an armored knight with 2 Complications.
> - Rolls: Success (any 6)
> - After Complications: Success → Conflict → Setback
> - **Expertise converts:** Setback → Conflict
> - **Result:** Marks 1 Harm + suffers Minor Consequence (1 Stress)
> - Kael's blow lands despite the armor, but he strains to penetrate the defense.

*(See Chapter 3: Characters for Expertise Talents)*
```

**Action Items:**
- [ ] Add Expertise to README.md (after line 62)
- [ ] Add Expertise to 01-introduction.md (after line 87)
- [ ] Add full Expertise section to 02-core-mechanics.md (after line 213)

---

### 2.2 Add Complication Tags to Overview Sections

**Problem:** The 9 Complication tags (Resilient, Warded, Elusive, Stealthy, Alert, Complex, Resolute, Legendary, Deadly) aren't mentioned in overview files.

**Files to Update:**

**A. README.md**
- **Location:** Line 64-76 (Momentum & Complications section)
- **Replace current Complications paragraph with:**
```markdown
**Complications** reduce outcome by -1 tier (Triumph → Success → Conflict → Setback → Disaster)
- Unlimited stacking
- Source: Challenge Complications (enemy defenses represented by tags)
- Negate with: Act with Potency (ignore 1), Talents, Triumph

**Common Complication Tags:**
- **Resilient** — Hinders actions that try to harm, damage, or destroy
- **Warded** — Hinders magical attacks and effects
- **Elusive** — Hinders attacks (physical or magical)
- **Stealthy** — Hinders attempts to detect, track, or perceive
- **Alert** — Hinders stealth, ambush, or deception
- **Resolute** — Hinders persuasion, intimidation, or mental influence
- **Deadly** — Increases Consequence severity by 1 tier when you fail
- **Legendary** — Reduces outcome by 2 tiers (double Complication)
- **Complex** — Hinders attempts to solve, unlock, or understand

*(See Chapter 6: Challenges for complete Complication system)*

**Triumph ignores all Complications.**
```

**B. 01-introduction.md**
- **Location:** After line 50 (first Complication mention)
- **Add:**
```markdown
Challenges may have **Complication tags** that hinder specific actions:
- **Resilient** (hard to damage), **Elusive** (hard to hit), **Alert** (hard to deceive)
- **Warded** (magically protected), **Resolute** (strong-willed), **Deadly** (dangerous when you fail)
- See Chapter 6: Challenges for the complete tag system
```

**Action Items:**
- [ ] Update README.md Complications section (lines 64-76)
- [ ] Add Complication tags to 01-introduction.md (after line 50)

---

### 2.3 Consolidate Duplicate Sections

**Problem:** Key concepts explained 2-3 times within same files, creating bloat.

**Files to Fix:**

**A. 04-action-resolution.md - Consolidate Triumph Explanations**

**Locations:** Lines 167-174, 177-188, 1029-1033

**Fix:**
- Keep **lines 167-174** (first comprehensive explanation)
- Delete **lines 177-188** (redundant)
- Keep **lines 1029-1033** (Quick Reference - but convert to table format only)

**B. 04-action-resolution.md - Merge Progress Tracks Sections**

**Locations:** Lines 437-492 (detailed), Lines 770-801 (duplicate)

**Fix:**
- Keep **lines 437-492** (main explanation)
- Delete **lines 770-801** (duplicate detail)
- Add cross-reference at line 770: "*(See Progress Tracks section, line 437)*"

**C. 07-gm-guide.md - Merge Soft/Hard Move Explanations**

**Locations:** Lines 33-59 (first), Lines 100-151 (GM Moves section)

**Fix:**
- Keep **lines 33-59** (Telegraph danger, then follow through)
- **Lines 100-151:** Remove redundant definition, keep only the Suspense/Impact/Challenge categorization
- Change line 100 to: "GM Moves fall into three categories (see 'Telegraph danger, then follow through' above):"

**D. advancement.md - Consolidate Progression Summaries**

**Locations:** Lines 7-20 (Level Progression Table), Lines 24-48 (Power Curve Summary), Lines 494-512 (Quick Reference)

**Fix:**
- Expand **Level Progression Table** (lines 7-20) to include all details from Power Curve Summary
- Delete **Power Curve Summary** (lines 24-48)
- Keep **Quick Reference** (lines 494-512) but as formulas only, remove prose

**Updated Level Progression Table:**
```markdown
| Level | Approaches | Talents | Traits | Rank | Gain | Notes |
|-------|------------|---------|--------|------|------|-------|
| **1** | 3/2/1/1/0 (7) | 2 | 3 | 1 | **Start** | Choose Calling (Core + 1 secondary) |
| **2** | 3/3/1/1/0 (8) | 3 | 3 | 1 | +1 Approach (cap 2), +1 Talent | |
| **3** | 3/3/2/1/0 (9) | 3 | 3 | 1 | +1 Approach (cap 3) | |
| **4** | 4/3/2/1/0 (10) | 4 | 3 | **2** | **Rank 2**, +1 Approach (cap 4), +1 Talent | **Seasoned Adventurers** |
...
```

**Action Items:**
- [ ] Consolidate Triumph explanations in 04-action-resolution.md
- [ ] Merge Progress Tracks sections in 04-action-resolution.md
- [ ] Merge Soft/Hard Move explanations in 07-gm-guide.md
- [ ] Consolidate progression summaries in advancement.md

---

### 2.4 Reorganize GM Guide Structure

**Problem:** Related content scattered; Soft/Hard Moves explained twice.

**File:** `07-gm-guide.md`

**Restructure:**

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

**Proposed Order:**
1. GM Principles (9-31)
2. **GM Moves Framework** (consolidated 33-158)
   - Telegraph danger basics
   - Three Tiers (Suspense/Impact/Challenge)
   - Vigilance pattern (move from line 160)
3. **Session Structure** (move from line 427)
4. Spotlight Management (202-231)
5. **Structured Scene Tools** (group together)
   - Challenges (452-494)
   - Battlegrounds (525-550)
   - Clocks & Tracks (593-616)
6. **Optional Mechanics** (group together)
   - Pacing Combat (360-383)
   - Threat Pool (385-400)
   - Tangles (554-590)

**Benefits:**
- Core GM moves grouped together
- Session/scene tools grouped logically
- Optional mechanics clearly separated

**Action Items:**
- [ ] Reorganize 07-gm-guide.md sections
- [ ] Update internal cross-references after reorganization

---

## Phase 3: Clarity Improvements (Week 3)
**Goal:** Fix confusing sections, add missing context  
**Estimated Time:** 6-8 hours  
**Files Affected:** 6 files

### 3.1 Fix Introduction Timing Issues

**File:** `01-introduction.md`

**A. Add Edge/Bane Cap Earlier**
- **Current:** Line 70 (late in document)
- **Fix:** Add cap to line 46 when first introduced
```markdown
**Edge/Bane:** Situational advantages (Edge) or complications (Bane) add or remove d6 from your pool before rolling **(cap: ±2d)**. These cancel each other 1:1.
```

**B. Clarify Assess Questions**
- **Line 31:** Current: "Ask specific questions"
- **Fix:** "Ask 2 questions about the situation (1 question on Conflict)"

**C. Add Recall Clarifying Question**
- **Line 32:** Current: "GM tells you something useful"
- **Fix:** "GM tells you something useful, and you may ask 1 clarifying question"

**D. Clarify Act with Potency as Choose-One**
- **Line 59:** Current: Lists three effects without clarifying
- **Fix:** "**Choose one:** gain 1 Edge (+1d), ignore 1 Complication, OR enable an extraordinary feat"

**E. Lead Conditions with Fiction**
- **Lines 68-74:** Currently mechanics-first
- **Fix:** Start with "**Conditions** are temporary impairments (Wounded, Frightened, Poisoned) that hinder your actions. Each Condition..."

**Action Items:**
- [ ] Add Edge/Bane cap to line 46
- [ ] Clarify Assess questions at line 31
- [ ] Add clarifying question to Recall at line 32
- [ ] Clarify Act with Potency at line 59
- [ ] Rewrite Conditions section (lines 68-74) to lead with fiction

---

### 3.2 Define Terms Before Using

**Files:** `01-introduction.md`, `02-core-mechanics.md`

**A. Define "Track" and "Mark" (01-introduction.md)**

**Location:** Before line 27 (action descriptions)

**Add:**
```markdown
### Progress Tracks

Extended challenges use **Progress Tracks** (4-8 tick boxes) representing obstacles, enemy endurance, or social resistance:
- **Harm Track:** Physical damage to enemies or obstacles
- **Will Track:** Social/mental resistance
- **Obstacle Track:** Environmental challenges

When you succeed at certain actions, you **mark** (fill in) ticks on the appropriate track. When the track fills completely, you overcome the challenge.

*(See Chapter 4 for complete track rules)*
```

**B. Define "Primary Effect" (02-core-mechanics.md)**

**Location:** Before line 38 (first use of "Primary Effect")

**Add:**
```markdown
Each Action has a **Primary Effect**—what it accomplishes when you succeed. The Primary Effect is always free; you don't need to spend Momentum or invoke Traits to get it.
```

**Action Items:**
- [ ] Add track/mark definitions to 01-introduction.md (before line 27)
- [ ] Add Primary Effect definition to 02-core-mechanics.md (before line 38)

---

### 3.3 Simplify Complex Procedures

**A. Rewrite Stress Overflow (05-resilience.md lines 96-106)**

**Current:** Complex nested rules with exception mid-flow

**Rewrite as numbered steps:**
```markdown
## Stress Overflow

When you would mark Stress but your Stress Track is full:

**Step 1: Check for Resist Consequence**
- If you have Momentum available, you may spend 1 Momentum to **Resist Consequence** (roll Defy to reduce the incoming Consequence)
- If you successfully resist, you may avoid the overflow entirely

**Step 2: Choose Your Path** (if overflow still applies)

You must choose one:

**A) Take a Burden**
- Gain a persistent **Burden** (Condition that doesn't clear on short rest)
- The Burden's tier depends on the incoming Consequence:
  - Minor Consequence → Burden 1
  - Major Consequence → Burden 2
  - Severe Consequence → Burden 3
- Keep your Stress Track full

**B) Be Taken Out**
- Clear your Stress Track completely
- You're removed from the scene (unconscious, captured, or otherwise incapacitated)
- The GM narrates what happens

**Special Case:** If you already have a Burden of the same name, it refreshes to whichever tier is higher (existing or new).
```

**B. Break Up Secondary Effects (04-action-resolution.md lines 348-434)**

**Current:** 86 lines of mixed content

**Fix:** Add subsection headers:
```markdown
## Secondary Effects (from Traits)

### Core Categories (353-372)
[Greater Effect, Secondary Effect, Build Momentum content]

### Inflicting Conditions on Enemies (376-405)
[Condition infliction rules]

### GM Guidance: Adjudicating Secondary Effects (407-434)
[GM guidance section]
```

**Action Items:**
- [ ] Rewrite Stress Overflow as numbered steps (05-resilience.md)
- [ ] Add subsection headers to Secondary Effects (04-action-resolution.md)

---

### 3.4 Update Consequence Terminology

**A. README.md - Replace Stress with Consequence Tiers**

**Line 60:** Current: "reduce/avoid any consequence (Stress, Condition, or narrative setback)"

**Fix:** "reduce/avoid any Consequence (Minor/Major/Severe: Impact Moves, Stress, Conditions, narrative setbacks)"

**B. 02-core-mechanics.md - Add Consequence Tier Terminology**

**After line 123 (outcome tiers), add:**
```markdown
### Consequence Tiers

Outcomes map to **Consequence tiers**:
- **Conflict** → **Minor Consequence** (GM makes soft Impact Move: mark 1 Stress, lose position, create complication)
- **Setback** → **Major Consequence** (GM makes hard Impact Move: mark 2 Stress, serious danger, objective setback)
- **Disaster** (optional) → **Severe Consequence** (Taken Out, Burden inflicted, catastrophic failure)

*(See Chapter 4 for complete Impact Move lists)*
```

**Action Items:**
- [ ] Update README.md Resist Consequence description (line 60)
- [ ] Add Consequence tier section to 02-core-mechanics.md (after line 123)

---

## Phase 4: Minor Polish (Week 4)
**Goal:** Remove remaining redundancies, standardize formatting  
**Estimated Time:** 3-4 hours  
**Files Affected:** 10 files

### 4.1 Remove Within-File Redundancies

**A. README.md**
- [ ] Lines 49, 56, 66-68: Consolidate three "Build Momentum" explanations into one (keep line 49, reference it at 56 and 66)
- [ ] Lines 42, 75: Remove duplicate "Triumph ignores Complications" (keep 42, delete 75)
- [ ] Lines 62, 125: Momentum cap mentioned twice (keep 62, remove from 125)

**B. 01-introduction.md**
- [ ] Lines 70, 74: Pool modifier cap stated twice (keep 70, simplify 74 to just the example)
- [ ] Lines 72-73 + 73-74: Condition clearing mechanics + examples (combine into one paragraph with inline examples)
- [ ] Lines 62, 87: Momentum cap stated twice (keep 62, delete 87 reference)

**C. 05-resilience.md**
- [ ] Lines 65-69, 125-127, 257: Edge/Bane cap explained three times (keep 65-69, delete others, add cross-reference)
- [ ] Lines 42, 119, 235: Short rest clearing stated three times (keep 42, cross-reference at 119 and 235)
- [ ] Lines 96-106, 262-268: Burden gaining via overflow explained twice (keep 96-106 as detailed, make 262-268 a brief cross-reference)

**D. challenge-creation.md**
- [ ] Lines 9-159 and 1300-1443: Full duplication of Quick Challenge Creation Recipe (keep 9-159 detailed, convert 1300-1443 to pure formula/table format)
- [ ] Lines 162-214 and 1446-1498: Encounter Budgeting duplicated (same approach)
- [ ] Lines 132-148, 336-346, 1427-1443: Expected rolls tables appear 3 times (keep one authoritative version, cross-reference others)

---

### 4.2 Standardize Quick Reference Sections

**Problem:** Quick Reference sections currently repeat full prose explanations instead of being pure reference.

**Files to Update:**
- `02-core-mechanics.md` lines 313-345
- `04-action-resolution.md` lines 1008-1058
- `challenge-creation.md` lines 1300-1638
- `gm-cheat-sheet.md` (already good - use as model)

**Approach:**
- Convert to **table/formula format only**
- Remove all explanatory prose (keep in main body)
- Use format like `gm-cheat-sheet.md` (concise, scannable)

**Example Transformation:**

**Before (prose):**
```markdown
**Conflict (any 4-5)** — You succeed at your Primary Effect but suffer a Minor Consequence. The GM makes a soft Impact Move: mark 1 Stress, lose position, or introduce a complication.
```

**After (table):**
```markdown
| Outcome | Effect | Consequence |
|---------|--------|-------------|
| **Conflict** (4-5) | Success + Primary Effect | Minor (soft Impact Move: 1 Stress, lose position, complication) |
```

---

### 4.3 Add Cross-References

**A. First Complication Mention**
- `01-introduction.md` line 50: Add "*(see Chapter 6: Challenges for Complication tags)*"
- `02-core-mechanics.md` line 123: Add "*(see Chapter 6 for complete Complication system)*"

**B. First Track Mention**
- `01-introduction.md` lines 27-29: Add "*(see Chapter 4 for complete track rules)*" after action descriptions
- `02-core-mechanics.md` line 38: Add "*(tracks detailed in Chapter 4)*"

**C. Momentum Cap Talent Reference**
- `03-characters.md` line 137: Change to "Momentum Cap: 2 *(can be increased to 3 via Relentless Talent, see line 352)*"

**D. Expertise Reference**
- `02-core-mechanics.md` line 203: Change parenthetical to "*(see Expertise section below, line [X])*"

---

### 4.4 Minor Terminology Consistency

**A. Standardize Track Terminology**
- **Decision:** Use "Progress track" throughout
- **Files:** `README.md`, `01-introduction.md`, `02-core-mechanics.md`
- **Find/Replace:** "Obstacle track" → "Progress track" (when referring generically)
- **Keep:** Specific names (Harm track, Will track) when referring to track types

**B. Standardize Burden Capitalization**
- **File:** `05-resilience.md`
- **Rule:** Always capitalize "Burden" when referring to the game term
- **Find/Replace:** Check all instances, ensure consistent capitalization

**C. Verify "Hinders" Consistency**
- **All files:** Ensure Complication descriptions use "hinders" not "blocks" or "prevents"
- **Already correct** per review, but verify: `grep -r "blocks\|prevents" heroic-fantasy-rpg/*.md`

---

## Verification Checklist

After completing all phases, run these checks:

### Terminology Verification
```bash
# Check for outdated action names
grep -r "Defy\|Clash\|Talk\|Sense\|Know" heroic-fantasy-rpg/*.md | grep -v "Defy +" | grep -v "# Defy"

# Check for invalid Approaches
grep -r "Wits\|Intelligence\|Might" heroic-fantasy-rpg/*.md

# Check for "blocks" terminology (should be "hinders")
grep -r "blocks\|blocking" heroic-fantasy-rpg/*.md

# Check for Offense tags (should not exist)
grep -r "Offense" heroic-fantasy-rpg/*.md
```

### Structure Verification
```bash
# Check for duplicate section headers
grep -r "^## " heroic-fantasy-rpg/*.md | sort | uniq -c | sort -rn

# Find remaining Disaster references (should be minimal)
grep -r "Disaster" heroic-fantasy-rpg/*.md
```

### Cross-Reference Verification
```bash
# Find broken chapter references
grep -r "Chapter [0-9]" heroic-fantasy-rpg/*.md | grep -v ".md:.*Chapter"

# Find references to lines that may have shifted
grep -r "line [0-9]" heroic-fantasy-rpg/*.md
```

---

## Success Criteria

**Phase 1 Complete:**
- [ ] No outdated action names remain (Defy/Clash/Talk/Sense/Know)
- [ ] Tier/Rank relationship clarified or unified
- [ ] Disaster removed or properly integrated as optional
- [ ] No invalid Approach references
- [ ] Calling list matches across all files

**Phase 2 Complete:**
- [ ] Expertise explained in README, Introduction, Core Mechanics
- [ ] Complication tags listed in overview files
- [ ] No duplicate Triumph/Progress Tracks/Soft-Hard Move explanations
- [ ] GM Guide reorganized logically

**Phase 3 Complete:**
- [ ] Edge/Bane cap mentioned when first introduced
- [ ] Tracks and Primary Effect defined before use
- [ ] Stress Overflow rewritten as clear steps
- [ ] Consequence tier terminology consistent

**Phase 4 Complete:**
- [ ] No within-file redundancies (Build Momentum, caps, etc.)
- [ ] Quick Reference sections are tables, not prose
- [ ] Cross-references added throughout
- [ ] Terminology standardized (tracks, Burden, hinders)

---

## Estimated Timeline

**Week 1 (Phase 1):** 4-6 hours
- **Day 1-2:** Action terminology find/replace (1-2 hours)
- **Day 3:** Tier/Rank decision + implementation (2-3 hours)
- **Day 4:** Disaster resolution + Wits fix + Calling list (1 hour)

**Week 2 (Phase 2):** 8-12 hours
- **Day 1-2:** Add Expertise and Complication tags (3-4 hours)
- **Day 3-4:** Consolidate duplicate sections (3-4 hours)
- **Day 5:** Reorganize GM Guide (2-4 hours)

**Week 3 (Phase 3):** 6-8 hours
- **Day 1-2:** Fix Introduction timing issues (2-3 hours)
- **Day 3:** Define terms before using (1-2 hours)
- **Day 4-5:** Simplify complex procedures + update terminology (3 hours)

**Week 4 (Phase 4):** 3-4 hours
- **Day 1:** Remove within-file redundancies (1-2 hours)
- **Day 2:** Standardize Quick Reference sections (1 hour)
- **Day 3:** Add cross-references + terminology consistency (1 hour)

**Total:** 21-30 hours over 4 weeks

---

## Notes for Implementation

1. **Backup First:** Create git branch before starting: `git checkout -b documentation-fix-2026-06`

2. **Work in Order:** Complete Phase 1 before Phase 2—terminology must be correct before restructuring.

3. **Test After Each Phase:** Read through affected files to ensure changes make sense in context.

4. **Update Line Numbers:** After Phase 2 reorganization, many line numbers in this plan will shift. Update the plan or work from section headers instead.

5. **Get Feedback:** After Phase 1, consider playtesting to verify clarity before proceeding to structural changes.

6. **Commit Frequently:** Commit after each major fix with descriptive messages (e.g., "Fix action terminology in character creation")

---

## Questions for Review

Before starting implementation, please decide:

1. **Tier vs Rank (Section 1.2):** Option A (keep Tier 0-4, add mapping) or Option B (replace with Rank names)?

2. **Disaster Outcome (Section 1.3):** Option A (remove entirely) or Option B (keep as optional edge case)?

3. **Calling List (Section 1.5):** Option A (Vanguard/Hunter valid) or Option B (Wanderer valid)?

4. **Scope:** Approve all 4 phases, or start with Phase 1 only and reassess?

---

**End of Fix Plan**
