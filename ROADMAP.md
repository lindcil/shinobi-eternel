> ✅ v4.3 Reactions Expansion : livrée. v4.3 Reactions Expansion — fait
> ✅ v4.2 Combat & Animation : livrée. v4.2 Combat & Animation — fait
> ✅ v4.1 Skill Tree Constellation : livrée. v4.1 Skill Tree Constellation — fait
> ✅ v4.0 Living Open World : livrée. v4.0 Living Open World — fait
> ✅ v3.9 QoL & Progression : livrée. v3.9 QoL & Progression (fait)
> ✅ v3.8 Maîtres Update : livrée. v3.8 Maîtres Update (fait)
> ✅ v3.7.4 Kage Bunshin : livrée. v3.7.4 Kage Bunshin (fait)
> ✅ v3.7.3 Roue fluide : livrée. v3.7.3 Roue fluide (fait)
> ✅ v3.7.2 Animation Update : livrée. v3.7.2 Animation Update (fait)
> ✅ v3.7.1 Équilibrage du chakra : livrée. v3.7.1 Équilibrage du chakra (fait)
> ✅ v3.7 Visual & Character Update : livrée. v3.7 Visual & Character — UI encre, animations cohérentes, accessoires équipables (fait)
> ✅ v3.6 Modes Rework Update : livrée. Sharingan 8 paliers, Jinchūriki par queue, 5 éléments, ultimes en duo.
> ✅ v3.5 Open World Update : livrée. Monde ouvert, maîtres, QTE, apprivoisement, 30 événements.
> ✅ v3.4 Combat Basics Update : livrée. Combos, Shunshin, chocs de projectiles, Bijūdama nucléaire et QTE.
> ✅ v3.3 Secret & Unique Technique Update : livrée le 19/10/2026 (techniques secrètes, tags, movesets, Arène 1v1, chakra sur C).

# Shinobi Éternel II — Roadmap of themed updates

**Studio rule:** one update = one theme. Each update has a clear goal, a closed list of features, and acceptance criteria tested headless (0 console errors, save compatible, Notes de version tab updated, screenshots, zip). No "little of everything" updates.

| Version | Theme | Status |
|---|---|---|
| 3.0 | Voie des Modes (staged modes, wheel, chakra variants) | Shipped |
| 3.1 | Réaction Update | **Shipped** |
| 3.2 | Bijū Update | **Shipped** |
| 3.3 | Secret & Unique Technique Update | ✅ Shipped |
| 3.4 | Invocation Update | Proposed |
| 3.5 | Village & Team Update | Proposed |
| 3.6 | Taijutsu & Kenjutsu Update | Proposed |
| 3.7 | Akatsuki Update (story) | Proposed |
| 3.8 | Online & Ranked Update | Proposed |

---

## v3.1 — Réaction Update (shipped)
**Goal:** make element mixing the heart of combat, and keep it readable.

**Features**
- Elemental marks (炎 風 水 雷 土) shown above enemies with a duration ring.
- A reaction table with 10 pairs: Fire Storm, Electrocution, Mire, Blinding Steam, Storm, Lava, Sandstorm, Blizzard, Plasma, Magnetism.
- Six special reactions:
  - Mirage and Nightmare (genjutsu).
  - Sharingan, Byakugan and Rinnegan bonuses.
  - Ally Combo.
- On-screen reaction names, a reaction feed, and distinct effects per reaction.
- Status icons above every enemy.
- Enemies that resist an element (盾), "Alchemist" enemies that use reactions, and A-rank enemies that take less from reactions.
- Réactions tab (grid and Codex), plus 2 tutorial steps.

**Acceptance criteria (met)**
- All 10 pairs trigger in the headless test.
- An ally combo and a dōjutsu bonus have been observed.
- An Alchemist casts with a warning circle.
- Tutorial is 20/20 steps.
- 0 console errors, v3.0 save loads.

## v3.2 — Bijū Update (shipped)
**Goal:** the nine tailed beasts each have a strong, distinct identity.

**Features**
- The 9 canonical bijū with their own kit (V1, V2, full form, Chakra Mode), silhouette, and Bijūdama colour and size.
- Bond / partner system (5 levels).
- Capture fights with a sealing phase.
- Enemy jinchūriki that use staged modes.
- Bijū tab.

**Acceptance criteria (met)**
- 9 distinct bodies (`body: 'bj'`), and 9 kits executed with no errors.
- An enemy jinchūriki reaches the final stage.
- Sealing → the beast is added to `p.beasts`.
- 0 console errors, saves compatible.

## v3.3 — SECRET & UNIQUE TECHNIQUE UPDATE (✅ shipped 19/10/2026)
**Goal:** more secret techniques, and a technique UI you can sort by role.

**Features**
1. **12 new secret techniques**, at least one per clan plus 3 neutral, each with a unique effect and sound. Examples:
   - Hiraishin (marked teleport).
   - Kamui (target vanishes for 2 s).
   - Eight Gates (stacking self-buff that costs HP).
   - Sand Burial.
   - Hiding in Ash.
   - Amaterasu Shield.
   - Puppet Theatre.
   - Bunshin Daibakuha.
2. **Tags / subcategories** on every technique: Mobilité, AoE, Projectile, Mêlée, Contrôle, Soutien, Défense (2 maximum per technique), shown as coloured pills.
3. **Filtering** by tag:
   - In the Library and in Préparation (multi-select chips, combined with element and rarity).
   - In the in-game wheel: a "filter" key cycles through tags.
4. **Unlock through challenges:**
   - Each secret technique has a dedicated mission (e.g. "Hit 5 enemies with a single Kamui").
   - Shown in a Secrets tab with a progress bar.
5. **Secret mastery:** 3 levels that change the effect (not just the damage).

**Acceptance criteria**
- 100 % of TECH entries have at least 1 tag, checked by an automated test.
- Filtering works in the Library, Préparation and the wheel (keyboard, gamepad, touch).
- Each new secret technique has been cast headless without errors and has a challenge that can be completed.
- 0 errors; saves from v3.2 load, and existing secrets are kept.

## v3.4 — Invocation Update (proposed)
- **Goal:** summoning contracts as a third axis next to modes.
- **Features:**
  - 6 contracts (toads, snakes, slugs, hawks, dogs, monkeys), each with 3 summon sizes.
  - Sage Mode tied to the contract, as a 3-stage mode.
  - Combined summon + jutsu (oil + fire, etc.).
  - Contracts tab.
- **Acceptance criteria:**
  - Each summon has a distinct AI and silhouette.
  - Sage Mode follows the modes rules (wheel, stages, aura).
  - 0 errors.

## v3.5 — Village & Team Update (proposed)
- **Goal:** a living team of three.
- **Features:**
  - Recruitable teammates with personalities and their own build.
  - Team jutsu (combos with two people).
  - Village reputation and a mission board by rank.
  - Sensei who unlocks techniques.
- **Acceptance criteria:**
  - Ally bots use reactions and combos.
  - 3 team jutsu work with bots.
  - The team is saved.

## v3.6 — Taijutsu & Kenjutsu Update (proposed)
- **Goal:** real, deep melee.
- **Features:**
  - Frame-data combos and cancels.
  - Parry and perfect counter.
  - Martial styles (Gōken, Jūken, Kenjutsu styles).
  - The Eight Gates as a 4-stage mode.
  - Weapons with movesets.
- **Acceptance criteria:**
  - 3 full styles.
  - The Eight Gates mode follows the modes rules.
  - Combo inputs are readable on touch.

## v3.7 — Akatsuki Update (proposed)
- **Goal:** a story arc and 10 iconic bosses.
- **Features:**
  - A 10-stage chapter.
  - Bosses with phases (Pain/Rinnegan, Itachi/genjutsu, Kisame/Samehada, Deidara/explosions, Sasori/puppets…).
  - Cutscenes rendered in the engine.
  - Rewards: cosmetics and a cloak.
- **Acceptance criteria:**
  - Each boss has at least 3 phases and a unique mechanic.
  - The chapter can be finished solo and in a duo.

## v3.8 — Online & Ranked Update (proposed)
- **Goal:** stable PvP.
- **Features:**
  - Ranked 1v1/2v2.
  - Balancing of modes and reactions for PvP.
  - Replays.
  - Spectator mode.
- **Acceptance criteria:**
  - Network test with 2 clients.
  - Balance pass on modes (bijū/dōjutsu caps in PvP).
