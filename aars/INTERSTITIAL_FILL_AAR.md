# SWEEP/SORT WAVE 176B: INTERSTITIAL FILL + FULL CLASSIFICATION

## Summary
Filled interstitial connections between tuebor braids and detroit graph.
Achieved 100% classification coverage (341/341 nodes sorted).

## Graph Evolution

| Metric | Before | After | Delta |
|--------|--------|-------|-------|
| Nodes | 329 | 341 | +12 |
| Edges | 773 | 926 | +153 |
| Avg degree | 4.7 | 5.4 | +0.7 |
| Isolated (deg≤1) | 66 | 16 | −50 |
| Sort coverage | 90.0% | 100.0% | +10% |
| Other (unsorted) | 34 | 0 | −34 |

## New Nodes Added (12)
- **From tuebor braids (11)**: america_pac, att_inc, cispa, clutch_justice, tim_dunn,
  glcf, nrcc, mike_rogers, schwarzman, slf, state_bar_upl
- **From braid evidence (1)**: kenneth_griffin (Citadel CEO)

## Interstitial Edges (153 new)
1. **Braid-to-graph connections** (24): political donations, payment/client,
   legislation, investigation, lobbying, jurisdiction, governance
2. **Institutional pipelines** (69): JTC/AGC staff → MI Supreme Court,
   UPL staff → SBM, courts → JTC, universities → MDE
3. **Authorization chains** (17): charter schools → DPSCD
4. **Braid page evidence** (7): Griffin donations, AT&T↔Rogers,
   NRCC amplification, AFP→Rogers Super PAC
5. **Reduction passes** (36): geography→jurisdiction, advocacy,
   media, criticism, contractor, political connections

## Classification Sort Passes
| Pass | Method | Entities | Coverage |
|------|--------|----------|----------|
| 1 | Phase 1 hardcoded | ~230 | 67.6% |
| 2 | Phase 2 rules | ~269 | 79.1% |
| 3 | Phase 3 heuristics | ~306 | 90.0% |
| 4 | Braid interstitial | ~318 | 93.2% |
| 5 | Full resolution | 341 | 100.0% |

## Final Sort Distribution
| Class | Count | % | Description |
|-------|-------|---|-------------|
| self | 120 | 35.2% | The system being documented |
| partial | 114 | 33.4% | Entangled with system |
| null | 100 | 29.3% | External routing/funding |
| non-self | 7 | 2.1% | Corruption nexus |

## Compressed Files
- **braid-tracker.js**: 356→298 lines (−16%)
  - buildWidget(166) → widgetCSS() + widgetHTML() + widgetBind() + dispatcher(18)
  - EPITOPE_MAP: 30→91 keywords (3x coverage)

## Hub Nodes (deg > 20)
1. Banks (131) — center of gravity
2. MI Supreme Court (83) — institutional apex
3. MDE (46) — education pipeline
4. Purpose Charter (39) — authorization subject
5. JTC (38) — enforcement arm
6. MacDowell (37) — authorization subject
7. DPSCD (36) — authorizer
8. AGC (35) — enforcement arm
9. 3rd Circuit (26) — judicial
10. SBM (23) — regulatory
11. Beasley (21) — connected actor

## Files Modified
- graph.json (golgi × 2 paths)
- classification.json (golgi × 3 paths)
- braid-tracker.js (golgi + local HUD repo)
