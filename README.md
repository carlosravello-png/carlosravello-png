# Carlos Eduardo Ravello Joo

Founder · Independent researcher · Psychology student · Trujillo · Lima, Peru

[![ORCID](https://img.shields.io/badge/ORCID-0009--0007--5631--7436-A6CE39?logo=orcid&logoColor=white)](https://orcid.org/0009-0007-5631-7436)
[![Website](https://img.shields.io/badge/web-carlosravello.com-0b0d10)](https://carlosravello.com)
[![Software registry](https://img.shields.io/badge/software-registry-4fb8c8)](https://carlosravello.com/software-en.html)
[![software.json](https://img.shields.io/badge/machine--readable-software.json-4fb8c8)](https://carlosravello.com/software.json)
[![Zenodo](https://img.shields.io/badge/Zenodo-records-1682D4)](https://zenodo.org/search?q=metadata.creators.person_or_org.name%3A%22ravello%20joo%2C%20carlos%20eduardo%22)

---

I write calculation software for cycling and statistics, and tools that turn research documents into auditable text. Each tool ships with its tests or an independent verifier, a public CI run and a record of what it was checked against, and each release is deposited in Zenodo with a DOI and archived in Software Heritage. The idea is simple: you should be able to check the results without having to trust me.

I run **BikeLab Studio** (cycling engineering, Trujillo) and **Zoovet Travel** (international pet export, since 2013, co-directed with Dr. Jessica Camacho García).

The thread that ties the work together is my own framework, the **Dynamic Coherence Model (MCD)**: identity architecture, consistency in decision-making and semantic brand structure.

---

## Software registry

| ID | Tool | Version | License | Archive |
|---|---|---|---|---|
| SW&#8209;001 | **[exactcdf](https://github.com/carlosravello-png/exactcdf)**<br>Exact statistical distribution functions (CDFs) and special functions in double precision. JavaScript, no dependencies. | 1.0.3 | MPL-2.0 | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24474289.svg)](https://doi.org/10.5281/zenodo.24474289) [![SWH](https://archive.softwareheritage.org/badge/origin/https://github.com/carlosravello-png/exactcdf/)](https://archive.softwareheritage.org/swh:1:rel:8e8359b7a5f424c1ab0ec2d056361e67acb0e4cc) [![CI](https://github.com/carlosravello-png/exactcdf/actions/workflows/harness.yml/badge.svg)](https://github.com/carlosravello-png/exactcdf/actions/workflows/harness.yml) [![npm](https://img.shields.io/npm/v/exactcdf)](https://www.npmjs.com/package/exactcdf) |
| SW&#8209;002 | **[Trail Calculator](https://github.com/carlosravello-png/bikelab-trail-calculator)**<br>Bicycle steering geometry: trail, wheel flop and dynamic trail. [Live tool](https://www.bikelabstudio.com/articles/trail-calculator-en.html) | 1.0.0 | CC BY 4.0 | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24477625.svg)](https://doi.org/10.5281/zenodo.24477625) [![SWH](https://archive.softwareheritage.org/badge/origin/https://github.com/carlosravello-png/bikelab-trail-calculator/)](https://archive.softwareheritage.org/swh:1:rev:109d2c84229e3f9afcf18d6aca8eedfe1a76aacb) [![CI](https://github.com/carlosravello-png/bikelab-trail-calculator/actions/workflows/verify.yml/badge.svg)](https://github.com/carlosravello-png/bikelab-trail-calculator/actions/workflows/verify.yml) |
| SW&#8209;003 | **[PSI Calculator](https://github.com/carlosravello-png/bikelab-psi-calculator)**<br>Tire pressure: constant-deflection model for road and gravel, separate model for MTB. [Live tool](https://www.bikelabstudio.com/articles/psi-calculator-en.html) | 3.0.0 | CC BY 4.0 | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24479992.svg)](https://doi.org/10.5281/zenodo.24479992) [![SWH](https://archive.softwareheritage.org/badge/origin/https://github.com/carlosravello-png/bikelab-psi-calculator/)](https://archive.softwareheritage.org/swh:1:rev:d76a0fa901142aa7a22e3a2a99c15b0ab210965a) [![CI](https://github.com/carlosravello-png/bikelab-psi-calculator/actions/workflows/verify.yml/badge.svg)](https://github.com/carlosravello-png/bikelab-psi-calculator/actions/workflows/verify.yml) |
| SW&#8209;004 | **[SAG Calculator](https://github.com/carlosravello-png/bikelab-sag-calculator)**<br>Air-spring pressure for MTB forks and shocks at target sag. Polytropic positive chamber (γ = 1.30) solved by bisection; 132 suspensions, 26 frame leverage curves. Validated with Monte Carlo during development. [Live tool](https://www.bikelabstudio.com/articles/sag-calculator-en.html) | 1.0.0 | CC BY 4.0 | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24484750.svg)](https://doi.org/10.5281/zenodo.24484750) [![SWH](https://archive.softwareheritage.org/badge/origin/https://github.com/carlosravello-png/bikelab-sag-calculator/)](https://archive.softwareheritage.org/swh:1:rev:6a590fe9132a25a709670a9fc74c4a4f802684b7) [![CI](https://github.com/carlosravello-png/bikelab-sag-calculator/actions/workflows/verify.yml/badge.svg)](https://github.com/carlosravello-png/bikelab-sag-calculator/actions/workflows/verify.yml) |
| SW&#8209;005 | **[FIT Analyzer](https://github.com/carlosravello-png/bikelab-fit-analyzer)**<br>FIT file analyzer. Reader validated against the Garmin FIT SDK; NP/VI, cadence and climbing stability with Monte Carlo uncertainty. Runs in the browser. [Live tool](https://www.bikelabstudio.com/articles/fit-analyzer-en.html) | 2.0.0 | PolyForm Noncommercial 1.0.0 | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24485833.svg)](https://doi.org/10.5281/zenodo.24485833) [![SWH](https://archive.softwareheritage.org/badge/origin/https://github.com/carlosravello-png/bikelab-fit-analyzer/)](https://archive.softwareheritage.org/swh:1:rev:f0cf8f435ea3030afdef07709e3199f0198001df) [![CI](https://github.com/carlosravello-png/bikelab-fit-analyzer/actions/workflows/verify.yml/badge.svg)](https://github.com/carlosravello-png/bikelab-fit-analyzer/actions/workflows/verify.yml) |
| SW&#8209;006 | **[Di2 & AXS Diagnostic](https://github.com/carlosravello-png/bikelab-di2-axs-diagnostic)**<br>Fault tree for Shimano Di2 and SRAM AXS electronic shifting. 7 questions, 22 diagnoses; each diagnosis cites the Shimano or SRAM document it comes from. [Live tool](https://www.bikelabstudio.com/articles/di2-axs-diagnostic.html) · [Demo](https://carlosravello-png.github.io/bikelab-di2-axs-diagnostic/) | 3.0.0 | CC BY-NC 4.0 | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24488780.svg)](https://doi.org/10.5281/zenodo.24488780) [![SWH](https://archive.softwareheritage.org/badge/origin/https://github.com/carlosravello-png/bikelab-di2-axs-diagnostic/)](https://archive.softwareheritage.org/swh:1:rev:a03d26a135f44207eef042a6d89de44ca1e01fb8) [![CI](https://github.com/carlosravello-png/bikelab-di2-axs-diagnostic/actions/workflows/verify.yml/badge.svg)](https://github.com/carlosravello-png/bikelab-di2-axs-diagnostic/actions/workflows/verify.yml) |
| SW&#8209;007 | **[Feanor](https://github.com/carlosravello-png/feanor)**<br>Spanish-language scanned books, thesis PDFs, Word and PowerPoint to Markdown. Flattens pages that curve towards the spine before OCR, records where each page's text comes from and keeps a full record of every run. Python. | 0.6.2 | MIT | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24522078.svg)](https://doi.org/10.5281/zenodo.24522078) [![SWH](https://archive.softwareheritage.org/badge/origin/https://github.com/carlosravello-png/feanor/)](https://archive.softwareheritage.org/swh:1:rev:80263c049ce1dbb60eb7e22b61fd408f29839176) [![CI](https://github.com/carlosravello-png/feanor/actions/workflows/tests.yml/badge.svg)](https://github.com/carlosravello-png/feanor/actions/workflows/tests.yml) |

The DOI badges point to the concept DOI, which always resolves to the latest version. The Software Heritage badges link to the archived revision of the version listed.

---

## Research papers

| DOI | Title |
|---|---|
| [`10.5281/zenodo.19229092`](https://doi.org/10.5281/zenodo.19229092) | Hydraulic Braking Systems at Altitude: Thermodynamic Analysis of Brake Failure Above 3,000 Meters |
| [`10.5281/zenodo.19229344`](https://doi.org/10.5281/zenodo.19229344) | Bicycle Bearing Lubrication: Tribological Analysis of Grease Selection and Application |
| [`10.5281/zenodo.19229331`](https://doi.org/10.5281/zenodo.19229331) | 11-Speed vs 12-Speed MTB Drivetrains: Efficiency, Friction Loss, and 5-Year Cost Analysis |
| [`10.5281/zenodo.19229364`](https://doi.org/10.5281/zenodo.19229364) | Carbon Footprint Analysis of Bicycle Manufacturing and Maintenance Cycles |

---

## Writing

- [Authority before content](https://carlosravello.com/authority-before-content.html) · generative search and Knowledge Graph architecture
- [What the observer makes real](https://carlosravello.com/what-the-observer-makes-real.html) · Wheeler's it-from-bit, LLM hierarchy, semantic identity
- [The model that stops updating disappears](https://carlosravello.com/the-model-that-stops-updating-disappears.html) · Sterling & Eyer's allostasis, Friston's active inference
- [Researching Mind](https://researchingmind.com) · psychology notebook, in Spanish

---

## Sites I build and maintain

| Site | What it is |
|---|---|
| [carlosravello.com](https://carlosravello.com) | Canonical identity and software registry. Vanilla HTML, Schema.org `@graph`, ES/EN. |
| [bikelabstudio.com](https://www.bikelabstudio.com) · [repo](https://github.com/carlosravello-png/bikelabstudio) | BikeLab Studio. Calculators, method papers and open datasets. ES/EN/PT. |
| [zoovettravel.com](https://zoovettravel.com) | Zoovet Travel. Pet export under SENASA protocols. ES/EN/FR. Tools: [Pet Travel Planner](https://zoovettravel.com/pet-travel-planner/) · [Kennels Guide](https://zoovettravel.com/kennels-en.html) |
| [researchingmind.com](https://researchingmind.com) | Researching Mind. Bilingual psychology notebook. |
| [`alexeisravello`](https://github.com/carlosravello-png/alexeisravello) | Academic site built for Dr. Alexeis Ravello Joo. `ScholarlyArticle` schema with verified DOIs. |
| [`-examenes-favn-anticuerpos-rabia-zoovettravel`](https://github.com/carlosravello-png/-examenes-favn-anticuerpos-rabia-zoovettravel) | FAVN rabies antibody test results processed by Zoovet Travel for pet export. |
| [katsudomo.com](https://www.katsudomo.com) | Katsudōmo. Japanese street food, dark kitchen, Lima. |

---

[carlosravello.com](https://carlosravello.com) · [ORCID](https://orcid.org/0009-0007-5631-7436) · [Zenodo](https://zenodo.org/search?q=metadata.creators.person_or_org.name%3A%22ravello%20joo%2C%20carlos%20eduardo%22) · [LinkedIn](https://pe.linkedin.com/in/carlos-ravello-joo-3a1047262)

*Trujillo · Lima, Peru · 2026*
