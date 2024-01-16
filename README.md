# Repository Overview: ODE_AM Ontologies

## Introduction

This repository is dedicated to the ontologies developed within the ODE_AM project. The primary focus of this project is the systematic management of process and material data, encompassing three specific manufacturing processes: Powder Bed Fusion (PBF) Laser Beam Metal at Fraunhofer IGCV, Direct Energy Deposition (DED) at TU Ilmenau, and Composite Extrusion Modeling at MFPA Weimar. These ontologies serve as a structured framework for data acquisition strategies across these varied manufacturing domains.

## Usage
The usage is given in combination withing a developed workflow and web-application, incordporating the ontologies as a backbone and mapping the different files and formats along the process chain to the ontology, whereas triples are stored in a triplestore and raw data are uploaded to the cloud for backup. The general workflow for powder bed fusion laser beam metal is shown here:

![grafik](https://github.com/ThomasBjarsch/ODE_AM/assets/115726934/4bcbc461-2fdc-4397-a8e0-cc853ffe9c10)




## Ontology Descriptions

### Fraunhofer IGCV Manufacturing Application Ontology

This ontology encapsulates a broad range of classes that are pertinent to the manufacturing domain. It includes general classes that are applicable across various manufacturing fields, such as 'Machine', 'STL-File', and 'Steel'. This ontology aims to standardize and integrate diverse manufacturing concepts into a cohesive structure.

### Fraunhofer IGCV Additive Manufacturing Application Ontology

Building upon the Manufacturing Application Ontology, this ontology specifically targets additive manufacturing. It encompasses parameters commonly employed in the additive manufacturing sector, such as 'Build Platform Temperature' and 'Layer Height'.

### Fraunhofer IGCV Powder Bed Fusion Application Ontology

Aligned with the project's focus, this ontology is tailored to the Powder Bed Fusion process. It includes classes representing various parameters and specifications unique to the Powder Bed Fusion process, particularly those used in the M290 machine by Electro Optical Systems GmbH.

## Class Generation Strategy

The development of classes within these ontologies is driven by project-specific requirements. Wherever possible, pre-existing classes from the Basic Formal Ontology (BFO) and Common Core Ontologies (CCO) are leveraged, ensuring consistency and interoperability with established ontological standards.

## Hierarchical Structure

### Top-Level Ontology

The Basic Formal Ontology (BFO) is employed as the top-level ontology, providing a high-level conceptual framework that underpins the entire ontological structure.

### Mid-Level Ontologies

At the mid-level, Common Core Ontologies (CCO) are used. These ontologies provide a more detailed and domain-specific layer of categorization, bridging the gap between the abstract concepts in BFO and the specific classes in the project's ontologies.

## Methodological Approach
Publications:
- PBF-LB/M Datamanagament using developed web-app has been presented at FEMS EUROMAT 2023:
  Thomas Bjarsch: MAKE THIS CURSIVE:Ontology-based material data management in metal additive manufacturing domain
  The written conference Beitrag is work in progress.
- Publication for a special issue in "Advancded Engineering Materials" is ongoing.

## Methodological Approach

### Class Generation and Integration

The methodology for generating classes within these ontologies is based on the relevance to the ODE_AM project, in this case taken by expert's interviews on possible influencing factors on material properties. A selective approach ensures that only pertinent classes are developed, while existing classes from BFO and CCO are adapted and integrated to maintain coherence and compatibility with broader ontological frameworks.

### Implementation and Application

An important aspect of this project is the implementation of a web application for efficient data import and visualization. This application serves as a practical tool for leveraging
