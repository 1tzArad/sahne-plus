## Sahne+ 1.3.9

**Version:** 1.3.9 · **Release date:** 2026-10-01

### What's new
- **Your KickBot queue settings now apply.** The delay between alerts, the play/pause state and the other tip-queue settings you change in KickBot were silently dropped, so Sahne+ always waited its own 5 seconds between alerts. They now take effect as soon as KickBot sends them. Note: a queue paused in KickBot holds every alert, Kick subs and StreamElements tips included, until you set it to play again; the Home page shows the state. Thanks @SoroushRF (#12).
- Verify this installer: `gh attestation verify .\Sahne-Plus-Setup-1.3.9.exe --repo AmirEyZed/sahne-plus`

### How to update
Sahne+ 1.3.1 and later show a notice inside the app: click **آپدیت**. From 1.3.0 or older, install this file manually once.

### Files in this release
- `Sahne-Plus-Setup-1.3.9.exe` — Windows installer (per-user, no admin rights needed)
- `SHA256SUMS.txt` — SHA-256 checksum of the installer (generated in the release workflow)
- `README-FA.txt` — راهنمای فارسی

### Notice
SHA-256 checksums verify the integrity of downloaded files; the provenance attestation proves the file was built by this repository's workflow from the public source. Neither is a security audit. The installer is not code-signed yet; Windows SmartScreen may warn — verify, then choose **More info → Run anyway**. Download Sahne+ only from this repository's Releases page.

Sahne+ is an independent third-party application and is not affiliated with, endorsed by, or sponsored by Kick, KickBot, StreamElements, baha24 or Bonbast. Privacy: [PRIVACY.md](https://github.com/AmirEyZed/sahne-plus/blob/main/PRIVACY.md) · Terms: [TERMS.md](https://github.com/AmirEyZed/sahne-plus/blob/main/TERMS.md) · Security: [SECURITY.md](https://github.com/AmirEyZed/sahne-plus/blob/main/SECURITY.md)
