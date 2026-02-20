<p align="center">
  <img src="https://dorsalhub.com/static/img/dorsal-logo.png" alt="DorsalHub" width="300">
</p>

<p align="center">
  <strong>Generating, validating, and managing structured file metadata.</strong>
</p>

---

Welcome to **DorsalHub**! We build tools that provide a unified, strict contract for data engineering tasks, decoupling data producers (like ML models and ad-hoc scripts) from downstream consumers. 

Our ecosystem is anchored by our private-by-default platform for searching and tagging file metadata, supported by our core open-source repositories.

### 📦 Core Repositories

* **[`dorsal`](https://github.com/dorsalhub/dorsal)**
  Our primary Python library and CLI tool for extracting metadata. It runs a local-first extraction pipeline, checks annotations against strict schemas, and pushes records directly to DorsalHub.
  
* **[`open-validation-schemas`](https://github.com/dorsalhub/open-validation-schemas)**
  The backbone of our data contracts. This repository houses our strict, versioned JSON schemas for standardizing everything from audio transcriptions to object detection and LLM outputs. 

* **[`dorsal-adapters`](https://github.com/dorsalhub/dorsal-adapters)**
  The bridge to external systems. This strictly typed Python library translates Open Validation Schemas-compliant JSON records into industry-standard formats (like `.srt`, `.vtt`, or `.tsv`), and parses them back into JSON.

### 🔗 Resources

* **Website**: [dorsalhub.com](https://dorsalhub.com)
* **Documentation**: [docs.dorsalhub.com](https://docs.dorsalhub.com)

---
*All of our open-source tools are provided under the Apache 2.0 license.*
