# Rules Drift Analysis
## Comparing New Chapters vs. Source Documents

**Date:** 2026-06-30  
**Purpose:** Identify any discrepancies between reorganized chapters and source material

---

## Chapter 1: The Action Roll

**Source files:** 02-core-mechanics.md, 04-action-resolution.md

### ✅ Matches Source
- Dice pool formula (Approach + Boons - Banes)
- Four outcomes (Triumph/Success/Conflict/Setback)
- Pool minimum (0d → 2d take lowest) ✅ **CONFIRMED**
- Boon/Bane ±2 cap
- Expertise (Setback → Conflict)
- Edge (ignore Complications)
- Triumph requires actual double 6s (not upgraded)

### ⚠️ Potential Issues Found

**1. Strong Vantage Boons**
- **Source (vantage.md, line 30):** "Roll with 1 Boon (advantageous position)"
- **Source (02-core-mechanics.md, line 37):** "Roll with 1 Boon (or 2 Boons in exceptional circumstances)"
- **Our Chapter 1:** States "Roll with 1 Boon" only
- **Status:** ❓ **UNCLEAR** - Should we mention "or 2 Boons in exceptional circumstances"?
- **Recommendation:** Add note about exceptional circumstances granting 2 Boons

**2. Probability Tables**
- **Source:** Not found in 02-core-mechanics.md or 04-action-resolution.md
- **Our Chapter 1:** Includes probability tables
- **Status:** ✅ **ENHANCEMENT** - We added useful reference tables

---

## Chapter 2: Taking Action

**Source files:** 02-core-mechanics.md, 04-action-resolution.md

### ✅ Matches Source
- Five Actions (Defy, Clash, Talk, Sense, Know) with correct descriptions
- Five Approaches (Daring, Grace, Charm, Cunning, Spirit)
- Starting array (3/2/1/1/0)
- Approach maximum (5)
- Vantage 5-tier system (Certain/Strong/Standard/Limited/Impossible)
- High Stakes (optional, +1 consequence tier)

### ⚠️ Potential Issues Found

**1. Strong Vantage Description**
- **Source (02-core-mechanics.md, line 36-37):**
  ```
  **Strong** — Golden opportunity, dominant advantage:
  - Roll with 1 Boon (or 2 Boons in exceptional circumstances)
  ```
- **Our Chapter 2, line 317:** "**Roll with 1 Boon** (advantageous position)"
- **Status:** ⚠️ **INCONSISTENT** - Missing "(or 2 Boons in exceptional circumstances)"
- **Recommendation:** Add this to Chapter 2

**2. Vantage Examples**
- **Source:** Has more detailed examples in vantage.md
- **Our Chapter 2:** Has briefer examples, points to Vantage Reference (Part 3)
- **Status:** ✅ **INTENTIONAL** - We're cross-referencing to avoid duplication

---

## Chapter 3: Consequences

**Source files:** 04-action-resolution.md

### ✅ Matches Source
- Consequence tiers (Minor/Major/Severe)
- Complication mechanics (reduce outcome by 1 tier)
- Resolution order (roll → Complications → Expertise → consequences)
- Progress Track types (Harm, Will, Obstacle, Countdown)
- Track sizes by Tier (0=0, 1=2, 2=4, 3=6, 4=8)
- Resist Consequence (spend Momentum, roll Defy)
- Triumph ignores all Complications
- Expertise doesn't protect against Disaster

### ⚠️ Potential Issues Found

**1. Minor Consequence - "Lose position" wording**
- **Our Chapter 3, line 50:** "Lose position or advantage (can shift Vantage down)"
- **Source:** Doesn't explicitly say "can shift Vantage down"
- **Status:** ✅ **CLARIFICATION** - This is a helpful addition, not drift

**2. Complication Tags**
- **Source (06-challenges.md):** Has 8 tags
- **Our Chapter 3:** Lists all 8 tags correctly
- **Status:** ✅ **CORRECT**

**3. Marking Tracks on Outcomes**
- **Source (04-action-resolution.md, line 536-540):**
  ```
  - **Setback:** Mark 0 ticks + you face Major Consequence
  - **Conflict:** Mark 1 tick + you face Minor Consequence  
  - **Success:** Mark 1 tick
  - **Triumph:** Mark 1 tick + gain 1 Momentum + ignore all Complications
  ```
- **Our Chapter 3:** Matches this exactly
- **Status:** ✅ **CORRECT**

---

## Missing or Incomplete Content

### Content We Haven't Migrated Yet
These are in source files but not in our chapters yet (by design—they belong in later chapters):

**From Chapter 4 (Resilience):**
- Push Yourself (mark Stress for Boon) - mentioned but full rules in Ch 4
- Assist (mark Stress to grant Boon) - mentioned but full rules in Ch 4
- Stress track (5 boxes)
- Conditions system
- Burdens
- Taken Out
- Short/Long Rest

**From Chapter 5 (Momentum):**
- Create an Opening (1 Momentum → 1 Boon + 1 Edge)
- Resist Consequence (full procedure)
- Momentum cap (2, raised to 3 by Talent)
- Build Momentum (Trait effect)
- Tangles (optional)

**From Chapter 6 (Traits):**
- Trait invocation (Conflict or better)
- Special Effects (Greater Effect, Secondary Effect, Build Momentum)
- One Trait per roll rule

---

## Cross-Reference Accuracy

### References in Our Chapters

**Chapter 1 references:**
- Chapter 2 (for Actions, Approaches, Vantage) ✅
- Chapter 3 (for Complications) ✅
- Chapter 4 (for Resilience) ✅
- Chapter 5 (for Momentum) ✅
- Chapter 6 (for Traits) ✅

**Chapter 2 references:**
- Chapter 1 (for dice mechanics) ✅
- Part 3 (for Vantage Reference) ✅
- Chapter 13 (for Challenges) ✅

**Chapter 3 references:**
- Chapter 1 (for Edge, Expertise) ✅
- Chapter 5 (for Momentum, Resist Consequence) ✅
- Chapter 13 (for Challenge design) ✅
- Part 3 (for Vantage Reference) ✅

**Status:** ✅ **CORRECT** - All cross-references are accurate

---

## Key Findings Summary

### 🔴 Issues Requiring Fixes

**1. Strong Vantage Missing Exceptional Circumstances**
- **Location:** Chapter 2, line 317
- **Current:** "Roll with 1 Boon (advantageous position)"
- **Should be:** "Roll with 1 Boon (or 2 Boons in exceptional circumstances)"
- **Also affects:** Chapter 1 (should mention this too)

---

### ✅ Intentional Differences (Not Drift)

1. **Probability tables added** - Enhancement, not drift
2. **Briefer examples with cross-references** - Avoiding duplication
3. **"Can shift Vantage down" clarification** - Helpful addition
4. **Reframed around "Action Roll"** - Better terminology

---

### 📋 Content Status by Chapter

| Chapter | Status | Notes |
|---------|--------|-------|
| Chapter 1 | ⚠️ Minor issue | Missing "exceptional circumstances" for Strong Vantage |
| Chapter 2 | ⚠️ Minor issue | Missing "exceptional circumstances" for Strong Vantage |
| Chapter 3 | ✅ Complete | No drift detected |

---

## Recommendations

### Immediate Fixes Needed

1. **Add to Chapter 1 (The Action Roll), Boons section:**
   ```
   **Strong Vantage:** Grants 1 Boon (or 2 Boons in exceptional circumstances)
   ```

2. **Update Chapter 2 (Taking Action), Strong Vantage section:**
   ```
   **Strong** — Golden opportunity, dominant advantage  
   - **Roll with 1 Boon** (or 2 Boons in exceptional circumstances)
   ```

### Future Verification Needed

Once we complete Chapters 4-6, verify:
- Push Yourself mechanics match 05-resilience.md
- Assist mechanics match 02-core-mechanics.md
- Momentum spending matches 04-action-resolution.md
- Trait Special Effects match 04-action-resolution.md
- Conditions system matches 05-resilience.md

---

## Conclusion

**Overall Status:** 🟢 **GOOD**

Only **one minor issue** found across all three chapters:
- Strong Vantage should mention "or 2 Boons in exceptional circumstances"

Everything else is either:
- ✅ Accurate to source
- ✅ Intentional enhancement (probability tables)
- ✅ Intentional structure (cross-referencing to avoid duplication)

The reorganization is proceeding well with minimal drift.
