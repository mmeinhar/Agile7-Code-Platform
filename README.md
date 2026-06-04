# Agile7 Code Platform (ACP)

[![DOI](https://zenodo.org/badge/1049337813.svg)](https://doi.org/10.5281/zenodo.20543683)

**Version DOI (v1.02b):** https://doi.org/10.5281/zenodo.20543683  
**Concept DOI (Latest Version):** https://doi.org/10.5281/zenodo.20543684

## Overview

The Agile7 Code Platform (ACP) is an AI-driven, IDE-integrated software engineering platform designed to maintain continuous alignment between business requirements, project models and its supporting scripts, and generated code through end-to-end traceability.

ACP combines Model-Driven Engineering (MDE), Business Requirements Validation (BRV), AI-assisted code generation, and validation-driven development workflows to help organizations reduce architectural drift, improve software quality, and maintain business-to-code alignment throughout the software development lifecycle.

## Vision

ACP aims to transform software development by treating business requirements, models, and their supporting scripts as authoritative development artifacts while using AI to generate, validate, and regenerate software implementations.

The platform is designed to support modern software engineering practices through:

- AI-driven software generation and regeneration
- IDE-integrated development workflows
- End-to-end requirements-to-code traceability
- Business Requirements Validation (BRV)
- Continuous architecture validation
- Incremental code generation
- LLM-agnostic architecture
- Agentic and traditional execution models

## Key Architectural Concepts

### AI-Driven Architecture

ACP integrates AI into its core architecture through a Prompt-Based Build Engine that transforms requirements, software project models (currently UML), and supporting scripts into software implementations while remaining independent of specific LLM providers.

### IDE-Integrated Development

ACP is designed to integrate directly into developer workflows through its IDE plugin and supporting web services.

Architects and engineers work with models and supporting scripts as primary development artifacts while using the ACP IDE plugin to perform modeling, validation, traceability analysis, code generation, and regeneration activities.

### End-to-End Traceability

ACP maintains alignment between:

- Business Requirements
- Product Requirements Documents (PRDs)
- Software Project Model Diagrams (Phase 1 = UML via plantuml) and their supporting scripts
- Generated Code

This traceability enables software implementations to be continuously validated against business and architectural intent.

### Business Requirements Validation (BRV)

BRV provides traceability and validation between business requirements, software project model diagrams and their supporting scripts, and generated implementations to help ensure that software remains aligned with stakeholder objectives.

### Requirements Fidelity Score (RFS)

RFS measures how closely software project model diagrams and their supporting scripts align with business requirements and use cases that are input into the BRV website portal by product managers. The manager can set percentage-based business-to-software project model and software project-to-code alignment values as the minimum that are acceptable for code development and/or release repository check-in actions. 

### Code Fidelity Score (CFS)

CFS validates generated code against approved software project model diagrams and supporting artifacts to help prevent architectural drift and implementation divergence.

### Model-Driven Integrity

ACP treats business requirements, software project model diagrams, and their supporting scripts as the authoritative source of truth. 

To preserve alignment and traceability, software changes are intended to originate from approved models and scripts rather than from direct modifications to generated code.

Generated code is continuously validated against these artifacts through automated validation and CI/CD workflows. Code that cannot be traced back to approved requirements, models, and scripts may fail validation, requiring updates to the underlying artifacts and regeneration of the affected code.

This approach helps maintain business requirements-to-model-to-code alignment while reducing architectural drift, documentation divergence, and manual coding inconsistencies by preventing the IDE user from checking-in directly-modified AI-generated code into its repository.

### Incremental Code Generation

ACP supports subsystem-based and incremental code generation, enabling large-scale systems to be generated, validated, and regenerated efficiently while minimizing unnecessary LLM compute.

### LLM-Agnostic Design

ACP is designed to support multiple Large Language Models through abstraction layers and standardized prompt templates, reducing dependency on any single AI provider.

## Current Release Scope

This repository currently includes the ACP Software Architecture Whitepaper which contains the following
- ACP Functional Specification
- Reference architecture documentation
- System workflows and design concepts
- Implementation roadmap
- Architectural diagrams and supporting materials

## Intended Audience

- Software Architects
- Principal Engineers
- Technical Leads
- Engineering Managers
- Enterprise Development Teams
- Organizations exploring AI-driven software engineering practices

---

## Getting the Whitepaper

The full whitepaper PDF is included in this repository:

- [Agile7_Code_Platform_Whitepaper.pdf](https://github.com/mmeinhar/Agile7-Code-Platform/blob/main/Agile7_Whitepaper_ACP.pdf)

---

## License

This project is **open-source**. See the [LICENSE](LICENSE) file for details.

---

## About the Author

**Max Meinhardt** – Founder of [Agile7](https://agile7.com), Max is a software engineer with 30 years of experience in software engineering which include enterprise and government web software implementation, web software energy-efficiency and performance optimization, AI-native web software development platform architecture and implementation, and embedded software and firmware implementation.

---

**Connect:** Max Meinhardt – [LinkedIn Profile](https://www.linkedin.com/in/maxmeinhardt)

---

## Citation

If you use or reference ACP, please cite:

Meinhardt, M. (2026).
*Agile7 Code Platform (ACP): Software Architecture Whitepaper*.
Zenodo.
DOI: https://doi.org/10.5281/zenodo.20543683
