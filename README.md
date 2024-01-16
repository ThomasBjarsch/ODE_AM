# Repository Overview: ODE_AM Ontologies

## Introduction

This repository is dedicated to the ontologies developed within the ODE_AM project. The primary focus of this project is the systematic management of process and material data, encompassing three specific manufacturing processes: Powder Bed Fusion (PBF) Laser Beam Metal at Fraunhofer IGCV, Direct Energy Deposition (DED) at TU Ilmenau, and Composite Extrusion Modeling at MFPA Weimar. These ontologies serve as a structured framework for data acquisition strategies across these varied manufacturing domains.

## Ontology Descriptions

### Fraunhofer IGCV Manufacturing Application Ontology

This ontology encapsulates a broad range of classes that are pertinent to the manufacturing domain. It includes general classes that are applicable across various manufacturing fields, such as 'Machine', 'STL-File', and 'Steel'. This ontology aims to standardize and integrate diverse manufacturing concepts into a cohesive structure.

### Fraunhofer IGCV Additive Manufacturing Application Ontology

Building upon the Manufacturing Application Ontology, this ontology specifically targets additive manufacturing. It encompasses critical parameters commonly employed in the additive manufacturing sector, such as 'Build Platform Temperature' and 'Layer Height', providing a structured approach to categorizing additive manufacturing data.

### Fraunhofer IGCV Powder Bed Fusion Application Ontology

Aligned with the project's focus, this ontology is tailored to the Powder Bed Fusion process. It includes classes representing various parameters and specifications unique to the Powder Bed Fusion process, particularly those used in the M290 machine by Electro Optical Systems GmbH.

## Class Generation Strategy

The development of classes within these ontologies is driven by project-specific requirements. Wherever possible, pre-existing classes from the Basic Formal Ontology (BFO) and Common Core Ontologies (CCO) are leveraged, ensuring consistency and interoperability with established ontological standards.

## Hierarchical Structure

### Top-Level Ontology

The Basic Formal Ontology (BFO) is employed as the top-level ontology, providing a high-level conceptual framework that underpins the entire ontological structure.

### Mid-Level Ontologies

At the mid-level, Common Core Ontologies (CCO) are utilized. These ontologies provide a more detailed and domain-specific layer of categorization, bridging the gap between the abstract concepts in BFO and the specific classes in the project's ontologies.

## Methodological Approach

### Class Generation and Integration

The methodology for generating classes within these ontologies is based on the relevance to the ODE_AM project. A selective approach ensures that only pertinent classes are developed, while existing classes from BFO and CCO are adapted and integrated to maintain coherence and compatibility with broader ontological frameworks.

### Data Acquisition and Structuring

The ontologies are designed to support varied strategies for data acquisition, particularly tailored to the specific manufacturing processes involved in the project. This approach ensures that the data structure is aligned with the practical needs and nuances of each manufacturing method.

### Implementation and Application

An important aspect of this project is the implementation of a web application for efficient data import and visualization. This application serves as a practical tool for leveraging
