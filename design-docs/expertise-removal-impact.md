# Removing Expertise: Math & Impact Analysis

## Current State: How Expertise Actually Works

**Expertise converts Setback → Conflict when acting in your domain.**

Critical limitation: **Expertise does NOT convert Disaster.** It only triggers when your final outcome (after Complications) is exactly Setback.

---

## The Math: When Does Expertise Actually Help?

### Against 0 Complications (Undefended Enemy)

**Without Expertise (2d6):**
- Triumph: 3%
- Success: 31%
- Conflict: 25%
- **Setback: 44%** ← You fail, make no progress

**With Expertise (2d6):**
- Triumph: 3%
- Success: 31%
- Conflict: 69% (25% rolled + 44% converted)
- Setback: 0%

**Expertise helps 44% of the time** (converts all Setbacks)

**Success rate:** 59% → 59% (Triumph + Success unchanged, but Conflict increases)

---

### Against 1 Complication (Standard Enemy)

**Raw Roll → After Complication → After Expertise:**

- Triumph (3%) → **Triumph** (ignores Complications)
- Success (31%) → Conflict → **Conflict** (make progress)
- Conflict (25%) → Setback → **Conflict** (Expertise saves)
- Setback (44%) → Disaster → **Disaster** (Expertise can't help)

**With Expertise: Make progress 59% of the time** (3% + 31% + 25%)

**Without Expertise (2d6):**
- Triumph (3%) → Triumph
- Success (31%) → Conflict (make progress)
- Conflict (25%) → Setback (NO progress)
- Setback (44%) → Disaster (NO progress)

**Without Expertise: Make progress 34% of the time** (3% + 31%)

**Expertise helps 25% of the time** (converts rolled Conflicts that became Setback)

---

### Against 2 Complications (Heavily Defended Enemy)

**Raw Roll → After Complications → After Expertise:**

- Triumph (3%) → **Triumph**
- Success (31%) → Conflict → Setback → **Conflict** (Expertise saves)
- Conflict (25%) → Setback → Disaster → **Disaster** (can't help)
- Setback (44%) → Disaster → Disaster → **Disaster** (can't help)

**With Expertise: Make progress 34% of the time** (3% + 31%)

**Without Expertise: Make progress 34% of the time** (3% + 31%)

**Expertise helps 31% of the time** (only on rolled Success)

**But the success rate is the SAME** because against 2 Complications, only Triumph and Success make progress regardless.

---

### Against 3 Complications (Edge-Gated Enemy)

- Everything except Triumph → Disaster
- Expertise can't convert Disaster
- **Expertise helps 0% of the time**

---

## Key Finding: Expertise Is Weakest When You Need It Most

| Complications | Without Expertise | With Expertise | Difference |
|---------------|-------------------|----------------|------------|
| 0 | 59% success | 59% success | **+0%** (but more Conflict vs Setback) |
| 1 | 34% success | 59% success | **+25%** |
| 2 | 34% success | 34% success | **+0%** |
| 3 | 3% success | 3% success | **+0%** |

**Expertise only helps significantly against 1 Complication.** Against 0, 2, or 3+ Complications, it barely matters for success rate.

---

## If We Remove Expertise: Compensation Options

### Option A: No Compensation

**Impact:** Characters fail 44% of the time (rolled Setback) instead of ~0% in their specialty.

Against 1 Complication: 34% success → that's a 25% drop.

**This is brutal.** Too punishing.

---

### Option B: Make Traits Grant +1 Boon

**3d6 pool (2 base + 1 from Trait):**
- Triumph: 9%
- Success: 42%
- Conflict: 26%
- Setback: 23%

**Against 0 Complications:**
- Make progress: 77% (everything except Setback)
- vs. 59% with Expertise
- **Better than Expertise!**

**Against 1 Complication:**
- Triumph (9%) → Triumph
- Success (42%) → Conflict
- Conflict (26%) → Setback
- Setback (23%) → Disaster

**Make progress 51%** (9% + 42%)
- vs. 59% with Expertise
- **Slightly worse, but close**

**Against 2 Complications:**
- Triumph (9%) → Triumph
- Success (42%) → Conflict → Setback
- Conflict (26%) → Setback → Disaster
- Setback (23%) → Disaster → Disaster

**Make progress 51%** (9% + 42%)
- vs. 34% with Expertise
- **Much better than Expertise!**

---

### Math Summary: +1 Boon vs. Expertise

| Complications | 2d6 + Expertise | 3d6 (no Expertise) |
|---------------|-----------------|-------------------|
| 0 | 59% | **77%** (+18%) |
| 1 | 59% | **51%** (-8%) |
| 2 | 34% | **51%** (+17%) |
| 3 | 3% | **9%** (+6%) |

**+1 Boon is better than Expertise in most situations!**

The only place it's worse is against 1 Complication (51% vs 59%).

---

## Downstream Effects of Removing Expertise

### 1. Against 1 Complication, Specialists Struggle More

**The scenario you asked about:** A character faces a Resilient enemy (1 Complication) they can't bypass.

**Current system (2d6 + Expertise):** 59% success rate
**New system (3d6, no Expertise):** 51% success rate

**That's an 8% drop.** Not catastrophic, but noticeable over repeated rolls.

**Example:** Fighting an armored knight. You need 4 progress to defeat them.

- **With Expertise:** Average 1.51 progress per roll → ~2.6 rolls to win
- **Without Expertise:** Average 1.42 progress per roll → ~2.8 rolls to win

You need ~1 extra action on average. That's 1-2 more Stress marked from Consequences.

---

### 2. Momentum Economy Changes

**Create an Opening** (1 Momentum = +1 Boon + 1 Edge) becomes MORE valuable.

**Current system:**
- Edge cancels the Complication → you face it as 0 Complications
- With Expertise: 59% success rate at 2d6 → 59% with Edge at 2d6

**New system:**
- Edge cancels the Complication → you face it as 0 Complications
- Without Expertise: 51% success rate at 3d6 → **77% with Edge** at 3d6

So Create an Opening becomes MORE powerful without Expertise, because:
1. You're compensated with +1 Boon (now at 3d6)
2. Edge removes the Complication
3. At 3d6 vs. 0 Complications, you succeed 77% of the time

**This makes Momentum MORE important, which might be desirable** (more decision points).

---

### 3. "Unstoppable Expert" Fantasy Weakens

**Current:** A master swordsman with Expertise: Heavy Blades almost never fails at swordplay (converts Setback → Conflict).

**New:** A master swordsman invokes their Trait, gets +1 Boon, but still rolls Setback 23% of the time.

**Is this a problem?** Depends on your design goals.

- If you want "masters are reliable," Expertise is important
- If you want "even masters face uncertainty," removing Expertise is fine

---

### 4. Character Building Simplifies

**Current:** Players track "Expertise: Heavy Blades, Expertise: Intimidation" separately from Traits/Talents.

**New:** Traits just work better (grant +1 Boon). No separate tracking.

This is cleaner character design.

---

## Alternative: Change What Expertise Does

Instead of removing Expertise, **change it to something simpler that happens earlier in resolution.**

### Option: Expertise = +1 Edge in Your Domain

**Current:** Expertise converts Setback → Conflict (step 9, post-Complications)

**New:** Expertise grants +1 Edge when acting in your domain (step 7, cancels Complications)

**Math against 1 Complication:**

With Expertise = +1 Edge:
- Automatically cancel the Complication (via Expertise Edge)
- Your raw roll becomes your final outcome
- 2d6 pool:
  - Triumph: 3%
  - Success: 31%
  - Conflict: 25%
  - Setback: 44%

Make progress: 59% (everything except Setback)

**This is identical to current Expertise math against 1 Complication!**

**Math against 2 Complications:**

With Expertise = +1 Edge:
- Cancel 1 Complication, 1 remains
- Triumph: 3% → Triumph
- Success: 31% → Conflict
- Conflict: 25% → Setback
- Setback: 44% → Disaster

Make progress: 34%

**Also identical to current Expertise!**

---

### Why This Is Better

**Expertise = +1 Edge** is mathematically equivalent to current Expertise, but:

✅ **Happens earlier in resolution** (step 7 vs step 9)
✅ **Feels more proactive** ("I ignore their armor" vs "I failed but I'm a master")
✅ **Consolidates mechanics** (Edge already exists for Create an Opening, Talents)
✅ **Still maintains "unstoppable expert" fantasy** (specialists reliably bypass 1 Complication)

**Resolution flow:**
1. Frame → Pool → Boons/Banes → Roll
2. Raw outcome → **Spend Edge (including +1 from Expertise if applicable)** → Apply Complications → Final outcome

**Expertise becomes "passive Edge source"** instead of a unique outcome conversion mechanic.

---

## My Recommendation: Change Expertise, Don't Remove It

**Don't remove Expertise.** Instead, **redefine it as "+1 Edge in your domain."**

### New Expertise Rule

> **Expertise**
> 
> When you act within your domain of Expertise, you automatically gain **+1 Edge** before Complications apply.
> 
> This Edge cancels 1 Complication, like any other Edge.

### What This Achieves

1. ✅ **Same math** (success rates unchanged)
2. ✅ **Simpler** (Edge already exists, just add +1 to the count)
3. ✅ **Feels more active** (specialists bypass defenses, not convert failures)
4. ✅ **Happens earlier** (step 7 instead of step 9)
5. ✅ **Preserves "reliable specialist" fantasy**

### Character Sheet Changes

**Current:**
- Expertise: Heavy Blades, Expertise: Intimidation

**New:** (exactly the same)
- Expertise: Heavy Blades, Expertise: Intimidation
- But mechanically, it grants +1 Edge instead of converting Setback

---

## Summary Table: Three Options

| Approach | Success vs 1 Complication | Complexity | Specialist Fantasy |
|----------|-------------------------|------------|-------------------|
| **Current (Expertise = convert Setback)** | 59% | 10 steps | Strong |
| **Remove Expertise (Trait = +1 Boon)** | 51% (-8%) | 9 steps | Weakened |
| **Redefine (Expertise = +1 Edge)** | 59% (same) | 9-10 steps | Strong |

---

## Final Recommendation

**Redefine Expertise as "+1 Edge in your domain."**

This keeps the mechanical benefit (specialists reliably bypass 1 Complication) while simplifying the resolution flow (Edge happens at step 7, not a separate step 9).

If you want to go further and ALSO make Traits grant +1 Boon, you'd have:
- **Trait invoked:** +1 Boon (3d6 pool)
- **Expertise in domain:** +1 Edge (cancel 1 Complication)

Against 1 Complication, this would be:
- 3d6 pool, 1 Complication cancelled by Edge
- Raw roll = final outcome
- Success rate: 77%!

That might be too strong, but it would make specialists feel VERY reliable.

---

## Questions for You

1. **Do you want to preserve the "unstoppable expert" fantasy?** (Expertise helps with this)
2. **Is the 8% success drop acceptable?** (51% vs 59% against 1 Complication)
3. **Should specialists bypass Complications (Edge) or be harder to make fail (convert Setback)?**

My instinct: Keep Expertise, redefine it as +1 Edge. Same math, better feel.
