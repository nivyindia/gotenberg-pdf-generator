## 📌 Nivy AIOS Work Status — Quick Resume

- **Last updated:** 2026-09-16
- **Role:** PDF/document infrastructure component supporting the broader AIOS ecosystem.
- **Completed:** Repository-level autonomous execution guidance and persistent cross-session status tracking established.
- **Exact completion %:** Not inferred from this component's upstream feature set.
- **Where to start:** `AIOS-WORK-STATUS.md` → then `nivyindia/Nivy-Next-AIOS` canonical plan/tracker.

**Detailed status:** [AIOS-WORK-STATUS.md](AIOS-WORK-STATUS.md)

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

Questions and feedback: [GitHub Discussions](https://github.com/gotenberg/gotenberg/discussions).
Bug reports: [GitHub Issues](https://github.com/gotenberg/gotenberg/issues).

## Sponsors

If Gotenberg powers your workflow or your business, consider [**becoming a sponsor**](https://github.com/sponsors/gulien).

**Historic & GitHub Sponsors**

- [TheCodingMachine](https://thecodingmachine.com/)
- [pdfme](https://pdfme.com/)
- [PDFBolt](https://pdfbolt.com)
- [FileToPDF.dev](https://filetopdf.dev)

**Powered By**

- [Docker](https://docs.docker.com/docker-hub/repos/manage/trusted-content/dsos-program/)
- [JetBrains](https://www.jetbrains.com/community/opensource/)
