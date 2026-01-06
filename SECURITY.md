# Security Policy

Eisengrau is an educational, multi-author repository that contains code, notes,
and supporting materials. While this project is not security-critical software,
we take security and responsible disclosure seriously.

---

## Supported Versions

Eisengrau does not publish numbered releases. The **default branch** is treated
as the actively maintained version.

If you discover a security issue affecting repository content, tooling, or
automation, please report it as described below regardless of version.

---

## Reporting a Vulnerability

Please **do not** open a public GitHub issue or discussion for vulnerabilities.

Instead, report security concerns privately to the maintainers using one of the
following methods:

1. **GitHub Private Vulnerability Reporting** (preferred), if enabled for this
   repository, or
2. Email the maintainers.

When reporting, include:
- a clear description of the issue and its impact,
- the file path(s) and commit hash(es) involved (if applicable),
- minimal reproduction steps or a proof-of-concept (if safe),
- any suggested remediation.

---

## What Counts as a Security Issue

Examples of in-scope issues include:
- malicious or intentionally harmful code submissions,
- obfuscated code designed to hide unsafe behaviour,
- hidden network calls, credential harvesting, or data exfiltration,
- supply-chain risks (malicious dependencies, compromised scripts),
- CI/CD workflow vulnerabilities (e.g. unsafe GitHub Actions usage),
- secrets accidentally committed to the repository (API keys, tokens, passwords),
- unsafe build or execution instructions that could cause harm.

Non-security issues (out of scope) include:
- algorithmic inefficiency,
- incorrect solutions (unless they cause unsafe behaviour),
- stylistic concerns,
- performance-only regressions without security impact.

If you are unsure, report it anyway.

---

## Handling and Response

Maintainers aim to:
- acknowledge valid reports,
- assess severity and scope,
- coordinate a fix,
- and minimise unnecessary exposure.

Response times may vary depending on academic schedules and availability, but
reports will be handled in good faith.

If the issue affects users, maintainers may publish a brief public note after
a fix is available.

---

## Safe Contribution Expectations

All contributors must ensure that submitted code:
- contains no malicious, obfuscated, or deliberately misleading behaviour,
- follows the repository’s conventions and language standards,
- avoids unnecessary external dependencies,
- does not include secrets or private data.

If your solution requires running code, it should be clearly documented and
should not perform unexpected network calls or filesystem modifications outside
the repository directory.

---

## Responsible Disclosure

Please:
- avoid public disclosure until maintainers have had an opportunity to address
  the issue,
- avoid sharing exploit details that increase risk unnecessarily,
- provide enough detail to reproduce and validate the issue responsibly.

Thank you for helping keep Eisengrau safe and trustworthy.
