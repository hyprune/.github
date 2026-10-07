# Security policy

Hyprune is pre-release. No version currently has a long-term support commitment. Report problems in the latest development code or proposed contracts; include the relevant commit, Hyprland build and affected component.

## Private reporting

Use **Security → Report a vulnerability** in the affected Hyprune GitHub repository. For issues spanning components, use [core's private reporting form](https://github.com/hyprune/core/security/advisories/new). Include a minimal reproduction, impact, affected versions and any mitigation. Do not include launch tokens, private window contents or unrelated personal data.

**Owner setup required:** enable and test GitHub private vulnerability reporting on each public repository before inviting reports. If the button is unavailable, the reporting route has not been enabled. Do not put exploit details in a public issue; a public request to enable private reporting may omit all vulnerability details. No email fallback is published.

The project will acknowledge and coordinate reports as maintainers become available; we cannot promise response times yet. Agree on a disclosure timeline privately. Security fixes should include regression tests and relevant compatibility notes.

## Relevant boundaries

Compositor render reentrancy, plugin lifecycle, IPC grants/tokens, sandbox escape, input routing, package paths and asset parser limits are security-sensitive. Same-UID unsandboxed processes are trusted host code, not isolated extensions. World packages must be data-only.
