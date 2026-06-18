# Design Note: Universal Consequence Framework

**Status:** Proposed for system-wide implementation

---

## Problem Statement

Currently, the system uses inconsistent language for describing outcomes and consequences:
- "Soft Impact Move" vs "minor consequence" vs "complication"
- "Hard Impact Move" vs "major consequence"
- No clear tier progression for modular traits

This makes it harder to:
- Design traits that modify consequences universally
- Teach the system consistently
- Create modular design elements (enemy traits, hazard types, etc.)

---

## Proposed Solution: Universal Consequence Tiers

**Three-Tier Consequence Framework:**

| Outcome | Consequence Tier | GM Response |
|---------|------------------|-------------|
| **Conflict** | **Minor Consequence** | Soft Impact Move (1 Stress, lose position, side effect) |
| **Setback** | **Major Consequence** | Hard Impact Move (2 Stress, serious danger, objective setback) |
| **Disaster** | **Severe Consequence** | Disaster Move (Taken Out, Burden inflicted, objective fails catastrophically) |

**Triumph/Success:** No consequence (clean success)

---

## Benefits

1. **Consistent terminology** — One phrase per tier across all chapters
2. **Modular design** — Traits can universally increase/decrease Consequence tier
3. **Clear escalation** — Minor → Major → Severe progression is intuitive
4. **Future-proof** — Easy to add new mechanics that interact with consequences
5. **Easier to teach** — "This enemy has Deadly — it increases Consequence tier by 1"

---

## Example Trait Applications

### Enemy Traits

**Deadly:** When you suffer Consequences from this enemy's actions, increase the Consequence tier by 1 (Minor → Major, Major → Severe).

*Example: You attack a Deadly Troll. Your outcome is Conflict (Minor Consequence base). Deadly increases it: Minor → Major Consequence (mark 2 Stress instead of 1).*

**How Deadly Interacts with Expertise:**
- Expertise converts Setback **outcome** → Conflict **outcome** (you succeed)
- Deadly increases **Consequence tier** (it costs more)
- **Result:** Expert succeeds but suffers harsher consequences
- **Example:** Expert vs Deadly enemy rolls Setback → Expertise → Conflict outcome (mark progress) → Minor Consequence → Deadly → Major Consequence (2 Stress instead of 1). You succeed but it hurts.

**Armored:** When you deal harm to this enemy, decrease your Consequence tier benefit by 1 (if your attack would normally trigger no consequence on the enemy, it now triggers a Minor Consequence on you instead — represent glancing blow, armor absorbing hit, etc.).

### Hazard Traits

**Extreme Hazard:** When you fail to overcome this hazard, increase the Consequence tier by 1.

**Deadly Trap:** When triggered, this trap inflicts a Major Consequence automatically (does not require failed roll — representing very dangerous traps).

### Player Abilities

**Expertise:** When you take an action within your area of Expertise, if your final outcome (after applying all Complications) would be a **Setback**, the outcome is a **Conflict** instead. This does not protect against Disaster outcomes.

*Note: Expertise changes the outcome (failure → success), not the consequence severity. Traits like Deadly can still increase consequence cost.*

**Armor:** Reduce physical Consequence tier by 1 when defending (Major → Minor, Minor → none).

**Defensive Talent:** Once per scene, reduce an incoming Consequence tier by 1.

### Weapon Properties

**Armor Piercing:** Increase Consequence tier for the defender by 1 when you successfully attack.

**Brutal:** When you deal Major Consequences, they become Severe Consequences instead.

---

## Implementation Checklist

### Chapter 2: Core Mechanics
- [ ] Add Consequence Tier framework to core definitions
- [ ] Define Minor/Major/Severe explicitly
- [ ] Update Edge & Bane section to reference Consequence tiers

### Chapter 4: Action Resolution
- [ ] Replace "soft Impact Move" with "Minor Consequence" throughout
- [ ] Replace "hard Impact Move" with "Major Consequence" throughout
- [ ] Update Impact Moves section to use new terminology
- [ ] Update Disaster section to use "Severe Consequence"
- [ ] Update Enemy Actions & Reactive Defy to use new language

### Chapter 5: Resilience
- [ ] Update Stress and Conditions to reference Consequence tiers
- [ ] Clarify how Consequence tiers interact with Stress marking

### Chapter 6: Challenges
- [ ] Update Challenge Trait examples to use Consequence tier modifiers
- [ ] Update Complication language to align with Consequence framework

### Chapter 8: Combat
- [ ] Update combat examples to use new terminology
- [ ] Ensure enemy actions reference Consequence tiers consistently

### Chapter 9: Callings
- [ ] ✅ Sage Arcane Formula updated (completed)
- [ ] Review other Calling abilities for consequence language
- [ ] Update Core Talents that reference consequences

### Chapter 10: Spellcasting
- [ ] Update all Conflict/Setback spell outcome descriptions
- [ ] Ensure Potent Spell consequences use new framework
- [ ] Update Ritual consequence language

---

## Terminology Reference

**Before (inconsistent):**
- "GM makes a soft Impact Move"
- "Unintended consequence"
- "Minor complication"
- "The spell has a side effect"

**After (consistent):**
- "You suffer a Minor Consequence (GM makes soft Impact Move)"
- "You suffer a Major Consequence (GM makes hard Impact Move)"
- "Increase/decrease Consequence tier by 1"

---

## Examples in Play

### Example 1: Basic Combat

**Player attacks knight with "Heavily Armored" trait.**
- Roll Clash → Success
- Knight's "Heavily Armored" increases defender's Consequence tier by 1
- Success normally = no consequence, but trait makes it Minor Consequence
- GM: "Your blade strikes true but glances off his plate mail — mark 1 Stress from the jarring impact" (Minor Consequence)

### Example 2: Sage Casting with Expertise

**Specialist Mind Sage uses Arcane Formula to attempt Mind spell.**
- Roll with 1 Bane → Setback (all 1-3)
- Normally Setback = Major Consequence
- Expertise reduces: Major → Minor
- GM: "The spell works but your nose bleeds from the strain — mark 1 Stress" (Minor Consequence instead of 2 Stress)

### Example 3: Deadly Enemy

**Player defends against Tier 2 Troll with "Deadly" trait.**
- Roll Defy → Conflict
- Conflict normally = Minor Consequence
- "Deadly" increases tier: Minor → Major
- GM: "You dodge but its claws rake your arm — mark 2 Stress and Bleeding 1 condition" (Major Consequence)

### Example 4: Stacking Modifiers

**Player with Heavy Armor defends against normal enemy.**
- Roll Defy → Conflict
- Conflict = Minor Consequence
- Heavy Armor reduces tier: Minor → None
- Result: "You deflect the blow with your shield — no consequence" (armor negated it)

---

## Open Questions

1. **Should Triumph explicitly state "No Consequence"?** Or is it implicit that Triumph = clean success?
   - **Recommendation:** Keep implicit, but state in Core Mechanics section for clarity

2. **Should Complications (from Challenge Traits) use Consequence language?**
   - **Current:** "1 Complication reduces outcome by 1 tier"
   - **Proposed:** "1 Complication increases Consequence tier by 1 (shifts outcome down: Success → Conflict, Conflict → Setback)"
   - **Benefit:** More consistent language

3. **Should some Talents explicitly "ignore Minor Consequences" instead of granting Edge?**
   - Example: "Iron Will — Ignore Minor Consequences from mental attacks"
   - **Benefit:** Creates alternative design space beyond Edge/Bane

4. **How do Consequence tiers interact with Resist Consequence (Momentum spend)?**
   - **Current:** Resist reduces mechanical consequences by steps (2 Stress → 0, tier 3 → tier 1)
   - **Proposed:** Resist reduces Consequence tier by 1-2 depending on roll (Success = -2 tiers, Conflict = -1 tier)

---

## Complications Framework

**Complications** reduce your outcome tier, increasing the Consequence you suffer.

**How Complications Work:**

Each Complication reduces your outcome by one tier:
- **Success** (no consequence) → **Conflict** (Minor Consequence)
- **Conflict** (Minor Consequence) → **Setback** (Major Consequence)
- **Setback** (Major Consequence) → **Disaster** (Severe Consequence)
- **Disaster** (Severe Consequence) → No further reduction (already worst outcome)

**Triumph ignores all Complications** — you suffer no consequence regardless of how many Complications are present.

**Order of Operations:**
1. Roll dice → determine raw outcome (Setback/Conflict/Success/Triumph)
2. Apply Complications (reduce outcome tier by 1 per Complication)
3. Apply Expertise (if final outcome is Setback, convert to Conflict outcome)
4. Map outcome to base Consequence tier (Conflict = Minor, Setback = Major, Disaster = Severe)
5. Apply trait modifiers (Deadly, Armor, etc.) that increase/decrease Consequence tier
6. Resolve final Consequence

**Example 1: Expertise + 2 Complications**

Bladedancer (Expertise: Heavy Blades) attacks Armored Knight (2 Complications)

| Roll | After Complications | After Expertise | Base Consequence | Final Result |
|------|---------------------|-----------------|------------------|--------------|
| Triumph | Ignores Complications | N/A | None | Triumph (no consequence) |
| Success | → Conflict → Setback | Setback → Conflict | Minor | **Conflict (Minor Consequence)** |
| Conflict | → Setback → Disaster | No change | Severe | **Disaster (Severe Consequence)** |
| Setback | → Disaster | No change | Severe | **Disaster (Severe Consequence)** |

**Example 2: Expertise + 2 Complications + Deadly Trait**

Bladedancer (Expertise: Heavy Blades) attacks Deadly Troll (2 Complications, Deadly trait)

| Roll | After Complications | After Expertise | Base Consequence | Apply Deadly | Final Result |
|------|---------------------|-----------------|------------------|--------------|--------------|
| Triumph | Ignores Complications | N/A | None | N/A | Triumph (no consequence) |
| Success | → Conflict → Setback | Setback → Conflict | Minor | → Major | **Conflict outcome + Major Consequence (mark progress but 2 Stress)** |
| Conflict | → Setback → Disaster | No change | Severe | N/A | **Disaster (Severe Consequence)** |
| Setback | → Disaster | No change | Severe | N/A | **Disaster (Severe Consequence)** |

**Key Insights:** 
- Expertise provides a safety net against Setback outcomes (converts failure to success) but cannot prevent Disaster
- Deadly increases Consequence severity but doesn't negate Expertise's success conversion
- Against high-Complication enemies, you need better rolls (not just Expertise) to avoid catastrophic failure
- Expertise ensures you make progress even when things hurt

---

## Terminology: Area of Expertise vs Domain

**Area of Expertise:** Used for Sage theorems, martial specialists, skill mastery
- "Expertise: Heavy Blades" (Champion)
- "Expertise: Stealth, Thievery, Deception" (Shadow)
- "Expertise: Your chosen Sphere" (Sage Specialist)

**Domain:** Used for Mystic's spiritual powers
- "Healing Domain" (Mystic patron grants)
- "Nature Domain" (Mystic patron grants)
- Not used for non-magical expertise

This distinction keeps spiritual/divine language separate from scholarly/skill-based language.

---

## Next Steps

1. **Finalize terminology** (confirm "Minor/Major/Severe Consequence" as standard)
2. **Update Chapter 2** with core definitions
3. **Systematic review** of all chapters to replace inconsistent language
4. **Create unified Impact Moves table** organized by Consequence tier
5. **Design example traits** demonstrating Consequence tier modification

---

## Related Design Patterns

- **Expertise** = Reduce Consequence tier by 1 (within domain)
- **Deadly/Brutal traits** = Increase Consequence tier by 1
- **Armor/Defense** = Reduce incoming physical Consequence tier
- **Potency** = Ignore Complications (prevent Consequence tier increase from Challenge Traits)

This framework creates a unified language for all consequence-modifying mechanics in the system.
