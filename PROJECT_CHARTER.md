# Project Charter — Vie

## Contributors
- **Project Lead:** Asher Wheatle, Dean Chou
- **Primary Contributors:** Asher Wheatle, Dean Chou, Bakari Kerr, Krish Saluja, Raul Valle
- **Secondary Contributors:** @sauucy (Discord)

## Definition
- **Research / Product Question:** Can we create a real time system that perceives the dynamic entities in a scene?
- **Claim / Hypothesis:** We can create a real time machine learning system that perceives dynamic and static objects in a scene.
- **Novelty:** Implement human cognitive perception to emulate human eyesight (with a path to Meta glasses integration).
- **Target Venue / Deliverable Context:** IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
- **Expected Artifacts:**
  - Paper
  - Code repository
  - Working demo

## Delegation (initial)
| Workstream | Owner(s) | Output | Due |
|---|---|---|---|
| Research SOTA | Raul Valle | Paper summary + key baselines | TBD |
| Data Engineering (SAM v3 on Hipergator + data transfer) | Asher Wheatle, Dean Chou | Reproducible data pipeline | TBD |
| Machine Learning Design (model research + implementation) | Bakari Kerr, Taher | Initial model design + training code | TBD |
| Deployable Demo (web or physical system) | Raul Valle, Taher, Bakari Kerr, Asher Wheatle | Demo prototype | TBD |

## Funding Use
- Budget: TBD
- What we will buy: Decent-quality camera/webcam
- Other expenses: Publication fees (if applicable)
- Approval process: TBD

## Timeline
- **Weekly meeting time:** Fridays at 6 PM EST
- **Paper draft date (if relevant):** 2026-04-27
- **Paper deadline (per updates sheet):** 2027-01-16

### Primary Milestones
| Milestone | Description | Date |
|---|---|---|
| M1 | Implement SAM v3 on toy dataset + find larger datasets | 2026-01-31 |
| M2 | Create annotations + initial model design | 2026-03-16 |
| M3 | Trained model + demo | 2026-04-19 |
| M4 | TBD | TBD |

## Definition of Done (DoD)
A milestone is “done” when:
- [ ] Repro steps exist (commands, versions, data pointers)
- [ ] Metrics are reported + comparable to baseline
- [ ] Artifacts are committed (code/docs) and discoverable
- [ ] A demo (or evaluation script) exists
- [ ] Open issues are filed for follow-up work
