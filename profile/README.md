<p align="center">
  <img src="https://dorsalhub.com/static/img/dorsal-text-512.png" alt="DorsalHub" width="300">
</p>

<p align="center">
  <strong>An annotation platform for files: annotate any file, by hand or with models.</strong>
</p>

---

[DorsalHub](https://dorsalhub.com) indexes files by their hashes and stores annotations about them: metadata, extracted text, transcripts and more. Our tools are open source.

* **[`dorsal`](https://github.com/dorsalhub/dorsal)**
  Python library and CLI. Scan files, run annotation models, build pipelines, and push results to DorsalHub.

* **[`pdf-extractor`](https://github.com/dorsalhub/pdf-extractor)**
  Fast, deterministic PDF text and layout extraction with pdfium. Install with `dorsal model install`.

* **[`whisper`](https://github.com/dorsalhub/whisper)**
  Speech-to-text transcription with CTranslate2-based Whisper models.

Annotations follow [OATS](https://oatschema.org), the Open Annotation Task Schemas: strict, versioned JSON Schemas for model outputs, with validators for Python, JavaScript and Rust ([github.com/oatschema](https://github.com/oatschema)).

---
*Our open-source tools are licensed under Apache 2.0.*
