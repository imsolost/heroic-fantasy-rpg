# Push Yourself Redesign: Complications & Refinements

## Problem 1: Push Yourself as a Talent Framework

### Current System

**Push Yourself** = Mark 1 Stress to gain +1 Boon (pre-roll)

**Talents key off this:**
- "When you Push Yourself while [doing X], you also [get special effect]"
- Example: "When you Push Yourself during combat, you also gain 1 Edge"

**The framework is:** Mark 1 Stress → get benefit. Talents add to the benefit.

---

### If We Change Push Yourself to Post-Roll Conversion

**New Push Yourself** = Mark 1 Stress to convert Setback → Conflict (post-roll)

**What happens to Talents that key off "Push Yourself"?**

**Example Talent (hypothetical):**
> **Surge of Speed:** When you Push Yourself on a movement action, you also move one additional zone.

**Current interpretation:** Mark Stress pre-roll for +1 Boon, ALSO move extra zone.

**New interpretation:** Mark Stress post-roll to convert Setback, ALSO move extra zone?

**This doesn't make fictional sense.** The Talent triggers when you're pushing through failure, but the "extra movement" benefit doesn't connect to "converting Setback."

---

### Solution Options

#### Option A: Two Flavors of Push Yourself

**Push Yourself becomes a category, not a single mechanic:**

1. **Push for Advantage (pre-roll):** Mark 1 Stress for +1 Boon
2. **Push Through Failure (post-roll):** Mark 1 Stress to convert Setback → Conflict

**You can only use one per action** (choose which makes sense).

**Talents specify which they key off:**
- "When you Push for Advantage on a movement action..." (pre-roll)
- "When you Push Through Failure in combat..." (post-roll)

**Pro:** Preserves both mechanics, Talents can use either  
**Con:** Two "Push Yourself" mechanics is more complex, not simpler

---

#### Option B: Separate the Mechanics Entirely

**Don't call the post-roll conversion "Push Yourself."**

**New names:**
- **Push Yourself (pre-roll):** Mark Stress for +1 Boon (unchanged)
- **Grit (post-roll):** Mark Stress to convert Setback → Conflict (new mechanic)

**Talents key off "Push Yourself" (pre-roll) as before.**

**You have two Stress-spending options:**
- Pre-roll: Push Yourself for +1 Boon
- Post-roll: Grit to convert Setback

**Pro:** Clear separation, Talents unchanged  
**Con:** Still two mechanics (didn't reduce complexity)

---

#### Option C: Unified "Mark Stress for Effect" Framework

**Push Yourself means:** "Mark 1 Stress to gain a benefit" (timing varies by context)

**The baseline benefits are:**
- Pre-roll: +1 Boon
- Post-roll: Convert Setback → Conflict

**You choose when to Push Yourself and which benefit applies** (but only once per action).

**Talents add to this:**
- "When you Push Yourself [in this context], you also [special effect]"
- The special effect happens at the same timing as your Push

**Example:**
> **Surge of Speed:** When you Push Yourself on a movement action, you also move one additional zone.

**Interpretation:**
- If you Push pre-roll (for +1 Boon), you ALSO move extra zone
- If you Push post-roll (convert Setback), you ALSO move extra zone
- The timing depends on when you choose to Push

**Pro:** Flexible, Talents still work  
**Con:** Might be confusing (when does the special effect happen?)

---

#### Option D: Separate Expertise from Push

**Don't merge them at all.**

**Keep both:**
- **Push Yourself (pre-roll):** Mark Stress for +1 Boon (unchanged)
- **Expertise (post-roll):** Passive Setback conversion in your domain (unchanged)

**Talents key off Push Yourself (pre-roll) as before.**

**Pro:** Nothing breaks  
**Con:** Didn't simplify anything (still have both Step 4 and Step 9)

---

### My Recommendation: Option B (Separate Mechanics, New Name)

**Don't call it "Push Yourself."** That framework should stay pre-roll.

**New mechanic: "Refuse to Fail" or "Dig Deep" or "Grit"**

**Push Yourself (pre-roll):**
- Mark 1 Stress for +1 Boon
- Talents can key off this
- Unchanged from current

**Refuse to Fail (post-roll):**
- Mark 1 Stress to convert Setback → Conflict
- New option available to everyone
- Replaces passive Expertise

**Resolution:**
1. Frame
2. Pool (Approach + Trait)
3. Boons/Banes
4. **Push Yourself?** (pre-roll, +1 Boon)
5. Roll
6. Raw Outcome
7. Edge
8. Complications
9. **Refuse to Fail?** (post-roll, convert Setback) ← replaces Expertise
10. Final Outcome

**Still 10 steps, BUT Step 9 is now active (player choice) instead of passive (check Expertise).**

**Net effect:**
- Removed passive Expertise
- Added active post-roll choice
- Preserved Push Yourself framework for Talents
- Still have both pre-roll and post-roll Stress spending

---

## Problem 2: Auto +1 Boon from Traits and the +2 Cap

### Current System

**Boons cap at +2d** (max pool = 4d6).

**Sources of Boons:**
- Circumstantial (good position, right tools, etc.)
- Assist (allies mark Stress)
- Push Yourself (mark Stress)
- Create an Opening (spend Momentum)

**Typical scenario:**
- Base: 2d6
- Circumstantial: +1 Boon = 3d6
- Assist: +1 Boon = 4d6 (capped)

---

### If Traits Auto-Grant +1 Boon

**New scenario:**
- Base: 2d6
- **Trait invoked: +1 Boon = 3d6** (automatic)
- Circumstantial: +1 Boon = 4d6 (capped)
- Assist: Can't add (already capped)

**Problem: You hit the cap constantly.**

If you invoke your Trait (which you usually do) AND have any circumstantial advantage, you're at cap. Assist and Push Yourself become worthless.

**This is Boon inflation.**

---

### Solution Options

#### Option A: Don't Auto-Grant Boon from Traits

**Revert the proposal.** Traits just unlock Approach and enable Special Effects (current system).

**Instead:**
- Remove Expertise as a mechanic
- Don't compensate with +1 Boon
- Specialists just fail more often (no safety net)

**Result:** Simpler, but specialists feel weaker.

---

#### Option B: Increase the Boon Cap

**Current cap:** +2 Boons (max 4d6)  
**New cap:** +3 Boons (max 5d6)

**This creates room:**
- Base: 2d6
- Trait: +1 Boon = 3d6
- Circumstantial: +1 Boon = 4d6
- Assist or Push: +1 Boon = 5d6

**Problem:** Changes core math. Pools of 5d6 succeed ~97% against 0 Complications. Might be too reliable.

---

#### Option C: Expertise Grants +1 Boon, But Not from Trait

**Separate Expertise from Trait invocation.**

**Character building:**
- During creation/advancement, you choose Expertise domains (Heavy Blades, Stealth, etc.)
- This is separate from Traits

**When you act in an Expertise domain:**
- You get +1 Boon (happens at Step 3, with Boons/Banes)
- This is a passive bonus, always on

**Traits:**
- Still unlock Approach
- Still enable Special Effects
- Do NOT grant +1 Boon

**Example:**
- Character has Expertise: Heavy Blades (from character building)
- Has Trait: Born Warrior (unlocks Daring Approach)
- Attacks with sword:
  - Invokes Trait (unlocks Daring)
  - Gets +1 Boon from Expertise automatically (domain applies)
  - Rolls 3d6 (2d6 base + 1 Boon from Expertise)

**This separates the two concepts:**
- Trait = your identity (unlocks Approach, Special Effects)
- Expertise = your training (grants Boons in specific domains)

**Problem:** We're back to tracking Expertise as a separate thing. Didn't simplify character building.

---

#### Option D: Expertise Grants Edge Instead

**Don't compensate with Boons at all.**

**Remove Expertise's Setback conversion.**

**Replace with: Expertise grants +1 Edge in your domain** (happens at Step 7).

**This was discussed earlier, but let's reconsider:**
- Specialists cancel 1 Complication automatically
- Doesn't inflate Boons
- Creates tactical advantage without raising floor

**Problem:** Doesn't help against 0 Complications (Edge wasted when there's nothing to cancel).

---

#### Option E: Don't Compensate Specialists at All

**Radical simplification:**

**Remove Expertise entirely.**
**Don't add +1 Boon.**
**Don't add Edge.**

**Specialists are just people with:**
- Higher Approach ratings (2-3d6 base)
- Relevant Traits (unlock Approaches, enable Special Effects)
- Relevant Talents (special abilities)

**They don't have a mechanical "never fail in my domain" safety net.**

**Result:**
- Much simpler (no Expertise mechanic at all)
- Specialists feel like "skilled people" rather than "infallible masters"
- Failure is always possible (even in your specialty)

**This changes the tone:**
- Current: Masters rarely fail in their domain
- New: Masters are better, but still face uncertainty

**Is this acceptable?** Depends on your design goals.

---

### My Recommendation: Option E (No Compensation)

**Remove Expertise entirely. Don't add +1 Boon or Edge.**

**Why:**
- ✅ Simplest solution (no new mechanics)
- ✅ No Boon inflation
- ✅ No Edge weirdness (wasted against 0 Complications)
- ✅ Cleaner character building (no Expertise tracking)

**Trade-off:**
- ❌ Specialists feel less "unstoppable"
- ❌ Failure rate increases in specialty (44% at 2d6, 23% at 3d6)

**But specialists still have:**
- Higher Approach ratings (roll more dice)
- Traits (unlock Special Effects)
- Talents (special abilities)

**They're still better.** Just not infallible.

---

## Revised Proposal: Conservative Simplification

### Remove Expertise, Add Post-Roll Option

**Step 1:** Remove Expertise entirely (passive Setback conversion)

**Step 2:** Add new post-roll option: "Refuse to Fail"

**Step 3:** Keep Push Yourself as pre-roll (+1 Boon)

**Step 4:** Don't add +1 Boon to Traits (no compensation)

---

### New Resolution (Still 10 Steps, But Step 9 Changes)

1. Frame
2. Pool (Approach + Trait if invoked)
3. Boons/Banes
4. **Push Yourself?** (mark Stress for +1 Boon) ← pre-roll, unchanged
5. Roll
6. Raw Outcome
7. Edge (cancel Complications)
8. Complications
9. **Refuse to Fail?** (mark Stress to convert Setback → Conflict) ← post-roll, NEW, replaces Expertise
10. Final Outcome

**Changes:**
- ✅ Removed passive Expertise (Step 9 was automatic check)
- ✅ Added active choice at Step 9 (player decision)
- ✅ Everyone can convert Setback (not just specialists)
- ✅ No Boon inflation (Traits unchanged)
- ⚠️ Still 10 steps (but Step 9 is more engaging)

**Net effect:**
- Expertise gone (simpler character building)
- Post-roll drama added (more player agency)
- Specialists not compensated (they just roll better via Approach)

---

### New Rules Text

**Push Yourself (unchanged)**
> When you make an Action Roll, you may **mark 1 Stress** before rolling to gain **+1 Boon**.

**Refuse to Fail (new)**
> When your final outcome is **Setback**, you may **mark 1 Stress** to convert it to **Conflict**. You succeed at your action, but face a Minor Consequence.
> 
> Describe how you push through—forcing past exhaustion, ignoring pain, refusing to give up.
> 
> You cannot use this to convert **Disaster**.

**Assist (unchanged)**
> When an ally makes an Action Roll, you may **mark 1 Stress** to grant them **+1 Boon** before they roll.

---

## Summary: What This Achieves

### Complexity Reduction

**Before:**
- Expertise (passive, specialists only, character tracking required)

**After:**
- Refuse to Fail (active, everyone, no tracking)

**Character sheets:**
- Before: Track "Expertise: Heavy Blades, Expertise: Stealth"
- After: Nothing to track (everyone has Refuse to Fail)

---

### Player Agency

**Before:** Expertise automatically converts Setback (you don't choose)

**After:** Refuse to Fail is a choice (do I spend Stress or accept failure?)

**More dramatic moment.**

---

### Specialist Differentiation

**Before:** 
- Specialists: Higher Approach + Expertise (never fail)
- Non-specialists: Lower Approach (fail often)

**After:**
- Specialists: Higher Approach + Traits + Talents (fail less)
- Non-specialists: Lower Approach (fail more, must spend Stress to Refuse to Fail)

**Both can Refuse to Fail, but specialists need it less often.**

---

### Problems Solved

✅ **No Boon inflation** (Traits don't auto-grant +1 Boon)  
✅ **Talents still work** (Push Yourself remains pre-roll framework)  
✅ **Simpler character building** (no Expertise tracking)  
✅ **More player agency** (active choice at Step 9)

---

### Remaining Questions

1. **Is it okay for specialists to fail more often?** (23% vs. 0% Setback rate)
2. **Is post-roll Stress spend too common?** (you'd Refuse to Fail ~20-30% of rolls)
3. **Should we keep both pre-roll Push AND post-roll Refuse?** (Two Stress spends feels redundant)

---

## Alternative: Only Post-Roll Stress Spend

**What if we removed pre-roll Push Yourself entirely?**

**Stress spending becomes:**
- Pre-roll: Assist only (help others)
- Post-roll: Refuse to Fail (save yourself)

**No more "mark Stress for +1 Boon."**

**You'd rely on:**
- Circumstantial Boons (GM grants)
- Create an Opening (Momentum spend)
- Assist (ally's Stress)

**Pros:**
- ✅ Fewer decision points (no pre-roll Stress gambling)
- ✅ More dramatic (all Stress spending is reactive)
- ✅ Simpler (one Stress-spending option for yourself)

**Cons:**
- ❌ Less proactive agency (can't boost odds preemptively)
- ❌ Breaks Talents that key off "Push Yourself"
- ❌ Major system change (high risk)

**Verdict:** Too radical. Keep pre-roll Push Yourself.

---

## Final Recommendation

**Implement the Conservative Simplification:**

1. **Remove Expertise** (passive Setback conversion, specialists only)
2. **Add "Refuse to Fail"** (active Setback conversion, everyone, costs Stress)
3. **Keep Push Yourself** (pre-roll +1 Boon, unchanged)
4. **Keep Traits as-is** (no auto +1 Boon, no inflation)

**Result:**
- Simpler character building (no Expertise tracking)
- More player agency (active choice at Step 9)
- No math changes (Boon cap unchanged, pools unchanged)
- Specialists still better (higher Approach) but not infallible
- Talents still work (Push Yourself framework preserved)

**This is a clean simplification with minimal risk.**
