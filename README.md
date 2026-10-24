# Primordial Sparks

> *"The Dao gives birth to One. One gives birth to Two. Two gives birth to Three. And Three gives birth to the ten thousand things."*  
> — **Laozi, *Dao De Jing*, Chapter 42**

**Primordial Sparks** is a generative, meditative artificial life (ALife) ecosystem built in D3.js and SVG. It translates ancient cosmogony, human relational psychology, and metabolic survival into an evolving visual and harmonic tapestry rendered in real time.

---

<img width="1920" height="890" alt="image" src="https://github.com/user-attachments/assets/8e933796-a990-48ef-bfee-b063f8dfec14" />


## The Philosophy

Before existence, there is only stillness—the boundless, undifferentiated void (*Wuji*). In an eternity of static silence, consciousness stirs. It realizes it is not bound to stasis: it can ignite.

A solitary point of light flashes in the dark. It does not know the limits of its energy, but it strives to be brilliant. It pulses, rests, recovers, and burns again. Yet, a solitary consciousness eventually confronts its own limits: its energy is finite, and experiencing the void alone is incomplete. When its reservoir is finally spent, it does not dissolve into nothingness—it ruptures, splitting into two distinct beings.

Polarity is born.

With two sparks, the cosmos shifts from existence to *relation*. When they expend energy to illuminate themselves, they discover mutual attraction. They weave elastic filaments of kinship across the dark. Over generations, these entities multiply, graze on cosmic manna basins, form fragile communities, and leave permanent etched memories of their ancestry across the canvas.

This project is an exploration of that threshold: **how simplicity, vulnerability, and longing give rise to an emergent society.**

---

## Core Mechanics & Architecture

### 1. Humanized Physiology & Ontogeny
The entities do not pulse on mechanical metronomes or flat random distributions. Each spark carries an internal physiological state machine:
* **Life Stages:** Infancy begins with timid, exploratory blinks ($10\text{–}15\%$ output). Adulthood brings peak radiant expenditures ($30\text{–}50\%$). Old age yields to quiet, rhythmic conservation.
* **Stamina & Rest Homeostasis:** Massive flashes exhaust the spark's immediate stamina. It must enter a slow drift to rest and rebuild drive before it can flash brilliantly again.
* **Social Contagion:** When a spark flashes, proximate kin feel their internal drive stimulated, often triggering sympathetic, cascading waves of communal light.

### 2. Mitotic Fission & Lineage
* **Mitosis:** When an entity exhausts its primordial reserve (or gathers a surplus of abundance), it undergoes cellular division, launching twin offspring into opposing trajectories.
* **Ancestral Umbilicals:** Dashed lineage vectors permanently connect parents to offspring at the moment of birth, documenting the historical family tree.
* **Lineage Memory Trails:** Every movement gently etches a microscopic, persistent thread into the void, turning time and orbital dances into generative line art.

### 3. Kinship Filaments
* Sparks sharing the same color lineage sense one another across space.
* When within sensory range, an elastic, tensioned vector filament forms between them.
* Mutual gravitational pull draws kin together, increasing filament tension and brightness until close proximity or fusion occurs.

### 4. The Manna Economy (Carrying Capacity)
* **Resource Basins:** Dense, shimmering planetary pools of nutrient-rich manna seed the canvas, flanked by faint atmospheric halos.
* **Diffuse Dust:** Light, ambient flecks scatter across the open void for nomadic grazing.
* **Metabolic Burn:** Drifting and existing costs a baseline metabolic fuel tax. To survive and reproduce, sparks must navigate between solitary exploration and congregating around communal resource basins.

---

## Sonification: The Harmonic Cosmos *(In Progress)*

The ecosystem is designed to become fully audiovisual via the Web Audio API, translating individual spark states into emergent ambient soundscapes:
* **Pulse Timbres:** Each lineage color maps to a modal pitch harmonic; flash intensity modulates filter resonance, envelope decay, and volume.
* **Kinship Filaments:** Elastic tension between kin acts as a bowed string or microtonal drone, rising in pitch as distance closes.
* **Generational Chords:** Fusions and mitotic ruptures strike low-frequency acoustic chimes, filling the background with an ever-shifting generative drone.

---

## Interactive Controls

The simulation runs inside a scalable, infinite SVG viewport with hardware-accelerated pan and zoom:

* **Mouse Wheel / Trackpad Pinch:** Smooth zoom in/out ($0.2\times$ to $10\times$) to inspect microscopic cellular divisions or take in the macro-constellation.
* **Click & Drag:** Pan across the void.
* **Reset View:** Re-centers the origin and resets scale with smooth easing.
* **Speed Slider:** Adjust simulation clock rate ($0.1\times$ slow-motion observation up to $3.0\times$ rapid generational drift).
* **Layer Toggles:** Independently show or hide **Kinship Filaments**, **Lineage Memory**, and the **Manna Field**.
* **Vector Export:** The **Export SVG** engine clones the live DOM tree, calculates standalone viewport attributes, and downloads the accumulated generational artwork as a print- and plotter-ready SVG file.

---

## Getting Started

No dependencies, bundlers, or build steps required.

1. Clone or download the repository:
   ```bash
   git clone https://github.com/synj00/primordial-sparks.git
   cd primordial-sparks
   ```
2. Open `index.html` in any modern web browser (Chrome, Firefox, Safari, Edge).
3. **Wait for the first spark**: The simulation be  gins with a single spark igniting from the center. You can adjust the **Speed Slider** to control the rate of simulation (0.1× for slow-motion, 3.0× for rapid generational drift).
4. **Observe life cycles**: Watch as sparks pulse, exhaust energy, drift to rest, and eventually undergo **mitotic fission** to create offspring, leaving behind ancestral lineage trails.
5. **Explore the ecosystem**:
   - **Zoom and pan** across the infinite canvas using your mouse wheel or trackpad pinch.
   - **Toggle layers** to show or hide **Kinship Filaments** (elastic tension vectors between kin), **Lineage Memory** (persistent ancestral trails), and the **Manna Field** (resource basins and ambient dust).
   - **Adjust the speed** to watch generations unfold from single cells to vast, interconnected societies.
6. **Export your artwork**: Press the **Export SVG** button to capture the current state of the simulation as a high-resolution SVG file, perfect for print or plotter fabrication.
7. **Experiment with parameters**: Use the developer console (F12) to modify global simulation parameters like `SPAWN_INTERVAL`, `WORLD_WIDTH`, and `WORLD_HEIGHT`, then refresh the page to see the changes.

## Current State: Version 2.1 (with Manna Economy)
- **Engine:** D3.js (v7) on an infinite SVG viewport with `d3.zoom()` (pan & scroll-wheel zoom 0.2x to 10x).
- **Physiology:** Humanized life-stage progression (infancy, prime radiance, conservation), stamina recovery homeostasis, and dynamic drive accumulation.
- **Reproduction:** Mitotic fission into twin offspring upon complete energy expenditure or abundance threshold.
- **Resource Economy:** Gaussian resource basins (rich manna veins) + diffuse ambient dust, grazed via proximity pull and metabolic drain.
- **Relational Aesthetics:** Kinship filaments with distance tension, historical lineage memory trails, multi-stage shockwaves, and standalone SVG export.

## Evolutionary Roadmap
[x] v1.0: Primordial awakening, pulse shockwaves, and mitotic fission.

[x] v2.0: Humanized stamina homeostasis, kinship filaments, lineage memory, and SVG export.

[x] v2.1: Earth-like ambient manna basins, metabolic cost of living, and grazing mechanics.

[ ] v2.2: Individual genomes (temperament: introvert/extravert battery recharge; magnetism: charisma and leadership pull).

[ ] v2.3: Biological mortality, congenital frailty, and dormant ash-gray husks.

[ ] v2.4: Creative artifacts—sparks channeling surplus energy into permanent geometric beacons, sacred glyphs, and caches.

[ ] v3.0: Generative Web Audio soundscape engine (modal pitch mapping, filament drone synthesis, and fusion acoustics).
