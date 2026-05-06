# Apex Chronicles — Canonical Manifest
*Single source of truth for all pipeline documents*

Last updated: May 5, 2026

---

## How to Use This Manifest

Every agent fetches this manifest before doing any work.
1. Locate the document needed and confirm its status.
2. Fetch the document using the raw URL listed below.
3. Confirm the fetch before beginning any work.
4. Locked documents take authority over drafts.
5. Deprecated documents have no canonical authority.
6. If a fetch fails, stop and report it. Do not fall back to memory.

---

## Document Status Hierarchy

| Status | Meaning |
|---|---|
| LOCKED | Non-negotiable. Constrains everything below it. |
| DRAFT | Directionally committed. Still refinable. |
| NOTED | Worth capturing. Not yet a formal decision. |
| CANONICAL SOURCE | Origin document for pipeline decisions. Entry-level authority applies — treat each entry according to its own stated status. |
| DEPRECATED | Superseded. Historical reference only. |
| REFERENCE | Supporting material. Not subject to pipeline. |

---

## Active Documents

### decision-log
- **Status:** CANONICAL SOURCE — contains entries of mixed status. 
  LOCKED entries within are non-negotiable. Document grows 
  continuously as decisions are recorded.
- **Raw URL:** https://raw.githubusercontent.com/SnowBroScott/apex-chronicles-canonical/refs/heads/main/decision-log
- **Notes:** Primary record of all design decisions. Every agent 
  fetches this document directly. Do not rely on summaries 
  or static uploads as substitutes for a live fetch.

---

## Pending Documents
*Documents to be created as the pipeline develops*

### run-design
- **Status:** NOT YET CREATED
- **Purpose:** Complete run structure specification — 20 minute arc, 
  three acts, mission types, power selection, player agency model.

### class-system
- **Status:** NOT YET CREATED
- **Purpose:** Four classes, movement, offensive suites, unlock 
  structure, mentor system.

### city-layer
- **Status:** NOT YET CREATED
- **Purpose:** Building model, mirror not gate philosophy, four stages, 
  restoration model, tutorial arc buildings.

### world-feedback
- **Status:** NOT YET CREATED
- **Purpose:** Citizens, Superhero Community, Rex Flynn, name emergence.

### CLAUDE.md
- **Status:** NOT YET CREATED
- **Purpose:** Project brief for Claude Code. Lives at repo root. 
  Engineering directives, tech stack, system specifications, 
  document access protocol.
- **Trigger:** After core design systems are locked and build work 
  is ready to begin.

### locked/ directory
- **Status:** NOT YET CREATED
- **Purpose:** Canonical, non-negotiable documents.

### draft/ directory
- **Status:** NOT YET CREATED
- **Purpose:** Directionally committed documents still in refinement.

### reference/ directory
- **Status:** NOT YET CREATED
- **Purpose:** Supporting material. Not subject to pipeline validation.
