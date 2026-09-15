> **UNIVERSAL START COMMAND:** Read `docs/REPO-CONTROL/00-MASTER-INSTRUCTIONS.md` and continue the work.
>
> Give this exact instruction to ChatGPT/Codex/another AI agent after opening this repository. It is the repository's main work instruction. The agent must read the master instructions, discover the control pack and indexed sources, determine the highest-priority unfinished work, execute when permitted, verify it, update tracking/README, commit, and continue. If the control file is missing, search the repository for the equivalent control/instruction system before creating duplicates.

## 📘 Repository Context — Read This First

- **Purpose:** PDF/document-generation infrastructure component supporting the broader Nivy AIOS ecosystem.
- **Main objective:** Provide reliable document-to-PDF conversion capability that can be used by governed AIOS workflows and document/report pipelines.
- **Main objects:** PDF conversion service, document conversion endpoints, HTML/URL/Markdown/Office input handling and related infrastructure.
- **Data/source:** Upstream Gotenberg project plus repository-specific deployment/configuration; verify version, security, licensing and runtime compatibility before production use.
- **Implementation plan:** AIOS integration follows the canonical Nivy Next AIOS plan, tool/connector contracts and verification evidence.
- **Progress rule:** Upstream feature completeness is not the same as Nivy AIOS integration completion.
- **How to use this README:** Understand the component → check `WORK-STATUS.md` → inspect local deployment/integration → trace actual AIOS use to canonical evidence.

## 📌 Nivy AIOS Work Status — Quick Resume

- **Last updated:** 2026-09-16
- **Role:** PDF/document infrastructure component supporting the broader AIOS ecosystem.
- **Completed:** Repository-level autonomous execution guidance and persistent cross-session status tracking established.
- **Exact completion %:** Not inferred from this component's upstream feature set.
- **Where to start:** `WORK-STATUS.md` → then `nivyindia/Nivy-Next-AIOS` canonical plan/tracker.

**Detailed status:** [WORK-STATUS.md](WORK-STATUS.md)

---

<p align="center">
    <img src="https://raw.githubusercontent.com/gotenberg/art/master/logo.png" alt="Gotenberg Logo" width="150" height="150" />
    <h3 align="center">Gotenberg</h3>
    <p align="center">A Docker-based API for converting documents to PDF</p>
</p>

---

**Gotenberg** is a Docker-based API for converting documents to PDF. Trusted in production by thousands of companies. Also adopted by notable open-source projects.

Send your files via `multipart/form-data`, get a PDF back. No need to manage Chromium, LibreOffice, or fonts yourself.

## Quick Start

```bash
docker run --rm -p 3000:3000 gotenberg/gotenberg:8
```

Convert a URL to PDF:

```bash
curl --request POST http://localhost:3000/forms/chromium/convert/url --form url=https://sparksuite.github.io/simple-html-invoice-template/ -o invoice.pdf
```

## Features

- **HTML, URL, Markdown to PDF** via Headless Chromium
- **Office documents to PDF** via LibreOffice (100+ formats)
- **Merge, split, rotate, flatten** PDFs
- **Watermark, stamp, encrypt** PDFs
- **PDF/A and PDF/UA** compliance
- **Screenshots** of URLs and HTML
- **Read/write metadata and bookmarks**

See the [full documentation](https://gotenberg.dev/docs/getting-started/introduction).

## Contributing

Questions and feedback: **GitHub Discussions**
Bug reports: **GitHub Issues**

## Sponsors

If Gotenberg powers your workflow or your business, consider becoming a sponsor.

**Historic & GitHub Sponsors**

- TheCodingMachine
- pdfme
- PDFBolt
- PDFBolt.dev

**Powered By**

- Docker
- JetBrains
