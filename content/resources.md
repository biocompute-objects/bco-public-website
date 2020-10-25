---
title: "Resources"
menu: "main"
---

<div class="col-lg-6 offset-lg-3 text-center">
<img src="/images/logo.about.png" class="img-fluid mx-auto d-block" width="75%" alt="">
</div>

<br>

Publicly available resources developed by the BioCompute community include:

### BCO Community

- The [BCO Gitter](https://gitter.im/biocompute-objects/) has spaces for general discussion, technical development, BCO implementation, and networking.

### BCO Documentation

- The [BCO SOP](https://www.biocomputeobject.org/BCO_SOP.html) provides guidance on BCO creation, versioning, and certification.
- The [BCO User Manual](https://www.biocomputeobject.org/BCO_UserManual.html) provides guidance on BCO evaluation.

### BCO Editor

- The [BCO Editor](https://portal.aws.biochemistry.gwu.edu/) is a form based creation tool for generating BioCompute Objects. The BCO Editor contains built-in linting and conformance against the current BioCompute specification. The BCO Editor includes a database of created BCOs. Unless specified in the embargo field, BCOs in the database are viewable to the general public. Legacy Editor site can be found [here](https://www.biocomputeobject.org/bco_editor_tst/).

### Software Packages

- The R package [biocompute](https://cran.r-project.org/package=biocompute) can create, validate, and export BioCompute Objects. Users can encode information in data frames, and compose BioCompute Objects from the domains defined by the standard. A checksum validator and a JSON schema validator are provided. Also supports exporting BioCompute Objects as JSON, PDF, HTML, or Word documents, and exporting to cloud-based platforms.

### BCO Registry

- The BioCompute consortium maintains a database of [registered authorities](https://biocomputeobject.org/registry.html). Registered authorities are able to assign their own IDs in the `object_id` field, such as gwu000001.

### BCO Aggregator (under construction)

- The BioCompute consortium maintains a database of submitted BCOs. The database acts as a mirror that generates checksums for validation.

### BCO "Cheat Sheet"

- A [quick reference guide](https://www.biocomputeobject.org/BCOCheatSheet.pdf) (PDF) for getting up to speed with reading a BCO.

### Platform Specific Tools

#### HIVE

The High-throughput Integrated Virtual Environment ([HIVE](https://hive.biochemistry.gwu.edu/dna.cgi?cmd=main)) for genome analysis and the widely used, open source Galaxy project both have platform specific tools for generating BioCompute Objects from workflows. Both of these can be found via the [landing page](https://www.biocomputeobject.org/landing.html).

#### Cancer Genomics Cloud

The [Cancer Genomics Cloud](https://www.cancergenomicscloud.org/) (CGC) has a powerful tool built into the CGC platform to capture and export a workflow as a BioCompute Object.

### References

1. [2791-2020 IEEE Standard](https://opensource.ieee.org/2791-object/ieee-2791-schema/)<br>
The official IEEE standard, known as IEEE 2791-2020.

1. [Repository](https://standards.ieee.org/standard/2791-2020.html)<br>
The open source repository referenced by the standard. Three formats of the publication are available.

1. [Semantic Versioning](https://semver.org/spec/v2.0.0.html)<br>
BioCompute versioning is based on semantic versioning, but does not use the "major" value in "major.minor.patch" (e.g. `2.4.11`).

    - Use "minor" increments for additions (e.g. the addition of a "`reviewedBy`" block).
    - Use "patch" for minor fixes (e.g. editorial spelling corrections).
    - There is no "major" increment in BCO versioning. A BCO is a record of a specific instance of an analysis, so major changes result in a new BCO.

1. [Provenance Ontology](https://jbiomedsem.biomedcentral.com/articles/10.1186/2041-1480-4-37)<br>
Contributor roles in a BCO are explicitly defined according to the Prov-O standard, and include roles for reviewing a BCO, creating the content in a BCO, and for authoring the BCO itself.

1. [JSON Schema](https://json-schema.org/draft/2019-09/json-schema-core.html)<br>
BioCompute is based heavily on the JSON Schema media type. Definitions and format within the BCO Schema adhere to "draft-handrews-json-schema-02."
