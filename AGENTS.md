# NästaStopp Suite — independent workspace

User instructions override upstream release instructions.

- Work only in HussamEl/NastaStopp-Suite. HussamEl/S20Ultra is a read-only source; never push, publish releases, open PRs, or change settings there.
- Preserve the original NästaStopp identity and phone/tablet/passenger-display flows. Do not replace the product with the earlier VårdNav website.
- Build separate taxi/Färdtjänst/Sjukresor and truck products. Share design and appropriate core components, not vehicle-specific behavior.
- Preserve the original privacy boundaries for passenger information. The browser work-device location feature must be explicitly enabled by the driver, authenticated, and expose last-update/connection state; never imply continuous background tracking on unsupported platforms.
- Android APKs do not run on iPad. Report platform support and untested behavior accurately.
- Read CLAUDE.md and docs/GUIDE.md for architecture. Their upstream branch/release destinations are historical and superseded by this file. Archived workflows under docs/upstream-workflows must not be automatically reactivated.
- Never commit signing keys, credentials or patient trip data. Reuse existing font licenses and attribution.

Current baseline: upstream Nästa Stopp 1.46, commit 901da16b0dc7e7da397fdd67ac2520fe55510cb2. Importing this baseline is not completion of the requested new applications.
