# Cenorya

**An experimental wearable-sensing project from Clinically AI LLC.**

Led by Danielle Holmes, MSN, RN, CCRN, NI-BC, a registered nurse, nurse informaticist, and nursing PhD student.

Cenorya's long-term goal is a wearable that can measure blood pressure without a cuff. It starts with a narrower question: how wearable physiological signals could support the decision to take a blood-pressure measurement with a validated cuff. The intended first-use research focus is Black women during pregnancy and postpartum. The current evidence review examines adult wearable sensing broadly; maternal-health research is coordinated separately.

> **Not a medical device and not medical advice.** Cenorya does not currently measure blood pressure or detect any condition. If you are pregnant or postpartum and concerned about your blood pressure or symptoms, take a reading with a validated cuff and contact your clinician. For severe headache, vision changes, chest pain or trouble breathing, seek emergency care.

## What I am building

The first prototype will collect optical pulse, motion, and local-temperature signals, preserve their timing, and make missing or unreliable data visible. The immediate goal is to establish what the system can reliably collect before developing or evaluating a clinical prediction model.

The next research question is whether earlier wearable signals can help identify when a cuff BP check would be useful. Answering it requires a defined forecasting interval, appropriate reference measurements, independent evaluation, and assessment of missed elevations and measurement burden. Existing research already investigates related prediction questions; Cenorya's novelty remains under evaluation.

The long-term goal is cuffless blood-pressure measurement. In the published evidence reviewed so far, no cuffless method has been validated in women after birth, and none has reported accuracy by measured skin tone. Any future cuffless reading would therefore be checked against a validated, correctly sized arm cuff, and its accuracy reported by measured skin tone, arm size and postpartum stage, before any claim is made.

## Current stage

- **Implemented in a separate development workspace:** a host-side USB stream checker, synthetic replay tools, and first bench firmware for the planned sensors. The firmware passes software tests on synthetic data only; it has not yet run on hardware. This repository currently contains the public project overview and plans.
- **In progress:** bench sensor assembly and first hardware bring-up (week of October 27, 2026), and a structured review of existing research.
- **Planned:** physical capture verification and a companion display showing collection status and data quality.
- **Not established:** BP prediction accuracy, useful prompting performance, equitable physiological signal reliability, or clinical benefit.

Synthetic software checks do not establish sensor performance or clinical validation. Cenorya currently provides no blood-pressure reading or validated clinical alert.

## Fellowship build goal

A reproducible bench demonstration that streams sensor data, preserves timestamps and missingness, and displays usable, missing, and unreliable intervals. Any simulated prompts will be explicitly labeled synthetic and will not direct clinical care.

See the [prototype roadmap](docs/ROADMAP.md), [research status](docs/RESEARCH_STATUS.md), and [demonstration plan](docs/DEMO_PLAN.md).

## Project boundaries

Cenorya is separate from Postpartum Monitor. This public repository is a project overview, not the private research archive or the complete engineering checkout. No human recordings, health information, credentials, or unpublished research records are included.

## How this work is done

Danielle Holmes is the principal investigator and final decision-maker. AI assistants (Claude by Anthropic and ChatGPT by OpenAI) help with drafting, literature checks and software. Their contributions are reviewed by Danielle, and AI-assisted literature judgments are not treated as independent human review.

## Citing and reuse

To reference this project, use the citation details in [CITATION.cff](CITATION.cff) (GitHub's "Cite this repository" button reads it). The contents are copyrighted and all rights are reserved; see [LICENSE](LICENSE). No open-source license has been selected yet. Contact Danielle through her [GitHub profile](https://github.com/dholmes1114) about reuse.

**Status updated October 26, 2026.** Cenorya is a provisional project name.
