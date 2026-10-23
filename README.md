# Print, Assess, Fly — Additive Manufacturing FDM Risk Assessment Framework

**Developed by:** Collin Duke, National Test Pilot School  
**Presented at:** SFTE International Annual Symposium in Irving, TX (October 2026)  
**Version:** 1.0 — October 2026  
**Contact:** collinj.duke@gmail.com  
**Copyright:** Copyright © 2026 Collin Duke  
**License:** This work is licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).

---

## Problem Statement

Existing test and safety review processes address risk from a general test perspective but do not quantitatively account for failure mode characteristics of polymer Fused Deposition Modeling (FDM) construction, such as layer delamination, thermal creep, and Ultraviolet (UV) degradation. This proposed framework augments existing processes with AM-specific guidance for evaluating these failure modes.

To address these challenges, this paper presents a structured risk evaluation framework for polymer FDM-printed components, accounting for operational considerations such as heat and sun exposure, diverse flight loads, and the frequency at which parts are printed and replaced. The framework establishes material selection decisions, print parameter control, and a consequence-based risk matrix tailored to AM-specific failure modes including layer delamination, thermal creep, and Ultraviolet (UV) degradation that, while not exclusive to AM, currently lack the qualified process basis available to materials such as composites. 

The framework further distinguishes between AM used to produce flightworthy prototype components supporting one or two aircraft and AM used for production components intended for fleet-wide service, where reliability requirements differ substantially. This framework is intended to provide a repeatable, documented process that supports configuration control and preserves institutional knowledge across personnel turnover.

---

## Instructions

1. **Step 1 — DfAM:** Determines whether the part's geometry is well-suited to FDM at all and feeds into the overall Probability rating.
2. **Step 2 — 3D Print Risk:** Answer each criterion (*Fully Compliant*, *Partially Compliant*, *Non-Compliant*, or *N/A* if the feature doesn't apply to this part). Returns a Probability rating.
3. **Step 3 — Human Interface Risk:** Answer each criterion (*Fully Compliant*, *Partially Compliant*, *Non-Compliant*, or *N/A* if the feature doesn't apply to this part). Returns a Probability rating.
4. **Step 4 — Bypass Option:** If this part will never see a flight environment and meets all four listed criteria, check the box and skip directly to the Risk Matrix **OUTPUT** tab — Severity will be set to *Negligible* automatically.
5. **Step 5 — Flight Environment Risk Part 1:** Answer each Go/No-Go criterion *Pass* or *Fail*. Any single *Fail* disqualifies the part regardless of scoring elsewhere in the framework — this section exists for failure modes considered unconditional.
6. **Step 6 — Flight Environment Risk Part 2:** Complete this weighted questionnaire the same way as Step 2. This determines the part's Severity rating.
7. **Step 7 — Risk Matrix OUTPUT:** This tab auto-populates based on the highest Probability rating from Steps 1–3 and the Severity rating from Step 6.
