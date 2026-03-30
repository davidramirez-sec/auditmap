# AuditMap

A control mapping reference tool I built to speed up audit scoping work.

When you're preparing for a SOC 1 or SOC 2 engagement, one of the first things you do is figure out which controls apply and what evidence you need to collect. Cross-referencing NIST, ISO 27001, and SOC 2 TSC manually across spreadsheets is tedious — so I built this to do it in one place.

**Live:** https://davidramirez-sec.github.io/auditmap

---

## What it does

- Search and filter 50 IT controls across 9 domains
- See each control mapped to NIST SP 800-53, ISO/IEC 27001, and SOC 2 TSC side by side
- **Gap Scorer** — select which frameworks you're already compliant with and it estimates your coverage toward the others
- **Evidence Checklist** — select controls in scope and export a CSV of what evidence you'd need to collect for each one

## Domains covered

Logical Access, Change Management, Computer Operations, Monitoring & Logging, Risk Management, Network Security, Endpoint Security, HR & Personnel, Physical Security

## Stack

Just vanilla HTML, CSS, and JS — no frameworks, no build tools, no backend. Open `index.html` in a browser and it works.

```
git clone https://github.com/davidramirez-sec/auditmap.git
open index.html
```

## What I'd add next

- PCI DSS v4.0 as a fourth framework
- Filter by specific TSC criteria (CC6, A1, C1)
- PDF export for the evidence checklist
- Saved selections between sessions

## About

Built by David Ramirez — IT audit and compliance, SSCP · CCSP · CySA+ · Security+ · ITIL v4.


📧 davidramirez.tech@gmail.com

---

*Control mappings are based on publicly available NIST, AICPA, and ISO documentation. For reference and scoping purposes only — not a formal audit opinion.*
