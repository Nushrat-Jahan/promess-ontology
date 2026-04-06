# PROMESS Ontology

## Overview

The **PROMESS Ontology** is an ontology developed to support the structured representation of concepts relevant to the PROMESS domain, including participants, study design, visits, medical conditions, risk factors, exposures, measurements, biological sampling, imaging examinations, clinical results, temporality, treatment, events, and place.

This repository contains the ontology source files, documentation assets, and publication material required to maintain and publish the ontology in a consistent and reusable form.

## Status

**Current status:** Draft v0.1  
This version is a working draft prepared for conceptual validation, ontology engineering, documentation generation, and iterative review.

## Ontology identifiers

- **Ontology IRI:** `https://w3id.org/promess/ontology`
- **Namespace:** `https://w3id.org/promess/ontology#`
- **Preferred prefix:** `promess`
- **Version IRI:** `https://w3id.org/promess/ontology/0.1-draft`
- **Version info:** `Draft v0.1`

## Maintainers and authors

- Nushrat Jahan, Université de Montpellier, LIRMM
- Lylia Abrouk, Université de Montpellier, LIRMM
- Sandra Bringay, Université de Montpellier, LIRMM
- Zubeyir Salis, INSERM, PhyMedExp

**Contact**
- nushrat.jahan@lirmm.fr
- lylia.abrouk@lirmm.fr
- sandra.bringay@lirmm.fr
- zubeyir.salis@inserm.fr

## License

This ontology is distributed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

## Repository name

**Recommended repository name:** `promess-ontology`

This name is short, clear, stable, and aligned with the ontology URI and documentation publication pattern.


## Main ontology files

The main ontology source files are:

- `PROMESS_ontology_final.ttl`
- `PROMESS_ontology_final.owl`

For editing and documentation generation, the Turtle file is the recommended primary source.

## Scope of the ontology

The PROMESS Ontology currently covers the following main branches:

- persons and study roles
- participant groups
- study and visit structure
- medical conditions
- risk factors
- exposures, including dietary and environmental exposure
- measurements
- biological samples and biomarkers
- imaging examinations
- clinical outcomes
- temporality
- treatment
- events
- place

## Documentation workflow

The documentation of this ontology is intended to be generated with **WIDOCO**.

### Recommended workflow

1. Edit the ontology in Protégé using the Turtle source file.
2. Keep ontology metadata inside the ontology whenever possible.
3. Run WIDOCO on `PROMESS_ontology_final.ttl`.
4. Review the generated cross-reference and metadata pages.
5. Publish the generated documentation in the `docs/` folder.
6. Serve the documentation through GitHub Pages.
7. Redirect the ontology URI through W3ID.

## Reuse and citation

When reusing this ontology, please cite the ontology name, version, ontology IRI, and authors.

Suggested citation form:

> PROMESS Ontology, Draft v0.1, Nushrat Jahan, Lylia Abrouk, Sandra Bringay, and Zubeyir Salis.

## Editing policy

When updating the ontology:

- preserve the ontology IRI
- update the version IRI for each released version
- update `owl:versionInfo`
- document major conceptual changes
- regenerate the WIDOCO documentation after structural modifications

## Notes for contributors

Before committing significant changes:

- validate class and property names
- verify domain and range declarations
- review disjointness axioms
- check inverse properties
- confirm that the documentation still matches the ontology content

## Tools

The following tools are recommended for working with this repository:

- Protégé for ontology editing
- WIDOCO for documentation generation
- WebVOWL for visualization
- GitHub Pages for publication

## Acknowledgement

This repository contains the draft ontology and documentation material prepared for the PROMESS ontology engineering workflow.
