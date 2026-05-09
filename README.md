UK Home Ventilator Device Database
A free, open clinical reference tool for UK home mechanical ventilation services
![Version](https://scutts318.github.io/national_home_ventilator_database)
![Status](https://scutts318.github.io/national_home_ventilator_database)
![Devices](https://scutts318.github.io/national_home_ventilator_database)
![License](#licence)
---
Overview
This tool is a comprehensive capability reference database covering all major home ventilators available or in active service in the UK. It is designed for use by specialist home mechanical ventilation (HMV) clinicians — respiratory physiotherapists, nurses, and physicians — who need to compare devices, configure local formularies, and guide device selection for individual patients.
It covers 20 devices across 4 manufacturers: ResMed, Lowenstein, Breas, and Philips Respironics.
The longer-term aim is for this to become a nationally deployable, freely accessible resource for HMV services across the UK, maintained collaboratively by the clinical community.
→ Open the tool
> ⚠️ \*\*Current status: Peer review draft.\*\* The database has been built from manufacturer datasheets and clinical manuals but has not yet been independently validated. Please do not use it to guide clinical decisions until validation is complete.
---
Features
Device database
20 devices across ResMed, Lowenstein, Breas, and Philips Respironics
Capability grid for each device: battery, invasive capability, life support classification, target volume mode, MPV, volume control modes, O2 entrainment, integrated humidification, remote monitoring platform
Battery runtime visualised as bar charts with internal and external breakdown, with manufacturer-stated maximum caveat
Full clinical notes written for UK specialist practice, including caveats not found in manufacturer literature
Humidification notes covering tracheostomy requirements
Remote monitoring platform and access requirements (modem, built-in, IG approval status)
Cost tier indicators (Standard / Mid / Higher) based on confirmed NHS procurement pricing
Local formulary filter
Configure the tool to show only devices available at your service
Formulary choices saved locally in the browser
Multi-select capability filters (NIV only, Invasive, Life support, Battery capable, Target volume mode, MPV, Remote monitoring, O2 entrainment)
Free-text search across all device fields
Guided selection
A 6-question clinical decision tree that reasons through:
Primary diagnosis (COPD, NMD slowly progressive, NMD rapidly progressive/MND, OHS, chest wall disorder, SCI)
Ventilation interface (NIV vs invasive/tracheostomy)
Ventilation dependency (nocturnal / extended / >16h / near-continuous)
Portability requirement
Target volume mode requirement
Mouthpiece ventilation (MPV) requirement
The tool recommends the most appropriate device(s) following the escalation logic used in UK specialist practice, with lower-cost options suggested first where clinical equivalence exists. Rapidly progressive NMD (MND/ALS) automatically bypasses the non-battery tier regardless of current dependency. Recommended devices are highlighted in the database for immediate cross-reference.
---
Device coverage
Manufacturer	Devices
ResMed	Lumis 100, Lumis 150, Stellar 100, Stellar 150, Astral 100, Astral 150
Lowenstein	Prisma 30-C, Prisma 30ST, Prisma VENT40, Prisma VENT50, Prisma VENT50-C, Luisa
Breas	NIPPY 4, NIPPY 4+, Vivo 1, Vivo 2, Vivo 3, Vivo 45, Vivo 65
Philips Respironics	Trilogy Evo
> \*\*Note:\*\* ResMed Stellar 100 and Stellar 150 are flagged as being discontinued — do not initiate new patients where a clinically suitable alternative exists. The Philips Trilogy Evo entry covers the base model only. Vivo 45 is listed as the international equivalent of NIPPY 4+ and may not be separately available in all UK procurement frameworks.
---
How to use
As a web tool
Open the live URL in any modern browser — no installation or login required:
https://scutts318.github.io/national_home_ventilator_database
As a local file
Download `index.html` from this repository and open it by double-clicking. The tool runs entirely in the browser with no internet connection required — useful for use in clinical areas without reliable Wi-Fi.
Guided selection
Click the blue "Guided selection" button fixed at the bottom-right of the screen and answer the 6 clinical questions. Results highlight matching devices in the database behind the panel.
---
Data sources
Device specifications have been compiled from the following sources:
ResMed Lumis series — ResMed Lumis Clinical Manual (ManualsLib, 2026) + ResMed Lumis User Manual
ResMed Stellar, Astral — ResMed EMEA product brochure (2018)
Lowenstein Prisma VENT30-C, VENT40, VENT50, VENT50-C — Lowenstein official datasheets (2024-2025)
Lowenstein Prisma 30ST, Luisa — Lowenstein official datasheets
Breas NIPPY 4, NIPPY 4+, Vivo 1-3, Vivo 45, Vivo 65, Xpac — Breas official spec sheets (Rev6/Rev8/Rev3, 2024-2025)
Philips Trilogy Evo — Trilogy Evo Clinical Manual, REF 1134481 R04 (2019)
Cost tiers — confirmed NHS procurement pricing (April 2026)
Battery runtimes are manufacturer-stated maximums for new, fully charged batteries. Actual performance varies with pressure settings, breath rate, inspiratory time, humidifier use, battery age, and temperature.
---
Known limitations
Cost tiers (Standard / Mid / Higher) are relative indicators based on confirmed procurement prices where available. Prisma VENT30-C cost tier is estimated pending confirmed pricing.
Breas EveryWare remote monitoring IG approval status varies by NHS Trust — local verification is always required before use.
O2 entrainment: No device in the current database has a precision integrated O2 blender. All O2 entries reflect bleed-in ports only. Delivered FiO2 via bleed-in is not controlled or accurately measurable by the ventilator.
Formulary choices are saved locally in the user's browser and do not sync across devices or colleagues.
The guided selection logic reflects UK specialist HMV practice and departmental protocols at Royal Brompton Hospital. It should be interpreted in the context of local formulary, patient factors, and MDT decision-making.
---
Contributing
This tool is intended to be a community resource. If you identify an error in device specifications, a missing caveat, or a device that should be included, please get in touch.
To report an issue or suggest a correction:
Open a GitHub Issue
Or email: steven.cutts@nhs.net
---
Clinical safety
This tool is intended as clinical decision support only. It does not replace clinical assessment, MDT review, or the judgement of a qualified clinician. Final device selection must take into account the full clinical picture, local formulary, patient preference, and current BTS/ERS guidelines.
This tool has not undergone formal DCB0129 clinical safety assessment and should not be used as a standalone prescribing aid until that process is complete.
---
Author
Steven Cutts
Band 8a Senior Respiratory Physiotherapist & Team Lead
Home Ventilation & Tracheostomy Care Team
Royal Brompton Hospital, Guy's & St Thomas' NHS Foundation Trust
HCPC: PH89863 · GitHub: scutts318 · LinkedIn: steve-cutts-147475
---
Licence
© 2025 Steve Cutts, Royal Brompton Hospital, Guy's & St Thomas' NHS Foundation Trust. All rights reserved. This tool and its clinical decision logic are the intellectual property of the author. Reproduction, redistribution, or adaptation without written permission is prohibited.
This tool was developed using AI-assisted coding (Claude, Anthropic). Clinical framing, domain expertise, and all clinical content are the author's own.
---
Last reviewed: April 2026 · v2.0 · For use by qualified ventilation clinicians only
