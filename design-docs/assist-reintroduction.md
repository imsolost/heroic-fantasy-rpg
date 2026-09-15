# Assist Reintroduction — September 2026

## Summary

Reintroduced **Assist** as a subsection of **Create an Opening**, adding constraints for helping allies to make it a meaningful commitment rather than fire-and-forget resource spending.

---

## The Change

### Create an Opening — Two Modes

**For Yourself:**
- Spend 1 Momentum → gain +1 Boon +1 Edge
- No additional requirements
- No additional risk

**Assist (For an Ally):**
- Spend 1 Momentum → ally gains +1 Boon +1 Edge
- **Requires fictional positioning:** Close enough, relevant capability (GM adjudicates)
- **Requires shared risk:** You suffer the same consequence if they roll Conflict/Setback

---

## Design Rationale

### Problem with Original Removal

When we removed Assist entirely, the only way to help allies was Create an Opening for them. This had no positioning requirement and no risk — you could safely dump Momentum into allies from across the battlefield with no commitment.

### Why These Constraints?

**Fictional Positioning Gate:**
- Makes the game more grounded
- Prevents abstract "I help somehow" from anywhere
- Forces tactical positioning decisions
- Still allows creative solutions ("I use magic to help from range")

**Shared Risk:**
- Makes Assist a genuine commitment, not just spending a resource
- Creates "we're in this together" moments
- Differentiates self-buffing (safe) from ally-buffing (risky)
- Rewards Build Momentum → ally self-buffs over direct Assist for safer support

### Risk/Reward Balance

**Low-risk team support:**
- Use Build Momentum Trait Special Effect
- Grant ally 1 Momentum
- They Create an Opening for themselves (safe)

**High-risk team support:**
- Directly Assist them
- Share their fate
- More narratively engaged

---

## Mechanical Details

### What "Shared Risk" Means

**You share the consequence, not the success:**
- If ally marks Harm track (success) + marks Stress (Conflict) → you only mark the Stress
- If ally marks Stress → you mark Stress
- If ally gains a Condition → you gain the same Condition
- If ally is pushed back → you're pushed back

**Example:**
> Kael attacks a knight (Resilient). Lyra Assists by flanking.
>
> Kael rolls 3d + 1 Boon = 4d → 2, 3, 4, 5 → Conflict
> Resilient reduces Conflict → Setback
> 
> **Both Kael and Lyra mark 2 Stress** (Major Consequence shared)
>
> The knight's blade catches both of them in the exchange.

### Edge Cases

**Q: Can I Assist from range with magic/abilities?**
A: Yes, if you can justify it fictionally. "I cast a blessing" works. "I help" doesn't.

**Q: Do I mark Harm tracks if they're attacking?**
A: No—you share consequences (costs), not successes (progress). They mark Harm, you mark Stress/Conditions.

**Q: Can multiple people Assist the same roll?**
A: No—"Only one character can Create an Opening for a given roll" (existing rule).

**Q: What if the ally Creates an Opening for themselves AND I Assist?**
A: No—only one Create an Opening per roll. Choose who does it.

---

## Files Updated

### Chapter 5: Momentum
**File:** `reorganized/part-1-the-rules/05-momentum.md`

**Changes:**
- Restructured Create an Opening into two subsections
- Added "For Yourself" (existing rules, unchanged)
- Added "Assist (For an Ally)" with fictional positioning + shared risk requirements
- Updated Tactical Considerations to reference risk/reward trade-off
- Added examples showing shared consequence mechanics

### Chapter 4: Resilience
**File:** `reorganized/part-1-the-rules/04-resilience.md`

**Changes:**
- Updated Teamwork (3+ People) section
- Changed example to show shared consequence when Assisting
- Added pointer to Chapter 5 for complete Assist rules

### Quick Start Guide
**File:** `reorganized/quick-start-guide.md`

**Changes:**
- Updated Create an Opening to show two modes (self vs. Assist)
- Added brief note about fictional positioning and shared risk for Assist

---

## Gameplay Implications

### Tactical Positioning Now Matters

**Before:** "I'm staying at range and spending Momentum to boost the fighter"

**After:** "If I want to boost the fighter, I need to get close and share the risk"

### Support Roles Have Two Paths

**Safe Support (Build Momentum):**
1. Character with Build Momentum Trait rolls well
2. Invokes Trait → grants ally 1 Momentum
3. Ally spends Momentum to buff themselves (safe)

**Committed Support (Assist):**
1. Character gets in position
2. Spends Momentum to Assist
3. Shares the outcome with ally (risky)

### Example Party Dynamics

**Mixed Party (1 fighter + 2 support):**

**Scout (Sense specialist):**
- Uses Sense to discover enemy weaknesses
- Uses Build Momentum to fuel Fighter
- Fighter self-buffs (safe)

**OR:**

- Gets close to flank
- Assists Fighter directly
- Both face consequences if roll goes badly
- More engaged, higher risk

---

## Examples Needing Updates

### Combat Examples in Design Docs

**File:** `design-docs/mixed-party-composition-example.md`

**Issues Found:**
- Line 86: Lyra Creates an Opening for Kael's dodge — needs position check
- Line 100: Lyra "creates distraction" with thrown dagger — not direct Assist, problematic
- Line 110: Shows Kael using Create an Opening (self) + Lyra's Create an Opening stacking → **VIOLATES "only one per roll" rule**

**Status:** Needs full rewrite to comply with new Assist rules

---

## Design Notes

### Why Not Just Remove Ally-Buffing Entirely?

Assist creates heroic "we're in this together" moments. The constraints make it meaningful rather than abstract resource-spending.

### Why Shared Risk Instead of Separate Cost?

**Separate cost** (e.g., "both mark 1 Stress to Assist") would be:
- More predictable
- Less dramatic
- Doesn't create "we succeed or fail together" moments

**Shared risk** creates:
- Genuine commitment
- Narrative weight ("I'm putting myself on the line for you")
- Asymmetric outcomes (ally rolls well, no cost; ally rolls badly, both suffer)

### Comparison to Grimwild

Grimwild removed Assist entirely. We reintroduced it but gated it:
- Grimwild: Support via Talents only
- Archon: Support via Momentum, but requires positioning + risk

This preserves team-play options while preventing fire-and-forget support.

---

## What's Next

1. **Update combat examples** in design docs to use new Assist rules
2. **Review Part 3 (Running the Game)** for any Assist references needing updates
3. **Playtest** to verify fictional positioning gate and shared risk feel good at the table
