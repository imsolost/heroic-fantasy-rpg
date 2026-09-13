# Expertise Analysis: Higher Dice Pools

## Dice Pool Probabilities

| Pool | Triumph | Success | Conflict | Setback |
|------|---------|---------|----------|---------|
| 2d6 | 3% | 31% | 25% | 44% |
| 3d6 | 9% | 42% | 26% | 23% |
| 4d6 | 13% | 39% | 42% | 6% |
| 5d6 | 20% | 40% | 37% | 3% |

**Key observation:** As pool size increases, Setback chance drops dramatically (44% → 23% → 6% → 3%).

---

## Scenario: Specialist vs. 0 Complications

### Current Expertise (Converts Setback → Conflict)

| Pool | Base Success | With Expertise | Benefit |
|------|-------------|----------------|---------|
| 2d6 | 59% | **100%** | +41% |
| 3d6 | 77% | **100%** | +23% |
| 4d6 | 94% | **100%** | +6% |
| 5d6 | 97% | **100%** | +3% |

**Finding:** Expertise's Setback conversion is MOST valuable at low dice pools. At 4d6+, you rarely roll Setback anyway.

---

### Expertise-as-Edge (Edge wasted, no conversion)

| Pool | Success | vs. Current Expertise |
|------|---------|---------------------|
| 2d6 | 59% | -41% |
| 3d6 | 77% | -23% |
| 4d6 | 94% | -6% |
| 5d6 | 97% | -3% |

**Finding:** At 4d6+, Expertise-as-Edge is nearly identical to current Expertise against undefended enemies (because Setbacks are rare anyway).

---

## Scenario: Specialist vs. 1 Complication

### Current Expertise (Converts Setback after reduction)

| Pool | Raw → After Comp | Final (with Expertise) | Success Rate |
|------|-----------------|----------------------|--------------|
| 2d6 | Apply -1 tier | Convert Setback | 59% |
| 3d6 | Apply -1 tier | Convert Setback | 77% |
| 4d6 | Apply -1 tier | Convert Setback | 94% |
| 5d6 | Apply -1 tier | Convert Setback | 97% |

Calculation for 3d6:
- Triumph (9%) → Triumph (ignores Comp)
- Success (42%) → Conflict
- Conflict (26%) → Setback → **Conflict** (converted)
- Setback (23%) → Disaster

Success = 9% + 42% + 26% = 77%

---

### Expertise-as-Edge (Cancel the Complication)

| Pool | After Edge (0 Comp) | Success Rate |
|------|-------------------|--------------|
| 2d6 | Raw roll | 59% |
| 3d6 | Raw roll | 77% |
| 4d6 | Raw roll | 94% |
| 5d6 | Raw roll | 97% |

**Finding:** IDENTICAL to current Expertise against 1 Complication!

---

## Scenario: Specialist vs. 2 Complications

### Current Expertise (Converts Setback after reduction)

| Pool | After -2 tiers | Final (with Expertise) | Success Rate |
|------|---------------|----------------------|--------------|
| 2d6 | Apply -2 tiers | Convert Setback | 34% |
| 3d6 | Apply -2 tiers | Convert Setback | 51% |
| 4d6 | Apply -2 tiers | Convert Setback | 52% |
| 5d6 | Apply -2 tiers | Convert Setback | 60% |

Calculation for 3d6:
- Triumph (9%) → Triumph (ignores Comps)
- Success (42%) → Conflict → Setback → **Conflict** (converted)
- Conflict (26%) → Setback → Disaster
- Setback (23%) → Disaster

Success = 9% + 42% = 51%

Calculation for 4d6:
- Triumph (13%) → Triumph
- Success (39%) → Conflict → Setback → **Conflict** (converted)
- Conflict (42%) → Setback → Disaster
- Setback (6%) → Disaster

Success = 13% + 39% = 52%

---

### Expertise-as-Edge (Cancel 1 Complication, 1 remains)

| Pool | After Edge (-1 tier remains) | Success Rate |
|------|---------------------------|--------------|
| 2d6 | Apply -1 tier | 34% |
| 3d6 | Apply -1 tier | 51% |
| 4d6 | Apply -1 tier | 52% |
| 5d6 | Apply -1 tier | 60% |

**Finding:** IDENTICAL to current Expertise against 2 Complications!

---

## Scenario: Specialist vs. 2 Complications WITH Create an Opening

**Key:** Create an Opening grants +1 Boon + 1 Edge

### Current Expertise (Pool+1, then -2 tiers, then convert Setback)

| Pool → After CaO | After -2 tiers | Final (Expertise) | Success Rate |
|-----------------|---------------|------------------|--------------|
| 2d6 → 3d6 | -2 tiers | Convert Setback | 51% |
| 3d6 → 4d6 | -2 tiers | Convert Setback | 52% |
| 4d6 → 5d6 | -2 tiers | Convert Setback | 60% |

Calculation for 2d6 → 3d6:
- Triumph (9%) → Triumph
- Success (42%) → Conflict → Setback → **Conflict** (converted)
- Conflict (26%) → Setback → Disaster
- Setback (23%) → Disaster

Success = 9% + 42% = 51%

---

### Expertise-as-Edge (Pool+1, 2 Edge cancels both Complications)

| Pool → After CaO | After Edge (0 Comp) | Success Rate |
|-----------------|-------------------|--------------|
| 2d6 → 3d6 | Raw roll | **77%** |
| 3d6 → 4d6 | Raw roll | **94%** |
| 4d6 → 5d6 | Raw roll | **97%** |

**MASSIVE DIFFERENCE!**

Against 2 Complications with Create an Opening:
- Current Expertise: 51% → 52% → 60% (at different pool sizes)
- Expertise-as-Edge: 77% → 94% → 97%

At 2d6 base pool: **+26% improvement!**

---

## Summary Table: Current vs. Expertise-as-Edge

### Against 0 Complications (No Create an Opening)

| Pool | Current | Edge | Difference |
|------|---------|------|-----------|
| 2d6 | 100% | 59% | **-41%** |
| 3d6 | 100% | 77% | **-23%** |
| 4d6 | 100% | 94% | **-6%** |
| 5d6 | 100% | 97% | **-3%** |

**Expertise-as-Edge is significantly worse at low pools, but the gap closes at higher pools.**

---

### Against 1 Complication (No Create an Opening)

| Pool | Current | Edge | Difference |
|------|---------|------|-----------|
| 2d6 | 59% | 59% | Same |
| 3d6 | 77% | 77% | Same |
| 4d6 | 94% | 94% | Same |
| 5d6 | 97% | 97% | Same |

**Identical performance.**

---

### Against 2 Complications (No Create an Opening)

| Pool | Current | Edge | Difference |
|------|---------|------|-----------|
| 2d6 | 34% | 34% | Same |
| 3d6 | 51% | 51% | Same |
| 4d6 | 52% | 52% | Same |
| 5d6 | 60% | 60% | Same |

**Identical performance.**

---

### Against 2 Complications (WITH Create an Opening)

| Pool | Current | Edge | Difference |
|------|---------|------|-----------|
| 2d6 | 51% | **77%** | **+26%** |
| 3d6 | 52% | **94%** | **+42%** |
| 4d6 | 60% | **97%** | **+37%** |
| 5d6 | 73% | **100%** | **+27%** |

**Expertise-as-Edge is MUCH better when combined with Create an Opening against multiple Complications.**

---

## Key Insights

### 1. Pool Size Matters for the Comparison

At **2d6 (low competence):**
- Expertise-as-Edge is much worse against 0 Complications (-41%)
- But much better with Create an Opening against 2 Complications (+26%)

At **4d6+ (high competence):**
- Expertise-as-Edge is nearly identical against 0 Complications (-6%)
- Still much better with Create an Opening against 2 Complications (+37%)

**Conclusion:** The downside of Expertise-as-Edge (worse vs. undefended enemies) mostly affects low-competence characters. High-competence characters rarely roll Setback anyway.

---

### 2. Create an Opening Becomes Much More Powerful

With Expertise-as-Edge, spending 1 Momentum for Create an Opening against a heavily-defended enemy becomes an extremely powerful tactical choice.

**Is this good or bad?**

**Good:**
- Rewards resource spending
- Creates meaningful tactical decisions
- Makes specialists feel very powerful when they set up
- Makes Momentum economy more important

**Bad:**
- Maybe too powerful? 77% → 94% success is very high
- Creates a large gap between "specialists with Momentum" and everyone else
- Non-specialists can't access this combo (only specialists have Expertise)

---

### 3. The "Master vs. Peasant" Problem Mostly Affects Low Pools

A character with 2d6 base pool is relatively inexperienced. At this level:
- Current Expertise: 100% success against undefended (never fails)
- Expertise-as-Edge: 59% success (fails 41% of the time)

But a character with 4d6 base pool (experienced specialist):
- Current Expertise: 100% success
- Expertise-as-Edge: 94% success (only 6% difference)

**At higher competence levels, the problem is much smaller.**

---

## The Trade-Off

**Expertise-as-Edge creates:**
- ✅ More tactical synergy with Create an Opening
- ✅ Better performance against heavily-defended enemies
- ✅ More important Momentum economy decisions
- ❌ Worse performance against undefended enemies (mostly at low pools)
- ❌ Edge timing confusion (declared before roll, but benefit is after?)

**Current Expertise creates:**
- ✅ Consistent performance across all enemy types
- ✅ Clear timing (happens at step 9, after everything else)
- ✅ Simple rule: "convert Setback → Conflict"
- ❌ Less synergy with Create an Opening
- ❌ Happens late in resolution

---

## Alternative: Expertise Grants +1 Boon (Not Edge)

What if Expertise just made your dice pool bigger?

### Against 0 Complications

| Base Pool → With Expertise | Success Rate |
|---------------------------|--------------|
| 2d6 → 3d6 | 77% |
| 3d6 → 4d6 | 94% |
| 4d6 → 5d6 | 97% |

Compare to current (100% at all pools): Worse, but not terrible.

### Against 1 Complication

| Base Pool → With Expertise | After -1 tier | Success Rate |
|---------------------------|---------------|--------------|
| 2d6 → 3d6 | -1 tier | 51% |
| 3d6 → 4d6 | -1 tier | 52% |
| 4d6 → 5d6 | -1 tier | 60% |

Compare to current (59% / 77% / 94%): Worse at 2d6 and 3d6, similar at 4d6.

### Against 2 Complications

| Base Pool → With Expertise | After -2 tiers | Success Rate |
|---------------------------|----------------|--------------|
| 2d6 → 3d6 | -2 tiers | 51% |
| 3d6 → 4d6 | -2 tiers | 52% |
| 4d6 → 5d6 | -2 tiers | 60% |

Compare to current (34% / 51% / 52%): Better at 2d6, same at 3d6+.

**+1 Boon is simpler but weaker at low Complication counts.**

---

## My Updated Recommendation

Looking at the higher pools, I think **Expertise-as-Edge might actually work**, with one caveat:

**The problem (worse vs. 0 Complications) mostly affects 2d6 pools.** At 4d6+, the gap is only 6%.

**The benefit (better with Create an Opening vs. 2 Complications) scales up**: +26% at 2d6, +42% at 3d6, +37% at 4d6.

**But there's still the timing confusion:** Edge is declared before rolling, but Expertise would grant Edge... when? Before the roll? That's weird for a passive ability.

**Maybe the answer is:** Keep current Expertise, accept that it happens at step 9. It works well, it's simple, and it doesn't have timing issues.

---

## Questions

1. Is the +26% to +42% boost with Create an Opening against 2 Complications too powerful?
2. Does the "master vs. peasant" problem at 2d6 pools bother you? (41% failure rate vs. 0%)
3. Should specialists with Momentum be MUCH better than non-specialists? (77% vs 34% against 2 Complications)
4. Is simpler timing (Edge at step 7) worth the fictional weirdness (masters struggle vs. peasants)?
