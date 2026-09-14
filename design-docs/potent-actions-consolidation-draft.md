# Potent Actions Consolidation - Draft Updates

## Current State Analysis

**Chapter 2 (lines 356-417):** Full canonical explanation
- What Potency Grants (Edge +1, Expanded Possibility, Scale Enhancement)
- Complete scale dimensions table
- How It Works (5-step process)
- Examples (Champion, Hunter, Sage, Vanguard)
- Interaction with Special Effects

**Chapter 9 (line 23):** Already condensed
- Brief definition with pointer to Ch. 2
- Design note about "Push Yourself to Potent" pattern (lines 471-472)

**Chapter 10 (lines 276-299):** Partially condensed but still repeats scale dimensions
- Points to Ch. 2 framework
- Re-lists the three scale dimensions (Heightened/Widespread/Extended)
- Magic-specific examples table

## Proposed Changes

### Chapter 9: Keep As-Is (Already Condensed)

Current line 23:
```markdown
**Potent:** An extraordinary effect that exceeds normal success — grants Edge +1, can unlock otherwise impossible actions, and enhances scale along one dimension (Heightened Impact, Widespread Effect, or Extended Duration). See **Chapter 2: Potent Actions** for the complete framework.
```

Current lines 471-472:
```markdown
**The "Push Yourself to Potent" Pattern:**
Most Talents combine passive competence (Expertise or Edge) with an active extraordinary option (Push Yourself → Potent effect). This creates a clear economy: you're always good at your domain (Expertise), and you can spend Stress to be *amazing* at it (Potent). The Stress cost makes it a genuine decision, not a default.
```

**KEEP BOTH** - These are appropriately brief.

---

### Chapter 10: Condense Further

**REPLACE lines 276-299 with:**

```markdown
### Potent Spells — Extraordinary Magic

**Potent Spells use the Potent Action framework** (see Chapter 2 for complete rules: Edge +1, Expanded Possibility, and scale enhancement via Heightened Impact, Widespread Effect, or Extended Duration).

**How to access Potent Spells:**
- **Sphere Mastery** (Sage) — Push Yourself to perform a Potent feat of magical theory within your mastered Sphere
- **Channel Divinity** (Mystic) — Push Yourself to perform a Potent miracle within your domains
- Other Talents that explicitly grant Potency in their domain

**Cost:** Mark 1 Stress to Push Yourself. Sage's Efficient Casting can be marked instead.

**Magic-specific scale examples:**

| Spell | Normal | Heightened | Widespread | Extended |
|-------|--------|------------|------------|----------|
| Stone Wall | Barrier, 1-2 actions | Nearly indestructible | 2-3 walls or much larger | Lasts entire scene |
| Fireball | Mark Harm, single target | Bypasses fire resistance | Small group affected | — |
| Charm | Mark Will, 1-2 actions | Affects resistant targets | Multiple people | Lasts entire scene |
| Invisibility | 1-2 actions | Undetectable (all senses) | Small group invisible | Lasts entire scene |

**Default Spell Durations:**

| Duration | When | Examples |
|----------|------|----------|
| **Instantaneous** | Effect happens once | Damage, healing, teleportation, dispelling |
| **Moment** | Lasts 1-2 actions | Buffs, barriers, constructs, summoned effects |
| **Scene** | Only via Potent + Extended Duration | Long-lasting protections, persistent effects |
| **Permanent** | Ritual only | Enchanted items, wards, consecrated ground |

Effects beyond Potent Spell scope — resurrection, binding entities, permanent enchantments, grand workings — are **Rituals**: structured scenes requiring preparation, components, and time, not single rolls. See the **Rituals** section below.
```

---

## Changes Summary

### Chapter 9: No Changes
Already appropriately condensed with pointer to Ch. 2.

### Chapter 10: Reduced by ~30 words
**Removed:**
- Re-explanation of the three scale dimensions (already in Ch. 2)
- "applied to magic" redundancy

**Kept:**
- Pointer to Ch. 2 for complete rules
- How to access (Sage vs Mystic)
- Cost explanation
- Magic-specific examples table (this IS unique to Ch. 10)
- Duration table (this IS unique to Ch. 10)
- Ritual pointer

**Result:** Ch. 10 now focuses on "how Potency works in magic context" rather than re-teaching what Potency is.

---

## Benefits

1. **Single Source of Truth:** Ch. 2 is canonical, Ch. 9/10 defer to it
2. **Easier Maintenance:** If Potency rules change, only update Ch. 2
3. **Cleaner Reading:** Ch. 10 readers who want full details know exactly where to look
4. **Domain-Specific Focus:** Ch. 10 focuses on magic-specific applications (the table), not re-teaching general concepts

---

## Alternative: Even More Aggressive Condensation (Not Recommended)

Could reduce Ch. 10 to just:
```markdown
### Potent Spells
See Chapter 2: Potent Actions for complete rules. Sages access via Sphere Mastery, Mystics via Channel Divinity. Mark 1 Stress to Push Yourself (Sage's Efficient Casting can be marked instead).
```

**But this loses the valuable magic-specific examples table.** The current proposed version strikes the right balance: defer to Ch. 2 for general rules, keep domain-specific content.
