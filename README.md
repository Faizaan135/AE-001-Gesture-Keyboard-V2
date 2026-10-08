# AE-001 — Gesture Keyboard V2

**ABBAS Engineering · Project AE-001**  
**Project phase:** Requirements / Feasibility  
**Status:** Active engineering redesign; no validated V2 implementation yet.

## Purpose
Redesign a previous wearable gesture-controlled keyboard prototype into a reliable, demonstrable input device with a validated use case. This repository is intended to hold **source-controlled engineering artefacts** rather than raw personal notes or final business records.

## Stage-gate workflow
1. Define and rank application-specific use cases.
2. Define measurable performance, usability, power and cost requirements.
3. Compare architecture options before selecting sensors and the host interface.
4. Design, implement and verify candidate subsystems.
5. Test against requirements with captured raw evidence and known test conditions.
6. Iterate, document and prepare a portfolio-quality case study.

## Project status (2026-10-08)
- [ ] Use cases benchmarked
- [ ] V2 requirements baselined
- [ ] Input architecture selected
- [ ] Prototype implemented
- [ ] Bench and user tests completed
- [ ] Validated results published

## Repository structure
```
/docs/                 public GitHub Pages project overview (non-sensitive)
/requirements/         version-controlled requirements templates
/research/             trade-offs and decision records
/hardware/             schematic/PCB source files once created
/firmware/             embedded implementation once created
/verification/         verification plans and automated tests
/scripts/              analysis and development utilities
```

## Source-of-truth rules
- **GitHub:** code, design source, simulation, automation and reviewed technical documentation.
- **Notion:** working journal, linked tasks and engineering decision tracking.
- **Google Drive:** formal controlled PDFs, BOM sheets, photographs, raw measurements and business records.

## Portfolio
[ABBAS Engineering portfolio](https://Faizaan135.github.io/) — parent portfolio website. This project repository is the public engineering record, while formal files remain in Drive and project tracking remains in Notion.

## GitHub Pages
The `docs/` folder includes a static project overview page. To publish the page, configure this repository at **Settings → Pages → Deploy from a branch → main → /docs → Save**.

> Important: A GitHub Pages website is **publicly accessible**, even on plans that permit private-source Pages. If you are using GitHub Free, the repository must be public for Pages. Only publish non-sensitive material.

## Licence
No open-source licence has been granted. Decide on a licence later before adding one.
