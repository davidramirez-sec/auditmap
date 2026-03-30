AuditMap
A control mapping reference tool I built to speed up audit scoping work.
When you're preparing for a SOC 1 or SOC 2 engagement one of the first things you do is figure out which controls apply and what evidence you need to collect. Cross-referencing NIST, ISO 27001, and SOC 2 TSC manually across spreadsheets is tedious. I built this to do it in one place.
Live: https://davidramirez-sec.github.io/auditmap

What it does
Search and filter 50 IT controls across 9 domains. Each control shows its mapping to NIST SP 800-53, ISO/IEC 27001, and SOC 2 TSC side by side.
The gap scorer lets you select which frameworks you're already compliant with and estimates how much coverage you're getting toward the others. The evidence checklist lets you select controls in scope and export a CSV of what you'd need to collect for each one.
Domains covered
Logical Access, Change Management, Computer Operations, Monitoring and Logging, Risk Management, Network Security, Endpoint Security, HR and Personnel, Physical Security
Stack
Vanilla HTML, CSS, and JS. No frameworks, no build tools, no backend. Open index.html in a browser and it works.
git clone https://github.com/davidramirez-sec/auditmap.git
open index.html
What I'd add next
PCI DSS v4.0 as a fourth framework, filtering by specific TSC criteria like CC6 and A1, PDF export for the evidence checklist, and saved selections between sessions.
About
Built by David Ramirez — SSCP · CCSP · CySA+ · Security+ · ITIL v4
davidramirez.tech@gmail.com
Control mappings are based on publicly available NIST, AICPA, and ISO documentation. For reference and scoping purposes only, not a formal audit opinion.
