# Rune-Galdr

> Northmen Faction — Elite magic support / buffer

## Overview

The **Rune-Galdr** is a rare mystic and the primary support spellcaster of the Northmen. Spawning exclusively in major encampments (Large Camps, Leader Camps) and heavy warband raids, the Rune-Galdr avoids direct melee confrontations, maintaining a safe distance (8–16 blocks) behind friendly battle lines.

Fragile when isolated, the Rune-Galdr acts as a massive force multiplier when surrounded by Viking Raiders, Berserkers, and the Party Leader, siphoning life from enemies into a lifesteal pool and redistributing it to wounded allies.

---

## Visual Characteristics & In-Game Model

- **Model & Silhouette:**
  - Slender, gaunt humanoid (1.9 blocks tall), heavily hunched with an arched back.
  - Visual variants include both **female and male** elder mystic models.
  - Rough dark cloth wraps the waist and legs under a tattered pitch-black hood that shrouds most of the face; bone charms and runic talismans swing from the belt.
- **Weapon & Stave:**
  - Wields a tall weathered wooden staff splitting into a two-pronged fork at the crown (resembling a runic boundary marker). A luminous, floating runestone hovers in the crevice, casting steady ambient light.
- **Visuals & Runes:**
  - Every spell and effect manifests as glowing **Elder Futhark runes** etched into the ground or hovering over allies.

---

## Stats & Baseline Attributes

| Attribute | Value | Details |
|-----------|-------|---------|
| **HP** | Low (approx. 20 HP / 10 hearts) | Highly vulnerable if isolated |
| **Armor** | Minimal (0-2 armor points) | Wears no metallic protection |
| **Role** | Support / Disrupter | Never initiates aggression independently |
| **Combat Range** | 8–16 blocks | Actively kites to maintain standoff distance |
| **Spawn** | Large Camps, Leader Camps, heavy raids | Typically 1, rarely 2 |

---

## Unique Mechanic: The Lifesteal Pool

The Rune-Galdr harnesses an internal storage mechanic to siphon life from enemies and redistribute it to allies:

1. **Siphoning (Drain):** Projects a channel beam into a player, gradually siphoning hit points.
2. **Lifesteal Pool Storage:** Stolen vitality is channeled directly into an internal **lifesteal pool**. This vitality does not immediately heal the Rune-Galdr; it remains banked for tactical casting.
3. **Potency Decay:** The fluid vitality inside the lifesteal pool is volatile. The longer the Rune-Galdr retains it without discharging, the less potent its restorative output becomes.
4. **Allied Transfusion:** When a friendly frontline fighter drops low on HP, the Rune-Galdr discharges the lifesteal pool into that target, granting strong healing over time.
5. **Emergency Self-Sustain:** Should the Rune-Galdr drop to critical health with no protectors nearby, the lifesteal pool can be discharged inward to restore its own vitality.

---

## In-Depth Abilities

### 1. Rune Shield — Area Defensive Ward
Strikes the earth firmly with the base of the staff, emitting an expanding circular shockwave of luminous runic energy (azure, violet, or gold) spanning a 6-to-8-block radius. The wave deals no damage.
- **Targets:** All friendly vikings (up to 4) caught **inside the shockwave** gain an individual magical barrier.
- **First Hit (100% Negation):** Completely absorbs the very first incoming strike at **100% damage reduction**, regardless of severity (fully negates charged critical hits, explosions, or heavy arrows).
- **Subsequent Hits:** Absorbs the next 3 to 6 hits with a **40% to 60%** damage reduction, decaying as the barrier splinters.
- **Barrier Break:** Shatters completely into runic motes once hit capacity is depleted.

### 2. Life Steal — Targeted Siphon & Bank
Aims the staff at a player within 10–12 blocks, locking onto them with a crimson-violet runic beam.
- **Damage & Drain:** The target takes continuous ticking damage while connected.
- **Filling the Pool:** Every unit of health drained flows directly into the Rune-Galdr's **lifesteal pool**.
- **Allied Transfusion:** Discharges the banked vitality to wounded allies (prioritizing low-HP Berserkers and Party Leaders) for strong health regeneration.
- **Counterplay:** Siphon tethers break when breaking line-of-sight behind terrain or exceeding 12 blocks distance.

### 3. Repel Shockwave — Emergency Melee Defense
Slams the staff downward, releasing a kinetic burst of concussive wind and runic force that hurls attackers **5 to 8 blocks backward**.

### 4. Rune Lock — Targeted Crowd Control
Inscribes a glowing binding rune onto the ground beneath a player's feet (0.7s reaction window); failing to exit locks player feet for **3 seconds** (movement speed set to 0, though attacking and blocking remain available).

### 5. Battle Galdr — Line Reinforcement
Grants **Strength I** and **Speed II** for **7.5 seconds** to 2–3 nearby allied vikings (visible glowing rune above their heads).

### 6. Phase Shift — Reactive Blink
Upon taking damage, instantly dissolves into runic dust and teleports up to **8 blocks away** behind friendly shields or cover.

### 7. Rune Shard — Primary Ranged Attack
Fires small, swift crystalline darts of runic energy dealing light damage at 12–14 blocks range.

### 8. Staff Strike Flurry — Emergency Melee Combo
Swift 5-hit sequence using the wooden staff, finishing with a knockback shove.
