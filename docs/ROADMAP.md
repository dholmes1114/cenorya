# Prototype roadmap

These are proposed milestones, not completed hardware or clinical results. Final scope depends on component availability and the research findings.

## 1 Verify acquisition

- Confirm the actual hardware bill of materials and electrical compatibility.
- Adopt a documented firmware-to-host packet format with sensor identity, units, sequence information and device timestamps.
- Capture a physical sensor stream and preserve exact raw records and separate host receipt times.
- Examine resets, interruptions, malformed records, sequence gaps and uncertain loss.

The current bench plan names a Feather nRF52840 Express, MAX30101 optical sensor, LIS3DH accelerometer and TMP117 temperature sensor. This is a proposed configuration, not a compatibility certification or a claim that assembly is complete.

## 2 Examine signal quality

- Define the meaning and provenance of each quality flag.
- Distinguish transport errors from physiological signal artifacts.
- Show intervals that cannot support interpretation instead of hiding them or assigning reassuring values.
- Document controlled bench challenges and their limitations.

## 3 Demonstrate the workflow

- Present collection status and quality in a companion display.
- Reproduce known failure scenarios with synthetic fixtures.
- Label synthetic signals and simulated prompts on screen.
- Package instructions, assumptions and observed limitations.

## 4 Prepare later research

- Resolve overlap with existing wearable BP prediction work.
- Specify input cutoff, reference time and intended lead time.
- Establish reference sampling that can identify unprompted elevations.
- Plan independent evaluation and appropriate subgroup/coverage analysis.

Human studies, clinical thresholds and predictive deployment require separate study design and governance. They are not promised as fellowship deliverables.
