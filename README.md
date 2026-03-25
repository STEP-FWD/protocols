# STEP Protocols

**STEP (Standardized Template for Experimental Procedures)** is an open framework for developing, maintaining, and version-controlling experimental protocols.

This repository contains curated STEP protocols designed to ensure **reproducibility, clarity, and continuous improvement** across experimental workflows.

---

## Purpose

Experimental procedures are often:

* difficult to reproduce
* inconsistently documented
* hard to evolve collaboratively

STEP addresses this by:

* standardizing protocol structure
* enabling version control via Git
* supporting transparent review and iteration
* maintaining a shared, open knowledge base

---

## Repository Structure

```
protocols/
  <domain>/
    <protocol-name>/
      protocol.md
      metadata.yaml
      figures/
templates/
schemas/
docs/
```

* `protocol.md` → human-readable protocol
* `metadata.yaml` → structured metadata (version, authors, equipment, etc.)
* `figures/` → images and supplementary material

---

## Protocol Format

Each STEP protocol follows a structured format:

* Description
* Step-by-step procedure
* Materials & equipment
* Parameters and ranges
* Issues, warnings, troubleshooting
* Validation and expected outcomes
* References and supplementary information

---

## Versioning

Protocols are version-controlled using Git.

We recommend semantic versioning:

* **MAJOR** → breaking or fundamental changes
* **MINOR** → improvements or additions
* **PATCH** → clarifications or minor fixes

---

## Contributing

We welcome contributions.

Typical workflow:

1. Fork the repository
2. Create a new branch
3. Add or modify a protocol
4. Submit a pull request

All contributions should:

* follow the STEP template
* include clear parameter definitions
* document validation and expected outcomes
* include safety considerations where applicable

---

## Governance

Protocols in the `main` branch are considered **reviewed and approved**.

Changes require:

* pull request review
* consistency with STEP standards
* clear justification for modifications

---

## License

This repository is licensed under **Creative Commons Attribution-ShareAlike 4.0 (CC BY-SA 4.0)**.

This means:

* you may use, modify, and distribute the protocols
* you must give appropriate credit
* any modified versions must be shared under the same license

---

## Vision

STEP aims to become a **living standard for experimental procedures**, enabling:

* reproducible science
* collaborative protocol development
* transparent evolution of best practices
