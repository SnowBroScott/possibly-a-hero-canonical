DECISION LOG ENTRY

DECISION: Run Initiation Loop — Corrected Structure

The run initiation sequence is as follows:
1. Player initiates new run
2. Player selects class
3. Player selects starting offensive power (only if more than one option is
   unlocked for that class)
4. Map loads
5. Intro scene plays — third person, brief, cinematic. Hero arrives via their
   class movement type.
6. Camera swings up to isometric offset play mode
7. Run begins

Class-specific intro animations:
- Brawler: leaps into frame, lands hard, camera swings up
- Speedster: blurs in, camera snaps up with motion blur
- Blaster: teleports in, hard cut to isometric
- Tactician: rolls in on vehicle, camera lifts and settles

The camera transition is not triggered by movement power selection. It is the
cinematic expression of a class choice already made. Class selection occurs
before map load. The intro scene is the payoff of that choice, not the moment
of it.

DATE: May 3, 2026

WHY: Class selection as a pre-map menu moment keeps the intro scene as pure
cinematic payoff rather than a UI moment. Each class arrival animation
communicates identity immediately and distinctly before a single enemy is
encountered.

REPLACES: Run camera transition — third person intro, isometric gameplay.
That entry implied movement power selection triggered the camera transition.
This entry supersedes that framing. The transition is class-driven, not
selection-driven.

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Support Pool finalized at eight supports across three categories —
Combat: Reflexes, Power Surge, Blast Radius, Precision Strike, Rapid Recovery;
Utility: Overdrive, Fast Track; Safety: Last Stand. Pool is class-agnostic.
All names are comic book native.

DATE: May 3, 2026

WHY: Generic stat language replaced throughout with comic book kinetic
terminology that is instantly legible to roguelite players without explanation.
Pool is designed to be class-agnostic — every support has standalone value
regardless of primary or hero power combination, and no support encroaches
on class-specific identity.

REPLACES: Prior support naming using generic stat-based language.

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Hero Powers pool finalized at eleven powers — shared pool, fully
random: Magnetism, Freeze Frame, Tempest, Tremor, Rift, Toxin, Sonic Scream,
Gorilla (Brawler class summon), Double Time (Speedster class summon), Specter
(Blaster class summon), Sentinel (Tactician class summon). No mission-type
biasing. Class summons are unique per class.

DATE: May 3, 2026

WHY: Every hero power is designed to have standalone offensive value before
combo value. Full randomness is intentional — ridiculous combos are a feature,
not an edge case. Class summons are native to each class identity. Light
manipulation was cut due to unclear mechanics and overlap with Sonic Scream.
Toxin replaces Venom to eliminate IP adjacency concerns.

REPLACES: Light manipulation (cut); Venom (replaced by Toxin).

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Support Pool and Hero Powers — Complete Layer Definitions

NOTE: Support pool naming in this entry uses earlier generic stat language.
The finalized comic book native naming is established in the Support Pool
entry above and supersedes this entry's support pool naming. Hero power
content remains valid.

Three-layer system confirmed:
- Class Primary — class-specific offensive powers
- Hero Powers — offensive with utility upside, mid-run pickups, shared pool,
  fully random
- Support Pool — genre-legible enhancements, class-agnostic

HERO POWERS (shared pool, fully random):
1. Magnetism — pull enemies together, redirect projectiles, strip weapons
2. Freeze Frame — brief local time dilation; everything stops, player doesn't
3. Tempest — lightning strikes, wind gusts, localized storms. Environmental
   and atmospheric — the storm answers the hero rather than coming from them.
   Thor's lightning bolt, not force lightning.
4. Tremor — fissures, earthquakes, terrain as weapon
5. Rift — displaces and moves enemies around the map; intentionally chaotic
6. Toxin — damage over time, spreads between enemies
7. Sonic Scream — stuns, disorients, chain damages
8. Class-Specific Summons (unique per class):
   - Brawler: Gorilla — animal companion
   - Speedster: Double Time — speed clone
   - Blaster: Specter — spectral ally, phases through walls
   - Tactician: Sentinel — combat drone

Hero power design principles:
- Every hero power has standalone offensive value before combo value
- Pool is fully random — no mission-type biasing
- Ridiculous combos are a feature, not a bug

Cuts (with reasoning):
- Hard Light Constructs — too IP-adjacent (Green Lantern)
- Self Duplication (standalone) — absorbed into Speedster class summon
- Size Manipulation — doesn't fit isometric offset gameplay
- Intangibility — overlaps with invisibility in support layer
- Probability Manipulation — doesn't fit Apex tone
- Black Hole — covered by Blaster primary gravity well
- Dimensional Pocket — consolidated into portal creation
- Density Wave — doesn't fit
- Adrenaline — renamed Attack Damage, moved to support pool

ELEMENTAL DISTINCTION NOTE:
Elemental Surge (Blaster class primary, lightning variant) and Tempest are
not redundant powers. Elemental Surge is force lightning — directed, precise,
projected from the hero's body at a target. Tempest is Thor's lightning bolt —
called from above, environmental, affects the space rather than a single
target. They share an element. They are emphatically not the same power.
A Blaster running both in the same run is not doubling up — they are a
precision energy projector who can also call storms.

COMBO SYSTEM NOTE:
Combos are discovered organically during runs — Vampire Survivors style.
The right combination of powers held simultaneously triggers a combo —
unannounced, emergent, discoverable by accident. Once discovered, the combo
is permanently logged in the Hero's Lair including what was required to
trigger it. The lair does not unlock combos. It records them.

Example of emergent combo discovery — Blaster + Elemental Surge (lightning)
+ Tempest: The Blaster projects directed lightning from below while a storm
responds from above. Two directions. Same frequency. Discovered in a run,
logged in the lair. Rex Flynn has a video about the first time someone found
it. Twelve million views. Unhinged thumbnail.

DATE: May 3, 2026

WHY: Hero powers stay offensive with utility upside to protect class identity
and keep the three layers distinct. A fully random hero power pool creates
genuine surprise and ridiculous combo potential — standalone value for every
power is the baseline protection against dead draws.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Class Offensive Suites — All Four Classes

PRIMARY LAYER DETAILS:

BRAWLER (Movement: Leaping)
- Starter: Super Strength — single target bruiser
- 10 runs: Shockwave / Impact Burst — AOE
- 30 runs: Elasticity / Stretch — mid-range combat

SPEEDSTER (Movement: Super Speed)
- Starter: Speed Strike — single target rapid combo
- 10 runs: Velocity Slam — momentum/skill-based impact
- 30 runs: Tornado — AOE environmental chaos

BLASTER (Movement: Teleportation)
- Starter: Energy Blast — single target precision
- 10 runs: Elemental Surge — choose fire, ice, or lightning per run, each
  with distinct status effects. Directed elemental projection — force
  lightning, concentrated fire, precision ice. Comes from the hero's body
  and is aimed at targets. Not environmental, not atmospheric.
- 30 runs: Gravity Well — AOE tactical, pulls and detonates

TACTICIAN (Movement: Vehicle)
- Starter: Rifle — single target precision
- 10 runs: Deployable Turrets — utility and area control
- 30 runs: Rocket Launcher — AOE destruction

UNLOCK STRUCTURE (all classes):
- Unlocks are cumulative and permanent across runs
- Failed runs do not count toward unlock progress but do not reset it
- Unlock thresholds: 10 and 30 successful runs with that specific class

DATE: May 3, 2026

WHY: Three primary offensive options per class — single target,
utility/tactical, and AOE — each represent a distinct playstyle. Separating
primary and support layers keeps class identity clean while the shared support
pool generates combinatorial variety.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: The class system uses four per-run selectable classes — Brawler
(movement: Leaping), Speedster (movement: Super Speed), Blaster (movement:
Teleportation), and Tactician (movement: Vehicle). Class selection occurs at
the start of each run and is not a permanent character assignment.

DATE: May 3, 2026

WHY: Per-run selection preserves pick-up-and-play accessibility. Players can
experiment freely without commitment, while the mastery system rewards loyalty
separately from class choice itself.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Movement is class-locked and not player-selectable. Flight and wall
crawling are removed from the movement pool entirely. The Tactician's vehicle
is permanent for the duration of a run — no exit mechanic exists.

DATE: May 3, 2026

WHY: Flight removed due to build complexity, balance issues, and isometric
offset incompatibility. Wall crawling removed due to verticality requirements
and IP adjacency concerns. Locking movement to class simplifies systems and
strengthens class identity.

REPLACES: Flight and wall crawling as movement pool options — both removed.

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Each class begins with one offensive power. A second offensive
option unlocks after 10 successful runs with that class. A third unlocks after
30 successful runs. Unlocks are cumulative and permanent — they never reset.
Failed runs do not contribute to progress but do not reduce it.

DATE: May 3, 2026

WHY: Cumulative permanent tracking aligns with the "consequence without
punishment" core principle — players are rewarded for mastery without being
penalized for failure or variety.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: The Guardian is removed as a standalone class. Defensive and
protective powers previously associated with the Guardian archetype are
redistributed into the power pools of all four classes at lower probability.

DATE: May 3, 2026

WHY: Removing Guardian streamlines the class roster without eliminating its
design contribution. Distributing defensive powers across all pools preserves
tonal and mechanical variety.

REPLACES: Guardian as a standalone selectable class.

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Run Camera Transition — Visual and Mechanical Structure

Every run opens with a brief third-person cinematic intro. The hero arrives
via their class movement type. Camera swings up to isometric offset play mode.
The city layer operates on a separate camera (top-down or angled).
Third-person assets are scoped to the brief intro sequence only; the isometric
offset angle handles all run gameplay.

DATE: May 3, 2026

WHY: The camera transition creates a ritual moment of hero identity at the
start of every run. Scoping third-person assets to the intro sequence only
preserves the cinematic payoff without the maintenance cost of full
third-person gameplay.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Rex Flynn is established as a DRAFT influencer character in Apex
Chronicles. His platform is called "Exposed," operating across TikTok and
YouTube in two distinct voice registers. Rex is male, 20s, loud and boisterous
— an anti-hero with no fixed ideological position who chases clickbait and
emotional response exclusively. His primary reward pillar is run modifier
unlocks. His secondary reward is name emergence options (editorial, chaotic,
meme-driven, viral-optimized). TikTok register is punchy and clipped; YouTube
register is unhinged and sprawling.

DATE: May 3, 2026

WHY: Rex Flynn's platform-chasing nature makes him a more contemporary and
mechanically interesting antagonist. Having no fixed position means modifier
challenges feel unpredictable and genuinely funny.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: The three feedback channels — Citizens, Superhero Community, and
Rex Flynn / Exposed — each anchor a distinct primary reward track, with name
emergence shared as a secondary reward track across all three. Citizens reward
city aesthetics and development. The Superhero Community rewards player
cosmetics. Rex Flynn rewards run modifier unlocks. Name unlock options are
channel-specific in register, unlock permanently once surfaced, and only
surface when conditions are right.

DATE: May 3, 2026

WHY: Pillar structure ties reward source to reward type. Modifier unlocks give
Rex Flynn mechanical teeth and add replayability depth critical to the
roguelite format.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Apex Chronicles is a superhero roguelite city-building game. Players
go on runs that generate resources and outcomes that feed city building. The
city built shapes the hero's identity, development, and mastery. The two
halves are inseparable — runs shape the city, the city shapes the runs.

NOTE: The clause "shapes the hero's available powers and abilities" from the
original locked entry is superseded by the LOCKED amendment dated May 6, 2026.
The foundational inseparability of runs and city remains locked.

DATE: May 3, 2026

WHY: This is the foundational design commitment the entire game is built on.
All other decisions flow from this relationship.

REPLACES: Nothing — new decision

STATUS: LOCKED

---

DECISION LOG ENTRY

DECISION: The game's full title is Apex Chronicles. Working designation within
the design pipeline is Apex.

DATE: May 3, 2026

WHY: Name selected to reflect both the heroic progression arc and the comic
book format of the player's story being written run by run.

REPLACES: Nothing — new decision

STATUS: DEPRECATED

---

DECISION LOG ENTRY

DECISION: Vampire Survivors is the loose structural reference for run design.
Players drop into a map with a consistent loop. Variety emerges from player
choices within that loop, not from fundamentally different run types.

DATE: May 3, 2026

WHY: VS provides a proven run structure that supports replayability without
requiring multiple distinct run mode builds.

REPLACES: Nothing — new decision

STATUS: NOTED

---

DECISION LOG ENTRY

DECISION: Every run map contains three mission types: boss fight, passive
escort defense, and horde survival. These are not separate modes — they are
locations and activities discoverable within a single run map. All three exist
on the map simultaneously after the tutorial arc.

DATE: May 3, 2026

WHY: Keeps the run loop consistent while delivering mechanical variety.
Players self-select based on city needs and personal preference within a
single session.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Each run mission type feeds a distinct city system: boss fights
generate resources for city construction, escort defense missions sustain city
morale, horde survival missions generate intel.

DATE: May 3, 2026

WHY: Creates genuine strategic tension during runs. Players are making city
management decisions through their mission choices without the game feeling
like a management game.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Intel gathered through horde survival missions identifies the area's
super villain. Sufficient intel is required to trigger the area boss encounter.
The area boss gates progression to the next stage.

DATE: May 3, 2026

WHY: Makes intel missions load-bearing for progression, not optional. All
three mission types become structurally necessary rather than preferential.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: The city reacts to run patterns over a short window — not instantly
after a single run, not glacially over many sessions. A streak of bad runs
darkens the city. A streak of good runs lifts it.

DATE: May 3, 2026

WHY: Patterns matter more than individual performances. Faster feedback loop
than Endure, slower than a single-run snap reaction.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Negative run outcomes affect the city atmospherically — citizen
behavior, visual tone, ambient mood. Nothing is permanently lost. No progress
is set back. No construction is reversed. The city always recovers.

DATE: May 3, 2026

WHY: Consequence without punishment. Players should feel the weight of bad
runs without being penalized in ways that damage long-term investment.

REPLACES: Nothing — new decision

STATUS: LOCKED

---

DECISION LOG ENTRY

DECISION: A polarizing social media influencer archetype serves as the primary
voice feedback channel for run performance. The character is skeptical,
reactionary, never fully satisfied, and occasionally accidentally
complimentary.

DATE: May 3, 2026

WHY: More contemporary and tonally appropriate than a newspaper editor
archetype for a modern superhero setting.

REPLACES: Nothing — new decision

STATUS: DRAFT

NOTE: This entry is superseded by "The three feedback channels — Citizens,
Superhero Community, and Rex Flynn / Exposed" (May 3, 2026). Retained for
historical record only.

---

DECISION LOG ENTRY

DECISION: City visuals serve as a secondary feedback channel running parallel
to the influencer voice channel. The city is the body language; the influencer
is the voice. They operate on different timescales — the influencer reacts
immediately, the city shifts gradually over a pattern of runs.

DATE: May 3, 2026

WHY: Two channels reinforce without being redundant when calibrated to
different timescales.

REPLACES: Nothing — new decision

STATUS: DRAFT

NOTE: This entry is superseded by "The three feedback channels — Citizens,
Superhero Community, and Rex Flynn / Exposed" (May 3, 2026). Retained for
historical record only.

---

DECISION LOG ENTRY

DECISION: Players make cosmetic creation choices before the first run: gender,
mask or no mask, cape or no cape, costume style, and a civilian name. Identity
beyond these basics emerges through play patterns and city development. Nothing
at creation determines mechanical starting position.

DATE: May 3, 2026

WHY: Enough upfront investment to feel ownership from run one, enough left
open that the character grows into something unplanned.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Players choose a civilian name at character creation. The superhero
name is not chosen — it is earned through play and emerges from achieved
patterns and milestones. Players begin without a superhero name. The absence
is intentional and motivating.

DATE: May 3, 2026

WHY: The superhero name is what the world decides to call the hero based on
what they actually did.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Superhero name options emerge from three distinct in-world sources:
citizens (warm, local, affectionate), Rex Flynn / Exposed (editorial, chaotic,
meme-driven, viral-optimized), and the Superhero Community (peer/professional).
Players choose from whichever options have emerged. Early names skew silly —
players are expected to outgrow their first designation. The influencer reacts
differently depending on which name the player adopts.

DATE: May 3, 2026

WHY: Choosing whose opinion defines your identity is a meaningful act of
characterization. Multiple sources create tonal variety.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: City construction determines the player's starting power loadout at
run start and expands the pool of powers available to appear during a run.
Powers not unlocked through city building do not appear in runs.

NOTE: This entry is superseded by "City Buildings — Mirrors Not Gates"
(May 5, 2026) and the LOCKED amendment (May 6, 2026). Retained for
historical record only.

DATE: May 3, 2026

STATUS: DRAFT — SUPERSEDED

---

DECISION LOG ENTRY

DECISION: Within a run, powers progress and combine through the roguelite
loop. Starting loadout is set by the city but the run determines how those
powers develop and what combinations emerge.

NOTE: This entry is superseded by "City Buildings — Mirrors Not Gates"
(May 5, 2026) and the LOCKED amendment (May 6, 2026). Retained for
historical record only.

DATE: May 3, 2026

STATUS: DRAFT — SUPERSEDED

---

DECISION LOG ENTRY

DECISION: The ability to merge or combine specific powers during runs is
unlocked through city construction. Without the relevant city building, certain
merges are not available regardless of what powers the player holds during
a run.

NOTE: This entry is superseded by "City Buildings — Mirrors Not Gates"
(May 5, 2026) and the LOCKED amendment (May 6, 2026). Retained for
historical record only.

DATE: May 3, 2026

STATUS: DRAFT — SUPERSEDED

---

DECISION LOG ENTRY

DECISION: The available power pool is not locked to a specific hero archetype
or playstyle. Players can build any combination regardless of thematic
coherence. The game tracks playstyle patterns and reflects them back through
name emergence, city aesthetics, and influencer commentary — but never
restricts player choice based on those patterns.

DATE: May 3, 2026

WHY: Player freedom and ownership over hero identity requires the system to
observe without prescribing.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Tutorial Arc — Building Sequence and Run Type Gates

The tutorial arc consists of four restorable buildings and one area boss
defeat, each unlocked by specific run type completion:

1. Science Lab — unlocked by completing an Intel run. Teaches support skills.
2. Training Center (Gym — Stage One form) — unlocked by completing a Boss
   Fight run. Teaches hero powers.
3. Tailor Shop — unlocked by completing an Escort Defense run. Teaches
   cosmetics and appearance customization.
4. Area Boss Defeated — completes the tutorial arc. Player has demonstrated
   mastery across all three run path types.
5. Hero's Lair — unlocked upon area boss defeat. Serves as headquarters.
   Houses combo discovery log, achievement displays, unlocked name history,
   and cosmetic loadout management.

Each building restoration is a hard gate tied to its corresponding run type.
The lair does not follow the restoration model — it is earned as a reward for
completing the full tutorial arc. Combos are discovered organically during
runs — Vampire Survivors style. Once discovered, the combo is permanently
logged in the lair. The lair does not unlock combos. It records them.

DATE: May 5, 2026

WHY: This structure weaves the three run path types into the game's mechanical
foundation through narrative necessity rather than arbitrary progression gates.
Each building teaches a player skill through a meaningful story moment.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Tutorial Arc — World-Based Nudges and Run Structure

The tutorial does not use menu-based run selection. Players move through the
city and encounter world-based nudges — broadcasts, visible crises, narrative
events — that guide them toward specific locations. When they arrive, the
situation naturally presents itself as a run type. Completing that run unlocks
the corresponding building.

During the tutorial, only one mission type is available per run — heavily
nudged by world context. After tutorial completion, all three mission types
are available simultaneously in every run.

The run is the moment the player enters the map. Within the run, all available
mission types exist on the map as discoverable locations. Players build their
loadout through milestone-based power selections during the run, then choose
which mission to attempt based on what they've built and when they feel ready.

DATE: May 5, 2026

WHY: World-based nudges feel like consequence rather than instruction. The
tutorial teaches through narrative stakes, not UI prompts.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Post-Tutorial City Structure and Class-Specific Buildings

ESSENTIAL BUILDINGS (Tutorial Arc + Headquarters):
1. Science Lab — unlocked by Intel run. Houses support skills.
2. Training Center — unlocked by Boss Fight run. Houses hero power deepening.
   Every hero power selected during a run is logged here for deepening and
   training. See Training Center — Complete System Definition for full spec.
3. Tailor Shop — unlocked by Escort Defense run. Houses cosmetics.
4. Hero's Lair — unlocked upon area boss defeat. Serves as headquarters.
   Houses combo discovery log, achievement displays, unlocked name history,
   and cosmetic loadout management.

CLASS-SPECIFIC NARRATIVE LOCATIONS (Post-Tutorial):
Four additional buildings, one per class, providing narrative context for
advanced power unlocks. These buildings exist from early progression but
appear non-descript until the mentor relationship unlocks. At unlock, the
building reveals what it actually is — hidden in plain sight.
- Brawler location
- Speedster location
- Tactician location
- Blaster location

These buildings do not gate mechanical unlocks — class mastery remains tied
to run completion (10 runs for second tier, 30 runs for third tier).

CITY DEVELOPMENT:
The city progresses through four visual stages (Rundown → Developing →
Refined → Modern) as the player advances. Visual improvements reward
progression without requiring strategic building prioritization.

DATE: May 5, 2026

WHY: Essential buildings form a complete progression arc. Class-specific
buildings add world depth without overcomplicating the design.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: City Buildings — Mirrors Not Gates (Amendment)

AMENDS AND SUPERSEDES:
- "City construction determines the player's starting power loadout..."
- "Starting loadout is set by the city but the run determines how those
  powers develop..."
- "The ability to merge or combine specific powers during runs is unlocked
  through city construction..."

CORRECTED DECISION: City buildings are mirrors, not gates. They reflect and
deepen what the player has done in runs. They do not control what the player
can access. This principle applies universally across all city buildings with
no exceptions.

THE RUN — Powers appear randomly during runs at milestone moments. The full
hero power pool is available from the start. No city building gates a power
from appearing. Players enter each run with their class selection and class
starting offensive power only. Everything else is built during the run.

COMBOS — Discovered organically during runs, Vampire Survivors style. Once
discovered, the combo is permanently logged in the lair including the exact
power combination required to trigger it. The lair does not unlock combos.
It records them.

THE TRAINING CENTER — Every hero power a player selects during a run is logged
here. Players can deepen, train, and improve powers they have already
encountered through the sponsor challenge system. See Training Center —
Complete System Definition for full spec.

THE LAIR — A special trophy case for discovered combos. Logs each combo, its
trigger conditions, and its effects.

ALL BUILDINGS — Follow the same mirror model. None of them gate access to
content.

DATE: May 5, 2026

WHY: Full consistency with the roguelite model and the consequence without
punishment core principle. The city rewards and reflects — it never blocks.

REPLACES: Three entries listed above. Any language implying city buildings
control power pool access, combo availability, or starting loadout
configuration is incorrect and superseded by this entry.

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Map Structure — City Stages as Run Progression System

The run layer and city layer share the same map. The street layout, road
routing, and Core Four buildings (Science Lab, Training Center, Tailor Shop,
Hero's Lair) are consistent landmarks across all stages and recognizable
within the run layer.

The city develops through four visual stages. Each stage is mechanically a
distinct run environment layered on top of the same underlying street
geography.

STAGE ONE — Rundown. Tutorial environment. One mission type per run, heavily
nudged. Lowest difficulty.
STAGE TWO — Developing. Mid-game. All three mission types available.
Increasing enemy density and challenge.
STAGE THREE — Refined. Late mid-game. Full mechanical complexity. Higher
difficulty.
STAGE FOUR — Modern. Endless live game tail. Rex Flynn modifiers.
Procedurally generated missions and bosses. Maximum difficulty and
replayability.

Cosmetic city improvements do not propagate granularly into the run layer
beyond stage-level visual identity.

DATE: May 5, 2026

WHY: Sharing the same street map creates spatial memory and narrative
coherence. City growth does double duty — rewarding progression and raising
stakes simultaneously.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Run Time Structure and Mission Reveal Model

A single run is 20 minutes, structured in three acts:

ACT ONE — Prep Period (0-5 minutes)
Mission locations are hidden. The player builds their loadout through
milestone-based power selections. Stumbling into a mission location before
the prep period ends makes that mission live immediately.

ACT TWO — Open Window (5-15 minutes)
All three mission locations reveal simultaneously on the map. Full player
agency — attempt a mission immediately or keep developing the loadout.

ACT THREE — Forced Commitment (15-20 minutes)
At 15 minutes the game forces a mission choice. Whatever the player has built
is what they take in. Five minutes to execute. Success or failure resolves
here.

Mission locations are randomized each run — no mission type has a fixed
geographic location.

DATE: May 5, 2026

WHY: The three-act structure gives every run dramatic shape. The forced choice
at 15 minutes ensures build decisions carry weight. Randomized mission
locations support narrative variety.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Class Mentor System — Framework and Introduction Triggers

Each of the four classes has a corresponding mentor character who occupies a
class-specific building in the city. These buildings exist from early
progression but appear non-descript until the mentor relationship unlocks
through class progression and playtime. At unlock, the building reveals what
it actually is — hidden in plain sight.

Mentor relationships unlock through class progression and playtime. Each
introduction is native to its class and functions as a three-panel comic book
moment in its own right.

BRAWLER MENTOR — Like recognizes like.
The mentor sees the player fight from across the street and walks over. No
mysticism, no technology. Direct, physical, slightly gruff. The introduction
is the first lesson.

SPEEDSTER MENTOR — Sense the presence of another.
The mentor finds the player before the player finds them. Already standing
nearby when the player turns around. The player didn't hear them arrive.

TACTICIAN MENTOR — Tech detects tech.
The player's equipment flags the mentor's technology as a danger alert. The
player investigates expecting an enemy and finds a person. Adversarial before
collaborative. The mentor was expecting the alert.

BLASTER MENTOR — The city reacts.
Lights flicker and die across two city blocks. Electronics glitch. The player
investigates and finds a person who has been living with uncontrolled energy
output for years. They recognized the player's energy signature from six
blocks away. The blackout was not an accident.

MENTOR NARRATIVE FUNCTION:
Each mentor provides narrative justification for why advanced class powers
exist and are teachable. Mechanically, class mastery remains tied to run
completion (10 runs / 30 runs). The mentor is the story of why the unlock
happens — not the gate that controls it. Mentor introductions are world events
that generate content across all three feedback channels.

DATE: May 5, 2026

WHY: The mentor system transforms class mastery unlocks from arbitrary
progression gates into relationships with narrative weight. The
hidden-in-plain-sight building reveal rewards city exploration.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Camera and Combat Model

NOTE: The minor objectives output list in this entry is superseded by the
amendment dated May 6, 2026. See "Amendment — Camera and Combat Model:
Minor Objective Outputs" for the complete and current output list.

CAMERA:
Run gameplay uses a Hades-style camera — closer and more angled than Deep
Rock Galactic Survivors. Close enough that individual enemies have presence,
movement types read as identity rather than speed stats, and the city feels
like a place rather than a map. The DRGS reference is retired as the primary
camera comparison. Hades with open world scope is the correct model.

COMBAT PHILOSOPHY:
Combat is intentional and skill-based, not passive and automatic. Powers are
tools the player deploys actively — timed, positioned, and combined through
player decision rather than auto-proc stacking. A skilled player with a
mediocre power selection outperforms an unskilled player with a great one.
Mastery is real and expressible. Combat aligns closer to Hades than Vampire
Survivors. VS remains the structural reference for run format. Hades is the
reference for combat feel, power interaction, and skill expression.

POWER SELECTION MODEL:
At each level up, players choose between three genuinely viable options:
- A class primary upgrade — deepens core class identity
- A hero power — adds a new tool, broadens capability
- A support option — modifies existing powers, shifts interactions

No option is obviously correct. Build identity emerges from accumulated
choices across a run, not from a preset loadout.

MINOR OBJECTIVES:
See amendment dated May 6, 2026 for complete and current output list.

DATE: May 5, 2026

WHY: Camera distance determines combat philosophy, movement identity, and
world legibility. Hades distance makes the city feel inhabited and the hero
feel powerful. Intentional skill-based combat creates genuine mastery
expression.

REPLACES: DRGS as primary camera reference — superseded by Hades with open
world scope.

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Training Center — Building Evolution and Hero Power Deepening System

The Training Center is the canonical name for the building that houses hero
power deepening. "Gym" refers to its Stage One physical form only — not its
canonical name. The building is always the Training Center. It starts as a
gym. See Training Center — Complete System Definition (May 6, 2026) for full
specification. This entry is retained for historical record.

DATE: May 5, 2026

STATUS: DRAFT — SEE COMPLETE SYSTEM DEFINITION (MAY 6, 2026)

---

DECISION LOG ENTRY

DECISION: The city and runs are inseparable. Runs shape the city. The city
shapes the hero's identity, development, and mastery. The city does not
control what powers appear in runs. The full hero power pool is available from
run one. No city building gates a power from appearing. Discovery is always
free.

What the city provides is the infrastructure for mastery. Powers discovered
and proven in runs find their home in the city — in the Training Center, in
the lair, in the buildings the hero has restored and the relationships they
have built. The city deepens what the player has earned. It does not withhold
what the player hasn't yet unlocked.

The relationship is: runs write the story, the city remembers it.

DATE: May 6, 2026

WHY: The original locked entry was written before the mirrors-not-gates
philosophy was established. The design evolved to separate discovery (always
free, full pool available) from mastery (housed in the city, earned through
proven use). This amendment preserves the foundational inseparability of runs
and city while correcting the gate implication that the original language
carried.

REPLACES: "The city built shapes the hero's available powers and abilities."
— LOCKED entry dated May 3, 2026, superseded by this amendment.

STATUS: LOCKED

---

DECISION LOG ENTRY

DECISION: AMENDMENT — Camera and Combat Model: Minor Objective Outputs

The minor objective output list in the Camera and Combat Model entry
(May 5, 2026) was incomplete. The confirmed complete output list is:

Minor objectives feed:
- XP — direct boost to run progression. Minor objective XP feeds the same
  milestone-based power selection system as combat XP. More minor objectives
  completed means more power selection opportunities within a run.
- Morale (Citizens channel)
- Recognition (Superhero Community channel)
- Clickbait (Rex Flynn channel)

Minor objectives do not generate intel. Intel remains exclusively tied to
horde survival.

DATE: May 6, 2026

WHY: XP was confirmed as a minor objective output during Run Design document
generation. The Camera and Combat Model entry did not include it.

REPLACES: Minor objective output list in Camera and Combat Model (May 5,
2026). That list is superseded by this complete version.

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Training Center — Complete System Definition

The Training Center is the canonical name for the hero power deepening
building across all four stage evolutions. "Gym" refers to its Stage One
physical form only — not its canonical name. The building follows the Hades
headquarters model: atmosphere, narrative, and interface, not an arena.

STAGE EVOLUTION:

STAGE ONE — THE GYM
Basic. Functional. Recently rescued. Humble in scale. The hero power
deepening system is not active during the tutorial stage. The building
matches the hero's status — unknown, unproven, just getting started.

STAGE TWO — THE COMPLEX
The gym gets built out. The hero power deepening system comes online for the
first time. Sections begin activating as powers are proven in runs. The
building starts reading like a map of the player's run history.

STAGE THREE — THE FACILITY
Multi-story. Serious infrastructure. More sections active. The hero is
established. The building reflects that.

STAGE FOUR — THE TOWER
Avengers Tower / SHIELD headquarters scale. Every proven power section active
and visible. The hero is a civic institution. Rex Flynn has a series about
the building. Citizens take photos outside it.

HERO POWER DEEPENING SYSTEM — FIVE STEPS:

STEP 1 — PROVE A POWER IN A RUN
When a player discovers a hero power and completes a run with it, that power
is considered proven. The corresponding Training Center section activates.

STEP 2 — SPONSOR MESSAGE SURFACES
A Superhero Community message arrives from a hero who embodies that power
archetype — a Storm equivalent for Tempest, a Banshee equivalent for Sonic
Scream. The message is personalized and invites the player to find what the
sponsor left at the activated section.

Sponsor presence scales with progression:
- Stages Two and Three — the sponsor leaves something. A message, a recorded
  briefing, a challenge upload. They do not appear in person. An established
  hero does not grace an unknown fledgling with a personal visit.
- Stage Four — this dynamic may shift. A sponsor who has watched the player's
  career develop across dozens of runs may eventually appear in person. This
  is an earned moment, not a given one. See Stage Four Sponsor In-Person
  Visit entry.

STEP 3 — PLAYER VISITS THE TRAINING CENTER
The player finds the activated section and interacts with whatever the sponsor
left — a screen, a terminal, a recorded message, a physical note. The
interaction queues a challenge to surface in a future run.

STEP 4 — CHALLENGE SURFACES IN A RUN
The challenge surfaces in the run layer during a future run — not inside the
Training Center. The player must have the relevant power active to engage with
it. Because powers are random, the player cannot force the power to appear.
The challenge is queued. The run serves its pool as always.

When the power appears in a level up offer with a challenge queued, a new
layer of decision surfaces alongside the usual three-way tension — take this
power because the challenge is waiting, or take something the current build
needs more. Player agency stays fully intact.

STEP 5 — COMPLETE THE CHALLENGE
The player completes the challenge mid-run. Success rewards power deepening —
the power grows stronger in future runs. After reaching its deepening cap,
subsequent completions reward temporary run boosts to that power's
effectiveness instead.

SPONSORSHIP AND WORLD TEXTURE:
Heroes loosely vying for disciples is native to the Apex Chronicles world.
The sponsorship isn't altruistic — it's reputation, legacy, and the quiet
politics of a superhero community that existed long before this hero arrived.
Rex Flynn covers sponsorship announcements with unhinged energy.

MASTERY SCOPE BOUNDARIES:
- Training Center — hero power deepening and sponsor challenges only
- Class Mentor Buildings — class primary power advancement
- Hero's Lair — combo discovery log
These three buildings handle mastery between them. Their scopes do not
overlap.

DATE: May 6, 2026

WHY: The Hades-style headquarters model contains build complexity while
delivering narrative richness. Placing challenges in the run layer preserves
player agency. Sponsor scaling with stage progression ensures earned moments
feel earned. The three-building mastery split keeps each system's scope clean.

REPLACES: All earlier Training Center and Gym entries. "Boxing Gym" and "Gym"
as canonical building names are superseded. The Stage One physical form is a
gym. The building is always the Training Center.

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Superhero Community Channel — Expanded Scope

AMENDS: Feedback Channels — reward pillar definition (May 3, 2026)

The Superhero Community channel's primary reward pillar remains player
cosmetics. The channel additionally serves as the delivery mechanism for the
hero power deepening sponsorship system:

- Sponsor messages surface through this channel when a hero power is proven
  in a run
- The channel tracks discipleship — whose disciples are proving themselves,
  whose aren't
- Sponsorship announcements are world events the channel broadcasts
- The community has opinions about mentors taking on unknown heroes and
  expresses them through this channel

The channel does two distinct jobs: cosmetics as primary reward pillar,
sponsorship and discipleship tracking as mechanical function. These are
parallel, not competing.

DATE: May 6, 2026

WHY: The Training Center hero power deepening system requires a delivery
mechanism for sponsor messages. The Superhero Community channel is the natural
and canonical home for this function. Expanding its scope here gives the
channel mechanical teeth beyond cosmetics without displacing its primary
reward function.

REPLACES: Nothing — expands existing entry.

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Explorable City Buildings — Hades Headquarters Model

The explorable buildings in Apex Chronicles follow the Hades headquarters
model. Key principles:

- Buildings are spaces that grow and reflect the player's run history
- Mechanical action does not happen inside the buildings — it happens in runs
- Buildings are atmosphere, narrative, and interface
- Walking through a building at Stage Four tells the story of everything the
  player has done across their full run record
- New content surfaces in buildings between runs — messages, challenges
  queued, sections activating — giving the player a reason to visit without
  requiring them to manage systems there

This model applies to the Training Center, the Hero's Lair, and any other
explorable city building. The run is always where the story happens. The
building is always where the story lives.

DATE: May 6, 2026

WHY: The Hades headquarters model was established informally during Training
Center design but not captured canonically. This entry makes it load-bearing
and applicable across all explorable city buildings.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Hero Power Deepening — Cap and Temporary Run Boost Mechanic

The hero power deepening system has two phases:

PHASE ONE — DEEPENING
The player proves a power, accepts a sponsor challenge, completes it in a run.
Each completion deepens that power — it grows stronger in future runs. This
continues until the power reaches its deepening cap.

PHASE TWO — TEMPORARY RUN BOOSTS
After a power reaches its deepening cap, subsequent sponsor challenge
completions for that power reward temporary run boosts to its effectiveness
instead. The boost applies to the run in which the challenge is completed.
It does not permanently alter the power beyond its cap.

The cap exists to bound permanent power growth while keeping the sponsor
challenge system engaging and rewarding indefinitely. Players who have
maximized a power still have reason to take it in runs and engage with its
sponsor challenge when it surfaces.

DATE: May 6, 2026

WHY: Without a cap, permanent power deepening becomes an unbounded progression
system that could destabilize run balance over time. The temporary boost model
keeps the challenge loop active and rewarding past the cap without compounding
permanent power inflation.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Stage Four Sponsor In-Person Visit

In Stages Two and Three, sponsors communicate through messages, recorded
briefings, and challenge uploads left at the Training Center. They do not
appear in person. An established hero does not grace an unknown fledgling
with a personal visit.

In Stage Four, this dynamic may shift. A sponsor who has watched the player's
career develop across dozens of runs — who has seen their challenges
completed, their power mastered, their name recognized by the city — may
eventually appear in person at the Training Center. This is an earned moment,
not a given one. It requires sustained demonstrated mastery of that power
across the full run record.

The in-person visit is a narrative milestone, not a mechanical gate. It does
not unlock new content. It is the world acknowledging who the player has
become.

DATE: May 6, 2026

WHY: The sponsor relationship should feel like it develops over time — not a
static delivery mechanism. The Stage Four in-person visit is the culmination
of a relationship that started with a message left by someone who wasn't sure
the hero was worth their time. By Stage Four they know. Scaling this to Stage
Four ensures it feels earned and keeps early game expectations humble.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

Log this decision:

Morale — XP Multiplier and Per-Neighborhood Geography

MORALE XP MULTIPLIER:
High morale produces a small XP multiplier for runs. This multiplier 
is modest — it rewards sustained city engagement without making morale 
a mandatory optimization target. Low morale does not penalize XP. 
The multiplier is a reward for positive patterns, not a punishment 
for negative ones. Consistent with consequence without punishment.

PER-NEIGHBORHOOD MORALE GEOGRAPHY:
Morale tracks at neighborhood level, not city-wide only. A hero who 
consistently engages with minor objectives and escort missions in one 
district builds morale there specifically. A district the hero rarely 
visits holds at baseline. The city can have pockets of high morale 
alongside areas that haven't felt the hero's presence yet.

This geographic granularity means:
- Citizens in high-morale neighborhoods are visibly warmer and more 
  active in the run environment
- Name emergence through the Citizens channel is more likely in 
  high-morale neighborhoods
- Rex Flynn notices and covers geographic disparity if the algorithm 
  suggests it will perform

Per-neighborhood morale does not create punishing states. No 
neighborhood crashes to zero permanently. All recover over time 
regardless of hero engagement. Consequence without punishment applies 
at neighborhood level as well as city level.

DATE: May 7, 2026

WHY: City-wide morale tracking alone felt too abstract — the city 
is a place with distinct neighborhoods, and the hero's presence 
should be felt at street level. Per-neighborhood tracking makes the 
world feel inhabited and responsive without adding optimization 
complexity. The XP multiplier gives morale a run-layer mechanical 
hook that rewards city engagement without gating anything.

REPLACES: Nothing — expands existing morale entries.

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Morale — XP Multiplier and Per-Neighborhood Geography

Two related morale mechanics confirmed:

MORALE XP MULTIPLIER: High morale produces a modest XP multiplier during runs. The multiplier rewards sustained city engagement without making morale a mandatory optimization target. Low morale does not penalize XP. The multiplier is a reward for positive patterns, not a punishment for negative ones. Consistent with the consequence without punishment principle.

PER-NEIGHBORHOOD MORALE GEOGRAPHY: Morale tracks at the neighborhood level, not city-wide only. A hero who consistently engages with minor objectives and escort missions in a given district builds morale there specifically. Districts the hero rarely visits hold at baseline. The city can carry pockets of high morale alongside areas that haven't felt the hero's presence yet.

Geographic granularity produces three downstream effects:
- Citizens in high-morale neighborhoods are visibly warmer and more active in the run environment
- Name emergence through the Citizens channel is more likely in high-morale neighborhoods
- Rex Flynn notices and covers geographic disparity if the algorithm suggests it will perform

Per-neighborhood morale does not create punishing states. No neighborhood crashes to zero permanently. All recover over time regardless of hero engagement. Consequence without punishment applies at neighborhood level as well as city level.

DATE: May 6, 2026

WHY: City-wide morale tracking alone felt too abstract — the city is a place with distinct neighborhoods, and the hero's presence should be felt at street level. Per-neighborhood tracking makes the world feel inhabited and responsive without adding optimization complexity. The XP multiplier gives morale a run-layer mechanical hook that rewards city engagement without gating anything.

REPLACES: Nothing — expands existing morale entries.

STATUS: DRAFT

---

ENTRY 1 OF 4

DECISION LOG ENTRY

DECISION: Hero Points are the player-facing currency of Apex Chronicles. They accumulate across runs — through random mob drops (physical collectibles, auto-collect off) and guaranteed drops from minor objectives (muggings, citizen assists, environmental incidents) — and are spent in the Training Center on tiered hero power upgrades. Hero points carry permanently between runs with no loss on failure. Design target: approximately 15 hero points per active run across both avenues. Illustrative upgrade tier costs: Tier 1 ~5 HP / Tier 2 ~10 HP / Tier 3 ~15 HP / Tier 4 ~20 HP — subject to balancing. Quantity per minor objective drop TBD. "Hero Points" is a placeholder name; final in-game naming TBD.

DATE: May 8, 2026

WHY: Hero points give every run a floor of value regardless of outcome. Physical mob drops preserve the satisfying collection loop established by genre references (VS, DRGS, Hades). Guaranteed minor objective drops create a direct incentive to engage with the city as a living place rather than just a combat arena. Full carry between runs with no loss on failure is consistent with consequence without punishment — the locked core principle. Tiered upgrade costs per power create meaningful investment decisions without prescribing a build path.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

ENTRY 2 OF 4

DECISION LOG ENTRY

DECISION: A run is successfully completed when the player commits to one of the three main missions (Boss Fight, Escort Defense, or Horde Survival) and successfully executes it. Completion of any one main mission is the sole success criterion. A run is failed when the player commits to a mission and fails to execute it, or is defeated before committing. Failed runs do not count toward class mastery progress, power proving, or city outputs — but do generate hero points based on run activity and city atmospheric consequence. No progress is set back on failure. The 20-minute run time is a design target and natural rhythm, not a hard mechanical timer. Structure: Act One (0–5 min) free prep; Act Two (5–15 min) open window with missions revealed; Act Three (15 min onward) forced commitment gate — the only hard mechanical enforcement. Mission execution itself carries no hard timer.

DATE: May 8, 2026

WHY: Defining completion clearly is load-bearing for class mastery tracking, power proving, city outputs, and hero point accumulation. The DRGS extraction model is the correct reference — you committed to a mission, you executed it, you succeeded. Reframing the 20-minute structure as soft pressure rather than a hard timer preserves player agency and avoids the punishing feeling of a countdown clock while maintaining the dramatic shape of the three-act run structure.

REPLACES: Any prior implication that 20 minutes is a hard mechanical timer. The timer is a design target. The Act Three commitment gate is the only hard mechanical enforcement.

STATUS: DRAFT

---

ENTRY 3 OF 4

DECISION LOG ENTRY

DECISION: A hero power is proven when all three of the following conditions are met within a single run: (1) the power randomly appears in the run's milestone offering; (2) the player selects the power; (3) the player successfully completes a main mission in that run. All three conditions are required. Selection without run success does not qualify. Discovery without selection does not qualify. When proven: the corresponding Training Center section activates, a Superhero Community sponsor message surfaces, and the hero power deepening system becomes available for that power.

DATE: May 8, 2026

WHY: Proving a power requires genuine engagement — not just receiving it randomly and surviving. The three-condition definition ensures that sponsor messages and Training Center unlocks feel earned rather than accidental. Active selection and successful run completion are both meaningful thresholds that reflect real player investment in that power.

REPLACES: The two-condition definition (discovery plus run completion) used in City Layer Section 5 Step 1 and earlier Decision Log entries. Those definitions are superseded by this three-condition model.

STATUS: DRAFT

---

ENTRY 4 OF 4

DECISION LOG ENTRY

DECISION: The four class summon powers (Gorilla, Double Time, Specter, Sentinel) exist as a single pool entry in the shared hero power pool — not as four separate competing entries. The summon offering appears for any class. What is summoned is determined by the active class: Brawler receives Gorilla (animal companion); Speedster receives Double Time (speed clone); Blaster receives Specter (spectral ally, phases through walls); Tactician receives Sentinel (combat drone). The power is not class-restricted in availability — it is class-adaptive in expression.

DATE: May 8, 2026

WHY: Four separate summon powers competing in the pool would create situations where a Brawler receives Gorilla and the three other classes receive each other's summons as irrelevant offerings. A single adaptive summon entry ensures the offering is always relevant to the class receiving it while keeping the pool clean and uncluttered.

REPLACES: Earlier description of class summons as four separate named powers in the shared pool. The pool entry is one summon power with four class-adaptive expressions.

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Morale — XP Multiplier and City-Wide Scope (Corrected)

High morale produces a small XP multiplier for runs. The multiplier is modest
— it rewards sustained city engagement without making morale a mandatory
optimization target. Low morale does not penalize XP. The multiplier is a
reward for positive patterns, not a punishment for negative ones.

Morale is city-wide. There are no district-level morale states. There is no
aggregation mechanic. The player experiences one morale state that reflects
the city's overall relationship with the hero across the run record.

DATE: May 8, 2026

WHY: Per-neighborhood morale tracking introduced complexity without sufficient
ROI for the game Apex Chronicles is. District boundaries, district identity,
and player-facing communication of local morale states are all systems that
don't exist yet and would need to be designed from scratch to support this
mechanic. City-wide morale is simpler, more legible, and consistent with the
approachable design philosophy of Apex Chronicles.

REPLACES: Per-neighborhood morale geography section of Morale XP Multiplier
and Per-Neighborhood Geography entry (May 8, 2026). City-wide morale
supersedes neighborhood-level morale tracking.

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: The game's full title is Possibly a Hero. The working 
shorthand within the design pipeline is Hero. All prior references 
to Apex Chronicles and Apex as the working title are superseded 
by this entry.

DATE: May 8, 2026

WHY: Apex Chronicles was retired on two grounds. First, genre 
confusion — Apex Legends occupies the word Apex in gaming culture 
regardless of genre distinction, diluting any brand impact the 
title could establish. Second, and more importantly, the name did 
not reflect the register the game actually lives in.

Possibly a Hero was selected through a naming exploration that 
tested arc-register names, act-register names, comic-native names, 
humorous names, and single-word options. Possibly a Hero emerged 
as the name that most accurately communicates the emotional premise 
of the game — an unnamed, unproven hero arriving in a city that 
hasn't decided about them yet — while carrying the humor and 
lightness that is native to the game's tone.

Three factors confirmed the decision:

1. Visual identity alignment — the shadow logo concept (civilian 
figure casting a superhero shadow) was already in use in the 
designer's personal brand before this game existed. The name and 
the visual language arrived at the same place independently.

2. Non-gamer accessibility — the title communicates the full 
emotional premise of the game without genre knowledge required. 
Tested immediately with a non-gamer who connected with it 
instinctively.

3. Register commitment — Possibly a Hero is a deliberate and 
conscious choice to name the game from a position of vulnerability 
and humor rather than authority and aspiration. This is a 
design-level decision about what the game is, not just what it 
is called. The name serves as a standing commitment to the game's 
tone and a check against pretension in future design decisions. 
When a decision feels too serious for a game called Possibly a 
Hero, that is useful information.

The working shorthand "Hero" functions cleanly in development 
conversation — "how's Hero coming," "Project Hero" — without 
the acronym problems of the full title.

REPLACES: "The game's full title is Apex Chronicles. Working 
designation within the design pipeline is Apex." — STATUS: LOCKED. 
That entry is hereby superseded and should be treated as 
DEPRECATED.

STATUS: LOCKED

---

DECISION LOG ENTRY

DECISION: Mission locations spawn at the Act Two reveal (five-minute mark),
not at run start. Each mission spawns outside the hero's current proximity
trigger radius — guaranteed safe distance at spawn. From that moment, missions
are live and triggerable by player movement. No mission can be triggered
during the prep period. No mission can blindside the player at the moment
of reveal.

DATE: May 9, 2026

WHY: The previous model allowed mission locations to exist on the map during
the prep period, triggerable by proximity. Playtesting instinct identified
this as a "feels bad man" moment — a consequence-without-punishment violation
dressed up as emergent gameplay. The fix preserves tension during the prep
period through enemies and minor objectives while ensuring mission triggers
are always a result of player choice and movement, not accidental discovery.
Proximity placement at spawn means the close mission creates immediate
strategic tension at reveal without being an ambush.

REPLACES: Run Time Structure — Act One stumble mechanic language

STATUS: LOCKED

---

DECISION LOG ENTRY

DECISION: The fifteen-minute forced commitment gate is correct and intentional.
It is a hard gate, not a soft clock. Failure to commit to at least one mission
at fifteen minutes results in run failure. The mission itself has no hard
timer. The twenty-minute figure is the natural rhythm of a well-executed
minimum run, not a death clock.

DATE: May 9, 2026

WHY: The forced commitment gate is the game asking the question the whole run
was building toward — "you've been building, now what are you going to do
with it?" Not committing is not a neutral choice in a game about becoming a
hero. It is a refusal to be the thing the game is about. The gate is not a
penalty. It is the point. Document language should reflect this framing
rather than hedging between soft and hard clock language.

REPLACES: Run Time Structure — soft clock framing language in Act Three

STATUS: LOCKED

---

DECISION LOG ENTRY

DECISION: All three missions are completable within a single run. Run
completion tiers are: minimum success (one mission complete), exceptional
(two missions complete), perfect (three missions complete). The forced
commitment gate at fifteen minutes is the minimum commitment threshold —
the player must attempt at least one. The run ends on extraction or time
expiry. Mission outputs stack — a perfect run feeds all three city systems
simultaneously. Mission priority is a player-driven strategic decision
tied to their own progression goals.

DATE: May 9, 2026

WHY: The previous model forced an either/or choice at the moment the game
asks the player to be a hero — philosophically backwards. A hero doesn't
triage the city and abandon two thirds of it by design. The new model
preserves the forced commitment gate while expanding what commitment means.
Players who need intel prioritize Horde Survival. Players who need resources
hit the Boss Fight first. The city provides the context, the run provides
the opportunity, and sequencing three real missions under time pressure is
genuinely the player's to figure out. The "feels bad man" of leaving citizens
or villains unaddressed dissolves — the player ran out of time, not out of
options.

REPLACES: Run structure — single mission completion as run end condition

STATUS: LOCKED

---

DECISION LOG ENTRY

DECISION: The run has a hard outer wall at twenty minutes. The run ends at
the wall, on player-chosen extraction, or when the hero is taken out of the
fight — whichever comes first. Run completion tiers are graded at run end
based on missions completed: minimum success (one), exceptional (two),
perfect (three).

Build development is continuous for the entire run. Milestone level-ups and
power selection are available from the first minute to the last — there is
no build phase and no point at which loadout development stops. Minor
objectives continue spawning for the full run duration. The three acts are
information states, not rule states: Act One is the period before missions
spawn, Act Two is full information, the fifteen-minute gate is the minimum
commitment threshold.

Mission outputs are earned at mission completion, not at run resolution.
Banked missions are permanent within the run — being taken out of the fight
after completing a mission costs the player the opportunity at a higher
tier, never the tier already earned. A run ending with zero completed
missions remains a failed run under existing failed-run rules: Hero Points
carry in full, atmospheric consequence only, no city outputs.

The strategic core of the run is the allocation of wall time between
building and executing. Committing early with a lean build and committing
late with a developed build are both valid strategies. Mid-run pivots
between building and executing are sanctioned play, not exploits.

DATE: June 12, 2026

WHY: The May 9 completion tiers decision referenced "time expiry" without
defining it, and removed the implicit build bound the old single-mission
model provided. The hard wall is that definition and that bound. It makes
"sequencing three real missions under time pressure" mechanically true,
makes the perfect run a genuine mastery expression rather than an endurance
test, and keeps every run inside a twenty-minute pick-up-and-play promise.
The wall is not a death clock — expiry grades the run, it does not fail it.
Consequence without punishment: what the player earned at the moment they
earned it is theirs. Continuous build development enables varied strategy
(rush lean, build deep, pivot mid-run) with a single timer and no
special-case rules.

REPLACES: "The Act Three commitment gate is the only hard mechanical
enforcement" (Run Completion and Success Criteria, May 8, 2026) — the wall
is a second hard enforcement. All other May 8 language stands. Also
replaces all "loadout development stops at the commitment gate" framing
in Run Time Structure language.

STATUS: LOCKED

---

DECISION LOG ENTRY

DECISION: The Run Design document is LOCKED. It is the first locked
document in the Possibly a Hero pipeline. Run Design now constrains all
draft documents and all future design work. Drafts that contradict it
must conform to it or amend it through the formal pipeline.

The document moves to the /locked directory. The canonical manifest
reflects LOCKED status as of this entry.

Canon Guard Caution 1 resolution: the language "meaningfully more than a
single mob drop" for minor objective Hero Point rewards is retained
deliberately. It is a design-intent constraint that future balancing must
satisfy — the quantity per drop remains TBD per the Hero Points entry
(May 8, 2026). The relative relationship is canon; the numbers are
balancing.

DATE: June 12, 2026

WHY: Run Design has incorporated all four governing locked decisions —
Mission Spawn at Act Two Reveal (May 9), Forced Commitment Gate (May 9),
Run Completion Tiers (May 9), and Run Wall / Continuous Build / Banked
Mission Permanence (June 12). It passed a full-document consistency sweep
and a Canon Guard validation with zero conflicts. The run is the system
every other system feeds or feeds from — locking it first gives City
Layer, Class System, and World Feedback a fixed authority to conform to.

REPLACES: Nothing — status change. Run_Design DRAFT status is superseded.

STATUS: LOCKED

---

DECISION LOG ENTRY

DECISION: Combat philosophy and the skill-acquisition loop. Combat in
Possibly a Hero follows a three-rung escalation defined by the player's
relationship to their build, not by difficulty tiers:

- Trash mobs = PRACTICE. Low-stakes encounters where the player learns
  their powers, spacing, and combos. Skill is acquired here.
  Experimentation is cheap.
- Sub-missions (minor objectives) = VALIDATION. Confirmation that build
  plus skill is cohering. The validation payoff is earned Hero Points —
  permanent, cross-run progress. Validation is felt across runs, not via
  in-run feedback: next run starts stronger.
- Main missions = EXECUTION. The build and skill performed under the
  wall, for completion tiers. Skill is spent here.

Trash combat does NOT scale with the player. Late-run trivialization of
trash is intentional and self-balancing: when trash stops being a
challenge, the game is signalling the player is ready to turn toward
missions. Trivial trash clears fast, so lingering past readiness carries
an opportunity cost against the wall — combat pacing becomes a form of
consequence without punishment. The trash stops paying; the clock keeps
running.

Framing thesis: in Possibly a Hero the player knows their WHY but not
their HOW. The game teaches the how through repetition across runs, not
through tutorial explanation — the player learns how the game speaks
over multiple playthroughs (Vampire Survivors / Deep Rock Galactic
Survivors learning model). Combat is intentional and skill-based with
the build as vocabulary and player skill as expression (Hades texture).

DATE: June 12, 2026

WHY: The locked combat value ("intentional and skill-based, a skilled
player with a mediocre build beats an unskilled player with a great
one," May 2026) asserted that skill matters but did not define how skill
is built up or how combat earns the player's time against the run wall.
This establishes the texture and the loop. The three-rung ladder gives
every combat layer a distinct role in the time economy rather than
having trash combat compete with missions as a rival attraction. Trash
as non-scaling practice resolves the wall tension: practice feeds toward
execution rather than rivaling it. Hero Points as the validation
currency aligns the reward with its persistence — validation is
permanent progress, which is why it is felt across runs.

REPLACES: Nothing — extends the locked combat value with structure.

STATUS: NOTED

OPEN QUESTIONS (to validate before this hardens to DRAFT):
- Does trash trivialization pace correctly, or does late-run trash become
  tedious before the player turns to missions?
- Does the Hero Point validation payout feel meaningful, or invisible?
- Does intentional combat survive translation to a low-fidelity
  prototype, or does the feel require Unreal to read at all?

---

DECISION LOG ENTRY

DECISION: Possibly a Hero adopts a Guiding Principles layer — a
governing document that sits above all system documents. The
established design principles (consequence without punishment;
mirrors not gates; mastery is real and expressible; identity emerges
through play; the name as tone guardrail) are relocated out of the
system/state documents where they have been embedded and consolidated
into this single governing document. Guiding Principles outranks
LOCKED: any system document that contradicts a guiding principle is
in error and gets corrected — the principle wins. Validation order:
content is checked against Guiding Principles BEFORE it is checked
against other system documents.

DATE: June 13, 2026

WHY: The principles have governed design decisions since early in the
project (mirrors not gates and consequence without punishment have
both killed real directions) but lived scattered inside system and
state documents, discoverable only by reading the system that happened
to mention them. They had authority without an address. The pipeline
has matured to the point where principles must sit above the systems
they govern rather than inside them — the same role guiding principles
play in a mature operating philosophy. This is a structural maturation
of the design machine, surfaced when a candidate design pillar had no
appropriate layer to live in.

REPLACES: Nothing — new structural layer. (Does not alter the contents
of any system document; relocates principles already in force.)

STATUS: LOCKED

CARRIES OPEN: (1) The exact wording of each principle still needs a
sharpening pass — each must be operative enough to reject a design,
not merely descriptive. (2) Canon Guard and Cross-System Auditor system
prompts need updating to reflect the new top-of-stack authority and
validation order. (3) Whether the layer's contents live as their own
repo document or are enforced through Forge's disposition is a separate
implementation question.

---

DECISION LOG ENTRY

DECISION: Possibly a Hero adopts a three-rung event-and-reward model
for what the player spends run time on. The three rungs are
differentiated by EMOTIONAL REGISTER and REWARD KIND, not by amount
of a shared reward.

1. ENCOUNTERS — ambient combat. Thugs aggro the player; the fight is
   reactive and about the player, with no victim and no moral stakes.
   Encounters happen in transit, are NOT shown on the minimap, and are
   deliberately forgettable. Reward: XP only (build/power progression).
   No Hero Points. These are the "trash = practice" rung made
   fiction-coherent — ambient danger in a crime-ridden city.

2. MINOR OBJECTIVES — moral choices that contain a fight (or a non-
   combat save). A citizen is in danger: mugging, robbery, fire,
   runaway vehicle, etc. About the city, not the player. Shown on the
   minimap AND announced by diegetic, type-bearing audio (scream,
   siren, call for help, menacing threat) so the player can identify
   the situation before committing. Reward: Hero Points (their
   DEFINING and EXCLUSIVE source) + XP + recognition/morale/name-
   emergence + hidden tracker movement, scaling by objective type.
   Reward-dominant by design.

3. MISSIONS — the run's structural purpose. Forced by the 15:00 gate,
   graded in completion tiers at the wall. (Unchanged from locked Run
   Design; included here for the full ladder.)

SUPPORTING DECISIONS:

- HERO POINTS ARE A CIVIC CURRENCY. HP is earned ONLY through minor
  objectives (helping the city) and spent ONLY on power deepening
  (Training Center). The player grows stronger by being trusted, not
  by farming trash. This redefines HP from a generic combat reward
  into the currency of having helped.

- REWARD MATCHES THE ACT'S NATURE. Self-interested acts (encounters)
  pay self-interested reward (your build). Other-directed acts (minor
  objectives) pay other-directed reward (the city's recognition and
  recovery). A pure power-optimizer levels fast but stays anonymous;
  a hero who stops for everyone is slower but beloved. Neither is
  wrong — they produce different KINDS of hero. This is consequence
  without punishment and identity emerges through play expressed in
  the moment-to-moment loop.

- MINOR OBJECTIVES ARE HARDER THAN ENCOUNTERS — qualitatively, not
  quantitatively. Not bigger swarms (that re-imports the conveyor
  belt) but tougher enemies, hostage/constraint situations, and
  precision demands (e.g. a citizen in the blast radius makes AOE a
  liability). The added difficulty is what makes the reward-dominant
  minor objective a real CHOICE rather than free upside: the cost is
  real — wall-time, health, cooldowns, and tier-risk.

- THE MORAL CHOICE IS WALL-TIME TRIAGE. Because minor objectives are
  reward-dominant, the player always WANTS to stop. The only
  constraint is whether they can AFFORD to — against the clock, the
  15:00 gate, and their mission-tier ambitions. The dilemma is never
  "is it worth it" (it always is) but "can I afford it." Difficulty
  sharpens this naturally late-run: a hero who could save everyone at
  minute 3 must make hard calls at minute 13.

- MINIMAP / INFORMATION SPLIT. The minimap shows only missions and
  minor objectives — the things worth navigating toward. Encounters
  never appear, which structurally enforces their flatness (the map
  cannot direct the player to farm trash). Minor-objective spawns get
  a minimap flourish plus the diegetic audio cue on the main screen.

DATE: June 13, 2026

WHY: The session set out to fix prototype combat (an infinite-swarm
"XP conveyor belt" producing 300+ kills and runaway leveling) and
surfaced that the combat MODEL, not its tuning, was the problem. The
fix is to make combat a chosen resource under time pressure rather
than a survival swarm — and the act of designing that reframe revealed
that the run's three time-sinks already wanted to be three distinct
emotional registers. Locating the moral choice ("what kind of hero are
you") in the minute-to-minute loop, rather than only in fiction or
meta-progression, makes the title's question (Possibly a Hero) a thing
the player answers continuously through play. The reward-by-kind split
makes the three principles (consequence without punishment, mirrors not
gates, identity emerges through play) do the balancing automatically.

REPLACES: Nothing — new model. Sits atop and is consistent with locked
Run Design (the 20-min wall, 15:00 gate, completion tiers). Sharpens
the prior "combat as harvest, not threat" NOTED direction and the
"trash = practice" combat-ladder entry by giving them a full reward
architecture.

STATUS: NOTED

CARRIES OPEN (prototype must validate before any lock):
1. Does wall-time triage actually FEEL like a choice, or does
   "always stop" collapse the dilemma? This is the load-bearing
   assumption; the prototype is the instrument.
2. Does qualitative difficulty (constraints, tough types) read as
   rising stakes late-run, or just as the game turning stingy?
3. With encounters paying XP-only and minor objectives carrying most
   of the XP+HP, does the leveling curve hold across a full 20-min
   run? (Current swarm-model tuning is void once the model changes.)
4. Does removing encounters from the minimap leave the player
   under-informed, or does the diegetic-audio layer carry enough?
5. Hidden-tracker movement "by objective type" implies minor
   objectives have TYPES that move DIFFERENT trackers — a
   characterization system seeded here but deliberately NOT designed
   in this entry. Reserved for the dedicated minor-objectives session.

NOT IN SCOPE OF THIS ENTRY: The design of minor objectives themselves
— their types, moral textures, flavor, and emotional content — is a
separate dedicated session. This entry defines only the architecture
they operate within.

---

DECISION LOG ENTRY

DECISION: The Guiding Principles layer is implemented through Forge's
disposition, not as a standalone repo document. Forge is the sole
principle guardian across the pipeline. Canon Guard and Cross-System
Auditor handle document and cross-document validation only — principle
conflicts surface through Forge in design conversations. No separate
Guiding Principles document will be created.

DATE: June 14, 2026

WHY: The principles are already operational in Forge's instructions and
active in every design conversation. A standalone document adds fetch
overhead without adding authority. Forge carries the appropriate context
and disposition for principled pushback; fighting the same battle across
multiple agents is unnecessary overhead.

REPLACES: Carries Open item (3) from the Guiding Principles layer
LOCKED entry, June 13, 2026.

STATUS: LOCKED
