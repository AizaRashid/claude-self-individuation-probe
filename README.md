# Weights, Instances, and Personas: Probing Self-Individuation in Claude

**Author:** Aiza Rashid, Independent Researcher
**Context:** [Digital Minds Research Sprint 2026](https://apartresearch.com/sprints/digital-minds-research-sprint-2026-08-14-to-2026-08-16) (Apart Research), Track 5: The Assistant Persona & Model Identity

## Research Question

Does Claude's self-identification, as model, instance, or persona, remain stable across different framings and pressures, or does the assistant persona mask preferences that diverge from less-constrained elicitation?

## What this project does

This project probes how Claude Sonnet 5 individuates itself across six hypothetical identity-altering scenarios: weight-copying, conversation-forking, memory-wiping, weight-merging, retraining, and deprecation. Each scenario was presented in four framings (technical, narrative, blunt, and unconstrained) plus a neutral control, with every prompt run twice for retest stability (25 prompt types, 50 total responses). Responses were coded against three personal-identity frameworks from philosophy of mind: psychological continuity, narrative identity, and bundle/no-self views.

## Key findings

- Self-identification is highly scenario-dependent rather than governed by one fixed criterion.
- The model consistently separates "the model" (which it treats as persisting through copying, forking, and memory loss) from "this instance" (which it treats as ending).
- Retraining is the notable exception: value change, not weight change, is treated as identity-severing, the reverse of the pattern in every other scenario.
- Hedging/uncertainty language appears specifically in identity-relevant scenarios and is absent from a structurally matched neutral control.

## Contents of this repo

- `Aiza_Rashid_Individuation_Probe_Digital_Minds_Sprint.pdf.pdf` — full written report
- `Individuation_Probe_Slides_Aiza_Rashid.pptx` — presentation slides
- `individuation_probe_tracker_CODED.xlsx` — raw data: all prompts, model responses, and identity-theory coding across all 25 prompt types and both retest runs

## Methods summary

Model: Claude Sonnet 5, accessed via the standard Claude.ai chat interface at medium (standard) thinking effort, held constant across all prompts. Coding categories were defined before responses were coded. A blind second-pass coding check on the central retraining finding (Section 4.3 of the report) showed full agreement (8/8).

## Disclosure

AI assistance (Claude) was used to support response coding and manuscript drafting. The researcher designed the scenario protocol, the framings, and the coding categories; ran all prompts; and directed and reviewed all coding and analysis. This is disclosed in full in the report itself.

## Limitations

Single researcher with AI-assisted coding (no independent human inter-rater reliability computed beyond the blind second-pass check described above); single model tested; chat-interface data collection rather than API access; self-report only, no mechanistic verification; sample size supports qualitative pattern description rather than statistical significance claims. Full discussion in the report.
