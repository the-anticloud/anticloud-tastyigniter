# TASTYIGNITER

![license](https://img.shields.io/badge/license-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-supermarkets-lightgrey)

> Anticloud-hardened packaging of the upstream project `TASTYIGNITER` in category **SUPERMARKETS**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** SUPERMARKETS · **Upstream:** https://github.com/tastyigniter/TastyIgniter · **Upstream pin:** `035028bc43debb9da08a29e2c8030ec70a92126a` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

<p align="center"><a href="https://tastyigniter" target="_blank"><img src="https://tastyigniter.com/images/logos/logo-padded.png" width="400"></a></p>

<p align="center">
<a href="https://packagist.org/packages/tastyigniter/TastyIgniter"><img src="https://img.shields.io/packagist/v/tastyigniter/TastyIgniter.svg?label=Stable&style=flat-square" alt="Stable"></a>
<a href="https://packagist.org/packages/tastyigniter/TastyIgniter"><img src="https://poser.pugx.org/tastyigniter/flame/downloads" alt="Total Downloads"></a>
<a href="https://github.com/tastyigniter/TastyIgniter/blob/master/LICENSE.txt"><img src="https://img.shields.io/github/license/tastyigniter/TastyIgniter.svg?label=License&style=flat-square" alt="License"></a>
<a href="https://github.com/tastyigniter/TastyIgniter" title="PHP Versions Supported"><img alt="PHP Versions Supported" src="https://img.shields.io/badge/php-8.3%20to%208.4-777bb3.svg?logo=php&logoColor=white&labelColor=555555"></a>
<a href="https://translate.tastyigniter.com/engage/tastyigniter/"><img src="https://translate.tastyigniter.com/widget/tastyigniter/svg-badge.svg" alt="Translate"></a>
<a href="https://twitter.com/TastyIgniter"><img src="https://img.shields.io/twitter/follow/TastyIgniter.svg?label=Follow" alt="Twitter"></a>
</p>

[TastyIgniter](https://tastyigniter.com/) provides a professional and reliable platform for restaurants wanting to offer
online food ordering and table reservation to their customers.

![screenshot](https://tastyigniter.com/images/mockups/v4/Menus.png)

### Documentation
The best place to learn TastyIgniter is by reading the [documentation](https://tastyigniter.com/docs)

### Installation
Please read the [Installation Guide](https://tastyigniter.com/docs/installation) for more information.

### Questions
For questions and support please use the [Community Forum](https://forum.tastyigniter.com) or [Join us on Discord](https://tastyigniter.com/discord). 

### Issues
Please report bugs using the [GitHub issue tracker](https://github.com/tastyigniter/TastyIgniter/issues)

### Stay in touch
- [Follow us on Twitter](https://twitter.com/tastyigniter/) for announcements and updates.
- [Blog](https://tastyigniter.com/blog) for tips and latest developments in the food industry.

## Contributing
We would love your help building TastyIgniter! Please read the [Contributing Guidelines](.github/CONTRIBUTING.md) to learn how you can help.

Thank you to all the people who already contributed to TastyIgniter!

<a href="https://github.com/tastyigniter/TastyIgniter/graphs/contributors"><img src="https://opencollective.com/tastyigniter/contributors.svg?width=890&button=false" /></a>

## Supporting TastyIgniter
TastyIgniter is an MIT-licensed community-driven project with its continuous development made possible by the support of these awesome [backers](#contributing). If you'd like to help support the future of the project, please consider:
1. Donating development time to the project.
2. Spreading the word about TastyIgniter.
3. Becoming a sponsor by donating funds (see below).

## Sponsors
Become a sponsor and get your logo on our README on Github with a link to your site. 

### via Open Collective
<a href="https://opencollective.com/tastyigniter" target="_blank" rel="noopener noreferrer"><img src="https://opencollective.com/tastyigniter/sponsors.svg"></a>

<a href="https://opencollective.com/tastyigniter" target="_blank" rel="noopener noreferrer"><img src="https://opencollective.com/tastyigniter/backers.svg"></a>

### via Patreon
[[Become a Patreon sponsor](https://www.patreon.com/sampoyigi)]

## Built With :heart:
- Laravel full-stack PHP framework
- Bootstrap 5 front-end framework

## Author
TastyIgniter was created by [Samuel Adepoyigi](https://github.com/sampoyigi).

## Security Vulnerabilities
If you discover a security vulnerability within TastyIgniter, please send an e-mail to support@tastyigniter.com.

## License
TastyIgniter is open-source software licensed under the [MIT license](https://tastyigniter.com/licence/).

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Node.js / npm** (manifests: package.json; scanned in UPSTREAM_CLONE)
- Top-level source layout: `app/`, `bootstrap/`, `config/`, `database/`, `extensions/`, `lang/`, `public/`, `resources/`, `routes/`, `storage/`, `tests/`, `themes/`
- Snapshot size: **88 files**, **2765 lines of code** (measured; see Benchmarks)
- Primary languages: `.php` (53), `(none)` (23), `.js` (2), `.json` (2), `.md` (2), `.conf` (1)
- Upstream commit pinned for this packaging: `035028bc43debb9da08a29e2c8030ec70a92126a`

---

## Installation

Please read the [Installation Guide](https://tastyigniter.com/docs/installation) for more information.

*Section quoted from the upstream readme.*
Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

No usage section was found in the upstream readme. Entry points detected in this project directory:

```sh
npm start          # declared start script, when present
npm run dev        # declared dev script, when present
```

Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

The best place to learn TastyIgniter is by reading the [documentation](https://tastyigniter.com/docs)

*Section quoted from the upstream readme.*
---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Node.js / npm |
| Manifests detected | package.json |
| Files in snapshot | 88 |
| Lines of code | 2765 |
| Dependency references | 4 |
| Dependencies by ecosystem | npm: 4 |
| Upstream license | MIT |
| Overlay license | Anticommons 0.1.0 |

Top dependency references recorded in the benchmark snapshot:

| Ecosystem | Name | Version | Source file |
|-----------|------|---------|-------------|
| npm | axios | ^0.25 | package.json |
| npm | laravel-mix | ^6.0.6 | package.json |
| npm | lodash | ^4.17.19 | package.json |
| npm | postcss | ^8.1.14 | package.json |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

No configuration section was found in the upstream readme. Configuration-relevant files detected in this project directory:

- `.env.example`
- `.nginx.conf`
- `config`
- `package.json`

Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

Upstream contributions: fork the `TASTYIGNITER` project, create a feature branch, and open a pull request against upstream. Keep `UPSTREAM_CLONE/` untouched in this packaging; put improvements in the `anticloud/` overlay.

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: MIT** (evidence: `LICENSE.md` in the upstream snapshot).

License file excerpt:

```text
The MIT License (MIT)

Copyright (c) Samuel Adepoyigi <sam@sampoyigi.com>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and
associated documentation files (the "Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS
OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original MIT terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `MIT` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `TASTYIGNITER` (category: SUPERMARKETS)
- **Upstream URL:** https://github.com/tastyigniter/TastyIgniter
- **Pinned commit (SHA):** `035028bc43debb9da08a29e2c8030ec70a92126a`
- **Branch:** 4.x
- **Pin provenance:** GitHub API commits/4.x. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`58ad677861bc4db46338297c9204c09eaec261ed4bc04c5cab90b9cde7a5d68d`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

