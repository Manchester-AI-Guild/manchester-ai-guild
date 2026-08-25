# Security maintenance checklist

Quarterly review:

- Confirm `.gitignore` includes env, key, cert, and build-output patterns.
- Confirm `SECURITY.md` still reflects the reporting path and response targets.
- Review workflow pins for GitHub Actions and update stale majors.
- Confirm Gitleaks and CodeQL workflows are still appropriate for the repo type.
- Verify Dependabot and secret-scanning remain enabled where supported.
- Review open alerts and close out any false positives or stale findings.
