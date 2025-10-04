# Vulnerability Reports


This repository contains formatted vulnerability reports and PoCs (Proofs of Concept) intended for tracking, sharing internally, or publishing (with permission). Each vulnerability is stored in `vulnerabilities/` as its own markdown file. PoCs and test artifacts live under `poc/`.


> **Important:** Only test PoCs against systems you are authorized to test. Unauthorized scanning, exploitation, or disclosure is illegal and unethical.


## Repository structure


- `vulnerabilities/` — Individual vulnerability markdown files (one file per issue).
- `poc/` — Proof-of-Concept code and test artifacts.
- `.gitignore` — Recommended ignores for sensitive files.


## How to add a new vulnerability


1. Create a new file in `vulnerabilities/` named `YYYY-MM-DD-Short-Title.md` (e.g. `2025-10-04-csrf-profile-update.md`).
2. Follow the report template used in the example file. Include PoC by default when applicable.
3. Add any PoC files to `poc/` and reference them in the vulnerability markdown.
4. Commit and push with a descriptive message.


## Report template (summary)


Each vulnerability file should contain the following sections:


- Vulnerability ID / Title
- Impact
- Likelihood
- Risk Level
- Found In (host/URL)
- Vulnerability Description (formal paragraph style)
- Proof of Concept (PoC) — include code and reproduction steps
- Initial Recommendations (clear mitigations)


## Disclosure & Legal


If you plan to publish these reports publicly, ensure you have written permission from the system owner. Redact any personally identifiable information (PII) or credentials before publishing.


## License


Choose and add a license if desired. Example: `MIT`.
