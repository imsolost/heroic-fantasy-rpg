# Action Resolution Complexity Analysis

## Current Archon Resolution Flow

**Full step-by-step:**

1. **Frame action** (GM sets Stakes, Vantage)
2. **Determine pool** (Approach + Trait if invoked)
3. **Apply Boons/Banes** (circumstantial, capped at ±2)
4. **Push Yourself?** (mark 1 Stress for +1 Boon)
5. **Roll dice** (2d6 per die in pool)
6. **Determine raw outcome** (Triumph/Success/Conflict/Setback)
7. **Spend Edge** (if available, cancel Complications before they apply)
8. **Apply remaining Complications** (each reduces outcome by 1 tier)
9. **Apply Expertise** (if final outcome is Setback, convert to Conflict)
10. **Apply final outcome** (Consequence + mark tracks)

**That's 10 steps, 5 of which are subsystems that modify the outcome.**

---

## Blades in the Dark Resolution

1. **Frame action** (position + effect level)
2. **Determine pool** (Action rating + situational bonus dice)
3. **Roll all dice** (take highest single die)
4. **Read result:**
   - 6 = success
   - 4-5 = partial success
   - 1-3 = failure
5. **Apply consequence** (based on position)

**That's 5 steps. No post-roll modifiers.**

**Key design:**
- **Position** (controlled/risky/desperate) = pre-set Consequence severity
- **Effect** (limited/standard/great) = pre-set progress amount
- **No enemy stat blocks** - GM sets position/effect based on fiction
- **No tags** - everything is fictional positioning

---

## Grimwild Resolution (similar to Blades)

1. **Frame action** (position + effect)
2. **Determine pool** (attribute + skill + circumstantial dice)
3. **Roll pool** (d6s, take highest)
4. **Read result** (6 = yes, 4-5 = yes but, 1-3 = no)
5. **Apply consequence** (diminishing pools on damage)

**Also ~5 steps. Also no post-roll modifiers.**

---

## The Complexity Gap

**Blades/Grimwild:** Frame → Roll → Result. Done.

**Archon:** Frame → Roll → Raw Result → Edge → Complications → Expertise → Final Result → Apply

**The difference is post-roll modification layers.**

---

## What Each Archon Subsystem Does

| Subsystem | Purpose | Design Goal | Could It Be Removed? |
|-----------|---------|-------------|---------------------|
| **Boons/Banes** | Circumstantial difficulty tuning | GM tool for "is this harder/easier than normal?" | ❌ Load-bearing - GM needs a difficulty dial |
| **Complications** | Enemy defensive tags | Tactical puzzle: "how do I engage a Resilient + Deadly foe?" | 🤔 Maybe - but this is core differentiation vs. Blades |
| **Edge** | Cancel Complications tactically | Reward for positioning, Momentum spend, specialist abilities | 🤔 Only if Complications stay |
| **Expertise** | Convert Setback → Conflict | Safety net for specialists, raises floor | ✅ Feels optional |
| **Momentum** | Action economy resource | Pacing, Create an Opening, Resist Consequence | ❌ Load-bearing - central resource |

---

## The Core Question: Are Complications Worth Their Weight?

**Complications create complexity in TWO places:**
1. Challenge design (GMs assign tags)
2. Action resolution (players calculate which tags apply, spend Edge, etc.)

**What they buy you:**
- **Enemy differentiation:** A Resilient foe plays differently than an Elusive foe
- **Tactical depth:** Players must think about approach ("I can't hit the armored knight, I'll intimidate him")
- **Reward for mastery:** Edge/positioning lets specialists shine

**What Blades does instead:**
- **Fictional positioning:** "You're attacking a heavily armored knight" → GM sets position to Risky/Desperate
- **Effect:** "Your dagger won't do much against plate" → GM sets effect to Limited
- No tags, no Edge, no Expertise needed

**The Blades approach is simpler.** But it's also:
- More GM judgment-dependent (no mechanical tags to reference)
- Less tactically granular (can't "bypass armor" mechanically, only fictionally)
- Flatter character progression (no Expertise domains)

---

## Simplification Options

### Option 1: Remove Expertise Entirely

**Current:** Expertise converts Setback → Conflict in your domain

**Alternative:** Remove it. Characters with specialties just use Traits (which grant Boons) and Talents (which grant Edge or other effects).

**Impact:**
- ✅ Removes 1 resolution step (step 9)
- ✅ Simplifies character builds (no "Expertise: Heavy Blades" tracking)
- ⚠️ Characters fail more often in their specialties (no safety net)
- ⚠️ Makes Complications MORE punishing (if you roll poorly, you're just screwed)

**Compensation:** 
- Could make Traits grant **+1 Boon automatically when invoked** (currently they just unlock the Approach)
- This raises the floor by improving the dice pool instead of converting outcomes

---

### Option 2: Simplify Edge (Merge with Expertise)

**Current:**
- Edge = cancel Complications (before they apply)
- Expertise = convert Setback (after final outcome)

**Alternative: "Mastery"**
- When you have Mastery in a domain: **Ignore 1 Complication OR treat Setback as Conflict**
- Choose which effect when the roll resolves
- Single mechanic, single timing

**Impact:**
- ✅ Two mechanics → one
- ✅ Single resolution timing (after Complications apply)
- ⚠️ Less tactical (can't "spend Momentum for Edge proactively")
- ⚠️ Edge is currently tied to Create an Opening (1 Momentum = 1 Boon + 1 Edge)

**Problem:** This changes Create an Opening. What would it do instead?

---

### Option 3: Make Edge/Expertise Work Like Blades Position/Effect

**Radical simplification:**

Instead of Complications reducing outcomes, have **Vantage** determine BOTH difficulty AND Consequence severity (like Blades Position).

**New resolution:**
1. Frame action (GM sets Vantage)
2. Vantage determines **Boons/Banes** (difficulty) AND **Consequence tier if you fail**
3. Roll
4. Outcome = Triumph/Success/Conflict/Setback
5. Apply Consequence (pre-set by Vantage)
6. Mark progress

**This removes:**
- Complication tags entirely
- Edge mechanic
- Expertise mechanic

**This requires:**
- Vantage doing much more work (5 tiers might need rethinking)
- Enemy differentiation through fictional positioning only
- Losing tactical "bypass armor" depth

**This is basically "make Archon more like Blades."**

---

### Option 4: Keep Complications, Remove Expertise

**Most conservative simplification:**

- Keep Complications (enemy differentiation, tactical puzzles)
- Keep Edge (reward for positioning/spending)
- Remove Expertise (safety net feels redundant)

**Resolution becomes:**
1. Frame → Pool → Boons/Banes → Push? → Roll
2. Raw outcome → Spend Edge → Apply Complications → Final outcome

**9 steps → 8 steps** (minimal change)

**But:** Characters with Expertise would need something else. Options:
- **A: Grant +1 Boon when acting in domain** (moves it to step 3)
- **B: Grant +1 Edge when acting in domain** (changes it from safety net to tactical tool)
- **C: Just remove it, compensate with better Talents**

---

## My Analysis

**Expertise is the weakest subsystem.** Here's why:

1. **It solves a variance problem, not a tactical one**
   - Edge creates gameplay: "I position for advantage to bypass armor"
   - Expertise just says: "I rolled badly but I'm a master, so it's not as bad"
   - That's a safety net, not a decision point

2. **It overlaps with Boons**
   - Boons already raise your floor (more dice = less likely to fail)
   - Expertise is a second floor-raising mechanism
   - Do you need both?

3. **It's late in resolution**
   - Happens after everything else (step 9)
   - Feels like "wait, one more thing" rather than baked into the roll

4. **It's character complexity with low payoff**
   - Players track "Expertise: Heavy Blades, Expertise: Intimidation"
   - Rarely triggers (only on Setback after Complications)
   - Not as exciting as Talents or Traits

**Edge, by contrast, is load-bearing:**
- Creates tactical decisions (when to Create an Opening)
- Directly answers Complications (the core challenge layer)
- Tied to Momentum economy

**Complications are load-bearing:**
- Core enemy differentiation
- Creates tactical puzzles ("Resilient + Deadly = find another approach")
- Without them, combat is just "roll dice, mark track"

---

## Recommendation

**Remove Expertise. Replace with automatic Trait bonus.**

**Current Trait invocation:**
- Unlock an Approach (Spirit Trait unlocks Spirit Approach)
- Enables Special Effects (Enhanced Effect, Secondary Effect, Build Momentum)

**New Trait invocation:**
- All of the above, PLUS
- **Grant +1 Boon automatically**

**This:**
- ✅ Removes Expertise from resolution (step 9 gone)
- ✅ Raises floor by improving dice pool (mathematically similar to converting Setback)
- ✅ Simplifies character tracking (no "Expertise" list)
- ✅ Makes Traits feel more impactful ("invoking my Trait makes me roll better")
- ✅ Moves the benefit earlier in resolution (step 3 vs. step 9)

**Math check:**
- Current: 2d6 pool, Setback → Conflict conversion on bad roll
- New: 3d6 pool (via +1 Boon from Trait), less likely to roll Setback in first place
- Similar failure rate, simpler resolution

---

## What About Edge?

**Keep Edge as-is.** It serves a distinct purpose:
- Tactical: spend Momentum to bypass defenses
- Rewards positioning: Talents grant Edge in specific circumstances
- Answers Complications: the player-side counter to Challenge tags

**Edge is the "mastery" mechanic.** Expertise was trying to be a second mastery mechanic, but it's redundant.

---

## Summary

**Current resolution layers:**
1. Boons/Banes (GM difficulty tuning) ← Load-bearing
2. Complications (enemy defenses) ← Load-bearing
3. Edge (tactical bypass) ← Load-bearing (if Complications stay)
4. Expertise (safety net) ← **Weakest link, remove**
5. Momentum (resource economy) ← Load-bearing

**Simplification path:**
- Remove Expertise
- Make Traits grant +1 Boon automatically when invoked
- Keep everything else

**Result:**
- 10 steps → 9 steps
- Simpler character tracking
- Still has tactical depth (Complications + Edge)
- Still differentiated from Blades (mechanical tags vs. pure fiction)

---

## Open Question for Discussion

**Could we go further and remove Complications too?**

If we wanted to match Blades' simplicity, we'd need to:
1. Make Vantage do more work (set difficulty AND Consequence severity)
2. Remove Complication tags from enemies
3. Remove Edge mechanic
4. Differentiate enemies through fictional positioning + Track sizes only

**This would be simpler.** But it would also:
- Lose tactical depth (no "bypass armor" mechanics)
- Lose mechanical clarity (more GM judgment calls)
- Make Archon feel more like a Blades clone

**Is that trade worth it?**
