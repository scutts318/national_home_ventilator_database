# UK Home Ventilator Device Database

**A free, open clinical reference tool for UK home mechanical ventilation services**

[![Version](https://img.shields.io/badge/version-1.9-blue)](https://scutts318.github.io/uk-home-ventilator-database)
[![Status](https://img.shields.io/badge/status-peer%20review-orange)](https://scutts318.github.io/uk-home-ventilator-database)
[![Devices](https://img.shields.io/badge/devices-19-green)](https://scutts318.github.io/uk-home-ventilator-database)
[![License](https://img.shields.io/badge/license-MIT-lightgrey)](#licence)

---

## Overview

This tool is a comprehensive capability reference database covering all major home ventilators available or in active service in the UK. It is designed for use by specialist home mechanical ventilation (HMV) clinicians â€” respiratory physiotherapists, nurses, and physicians â€” who need to compare devices, configure local formularies, and guide device selection for individual patients.

It covers **19 devices** across **4 manufacturers**: ResMed, LÃ¶wenstein, Breas, and Philips Respironics.

The longer-term aim is for this to become a nationally deployable, freely accessible resource for HMV services across the UK, maintained collaboratively by the clinical community.

**[â†’ Open the tool](https://scutts318.github.io/uk-home-ventilator-database)**

> âš ï¸ **Current status: Peer review draft.** The database has been built from manufacturer datasheets and clinical manuals but has not yet been independently validated. Please do not use it to guide clinical decisions until validation is complete.

---

## Features

### Device database
- 19 devices across ResMed, LÃ¶wenstein, Breas, and Philips Respironics
- Capability grid for each device: battery, invasive capability, life support classification, AVAPs/iVAPS, MPV, volume control modes, Oâ‚‚ compatibility, integrated humidification, remote monitoring platform
- Battery runtime visualised as bar charts with internal and external breakdown
- Full clinical notes written for UK specialist practice, including caveats not found in manufacturer literature
- Humidification notes covering tracheostomy requirements
- Remote monitoring platform and access requirements (modem, built-in, IG approval status)

### Local formulary filter
- Configure the tool to show only devices available at your service
- Off-formulary devices are hidden, so clinicians select from what is actually prescribable locally
- Multi-select capability filters (NIV only, Invasive, Life support, Battery, AVAPs/iVAPS, MPV, Remote monitoring, Oâ‚‚ compatible)
- Free-text search across all device fields

### Guided selection
A 6-question clinical decision tree that reasons through:
1. Primary diagnosis (COPD, NMD, OHS, chest wall disorder, SCI)
2. Ventilation interface (NIV vs invasive/tracheostomy)
3. Ventilation dependency (nocturnal / extended / >16h / near-continuous)
4. Portability requirement
5. AVAPs / iVAPS requirement
6. Mouthpiece ventilation (MPV) requirement

The tool recommends the most appropriate device(s) following the escalation logic used in UK specialist practice, with lower-cost options suggested first where clinical equivalence exists. Recommended devices are highlighted in the database for immediate cross-reference.

---

## Device coverage

| Manufacturer | Devices |
|---|---|
| ResMed | Lumis 100, Lumis 150, Stellar 100, Stellar 150, Astral 100, Astral 150 |
| LÃ¶wenstein | Prisma 30-C, Prisma 30ST, Prisma 40, Prisma 50, Prisma 50-C, Luisa |
| Breas | NIPPY 4, NIPPY 4+, Vivo 1, Vivo 2, Vivo 3, Vivo 45, Vivo 65 |
| Philips Respironics | Trilogy Evo |

> **Note:** ResMed Stellar series is flagged as being discontinued â€” do not initiate new patients where an alternative is clinically suitable. The Philips Trilogy Evo entry covers the base model only.

---

## How to use

### As a web tool
Open the live URL in any modern browser â€” no installation or login required:

**[https://scutts318.github.io/uk-home-ventilator-database](https://scutts318.github.io/uk-home-ventilator-database)**

### As a local file
Download `index.html` from this repository and open it by double-clicking. The tool runs entirely in the browser with no internet connection required â€” useful for use in clinical areas without reliable Wi-Fi.

### Guided selection
Click the blue **"Guided selection"** button fixed at the bottom-right of the screen and answer the 6 clinical questions. Results highlight matching devices in the database behind the panel.

---

## Data sources

Device specifications have been compiled from the following sources:

- ResMed Lumis, Stellar, Astral â€” ResMed EMEA product brochure (2018)
- LÃ¶wenstein Prisma VENT30-C, VENT40, VENT50, VENT50-C â€” LÃ¶wenstein official datasheets (2024â€“2025)
- LÃ¶wenstein Prisma 30ST, Luisa â€” LÃ¶wenstein official datasheets
- Breas NIPPY 4, NIPPY 4+, Vivo 1â€“3, Vivo 45, Vivo 65, Xpac â€” Breas official spec sheets (Rev6/Rev8/Rev3, 2024â€“2025)
- Philips Trilogy Evo â€” Trilogy Evo Clinical Manual, REF 1134481 R04 (2019)

Battery runtimes are manufacturer-stated maximums for new, fully charged batteries. Actual performance varies with settings, temperature, battery age, and usage profile.

---

## Known limitations

- **Cost tiers** (Standard / Mid / Higher) are relative indicators only. Exact NHS Supply Chain framework prices are not included.
- **EPAP/PEEP ranges and alarm lists** for the ResMed range are pending confirmation from full technical specification sheets â€” the brochure data used may not capture all sub-model variants.
- **Breas EveryWare** remote monitoring IG approval status varies by NHS Trust â€” local verification is always required before use for remote monitoring.
- **Oâ‚‚ fields:** No device in the current database has a precision integrated Oâ‚‚ blender. All Oâ‚‚ entries reflect bleed-in ports only. Delivered FiOâ‚‚ via bleed-in is not controlled or accurately measurable by the ventilator.
- The guided selection logic reflects UK specialist HMV practice and departmental protocols at Royal Brompton Hospital. It should be interpreted in the context of local formulary, patient factors, and MDT decision-making.

---

## Contributing

This tool is intended to be a community resource. If you identify an error in device specifications, a missing caveat, or a device that should be included, please get in touch.

**To report an issue or suggest a correction:**
- Open a [GitHub Issue](https://github.com/scutts318/uk-home-ventilator-database/issues)
- Or email: steven.cutts@nhs.net

Pull requests are welcome from clinicians with verified expertise in home mechanical ventilation.

---

## Clinical safety

This tool is intended as **clinical decision support only**. It does not replace clinical assessment, MDT review, or the judgement of a qualified clinician. Final device selection must take into account the full clinical picture, local formulary, patient preference, and current BTS/ERS guidelines.

This tool has not undergone formal DCB0129 clinical safety assessment and should not be used as a standalone prescribing aid until that process is complete.

---

## Author

**Steven Cutts**
Band 8a Senior Respiratory Physiotherapist & Team Lead
Home Ventilation & Tracheostomy Care Team
Royal Brompton Hospital, Guy's & St Thomas' NHS Foundation Trust

HCPC: PH89863 Â· GitHub: [scutts318](https://github.com/scutts318) Â· LinkedIn: [steve-cutts-147475](https://www.linkedin.com/in/steve-cutts-147475)

---

## Licence

MIT Licence â€” free to use, adapt, and share with attribution.

This tool was developed using AI-assisted coding (Claude, Anthropic). Clinical framing, domain expertise, and all clinical content are the author's own.

---

*Last reviewed: April 2026 Â· v1.9 Â· For use by qualified ventilation clinicians only*

