# Vulnerability Reports — SQLi (fname) & CSRF (Profile Update)

**Generated:** 2025-10-04

## Overview
This repository contains concise, reproducible security reports and PoCs for two confirmed vulnerabilities discovered during authorized testing:

1. **SQL Injection** — injectable `fname` POST parameter on `edit-profile.php`.
2. **Cross-Site Request Forgery (CSRF)** — profile update endpoint lacking anti-CSRF protections.

CSRF vulnerability POC is located in `CSRF-Profile-Update.md file` as an individual markdown file and CSRF and SQL Injection vulnerabilities are under `CSRF and SQL Injection.md file`. Use the files here only for authorized testing and responsible disclosure.

---

