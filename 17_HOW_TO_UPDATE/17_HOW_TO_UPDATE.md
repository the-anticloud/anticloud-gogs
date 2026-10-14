# How to Update — GOGS

**Project:** `GOGS`
**Category:** SOFTWARE_DEVELOPMENT
**Domain:** software development tools
**Date:** 2026-10-08

---

## Update Procedure

### Checking for Updates
```bash
GOGS --version
GOGS check-update
```

### Applying Updates
```bash
pip install --upgrade GOGS
```

### Rolling Back
```bash
pip install GOGS==<previous-version>
```

### Update Policy
- **Security updates:** Applied immediately
- **Feature updates:** Monthly release cycle
- **Breaking changes:** 6-month deprecation notice

## Verification

16/16 PASS. Evidence: `ISOLATED_LAB_RESULTS/03_Result_Register.md`.
