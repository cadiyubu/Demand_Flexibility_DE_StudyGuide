# Phase 1 Plan — Demand Flexibility Learning Studio

Summary: 30 working sessions (Thu 15 Oct – Wed 25 Nov 2026), about 2–3 h each, taking Caro from TSO-side expertise to defensible judgment on demand flexibility in DE/EU. Brief, IA and lesson specs: the Claude doc "Demand Flexibility Learning Studio — Brief, IA & Learning Path".
Status: Day 0 done (14 Oct) · Next: Day 1

**Fallback (job starts before plan ends): drop to 1 h per day.**
- 1-hour session: 10 min brief · 35 min primary-source reading + note · 10 min sparring (3 questions) · 5 min journal.
- Each remaining lesson takes 2× the listed days; exercises shrink to the smallest version that meets criterion (c).
- L5 and L6 become one session each; L7–L10 keep full scope.
- Tooling (Days 26–27) moves after Phase 1 exit; weekly reviews stay.
- Note the switch date and new end date here.

## How we work each day (session protocol)
1. **Open** a new chat in the EnergyAuthorityExpert Project and type `Day N` + yesterday's "verify next" line from the journal.
2. **Claude briefs (10 min):** reads this plan + `registry/`, re-checks the status of today's rules on the web, gives the reading order with links.
3. **Caro reads primary sources (60–90 min)** and writes the concept note in her own words (`_templates/concept.md`).
4. **Claude spars (20 min):** 5 quiz questions, challenges each claim, checks the note against the quality rules, drafts registry entries.
5. **Caro closes (10 min):** journal entry, ticks the day below, commits.

**Weekly review (every Friday, 20 min):** rule freshness (all `checked` ≤ 30 days), content/tooling ratio (target 70/30), lesson completion, open questions closed.

**Lesson done when:** (a) concept note with ≥ 2 T1 sources in the registry; (b) 5-minute no-notes explanation, recorded or written; (c) exercise artifact saved; (d) ≥ 1 open question logged.

**External check (no practitioner):** public feedback after publishing; until then, red-team every key claim against published stakeholder positions and a fresh-eyes AI review. Log every correction in `notes/feedback-log.md`.

**Guardrails:** no code before Day 26 · facts only with a registry source · every rule carries status + date · AI may summarise a source, never set a legal status.

---

## Week 1 — Setup, L1 Energy/capacity/flexibility, L2 Flexibility needs (FNA)
| Day | Date | Focus | Output | Done when |
|---|---|---|---|---|
| - [x] 0 | Wed 14 Oct | Folder, registry seed, templates, plan | This folder | Exists |
| - [ ] 1 | Thu 15 Oct | Setup: `git init` + private GitHub repo; add MASTER_PROFILE to knowledge folder; paste backlog row ID 4; create `notes/feedback-log.md` (errors found, by whom, fix, date) | First commit, feedback log | Repo online |
| - [ ] 2 | Fri 16 Oct | L1 reading: definitions in Dir. (EU) 2019/944 Art. 2 and Reg. (EU) 2019/943 Art. 2 (EUR-Lex, consolidated) · Weekly review #1 | 2–3 source entries, concept draft | Definitions in own words |
| - [ ] 3 | Mon 19 Oct | L1 exercise: 12-product grid (what is bought × who buys) | `diagrams/l01-product-grid.mmd` | Every product placed with a source |
| - [ ] 4 | Tue 20 Oct | L1 close: 5-min explanation; red-team the note against one published stakeholder position | Journal, `notes/path/L01.md` | Lesson criteria a–d met |
| - [ ] 5 | Wed 21 Oct | L2 reading: ACER Decision 05/2025 Annex I (Art. 7–10), JRC FNA guide (Aug 2026); locate Germany's FNA report | Concept `fna.md` | 4 FNA deadlines stated |
| - [ ] 6 | Thu 22 Oct | L2 exercise: one week of DE residual load (ENTSO-E; register for token today) — mark ramp and short-term needs | Chart + note | Double-counting rule explained |
| - [ ] 7 | Fri 23 Oct | L2 close · Weekly review #2 | Journal, L02 | Criteria a–d met |

## Week 2 — L3 Roles, money and data flows · L4 Wholesale and dynamic tariffs
| Day | Date | Focus | Output | Done when |
|---|---|---|---|---|
| - [ ] 8 | Mon 26 Oct | L3 reading: EnWG §3 definitions, BDEW role model for market communication, aggregator rules in Dir. 2019/944 | Concept `roles-de.md` | 7 roles defined DE/EN |
| - [ ] 9 | Tue 27 Oct | L3 exercise: swimlane for one EV charger (money vs data flows) | `diagrams/l03-ev-swimlane.mmd` | No unlabelled arrow |
| - [ ] 10 | Wed 28 Oct | L3 close + glossary: 20 DE/EN terms | `glossary.yaml`, L03 | Criteria a–d met |
| - [ ] 11 | Thu 29 Oct | L4 (compressed: your BESS capstone covers spread economics): §41a EnWG dynamic tariffs (verify obligation scope), retail price components | Concept `dynamic-tariffs.md` | §41a status in registry |
| - [ ] 12 | Fri 30 Oct | L4 exercise: one month of 11 kW wallbox savings with real prices · Weekly review #3 | Calculation (notebook or sheet) | Reference case stated |
| - [ ] 13 | Mon 2 Nov | L4 close: where the €/MWh spread goes after taxes, levies, network fees | Journal, L04 | Criteria a–d met |

## Week 3 — L5 Balancing (compressed) · L6 Redispatch 2.0 (compressed) · Midpoint
| Day | Date | Focus | Output | Done when |
|---|---|---|---|---|
| - [ ] 14 | Tue 3 Nov | L5: regelleistung.net prequalification for pools; NC DR draft amendments to EBGL | Concept `balancing-dr.md` | Requirements listed with source |
| - [ ] 15 | Wed 4 Nov | L5 exercise + close: prequalification checklist for 2,000 heat pumps | Checklist, L05 | Pass/fail per requirement |
| - [ ] 16 | Thu 5 Nov | L6: Redispatch 2.0 from the DSO side; §§13, 13a, 14 EnWG; verify §13k status | Concept `redispatch-2-0.md` | Cost-based vs market-based explained |
| - [ ] 17 | Fri 6 Nov | L6 close: TSO-vs-DSO one-pager · Weekly review #4 · **Midpoint check:** 6 lessons? cut or extend? | L06, midpoint note | Decision written |

## Week 4 — L7 §14a EnWG · L8 §14c EnWG and local flexibility markets
| Day | Date | Focus | Output | Done when |
|---|---|---|---|---|
| - [ ] 18 | Mon 9 Nov | L7 reading: BNetzA BK6-22-300 and BK8-22/010-A; check 2026 EnWG amendments to §14a | Concept `enwg-14a.md` | Modules, 4.2 kW floor, fees explained |
| - [ ] 19 | Tue 10 Nov | L7: compare 3 DSO technical connection rules (e.g. EAM Netz, SW Nürtingen, a Bavarian DSO) | Comparison table | Differences sourced |
| - [ ] 20 | Wed 11 Nov | L7 exercise + close: fee-module decision tree for one household | `diagrams/l07-14a-tree.mmd`, L07 | Holds for 3 DSO rule sets |
| - [ ] 21 | Thu 12 Nov | L8 reading: §14c, §118(28) EnWG, BNetzA procedure status, NC DR chapter on DSO procurement | Concept `enwg-14c.md` | Status verified this week |
| - [ ] 22 | Fri 13 Nov | L8 exercise: 1-page §14c product spec for a congested MV/LV transformer (= seed of Backlog ID 1) · Weekly review #5 | `notes/path/L08-spec.md` | Passes red-flag list |
| - [ ] 23 | Mon 16 Nov | L8 close; red-team the spec against 2 published positions (e.g. DSO-association and aggregator consultation responses on §14c / local flexibility) | Journal, L08 | Every objection answered or logged |

## Week 5 — L9 Metering and M&V · Tooling slot (watcher)
| Day | Date | Focus | Output | Done when |
|---|---|---|---|---|
| - [ ] 24 | Tue 17 Nov | L9 reading (builds on your Colombia smart-meter analytics): MsbG rollout, iMSys/CLS control, baseline methods, NC DR measurement rules | Concept `baselines-mv.md` | 3 baseline methods compared |
| - [ ] 25 | Wed 18 Nov | L9 exercise + close: baseline error on one open load profile, two methods | Notebook, L09 | Error quantified |
| - [ ] 26 | Thu 19 Nov | Tooling: verify NeuRIS API status; write `scripts/check_sources.py` with an AI coding assistant (law XML, EUR-Lex, page-hash) | Script runs locally | Detects a changed fingerprint |
| - [ ] 27 | Fri 20 Nov | Tooling: weekly scheduled workflow opens an issue on change · Weekly review #6 | Workflow live | First scheduled run green |

## Week 6 — L10 Capstone · Phase 1 exit
| Day | Date | Focus | Output | Done when |
|---|---|---|---|---|
| - [ ] 28 | Mon 23 Nov | L10: revenue stacking, double counting, unit economics; Idea Judgment Canvas on 3 real ideas (EV, heat pump, industrial) | 3 files in `notes/judgments/` | Every score has evidence |
| - [ ] 29 | Tue 24 Nov | L10: publish-readiness review: fresh-eyes AI reviewer + red-team vs published positions on 3 notes + 1 verdict; pick first public items | Review notes, publish list | Every finding fixed or logged |
| - [ ] 30 | Wed 25 Nov | **Phase 1 exit:** definition-of-done checklist, gap list, Asset Explorer spec merged with Backlog ID 3; decide Phase 2 | `notes/phase1-exit.md` | Go/adjust decision written |

---

## Phase 1 definition of done
- [ ] 10 lessons meet criteria a–d
- [ ] Every rule in `registry/rules.yaml` checked ≤ 30 days
- [ ] ≥ 40 sources in the registry, ≥ 60 % T1
- [ ] 3 ideas judged with the Canvas
- [ ] 3 notes + 1 verdict passed adversarial review and are publish-ready
- [ ] Feedback log ready to receive public corrections
- [ ] Watcher live for 3 source types
- [ ] Gap list written

## Buffer rules
- Fall behind ≤ 2 days → absorb in the next Friday review.
- Fall behind > 2 days → compress L5/L6 further, never skip L7/L8.
- A lesson takes > 6 h → cut template fields, not sources.
