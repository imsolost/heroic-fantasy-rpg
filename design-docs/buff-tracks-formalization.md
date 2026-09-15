# Buff Tracks Formalization — September 2026

## Summary

Formalized Buff mechanic as Character Tracks (parallel to Afflictions) to resolve duration vagueness, improve tracking clarity, and unify the advantage/disadvantage system. Buffs now work like reverse Afflictions—they grant +1 Boon and tick down through use.

---

## Problem Statement

**Create Advantage** had three issues:
1. **Duration vagueness:** "typically 1-2 actions" created table confusion and inconsistent rulings
2. **Tracking difficulty:** No clear system for when advantages expired
3. **Power level unclear:** How impactful should one action spent on Create Advantage be?

---

## Solution: Buff Tracks

**Buffs are Character Tracks** (like Afflictions/Burdens) with:
- **Name:** What it does (Flight, Inspired, Shielded, etc.)
- **Size:** 2 boxes (default) or 3 boxes (Greater Effect)
- **Effect:** Grants +1 Boon OR fictional positioning to relevant actions
- **Mark trigger:** Mark 1 box when benefit is used
- **Completion:** When track fills, Buff ends
- **Recovery:** Clears on Short Rest (even if not full)

### Example
> **Mage casts protective blessing on Fighter:**
> - Success: Fighter gains **Shielded 2** [ ] [ ]
> - Fighter rolls to Defy dragon's breath: +1 Boon from Shielded, mark 1 box → [ X ] [ ]
> - Fighter rolls to Clash dragon: +1 Boon from Shielded, mark 1 box → [ X ] [ X ]
> - Shielded 2 is now exhausted and ends

---

## Mechanics

### Default Buff Creation (Defy → Create Advantage)

**On Success:**
- **Buff 2** for ally (or self): Grants +1 Boon OR positioning for 2 actions
- **Affliction 1** for enemy: PCs gain +1 Boon on one action against them (enemies don't roll, so Afflictions make them easier targets)
- **Environmental advantage:** Narrative effect (cover, barriers, hazards)

**Greater Effect (Trait invocation):**
- **Buff 3** (one ally, lasts 3 uses) OR
- **Broad Effect** (multiple allies each get Buff 2)
- **Affliction 2-3** (one enemy, PCs gain +1 Boon for 2-3 actions against them) OR
- **Broad Effect** (multiple enemies each get Affliction 1)

### Secondary Effect Buff (Trait → Create Advantage)

**Free Secondary Defy:**
- **Buff 1** for ally: Grants +1 Boon for 1 action
- **Affliction 1** for enemy: PCs gain +1 Boon on one action against them

Smaller than primary Defy because it's a free bonus effect.

---

## Track Interactions

### Afflictions on PCs vs. Enemies

**Critical distinction:** Afflictions work differently on PCs vs. enemies because enemies don't roll dice.

**On a PC:** Affliction applies **-1 Bane** to the PC's relevant Action Rolls. The PC is impaired, making their actions harder.

**On an enemy:** Affliction grants PCs **+1 Boon** when making relevant actions against that enemy. The enemy is vulnerable, making them an easier target.

*Example: Blinded knight doesn't roll to defend (enemies don't roll). Instead, PCs gain +1 Boon when attacking the blinded knight.*

### Buffs and Afflictions Coexist
- You can have **Inspired 2** (+1 Boon) and **Poisoned 2** (-1 Bane) simultaneously
- On relevant roll, both apply and cancel to net 0 modifiers
- **Both mark when used** — Buff depletes AND Affliction ticks down
- Subject to ±2 pool modifier cap (3 Buffs = +3 Boons worth but only +2d to pool)

### Refresh, Not Stack
- Same Buff cannot stack beyond initial size
- If you have **Inspired 2** [X] [ ] (1 use left) and gain **Inspired 2** again, it **refreshes** to [ ] [ ]
- Same as Afflictions

### Multiple Buffs Stack
- You can have **Inspired 2** + **Shielded 2** + **Flight 2** simultaneously
- Each grants +1 Boon if relevant to the action
- All mark when used

---

## Common Buff Names

**Offensive:** Inspired, Empowered, Focused, Blessed, Aiming

**Defensive:** Shielded, Warded, Protected, Braced, Fortified

**Positional:** Flight, Invisible, Swift, Enhanced Senses, Enlarged

**Social:** Charming, Intimidating, Commanding, Persuasive

---

## Design Rationale

### Why Tracks?

**Symmetry with Afflictions:**
- Afflictions are negative Character Tracks that tick down through use
- Buffs are positive Character Tracks that tick down through use
- One underlying system, two applications

**Clear Duration:**
- "Buff 2" is concrete: grants +1 Boon twice, then ends
- No more "typically 1-2 actions" table debates
- Self-documenting: track shows how many uses remain

**Trackable Power:**
- Default Buff 2 = 2 uses of +1 Boon = worth one action investment
- Greater Effect Buff 3 = 3 uses (stronger) OR Broad Effect (multiple allies)
- Balanced against other action options

**Fictional Positioning:**
- Not all Buffs grant Boons — some grant positioning
- **Flight 2:** You can reach aerial targets, cross chasms (mark when you leverage that advantage)
- **Invisible 2:** You can bypass visual detection (mark when you use that)
- Buff tracks work for both mechanical bonuses and fictional benefits

### Why 2 Boxes Default?

**1 box would be too weak:**
- Spending your entire action for +1 Boon on one ally's one action is poor economy
- Momentum → Create an Opening (self) grants +1 Boon +1 Edge for less

**2 boxes hits the sweet spot:**
- Worth the action investment
- Matches "1-2 actions" from previous wording
- Doesn't last too long (3+ would reduce urgency to spend it)

**3 boxes is premium:**
- Requires Greater Effect (Trait invocation at Conflict+)
- OR Broad Effect (multiple allies get 2 boxes each)
- Rewards investment in Traits

---

## Future Potential: Defensive Absorption

Currently, Buffs grant +1 Boon (help you resist harm) not absorption (prevent harm directly).

**Future option:** Defensive absorption Buffs
- **Temporary Armor 2** [ ] [ ]: Mark box instead of marking Stress from physical harm
- **Temporary Ward 2** [ ] [ ]: Mark box instead of marking Stress from magical harm
- **Temporary Morale 2** [ ] [ ]: Mark box instead of marking Stress from mental/social harm

This would be a separate mechanic from +1 Boon Buffs. Not implementing now, but design space is open.

---

## Files Updated

| File | Section | Change |
|------|---------|--------|
| `03-consequences.md` | Tracks introduction | Added Buff to "What you'll learn" list |
| `03-consequences.md` | Character Tracks table | Added Buff row: Size 2-3, mark when used, full means depletion, clears on Short Rest |
| `03-consequences.md` | Track Type sections | Added full "Buff Tracks (Temporary Advantages)" section with mechanics, examples, stacking rules |
| `03-consequences.md` | Track Design Summary | Updated from "Five applications" to "Six applications", added Buff summary |
| `02-taking-action.md` | Defy → Create Advantage | Replaced "grant +1 Boon" with Buff 2 creation, added examples with track notation |
| `05-momentum.md` | Support Toolkit | Updated "Defy to Create Advantage" to reference Buff tracks and Greater Effect options |
| `06-traits.md` | Secondary Effect table | Updated Create Advantage to create Buff 1 or Affliction 1 |
| `06-traits.md` | Create Advantage specifics | Clarified Secondary Effect creates Buff 1 (smaller than primary Defy) |
| `06-traits.md` | Greater Effect | Added explicit Buff 3 / Affliction 2-3 options for Defy Create Advantage |
| `06-traits.md` | Broad Effect | Added explicit multiple Buff 2 / Affliction 1 for group targets |
| `quick-start-guide.md` | Defy section | Updated "grant ally +1 Boon" to "create Buff for ally, inflict Affliction on enemy" |

---

## Gameplay Implications

### Before (Vague Duration)
- GM: "You inspire your ally with a rallying cry. They have +1 Boon on their next action."
- Player: "Does that last if I wait two turns?"
- GM: "Uh... probably? Let's say it fades after the scene?"
- **Result:** Inconsistent rulings, unclear value

### After (Buff Tracks)
- GM: "You inspire your ally with a rallying cry. They gain **Inspired 2** [ ] [ ], granting +1 Boon for their next two relevant actions."
- Player: "Perfect. I'll use it now to attack." (marks 1 box)
- Next turn: "I use the last of my inspiration to Defy." (marks 2nd box → Inspired ends)
- **Result:** Clear, trackable, consistent

### Tactical Depth
- **Support characters** can now see their contributions persist and matter
- **Recipients** know exactly how many uses they have
- **Combos** become clearer: "Give me Flight 2 and I'll use both charges to reach the tower and trigger the alarm"

---

## Examples in Play

### Example 1: Offensive Buff
> **Mage to Rogue:** "I cast a blessing of accuracy on you."
>
> Mage rolls Defy → Success → Rogue gains **Aiming 2** [ ] [ ]
>
> **Rogue's turn:** "I shoot the distant target." (+1 Boon from Aiming, mark box → [X] [ ])
>
> **Next turn:** "I shoot again." (+1 Boon from Aiming, mark box → [X] [X] → Aiming ends)

### Example 2: Positional Buff
> **Mage:** "I cast flight on myself."
>
> Mage rolls Defy → Success → Mage gains **Flight 2** [ ] [ ]
>
> **Mage's turn:** "I fly up to the tower window." (fictional positioning used, mark box → [X] [ ])
>
> **Next turn:** "I fly across the chasm." (positioning used again, mark box → [X] [X] → Flight ends)

### Example 3: Greater Effect
> **Bard:** "I inspire the whole party with an epic battle hymn!" (invokes "Voice of Legend" Trait)
>
> Bard rolls Defy → Conflict + Greater Effect (Broad Effect chosen)
>
> All 4 party members gain **Inspired 2** [ ] [ ] (+1 Boon to bold actions for 2 uses each)
>
> Bard marks 1 Stress (Minor Consequence from Conflict)

### Example 4: Enemy Affliction
> **Rogue:** "I throw sand in the knight's eyes!"
>
> Rogue rolls Defy → Success → Knight gains **Blinded 1** [ ]
>
> **Fighter's turn:** "I attack the blinded knight!" (gains +1 Boon from Blinded, mark box → [X] → Blinded ends)
>
> Knight's Blinded Affliction made them an easier target for the Fighter's attack

### Example 5: Buff + Affliction Cancel
> **Fighter has Inspired 2** [X] [ ] (1 use left) and **Poisoned 2** [X] [ ] (1 tick left)
>
> Fighter rolls to Clash: Both apply to combat → +1 Boon (Inspired) -1 Bane (Poisoned) = net 0
>
> Both mark: Inspired [X] [X] → ends, Poisoned [X] [X] → ends
>
> Fighter shakes off poison while using last of inspiration

---

## What Changed From Previous System

| Aspect | Before | After |
|--------|--------|-------|
| **Duration** | "typically 1-2 actions" (vague) | Buff 2 (2 boxes, explicit) |
| **Tracking** | Informal memory ("you still have that bonus?") | Formal track with checkboxes |
| **Power scaling** | Unclear how Greater Effect affects duration | Buff 3 (one target, 3 uses) OR Broad Effect (multiple targets, 2 uses each) |
| **Fictional positioning** | "You have advantage from flight" (no clear expiration) | Flight 2 [ ] [ ] (mark when you leverage it, 2 uses) |
| **Stacking clarity** | Undefined | Refresh rule (same as Afflictions) |
| **Short Rest interaction** | Unclear | Buffs clear on Short Rest (same as Afflictions) |

---

## Design Philosophy

**Tracks unify resolution.** We already use tracks for:
- Harm (damage enemies)
- Will (persuade/break)
- Obstacle (overcome challenges)
- Countdown (escalating threats)
- Stress (resilience buffer)
- Afflictions (negative effects tick down)
- Burdens (lasting harm)

**Buffs complete the symmetry:**
- Afflictions = negative Character Tracks (tick down through use)
- Buffs = positive Character Tracks (tick down through use)

One underlying system. Eight applications. That's the game.

---

## What's Next

1. ✅ Buff tracks formalized in Chapter 3
2. ✅ Create Advantage updated in Chapter 2
3. ✅ Support toolkit updated in Chapter 5
4. ✅ Trait interactions updated in Chapter 6
5. ✅ Quick Start Guide updated
6. **Pending:** Update combat examples to show Buff usage
7. **Pending:** Update Part 4 Reference with Buff track summary
8. **Future consideration:** Defensive absorption Buffs (mark box instead of Stress)

---

## Open Questions (None)

All design questions resolved:
- Default size: 2 boxes ✅
- Greater Effect: Buff 3 OR Broad Effect ✅
- Refresh vs. stack: Refresh (same as Afflictions) ✅
- Coexist with Afflictions: Yes, they cancel but both mark ✅
- Typed defenses (Armor/Ward): Future work, generic +1 Boon for now ✅
