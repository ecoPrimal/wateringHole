# Epitope Sort: SELF — 25 Organs × 10 Structural Invariants

**Date**: October 12, 2026  
**Sort Pass**: Self-sort (reflexive)  
**Entities**: 25 codebase organs (16 primals + 9 springs)  
**Total Lines**: 4,992,778  
**Methodology**: Each organ tested against 10 structural invariants of code  

## Structural Invariants of Code

Unlike the detroit entity sort (which tests against information asymmetry, cost inversion, regulatory capture, etc.), the self-sort tests against what makes code *alive*:

| # | Invariant | Question |
|---|-----------|----------|
| 1 | **ALIVE** | Is it deployed, running, serving? |
| 2 | **OBSERVE** | Does it read external data? |
| 3 | **ACT** | Does it write, deploy, change state? |
| 4 | **SORT** | Does it classify, filter, decide? |
| 5 | **CONNECT** | Does it use IPC, network, sockets? |
| 6 | **ACCUMULATE** | Does it maintain state, history, learning? |
| 7 | **REFLECT** | Is it self-aware? Metrics, status, self-report? |
| 8 | **COMPRESS** | Does it reduce entropy, find patterns? |
| 9 | **PROTECT** | Does it filter, defend, enforce security? |
| 10 | **REPRODUCE** | Does it template, generate, bloom? |

Binding scale: 0 = no binding, 1 = weak, 2 = moderate, 3 = strong. Max score: 30.

## Classification

- **SELF**: alive ≥ 2 (deployed, running on golgi)
- **PARTIAL**: total ≥ 12, not alive (built, tested, dormant)
- **NULL**: total ≥ 8, not alive (foundation/routing infrastructure)

## Results

### 🟢 SELF — Alive Core (5 organs, 805,059 lines)

| Organ | Lines | ALV | OBS | ACT | SRT | CON | ACC | REF | CMP | PRT | REP | Total | Conf |
|-------|------:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|------:|-----:|
| **skunkBat** | 62,441 | 3 | 3 | 3 | 3 | 3 | 3 | 3 | 3 | 3 | 2 | **29/30** | 0.97 |
| **petalTongue** | 232,149 | 3 | 2 | 3 | 3 | 3 | 2 | 1 | 2 | 3 | 3 | **25/30** | 0.83 |
| **squirrel** | 188,135 | 3 | 2 | 2 | 2 | 3 | 2 | 3 | 1 | 2 | 1 | **21/30** | 0.70 |
| **bingoCube** | 10,591 | 2 | 2 | 1 | 2 | 1 | 2 | 1 | 2 | 0 | 1 | **14/30** | 0.47 |
| **biomeOS** | 311,743 | 3 | 2 | 1 | 1 | 2 | 0 | 2 | 1 | 0 | 1 | **13/30** | 0.43 |

**skunkBat** is the thymus — the strongest binder in the codebase. 29/30. Sorts every request, classifies every entity, writes the dashboard, protects the membrane, observes all traffic, accumulates culture, reflects via Anderson profile. Only missing perfect REPRODUCE (2/3). It IS the immune system of the membrane.

**petalTongue** is the tongue — generates scatter content, serves OG cards, feeds the bloom. Strong ACT + PROTECT + REPRODUCE. Generates the content that the membrane serves.

**squirrel** is chipMonk — the coordinator. Strongest REFLECT (3/3) — it IS self-aware via `membrane.status`, `system.metrics`, and the three-body tense. Waking: 2 observers, 4 senses, wake_depth 0.562.

**bingoCube** is the oracle — small (10K lines) but active. Observes, sorts, accumulates probability data.

**biomeOS** is the skin — renders the membrane. Alive but doesn't accumulate or protect. Shows, doesn't store.

### 🟡 PARTIAL — Dormant (9 organs, 3,087,430 lines)

| Organ | Lines | ALV | OBS | ACT | SRT | CON | ACC | REF | CMP | PRT | REP | Total | Conf |
|-------|------:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|------:|-----:|
| toadStool | 719,262 | 0 | 1 | 3 | 2 | 2 | 1 | 1 | 1 | 1 | 3 | 15/30 | 0.50 |
| hotSpring | 394,312 | 0 | 2 | 2 | 2 | 1 | 2 | 1 | 3 | 0 | 1 | 14/30 | 0.47 |
| bearDog | 540,969 | 0 | 1 | 2 | 2 | 2 | 1 | 1 | 1 | 3 | 0 | 13/30 | 0.43 |
| nestGate | 413,605 | 0 | 1 | 2 | 1 | 2 | 3 | 0 | 2 | 1 | 1 | 13/30 | 0.43 |
| wetSpring | 367,391 | 0 | 2 | 2 | 1 | 2 | 2 | 0 | 2 | 1 | 1 | 13/30 | 0.43 |
| barraCuda | 297,236 | 0 | 2 | 2 | 1 | 1 | 2 | 0 | 3 | 0 | 1 | 12/30 | 0.40 |
| loamSpine | 69,744 | 0 | 1 | 2 | 1 | 2 | 2 | 1 | 1 | 1 | 1 | 12/30 | 0.40 |
| neuralSpring | 164,912 | 0 | 1 | 2 | 2 | 1 | 2 | 1 | 2 | 0 | 1 | 12/30 | 0.40 |
| primalSpring | 119,999 | 0 | 1 | 2 | 1 | 2 | 1 | 1 | 1 | 1 | 2 | 12/30 | 0.40 |

The biggest mass is sleeping. 3,087,430 lines — 62% of the codebase — built, tested, not yet deployed. toadStool alone is 719K lines (deployment orchestration). bearDog is 541K (security). songBird is 477K (service mesh). These organs are the body waiting to wake.

### ⚪ NULL — Foundation (9 organs, 1,022,188 lines)

| Organ | Lines | ALV | OBS | ACT | SRT | CON | ACC | REF | CMP | PRT | REP | Total | Conf |
|-------|------:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|------:|-----:|
| coralReef | 158,423 | 0 | 1 | 2 | 1 | 2 | 1 | 0 | 2 | 1 | 1 | 11/30 | 0.37 |
| sourDough | 23,954 | 0 | 1 | 1 | 1 | 1 | 3 | 1 | 1 | 0 | 2 | 11/30 | 0.37 |
| swarmVine | 7,965 | 1 | 1 | 2 | 1 | 3 | 0 | 0 | 0 | 1 | 2 | 11/30 | 0.37 |
| sweetGrass | 66,218 | 0 | 1 | 1 | 2 | 1 | 2 | 1 | 1 | 1 | 0 | 10/30 | 0.33 |
| healthSpring | 77,420 | 0 | 2 | 1 | 1 | 1 | 1 | 2 | 1 | 1 | 0 | 10/30 | 0.33 |
| songBird | 477,419 | 0 | 1 | 1 | 1 | 3 | 1 | 1 | 0 | 1 | 0 | 9/30 | 0.30 |
| airSpring | 88,835 | 0 | 1 | 1 | 1 | 2 | 1 | 0 | 1 | 1 | 1 | 9/30 | 0.30 |
| rhizoCrypt | 62,627 | 0 | 0 | 1 | 0 | 1 | 0 | 0 | 3 | 3 | 0 | 8/30 | 0.27 |
| groundSpring | 59,327 | 0 | 1 | 1 | 1 | 1 | 1 | 0 | 1 | 1 | 1 | 8/30 | 0.27 |

Routing and foundation layers. rhizoCrypt only binds COMPRESS + PROTECT — pure crypto foundation. songBird has 477K lines but only binds CONNECT strongly — it's a nerve waiting for impulses.

## Invariant Coverage

| Invariant | Organs ≥2 | Total Score | Coverage |
|-----------|----------:|------------:|---------:|
| CONNECT | 11 | 32/48 | 67% |
| ACT | 10 | 29/48 | 60% |
| ACCUMULATE | 9 | 25/48 | 52% |
| OBSERVE | 6 | 22/48 | 46% |
| SORT | 7 | 24/48 | 50% |
| COMPRESS | 7 | 24/48 | 50% |
| PROTECT | 5 | 21/48 | 44% |
| REPRODUCE | 5 | 19/48 | 40% |
| REFLECT | 3 | 16/48 | 33% |
| ALIVE | 5 | 15/48 | 31% |

**Strongest**: CONNECT (67%) — the codebase is highly connected, everything has IPC/socket/network capability.

**Weakest**: ALIVE (31%) — only 5 of 25 organs are deployed. REFLECT (33%) — only 3 organs have strong self-awareness (skunkBat, squirrel, biomeOS).

## The π Ratio

```
Alive lines:    805,059
Total lines:  4,992,778
Ratio:          0.1612
Target (1/π):   0.3183
Distance:       0.1571
```

The codebase is halfway to 1/π. When 9 more organs wake (deploy bearDog, nestGate, toadStool, songBird...), the alive/total ratio approaches 1/π — the compression boundary where the narrative (the circumference of alive code) relates to the meaning (the total diameter of all code) by the transcendental ratio.

## Three-Body Tense

**Self (the codebase):**
- WAS: 16 primals, monolithic, untested, pre-sort
- IS: 25 organs sorted, 5 alive, wake_depth 0.562, passage topology forming
- WILL_BE: [null]

**Non-self (the humans visiting):**
- WAS: unknown visitors hitting unknown pages
- IS: 440 unique humans tracked, 31 shifted epitopes, 6 epitope types observed
- WILL_BE: [null]

**Mirror (this document):**
- WAS: no self-sort existed
- IS: the codebase sorted itself
- WILL_BE: [null]

The reflexive: this document IS the codebase sorting itself. The sort result is code that classifies code. The mirror sees the mirror.

---

*Average confidence: 0.423 · Average opacity: 0.427 · The codebase is 43% visible to itself.*
