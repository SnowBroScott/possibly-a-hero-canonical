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

DECISION: Hero Powers pool finalized at ten powers — shared pool, fully
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

Three-layer system confirmed:
- Class Primary — class-specific offensive powers
- Hero Powers — offensive with utility upside, mid-run pickups, shared pool,
  fully random
- Support Pool — genre-legible enhancements, class-agnostic

SUPPORT POOL (8 total — shared across all classes):
Combat: Attack Speed, Attack Damage, Impact Area/AOE, Critical Hit Chance,
Cooldown Reduction
Utility: Movement Speed, Experience Multiplier
Safety: Revive

HERO POWERS (9 total — shared pool, fully random):
1. Magnetism — pull enemies together, redirect projectiles, strip weapons
2. Time Slow — brief local time dilation; everything slows, player doesn't
3. Weather Control — lightning strikes, wind gusts, localized storms
4. Earth/Ground Manipulation — fissures, tremors, terrain as weapon
5. Portal Creation — displaces and moves enemies around the map; chaotic
6. Venom/Toxin — damage over time, spreads between enemies
7. Sonic Scream — stuns, disorients, chain damages
8. Light Manipulation — blinds enemies, creates decoys
9. Class-Specific Summon (unique per class):
   - Brawler: Animal Companion
   - Speedster: Speed Clone
   - Blaster: Spectral Ally
   - Tactician: Combat Drone

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

COMBO SYSTEM NOTE (flagged for future development):
Combination abilities emerge from mastery of multiple power types
simultaneously. Not designed yet.

DATE: May 3, 2026

WHY: Support pool uses genre-legible framing so players understand mechanics
immediately. Hero powers stay offensive with utility upside to protect class
identity and keep the three layers distinct.

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
- 10 runs: Elemental Surge — choose fire, ice, or lightning per run
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

REPLACES: Flight and wall crawling as movement pool options — both removed

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

REPLACES: Guardian as a standalone selectable class

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Run Camera Transition — Visual and Mechanical Structure

Every run opens in a low-to-the-ground third-person perspective. The intro
scene plays — third person, brief, cinematic. Hero arrives via their class
movement type. Camera swings up to isometric offset play mode. The city layer
operates on a separate camera (top-down or angled). Third-person assets are
scoped to the brief intro sequence only; the isometric offset angle handles
all run gameplay.

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
Social Media Influencer — each anchor a distinct primary reward track, with
name emergence shared as a secondary reward track across all three. Citizens
reward city aesthetics and development. The Superhero Community rewards player
cosmetics. The Social Media Influencer rewards run modifier unlocks. Name
unlock options are channel-specific in register, unlock permanently once
surfaced, and only surface when conditions are right.

DATE: May 3, 2026

WHY: Pillar structure ties reward source to reward type. Modifier unlocks give
the influencer mechanical teeth and add replayability depth critical to the
roguelite format.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Apex Chronicles is a superhero roguelite city-building game. Players
go on runs that generate resources and outcomes that feed city building. The
city built shapes the hero's available powers and abilities. The two halves
are inseparable — runs shape the city, the city shapes the runs.

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

STATUS: LOCKED

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

DECISION: Every run map contains three path types: boss fight, passive escort
defense, and horde survival. These are not separate modes — they are locations
and activities discoverable within a single run map.

DATE: May 3, 2026

WHY: Keeps the run loop consistent while delivering mechanical variety.
Players self-select based on city needs and personal preference within a
single session.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Each run path type feeds a distinct city system: boss fights
generate resources for city construction, escort defense missions sustain city
morale, horde survival missions generate intel.

DATE: May 3, 2026

WHY: Creates genuine strategic tension during runs. Players are making city
management decisions through their path choices without the game feeling like
a management game.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Intel gathered through horde survival missions identifies the area's
super villain. Sufficient intel is required to trigger the area boss encounter.
The area boss gates progression to the next area or level.

DATE: May 3, 2026

WHY: Makes intel missions load-bearing for progression, not optional. All
three path types become necessary rather than preferential.

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
citizens (warm, local, affectionate), the social media influencer (editorial,
slightly damning), and social media (chaotic, meme-driven, no dignity).
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
(May 5, 2026). Retained for historical record only.

DATE: May 3, 2026

STATUS: DRAFT — SUPERSEDED

---

DECISION LOG ENTRY

DECISION: Within a run, powers progress and combine through the roguelite
loop. Starting loadout is set by the city but the run determines how those
powers develop and what combinations emerge.

NOTE: This entry is superseded by "City Buildings — Mirrors Not Gates"
(May 5, 2026). Retained for historical record only.

DATE: May 3, 2026

STATUS: DRAFT — SUPERSEDED

---

DECISION LOG ENTRY

DECISION: The ability to merge or combine specific powers during runs is
unlocked through city construction. Without the relevant city building, certain
merges are not available regardless of what powers the player holds during
a run.

NOTE: This entry is superseded by "City Buildings — Mirrors Not Gates"
(May 5, 2026). Retained for historical record only.

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
2. Boxing Gym — unlocked by completing a Boss Fight run. Teaches hero powers.
3. Tailor Shop — unlocked by completing an Escort Defense run. Teaches
   cosmetics and appearance customization.
4. Area Boss Defeated — completes the tutorial arc. Player has demonstrated
   mastery across all three run path types.
5. Hero's Lair — unlocked upon area boss defeat. Serves as headquarters.
   Houses combo development, mastery mechanics, achievement displays,
   cosmetic loadout management, and run statistics review.

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
1. Science Lab — unlocked by completing an Intel run. Houses support skills.
2. Boxing Gym — unlocked by completing a Boss Fight run. Houses hero powers.
   Every hero power selected during a run is logged here for deepening and
   training.
3. Tailor Shop — unlocked by completing an Escort Defense run. Houses
   cosmetics and appearance customization.
4. Hero's Lair — unlocked upon area boss defeat. Serves as headquarters.
   Houses combo discovery log, achievement displays, unlocked name history,
   and cosmetic loadout management. The most dramatic mirror in the city.

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
buildings add world depth without overcomplicating the design. Lean initial
scope allows for organic expansion if needed.

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

THE GYM — Every hero power a player selects during a run is added to the gym.
Players can deepen, train, and improve powers they have already encountered.

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
routing, and Core Four buildings (Lab, Gym, Tailor Shop, Lair) are consistent
landmarks across all stages and recognizable within the run layer.

The city develops through four visual stages. Each stage is mechanically a
distinct run environment layered on top of the same underlying street
geography.

STAGE ONE — Rundown. Tutorial environment. One mission type per run, heavily
nudged. Lowest difficulty.
STAGE TWO — Developing. Mid-game. All three mission types available. 
Increasing enemy density and challenge.
STAGE THREE — Refined. Late mid-game. Full mechanical complexity. Higher
difficulty.
STAGE FOUR — Modern. Endless live game tail. Rex Flynn modifiers. Procedurally
generated missions and bosses. Maximum difficulty and replayability.

Cosmetic city improvements do not propagate granularly into the run layer
beyond stage-level visual identity.

DATE: May 5, 2026

WHY: Sharing the same street map creates spatial memory and narrative
coherence. City growth does double duty — rewarding progression and raising
stakes simultaneously. Stage Four ensures a live game tail without requiring
separate mode development.

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
locations support narrative variety and prevent the world from feeling scripted.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Class Mentor System — Framework and Introduction Triggers

Each of the four classes has a corresponding mentor character who occupies a
class-specific building in the city. These buildings exist from early
progression but appear non-descript until the mentor relationship unlocks. At
unlock, the building reveals what it actually is — hidden in plain sight.

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
happens — not the gate that controls it. Mentor introductions are world
events that generate content across all three feedback channels.

DATE: May 5, 2026

WHY: The mentor system transforms class mastery unlocks from arbitrary
progression gates into relationships with narrative weight. The
hidden-in-plain-sight building reveal rewards city exploration. Mentor
introductions as world events connect the system to the feedback channels.

REPLACES: Nothing — new decision

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: Camera and Combat Model

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
The closer camera opens the city to minor objectives — incidental heroic
moments alongside the three main mission types. Muggings, citizens in danger,
environmental incidents. These are opportunities, not formal missions.

Minor objectives feed:
- Morale (Citizens channel)
- Recognition (Superhero Community channel)
- Clickbait (Rex Flynn channel)

Minor objectives do not generate intel. Intel remains exclusively tied to
the horde survival mission. Minor objectives are a natural source of early
name emergence — patterns of incidental heroism citizens notice before any
formal mission is completed.

DATE: May 5, 2026

WHY: Camera distance determines combat philosophy, movement identity, and
world legibility. Hades distance makes the city feel inhabited and the hero
feel powerful. Intentional skill-based combat creates genuine mastery
expression. Minor objectives make the city feel alive and feed the feedback
channel ecosystem naturally.

REPLACES: DRGS as primary camera reference — superseded by Hades with open
world scope.

STATUS: DRAFT

---

DECISION LOG ENTRY

DECISION: The Training Center is a single building with four distinct visual states — The Gym (Stage One), The Complex (Stage Two), The Facility (Stage Three), and The Tower (Stage Four) — that evolves across all city stages proportional to the hero's story and proven run history. The Hero Power Deepening System activates at Stage Two: when a player proves a hero power in a run, a Superhero Community message surfaces from a thematically matched hero, directing the player to a newly activated section of the training center. Sections remain dark and gated until the corresponding power is proven. The building is explorable at every stage and reads as a cumulative map of the player's run history. Hero power deepening (mastery development) is housed here; primary class power improvement is not.

DATE: May 6, 2026

WHY: One building with four visual states maps cleanly to the existing four-stage city progression without adding build complexity. The explorable building model (Hades reference) is proven to work at this scale. The Superhero Community message trigger gives an existing reward channel mechanical significance. Keeping discovery free and deepening housed in the building preserves the mirrors-not-gates philosophy while resolving the Canon Guard conflict around city-gated power access.

REPLACES: Earlier gym model that contained hero powers without a deepening system or stage-based evolution.

STATUS: DRAFT

---
