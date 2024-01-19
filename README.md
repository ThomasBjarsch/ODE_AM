# Repository Overview: ODE_AM Ontologies

---

## Introduction

This repository hosts ontologies developed for the ODE_AM project ([ODE_AM](https://www.materialdigital.de/project/13)), focusing on semantic modeling of the additive manufacturing process and management of process planning parameters as well as material data. It encompasses three manufacturing processes: Powder Bed Fusion (PBF) Laser Beam Metal at Fraunhofer IGCV, Direct Energy Deposition (DED) at TU Ilmenau, and Composite Extrusion Modeling at MFPA Weimar. These ontologies form a structured framework for data acquisition strategies in these manufacturing domains and are integrated into various workflows for data import and visualization, identifying correlations between process parameters and material characteristics.

![grafik](https://github.com/ThomasBjarsch/ODE_AM/assets/115726934/f8c4b1bc-921d-491e-a132-919ac1bf42b0)

Method for ontology publication as taken from Platform Material Digital: [Material Digital Ontology Publication Template](https://github.com/materialdigital/ontology_publication_template)

---

## Authors

- **Manufacturing Application Ontology:**
  - Thomas Bjarsch (Fraunhofer IGCV)

- **Additive Manufacturing Application Ontology:**
  - Thomas Bjarsch (Fraunhofer IGCV)

- **Powder Bed Fusion Application Ontology:**
  - Thomas Bjarsch (Fraunhofer IGCV)

- **Wire Arc Additive Manufacturing Ontology:**
  - Jan Reimann (TU Ilmenau), Mohamed Kamal (IDAC, TUHH)

- **Composite Extrusion Modeling Ontology:**
  - Heiko Beinersdorf (MFPA Weimar), Mohamed Kamal (IDAC, TUHH)

- **Mechanical Testing Ontology:**
  - Mohamed Kamal (IDAC, TUHH)

---

## Usage in Project

The ontologies are utilized in conjunction with a developed workflow and web application. They serve as a backbone for mapping various files and formats along the process chain. Triples are stored in a triplestore, and raw data are uploaded to the cloud for backup. 

Exemplary the general workflow for powder bed fusion laser beam metal using the web application is illustrated here:

![grafik](https://github.com/ThomasBjarsch/ODE_AM/assets/115726934/dee9a109-c188-4091-85e8-a006347a2267)

![grafik](https://github.com/ThomasBjarsch/ODE_AM/assets/115726934/ad1ca1a6-61fd-439a-bde5-d1463eb45657)

---

## Ontology Descriptions

### Manufacturing Application Ontology

This ontology covers a wide range of classes relevant to the manufacturing domain, including 'Machine', 'STL-File', and 'Steel', aiming to standardize and integrate various manufacturing concepts.

### Additive Manufacturing Application Ontology

Expanding on the Manufacturing Application Ontology, this ontology focuses on additive manufacturing, encompassing parameters like 'Build Platform Temperature' and 'Layer Height'.

### Powder Bed Fusion Application Ontology

Specific to Powder Bed Fusion, this ontology includes classes for parameters and specifications unique to this process, particularly for the M290 machine by Electro Optical Systems GmbH.

### Wire Arc Additive Manufacturing Ontology
Specific to wire arc additive manufacturing, this ontology includes classes for parameters and specifications unique to this process.

### Composite Extrusion Modeling Ontology
Specific to composite extrusion modeling process, this ontology includes classes for parameters and specifications unique to this process.

---

## Class Generation Strategy

Class development is driven by project-specific needs, utilizing pre-existing classes from the Basic Formal Ontology (BFO) and Common Core Ontologies (CCO) for consistency and interoperability.

---

## Reused Ontologies

### Overview of Ontology Import-Structure
![grafik](https://github.com/ThomasBjarsch/ODE_AM/assets/115726934/edfb379d-7503-4a8f-958d-dc4be9809c51)

### Top-Level Ontology

BFO is used as the top-level ontology, providing a foundational conceptual framework.

### Mid-Level Ontologies

CCO are employed at the mid-level, offering detailed, domain-specific categorization.

---

## Publications

- PBF-LB/M data management using the developed web app was presented at FEMS EUROMAT 2023 by Thomas Bjarsch: _"Ontology-based material data management in metal additive manufacturing domain"_. The written conference paper is in progress.
- A publication for a special issue in "Advanced Engineering Materials" is ongoing.

---

## Methodological Approach

Class generation is based on expert interviews on factors influencing material properties, ensuring relevance and integration of BFO and CCO classes for coherence. A detailed discussion of the methodology is available here: [Methodology Video](https://www.youtube.com/watch?v=s1bka7RIBN4)

---

## Class Documentation

Class documentation, based on labels and definitions, is automatically generated and will be available here: [Link TBD]
