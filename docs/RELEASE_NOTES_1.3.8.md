## Sahne+ 1.3.8

**Version:** 1.3.8 · **Release date:** 2026-09-30

### What's new
- **A paid donation now survives closing the app.** Since 1.3.7 a donation whose payment was taken while OBS was closed waits for a Browser Source. Now it also survives closing or restarting Sahne+ and plays afterwards, without charging twice. Thanks @SoroushRF (#10).
- **Your KickBot link stays hidden on screen.** The widget-link fields (first-run setup and «تغییر اتصال») are masked like the StreamElements token and emptied after connecting, so the key inside the link cannot be read when the app window is shared or streamed. Thanks @SoroushRF (#11).
- Verify this installer: `gh attestation verify .\Sahne-Plus-Setup-1.3.8.exe --repo AmirEyZed/sahne-plus`

### How to update
Sahne+ 1.3.1 and later show a notice inside the app: click **آپدیت**. From 1.3.0 or older, install this file manually once.

### Files in this release
- `Sahne-Plus-Setup-1.3.8.exe` — Windows installer (per-user, no admin rights needed)
- `SHA256SUMS.txt` — SHA-256 checksum of the installer (generated in the release workflow)
- `README-FA.txt` — راهنمای فارسی

### Notice
SHA-256 checksums verify the integrity of downloaded files; the provenance attestation proves the file was built by this repository's workflow from the public source. Neither is a security audit. The installer is not code-signed yet; Windows SmartScreen may warn — verify, then choose **More info → Run anyway**. Download Sahne+ only from this repository's Releases page.

Sahne+ is an independent third-party application and is not affiliated with, endorsed by, or sponsored by Kick, KickBot, StreamElements, baha24 or Bonbast. Privacy: [PRIVACY.md](https://github.com/AmirEyZed/sahne-plus/blob/main/PRIVACY.md) · Terms: [TERMS.md](https://github.com/AmirEyZed/sahne-plus/blob/main/TERMS.md) · Security: [SECURITY.md](https://github.com/AmirEyZed/sahne-plus/blob/main/SECURITY.md)
