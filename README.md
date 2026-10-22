# Luma for Mac: releases

Downloads and update feeds for **Luma for Mac** and the free **Luma Transfer** helper.
The application source lives in a private repository; this repo only hosts the signed,
notarized builds.

| App | Download | Requires |
| --- | --- | --- |
| Luma for Mac (30-day trial) | [Luma.dmg](https://github.com/Miotares/luma-releases/releases/latest/download/Luma.dmg) | macOS 26 |
| Luma Transfer (free) | [Luma-Transfer.dmg](https://github.com/Miotares/luma-releases/releases/latest/download/Luma-Transfer.dmg) | macOS 26 |

Both apps update themselves via [Sparkle](https://sparkle-project.org). The feeds in
`appcast/` are served by GitHub Pages:

- `https://miotares.github.io/luma-releases/appcast/luma.xml`
- `https://miotares.github.io/luma-releases/appcast/transfer.xml`

Every release lists `SHA256SUMS.txt` for the DMGs. Updates are additionally verified by the
apps with an EdDSA signature.
