> Repository integration: optional reference material for the root [Director Storyboard Skill](../../导演分镜-SKILL-2.0.md). Read the integration rules at the beginning of [SKILL.md](SKILL.md) first. Original source text follows; platform capabilities and empirical claims have not been independently verified.

<div align="center">

# ⚔️ Real Combat Director

## **V1.0 — Technique Enhanced** · 真人写实打斗导演系统

> 🥊 An industrial action-design system for **photoreal live-action fight scenes** in AIGC,
> plus **Seedance 2.5 / 2.0** prompt production — built to be driven by an AI agent / LLM
> 👥 Includes **small-scale multi-opponent choreography** (2–4 on screen: 1v2 / 1v3 / 2v2 / 3v3)

![Version](https://img.shields.io/badge/version-V1.0--technique%20enhanced-6a5acd)
![Tier](https://img.shields.io/badge/tier-R1%20realistic%20restrained-00b4d8)
![Multi](https://img.shields.io/badge/multi--opponent-1v2%20%7C%201v3%20%7C%202v2%20%7C%203v3-ff6b6b)
![Rulebooks](https://img.shields.io/badge/rulebooks-11%20modules-2ec4b6)
![Files](https://img.shields.io/badge/files-13-2ec4b6)
![Model](https://img.shields.io/badge/model-Seedance%202.5%20%7C%202.0-9d4edd)
![QC](https://img.shields.io/badge/QC-P0~P2%20gates-ff6b6b)
![Platform](https://img.shields.io/badge/platform-OpenClaw%20%7C%20Coze%20%7C%20Dify%20%7C%20WorkBuddy-ff9f43)
![Stars](https://img.shields.io/github/stars/lixiaoxiao9888-create/real-combat-director?style=social)

[简体中文](README.md) ｜ **English**

---

### 🎬 The Prompt-Rewrite Pipeline

```
📥 Take in a fight prompt → 🔍 Diagnose against the ironclad rules → 🎯 Break down moves via the 11-link chain
→ 🎥 Shot design by the 5 specs → 🚀 Package into the 7-segment format → ✅ P0~P2 machine check → 📄 Deliver
```

</div>

---

## 🧭 What this is

A **rule library an AI agent executes** (an OpenClaw skill / agent skill pack) — not a prompt-template dump. Drop `SKILL.md` and `references/` into your agent's skill directory and it's ready.

**It has one core job: rewriting fight prompts.**

Hand it an **existing fight prompt** — yours, someone else's, adapted from a novel, or just scribbled — and it rewrites it into a **7-segment deliverable you can paste straight into the video model**, fixing the defects along the way.

## 🚫 What it fixes

| # | Defect | Why it must be fixed |
|:---:|:---|:---|
| 1 | **Static beats** (standoff / charge-up / hang / pose-and-hold) | AI video cannot do "still performance" — it renders as a **frozen mannequin** |
| 2 | **Plant-and-trade fighting** (both stand still, alternating blows) | Contradicts real striking mechanics — a P0 blocker |
| 3 | **Abstract fight words** ("rapid exchange", "swings a punch", "brawl") | No impact, no contact point — the model renders a hand wave |
| 4 | **VFX words** (light wave / shockwave / magic circle / particles) | Banned in the R1 realistic tier — they turn it into fantasy |
| 5 | **Gore that gets blocked** (snap his bones / blood everywhere) | Platforms block it; must be translated into physical force description |
| 6 | **Copying the form** (reciting a 12-move kata in order, "A→B→C" arrow chains) | Those are form sequences, not fight sequences |
| 7 | **90° head-on mid/wide shots** | Cheap arcade side-scroller feel; kills depth |
| 8 | **Mixing version syntax** (writing 2.5's `{}` / `<>` inside a 2.0 prompt) | The two versions' contracts are fully split; mixing = broken output |
| 9 | **Multi-opponent "taking turns"** (A strikes, steps back; B strikes) | Multi-opponent plant-and-trade = P0; anyone not in turn renders as standing by |
| 10 | **Identical outfits causing cloning** (three identical suited men = one man copied thrice) | Needs ≥2 distinguishing traits per person + dedicated negative words |

## 🎯 Use cases

- **Modern combat** — underground boxing / gym sparring / street brawl
- **Cop-vs-criminal chase** — alley encounter / parking-lot takedown
- **Suspense assassination** — close-quarters grapple / joint lock
- **Comedic fight** — prop betrayal / self-inflicted hit
- **Kid-friendly fight** — safely translated action
- **Small-scale multi-opponent** — 1v2 / 1v3 / 2v2 / 3v3 (manhunt · two-on-one · small brawl), per `references/multi-opponent-rules.md`

> Non-VFX oriented. It deliberately **does not absorb** the R2 commercial-hype or R3 fantasy-ultimate systems (effect growth trilogy, dual-color particle clash, magic circles / divine phenomena, etc.).

## 🔥 Core capabilities

| Stage | Capability | Description |
|:---:|:---|:---|
| 📋 **Pre-locks** | Forced choices | **A** model version (Seedance 2.5 / 2.0) + **B** aspect ratio (16:9 / 9:16 / 21:9) — if unspecified, **no writing starts**; defaults are forbidden |
| 💥 **Move design** | 11-link kinetic chain | Force from the ground → hip/torso torque → spine transmission → millimetre contact point → flesh/bone deformation → next strike inherits state; mandatory for every key strike |
| 🥋 **Techniques** | 19 martial styles + 9 sword sets | Modern (Muay Thai / Sanda / Karate / Boxing / MMA) + traditional Chinese (Xingyi / Baji / Wing Chun / Bagua / Taiji / Shaolin / Chin Na) + weapons |
| 🛡️ **Defence** | 3-state collapse + exaggerated evasion | Full → broken guard → messy transition, continuous; "recover instantly after a break" is banned; tiny sidesteps are banned |
| 🎥 **Camera** | 5 specs + spatial rules | Shot size · angle · camera move · follow target; 90° head-on banned for mid/wide; camera-action semantic binding; hit-reaction toolbox |
| 📐 **Rhythm** | Beat arc + 3 hard rules | Engage → probe → pressure → break → reverse/settle; same rhythm ≤5s; fast-slow breathing |
| 💢 **Impact** | 4 impact tiers + air dynamics | Light micro-recoil → heavy deformation & displacement → finishing chain damage; no air-burst blasts — dust/water/cloth sell the air |
| 🚀 **Feeding** | 7-segment master format | 【Canvas/Style】→【Scene asset】→【Core characters】→【Stance declaration】→【Timeline storyboard】→【Sound】→【Hard prohibits】; copy the whole block to feed |
| ✅ **QC** | P0~P2 gates + checklists | Aspect consistency / axis crossing / static beats / word limit / VFX words / gore words / shot-length rhythm; 3-step re-verification after any edit |
| 👥 **Multi-opponent** | Choreography for 2–4 on screen | Single hero anchor (focus plane ≤2) · **primary/secondary axis** dual-layer management · **three-beat rotation** (press in / knocked back / circling; ≥1s with no movement and no impact = standing by = P0) · multi-opponent arc (engage → surrounded → **break point** → pick them off → settle) · anti-cloning (≥2 distinguishing traits per person + dedicated negatives) |
| 🛡️ **Compliance** | Safe-translation dictionary | High-risk words across impact / facial trauma / lethal strike / environment damage / blades → compliant rewrites (pass rate not guaranteed) |

## 📏 Three hard rhythm rules

> Violating any = **P0 blocker**. These three separate this pack from "just copying a technique library".

**① Machine-gun close-quarters exchange**
Every close-exchange beat uses a **serialized move chain**: **6–10 strikes within 2–3 seconds**, **zero gap between strikes** (throw-and-retract, retract-and-throw), and the defender **reacts differently to each strike while moving with footwork**. Vague wording like "the two exchange blows rapidly" is banned.

**② Overcrank / slow-motion defaults to 0**
Empirically it destroys rhythm. Allowed only on explicit request and ≤1s total; a 1–2 frame hit-stop at contact is **2.5 only** and doesn't count as overcrank.

**③ Plant-and-trade fighting is banned**
Both fighters standing still and alternating blows, or playing out a whole form in place = blocked. Every technique must **ride on footwork displacement or weight transfer** (step-in / lateral cut / retreat / position swap / low drop).

> **Take the spirit, not the form**: the technique library only supplies ① move names & outward shape, ② force principle & direction, ③ strike target & impact feedback. Sequencing and rhythm always follow this pack — **never copy the library's form order or arrow chains.**

## 👥 Multi-opponent (2–4 on screen)

> ★ Single source of truth: `references/multi-opponent-rules.md`. Triggered by "two or more fighting on screen / outnumbered / one-vs-many / encircled / group fight / 2v2 / 3v3" → **mandatory read**. It **overrides** the 1v1 defaults (axis lock / opening framing / stance declaration / shot-size strategy); the six ironclad rules stay in force.

| Mechanism | Rule |
|:---|:---|
| **Headcount cap** | 2–4 on screen; **≤3 actively engaged** in one shot; **no close-up with ≥3**; 5+ → split into 2–4 person sub-scenes |
| **Single hero anchor** | All camera work revolves around the hero; **the hero must be present in every main-line shot**; **focus plane ≤2** (a third person only as moving foreground / out-of-focus silhouette) |
| **Multi-axis management** | **Primary axis** (hero ↔ current main opponent, locked, no crossing) + **secondary axes** (others' side positions, never reversed within a shot); axis switching has exactly three legal triggers (knocked back / active turn / new threat entering) — **no instant cuts** |
| **Three-beat rotation** | At most one person actually contacts the hero at a time; everyone else must be **pressing in / knocked back / circling**; any character **≥1s with no displacement and no impact = standing by = P0** |
| **Multi-opponent arc** | Engage → surrounded → **break point** → pick them off (**accelerating**) → settle; the 8–12s pivot moves from "reversal" to the "break point" |
| **Ensemble camera** | The more people, the tighter the lens: over-the-shoulder to reveal the second person, layered blocking when several share the frame; **the eye-line cut becomes mandatory** (hero looks at a new threat → the next shot must cut to it) |
| **Anti-cloning** | Every non-hero needs **≥2 distinguishing traits** (build / hair / costume / weapon / stance habit); add negatives `same person repeated / costumes swapped / merged bodies / identical faces` |
| **Length & shots** | 1v2 → 4–5 shots; 1v3 → 5–6 shots; 2v2 / 3v3 → split into 2 groups (one primary axis each) |
| **Stance declaration** | Switch to a **three-line form**: primary-axis line (with axis lock) + secondary-axis line + full-cast movement line (per person `start→end` + reason) |

## ⚙️ Quick start

**Install** — drop `SKILL.md` and `references/` into your agent's skill directory:

```
# OpenClaw
~/.openclaw/workspace/skills/real-combat-director/
```

**Minimum execution sequence for the AI agent**:

```
Read SKILL.md → complete lock A (model version) + B (aspect ratio)
→ decide whether the input is a rewrite or a new build → any fight must pass kinetic-chain-11 + impact-physics
→ package per render-adapters' 7 segments → run the S5 checklist before delivery → deliver
```

## 📂 Directory layout

```
real-combat-director/
├── SKILL.md                          # Master router (pre-locks / 6 ironclad rules / 6-step workflow / command routing)
└── references/
    ├── r1-combat-core.md             # ★ R1 combat core (tier / rhythm / ending / emotional pivot / spirit-not-form)
    ├── kinetic-chain-11.md           # ★ 11-link kinetic chain (mandatory for key strikes)
    ├── real-fight-techniques.md      # ★ Real fight technique library (modern + Chinese martial arts + weapons + chains)
    ├── camera-action-specs.md        # ★ 5 camera specs & spatial rules (shot ladder / camera-action binding / 3 methods 6 forms)
    ├── defense-evasion-rules.md      # ★ 3-state defence & exaggerated evasion (incl. hit-reaction toolbox)
    ├── impact-physics.md             # ★ Real impact feedback & air dynamics (R1 finisher 3 acts + compliance dictionary)
    ├── render-adapters.md            # ★ Seedance 2.5/2.0 packaging (7 segments / stance / sound / negatives)
    ├── martial-styles-extended.md    # Extended martial arts library (19 styles / 36 leg techniques / chin na 36 / weapons)
    ├── technique-combo-library.md    # Technique & combo library (entries / combos / limbs / pivots / space / finishers / yielding)
    ├── multi-opponent-rules.md       # ★ Small-scale multi-opponent choreography (single source: hero anchor / axes / three-beat rotation / anti-cloning)
    └── storyboard-example.md         # Full example: 15s realistic fight storyboard + 2.5/2.0 packaged outputs
```

## 🕹️ Command routing

| Command | Action |
|:---|:---|
| `/定档` (lock tier) | S1: lock model version + aspect ratio; confirm subject/characters/scene/duration; output the project header |
| `/拆招` (break down moves) | S2: derive key strikes via the 11-link chain; pick techniques; write each strike's contact point / impact / inherited state |
| `/做分镜` (storyboard) | S3: output the 5-spec shot table for the R1 tier |
| `/投喂提示词` (feed prompt) | S4: output the Seedance 2.5/2.0 7-segment packaged prompt |
| `/审查` (review) | S5 + S6: run the checklist item by item; output P0/P1/P2 conclusions and a re-verification report |
| `/看板` (board) | Compile the project md into a single-file offline storyboard board |

## 🖥️ Platforms & models

| | Supported |
|:---|:---|
| **Agent platforms** | OpenClaw · WorkBuddy · Doubao agents / Coze · Dify and generic LLMs |
| **Video models** | **Seedance 2.5 / 2.0** (forced choice; the syntax contracts are fully split); Jimeng as secondary / legacy |
| **Outputs** | 7-segment feed prompt block · single-file offline storyboard board · project markdown |

## 📝 Version history

| Version | Date | Highlights |
|:---:|:---:|:---|
| **V1.0 — Technique Enhanced** | 2026-09-17 | Extracted from `short-drama-director` V6.8's R1 line as a standalone pack; added `martial-styles-extended.md` and `technique-combo-library.md` (spirit, not form); rhythm policy landed in `r1-combat-core.md` §8 |
| Revision 2 | — | Whole-pack review (rhythm calibres · numeric consistency), 27 fixes |
| Revision 3 | — | Leftover removal (fictional body-style table · output-side terms "freeze/standoff" · numeric calibres converged) |
| **Revision 4** | — | **Added multi-opponent choreography**: `references/multi-opponent-rules.md` (2–4 on screen · single hero anchor · primary/secondary axes · three-beat rotation against standing by · break-point arc · anti-cloning); minimal integration into `SKILL.md` / `r1-combat-core.md` / `camera-action-specs.md` / `render-adapters.md` — **the six ironclad rules were not rewritten** |

---

<div align="center">

**Upstream**: the R1 portion of `short-drama-director` V6.8
(action-previs / combat-direction-engine / combat-rhythm-defense3state / camera-specs-15rules /
martial-arts-combat-library / authentic-martial-taxonomy / action-ultimate-finisher /
action-cinematography-breakdown / seedance-render-engine / model-adapters / platform-safety-compliance-guide)

Beta build; integrates and reworks open-source material.

</div>
