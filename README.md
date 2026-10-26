# ipwhois Cookbook

<!-- ZQM-START -->
<!-- markdownlint-disable MD033 -->
<p align="center">
  <strong>ZQM Computing — Geospatial Engineering & Scientific Computing</strong><br>
  <a href="https://github.com/ZQM-Computing">ZQM Computing</a>
</p>
<!-- markdownlint-enable MD033 -->
<!-- ZQM-END -->

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

A **ipwhois cookbook** — WHOIS and RDAP lookups from Python. Wave-10 tool on Node-1 (wave-10 done except BBOT and certstream). Patterns are planned from the design, not yet from fleet runs. It is intended for Developers who resolve IP ownership and network data programmatically. Validate each pattern against your own data, software versions, and operating environment before adopting it.

## Repository role and status

**Status:** Active, public — seeding. Pattern passes land in follow-up work from fleet-verified setups; the tables below list what is planned, not what is already written.

**What this repository is:** ipwhois patterns — see the table below.

**What it contributes:** Part of the ZQM Computing geospatial portfolio. The umbrella index for the series is [geospatial-cookbooks](https://github.com/ZQM-Computing/geospatial-cookbooks).

**Standing:** This repository is maintained independently. Automated checks cover only the paths and environments configured in its workflows; they do not establish production readiness or operational certification.

## Who this is for

Developers who resolve IP ownership and network data programmatically.

## Prerequisites

- ipwhois in the fleet Python environment
- Python 3.11+
- IP addresses you are authorized to look up

## Patterns (planned)

| # | Example | What it will demonstrate |
|---|---------|--------------------------|
| 01 | `01-first-lookup` | WHOIS and RDAP lookups for an address |
| 02 | `02-network-info` | Network ranges, ASNs, and country data |
| 03 | `03-batch` | Batch lookups with rate-limit handling |

## Repository layout

```text
ipwhois-cookbook/
├── examples/          # pattern passes, landing in follow-up work
├── README.md
└── LICENSE
```

## Roadmap

- First pattern pass: the first two table rows
- Second pass: the remaining rows, from fleet-verified setups

## Contributing

A contributing guide lands with the first pattern pass. Report security issues to <zqmcomputing@gmail.com> — please do not open a public issue for those.

## More from this series

- [dnsrecon-cookbook](https://github.com/ZQM-Computing/dnsrecon-cookbook) — DNS enumeration from the command line
- [amass-cookbook](https://github.com/ZQM-Computing/amass-cookbook) — Passive subdomain enumeration and graph output
- [shodan-cookbook](https://github.com/ZQM-Computing/shodan-cookbook) — Internet-device search from the command line
