# EDOS Security Policy

Security matters in EDOS because the project executes code in a browser and may be used by students and educational institutions.

## Supported Version

Until formal versioned releases are established, security fixes are applied to the current version published in the default branch.

| Version | Supported |
|---|---|
| Current default branch | ✅ |
| Older copied or unofficial versions | ❌ |

## Reporting a Vulnerability

**Do not publish exploit details, proof-of-concept attacks, private tokens, or sensitive user information in a public GitHub Issue.**

Preferred reporting methods:

1. Use GitHub's private security-advisory / vulnerability-reporting feature if it is enabled for this repository.
2. If private reporting is unavailable, contact the project owner through the official GitHub profile/repository and request a private communication channel.

Please include:

- a clear description of the issue;
- affected browser/version if relevant;
- affected EDOS feature;
- reproducible steps;
- expected behavior;
- actual behavior;
- severity and possible impact;
- whether student data or code could be exposed;
- whether the issue requires user interaction; and
- a minimal proof of concept if safe to share privately.

## Security Areas of Special Interest

Reports are especially useful for issues involving:

- cross-site scripting (XSS);
- unsafe rendering of Markdown, CSV, notebooks, PDFs, or repository content;
- arbitrary HTML injection;
- malicious notebook output;
- unexpected external network requests;
- package-loading behavior;
- browser local-storage exposure;
- unsafe URL handling;
- GitHub repository-content loading;
- content-security weaknesses;
- sandbox escapes;
- credential/token exposure; or
- code execution outside the intended Pyodide/browser sandbox.

## Student Privacy

EDOS should avoid collecting or transmitting student code and personal information unnecessarily.

Security reports that identify accidental data transmission, privacy leaks, or unsafe telemetry are welcome.

## Responsible Disclosure

Please allow the project maintainers reasonable time to investigate and prepare a fix before publicly disclosing a vulnerability.

The project will try to acknowledge valid reports and coordinate remediation, but no guaranteed response or remediation timeline is promised.

## Third-Party Dependencies

Some vulnerabilities may originate in third-party components such as Pyodide, CDN-hosted scripts, browser engines, GitHub Pages, or external content.

When appropriate, maintainers may refer the report to the relevant upstream project.

## Out of Scope

The following are generally outside the project's direct control:

- vulnerabilities in an unsupported or outdated browser;
- malicious modifications in unofficial EDOS forks;
- attacks requiring a user to intentionally replace the official EDOS source with hostile code;
- vulnerabilities in third-party websites merely linked from educational material; and
- unsupported native Python packages that cannot operate correctly in Pyodide.

Thank you for helping keep EDOS safe for students and educators.
