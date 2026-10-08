# demo-2026

Vulnerable sample apps for comparing i3gis SAST before and after the Opengrep + DevSkim integration,
focused on languages SonarQube Community does not cover for security.

Each app lives on its own branch:

| Branch | App | Upstream | License |
|---|---|---|---|
| `igoat-swift` | iGoat-Swift (Swift / Obj-C) | https://github.com/OWASP/iGoat-Swift | GPL-3.0 (see `LICENSE` on that branch) |

Damn_Vulnerable_C_Program (C) and govwa (Go) have no upstream license, so they are kept as GitHub forks
instead of being copied here.

Changes from upstream (see the top commit on each branch): vendored third-party code removed
(`iGoat-Swift/iGoat-Swift/ThirdParty/`) so findings point at the app's own code.

These apps are intentionally insecure. Do not deploy them.
