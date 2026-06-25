# Vantage & Stakes Integration Summary

## What We Built

Two new core frameworks inspired by Grimwild Community Edition, Chasing Adventure, Blades in the Dark, and Dungeon World 2:

### **Vantage** ([vantage.md](vantage.md))
**Vantage is your difficulty system** — determines when to roll and how many Banes.

**The Four Tiers:**
- **Certain** → Auto-success (no roll)
- **Reasonable** → Standard roll (no modifier)
- **Doubtful** → Roll with 1-2 Banes
- **Impossible** → Cannot attempt

**Key Features:**
- Replaces separate "Easy/Standard/Hard/Very Hard" difficulty scale
- Emphasizes collaborative conversation between GM and players
- Players advocate for their positioning, GMs explain reasoning
- Three Questions tool for quick assessment
- Explicit connection to Stakes (complementary systems)

---

### **Stakes** ([stakes.md](stakes.md))
**Stakes frame danger** — adjusts consequence severity.

**The Three Levels:**
- **Low Stakes** → Reduce Consequence Tier by 1 (Conflict = narrative only)
- **Regular Stakes** → Standard consequences (default, no adjustment)
- **High Stakes** → Increase Consequence Tier by 1 (Conflict = 2 Stress)

**Key Features:**
- Simple tier adjustment (±1, with floor/ceiling)
- No special resolution tables—uses existing Consequence framework
- "The greater the stakes, the clearer the communication"
- Works independently from Vantage (can mix: Doubtful + Low Stakes, Reasonable + High Stakes)

---

## How They Work Together

**Vantage and Stakes are independent but complementary:**

| Dimension | What It Determines | Adjustment |
|-----------|-------------------|------------|
| **Vantage** | Can you attempt? How difficult? | Banes to dice pool (0, 1, 2) |
| **Stakes** | How dangerous is failure? | Consequence Tier adjustment (±1) |

**Examples:**
- Climbing training wall without rope → **Doubtful (1 Bane) + Low Stakes** → Hard but safe to fail
- Expert climbing easy cliff over lava → **Reasonable + High Stakes** → Easy but deadly to fail
- Non-climber scaling difficult cliff over lava → **Doubtful (2 Banes) + High Stakes** → Hard AND deadly (seek alternate approach!)

---

## Where They're Integrated

### **04-action-resolution.md** (Player-facing)
- **"When to Roll"** section → Brief Vantage summary with 4 tiers
- **"GM Assesses & Telegraphs"** section → Added Vantage + Stakes assessment
- Links to full frameworks for details

### **07-gm-guide.md** (GM-facing)
- **"Setting Vantage (Difficulty)"** section → Replaced old difficulty system with Vantage
- **"Setting Stakes (Danger)"** section → New section on Stakes calibration
- **"Consequence Calibration Guide"** → References Stakes for severity adjustment
- Removed old "Setting Difficulty" section (replaced by Vantage)
- Removed old "Adjudicating Vantage" section (replaced by new Vantage summary)

---

## Design Principles Applied

**From Grimwild Community Edition:**
- Vantage scale as unified difficulty system (Certain/Reasonable/Doubtful/Impossible)
- Stakes as consequence severity calibration
- "The greater the stakes, the clearer the communication"

**From Chasing Adventure:**
- Three Questions framework (Can they? How difficult? Is failure interesting?)
- Examples of when NOT to roll (sword vs dragon hide, shooting tied-up target)

**From Blades in the Dark:**
- Vantage as collaborative conversation, not unilateral ruling
- Players advocate for positioning, GMs explain reasoning
- Setting precedents through consistent rulings

**From Dungeon World 2:**
- Fictional positioning as shared responsibility
- "A pixie can't swing a greataxe unless magic explains it"
- Everyone clarifies what's happening in fiction

---

## What Changed from Original Design

### **Simplified:**
- ✅ Collapsed separate "Difficulty" and "Vantage" into single Vantage scale
- ✅ Stakes just adjusts Consequence Tier (±1) instead of special tables
- ✅ No more "Easy/Standard/Hard/Very Hard" terminology

### **Clarified:**
- ✅ Vantage determines WHEN to roll and HOW MANY Banes
- ✅ Stakes determines consequence SEVERITY
- ✅ They work independently (can mix Doubtful + Low Stakes, etc.)
- ✅ Consequence Tier cannot go below Minor (→ narrative) or above Severe

### **Emphasized:**
- ✅ Vantage is a conversation between GM and players
- ✅ Players should advocate for better positioning
- ✅ GMs should explain reasoning and set precedents
- ✅ Fiction first—if it doesn't make sense, it can't happen

---

## Quick Reference for GMs

**Before calling for a roll, ask:**

1. **What's their Vantage?** (Can they attempt? How difficult?)
   - Certain → Auto-success
   - Reasonable → Standard roll
   - Doubtful → 1-2 Banes
   - Impossible → Cannot attempt

2. **What are the Stakes?** (How dangerous is failure?)
   - Low → Reduce Consequence Tier by 1
   - Regular → Standard (default)
   - High → Increase Consequence Tier by 1

3. **Is failure interesting?**
   - No → Don't roll, let it happen
   - Yes → Call for roll

**Result:** Clear, consistent rulings that respect fiction and player agency.

---

## Files

- **[vantage.md](vantage.md)** — Complete Vantage framework (16KB)
- **[stakes.md](stakes.md)** — Complete Stakes framework (8KB)
- **[04-action-resolution.md](04-action-resolution.md)** — Integrated player-facing summaries
- **[07-gm-guide.md](07-gm-guide.md)** — Integrated GM-facing summaries

Both core documents link to full frameworks for deep reference.
