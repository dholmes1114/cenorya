# Cenorya

**An experimental wearable-sensing project from Clinically AI LLC.**

Led by Danielle Holmes, MSN, RN, CCRN, NI-BC, a registered nurse, nurse informaticist, and nursing PhD student.

Cenorya explores how wearable physiological signals could support the decision to take a blood-pressure measurement with a validated cuff. The intended first-use research focus is Black women during pregnancy and postpartum. The current evidence review examines adult wearable sensing broadly; maternal-health research is coordinated separately.

## What I am building

The first prototype will collect optical pulse, motion, and local-temperature signals, preserve their timing, and make missing or unreliable data visible. The immediate goal is to establish what the system can reliably collect before developing or evaluating a clinical prediction model.

The longer-term research question is whether earlier wearable signals can help identify when a cuff BP check would be useful. Answering it requires a defined forecasting interval, appropriate reference measurements, independent evaluation, and assessment of missed elevations and measurement burden. Existing research already investigates related prediction questions; Cenorya's novelty remains under evaluation.

## Current stage

- **Implemented in a separate development workspace:** a host-side USB stream checker and synthetic replay tools. This repository currently contains the public project overview and plans.
- **Planned:** sensor assembly, firmware, physical capture verification, and a companion display showing collection status and data quality.
- **In progress:** a scoping-review protocol and bounded comparison with existing research.
- **Not established:** BP prediction accuracy, useful prompting performance, equitable physiological signal reliability, or clinical benefit.

Synthetic software checks do not establish sensor performance or clinical validation. Cenorya currently provides no blood-pressure reading or validated clinical alert.

## Fellowship build goal

A reproducible bench demonstration that streams sensor data, preserves timestamps and missingness, and displays usable, missing, and unreliable intervals. Any simulated prompts will be explicitly labeled synthetic and will not direct clinical care.

See the [prototype roadmap](docs/ROADMAP.md), [research status](docs/RESEARCH_STATUS.md), and [demonstration plan](docs/DEMO_PLAN.md).

## Project boundaries

Cenorya is separate from Postpartum Monitor. This public repository is a project overview, not the private research archive or the complete engineering checkout. No human recordings, health information, credentials, or unpublished research records are included.

**Status updated October 26, 2026.** Cenorya is a provisional project name. No open-source license has been selected for this repository.
