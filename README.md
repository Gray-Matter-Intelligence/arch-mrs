Machine Readable Architecture Specification

# Objectives

1. Specify Architecture Specification in Machine Readable format, referred to as Machine Readable Spec (MRS)

2. Deterministic Automation to generate Design, Test & Documentation from MRS

> Note that the primary focus is semiconductor development, but the concept may also be extended for software or other systems

# Machine Readable Spec

Specify architecture definition & design requirements in YAML format. YAML is chosen over JSON due to the [lesser verbosity & ability to add comments](https://www.geeksforgeeks.org/html/what-is-the-difference-between-yaml-and-json/)

Where already established, other formats may be used, e.g. PlantUML (state or sequence diagrams) that specifies a **diagram** (document), but automation can create the design and test it

# MRS To Design & Test

Some examples

1. SoC reset and clock

2. Finite State Machines for digital component (part of a larger IP)

# MRS to Doc

## Markdown and UML based Documentation

MmDocs based documentation system, which supports Machine Readable Spec (MRS)

TODO: Improve explaination

1. Draw.io: https://pypi.org/project/mkdocs-drawio-exporter/#:~:text=Usage&text=The%20plugin%20will%20export%20the,than%20separate%20files%20per%20page.

> Install draw.io executable (in Ubuntu, use **sudo snap install drawio**)

2. PlantUML: https://github.com/christo-ph/mkdocs_build_plantuml

3. Tables (CSV, XLS): https://github.com/timvink/mkdocs-table-reader-plugin

Compare with https://timvink.nl/blog/reproducible-reports-with-mkdocs/

https://jameswillett.dev/getting-started-with-material-for-mkdocs/#introduction