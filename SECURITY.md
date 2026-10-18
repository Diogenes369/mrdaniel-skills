# Security policy

The skills in this repository are plain-text instructions (`SKILL.md`): no scripts, no network calls, no credentials, no code that runs. Every `v*` tag is released by GitHub Actions with a Sigstore build-provenance attestation, so a published skill can be verified against the commit it was built from.

## Reporting

If you find a problem (a skill that asks an assistant to do something unsafe, a mistaken fact, a leaked value), please report it privately through GitHub: **Security → Report a vulnerability** on this repository. You can also write through the site, [mrdaniel.co.il](https://mrdaniel.co.il).

Please do not open a public issue for a security problem before it is fixed.

## Supported versions

Only the latest release is maintained. A fix ships as a new version of the affected skill (`metadata.version` in its `SKILL.md`) and a new signed release.
