# 🚀 SAIC DevSecOps Pipeline Framework (`saic-devsecops-pipeline`)

**Classification:** `UNCLASSIFIED // INTERNAL USE ONLY`  
**Maintainer:** SAIC DevSecOps Working Group (`devsecops@saic.com`)

Standardized CI/CD pipeline definitions for GitHub Actions and Cloud Build supporting automated security scanning, container signing, and FedRAMP compliance enforcement.

## 🛠️ Repository Contents
* `.github/workflows/secops-gate.yml`: Automated GitHub Actions pipeline.
* `Dockerfile`: Hardened Debian distroless multi-stage build.
* `app_scanner.py`: SAST vulnerability scanner.
* `ci-cd-policy.md`: Enterprise container signing and vulnerability threshold policy.
