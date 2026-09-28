## Sahne+ 1.3.7

**Version:** 1.3.7 · **Release date:** 2026-09-28

### What's new
- **A paid donation is no longer lost when OBS closes at the wrong moment.** If the last Browser Source closed while KickBot was capturing a payment, the donation was marked as played but shown to nobody. It now waits at the front of the queue and plays when a Browser Source connects again, without charging twice. Thanks @SoroushRF (#8).
- **The update button no longer gets stuck.** A stalled connection or a full disk could leave «آپدیت» on «در حال دانلود» until the app was restarted. A download without progress for 60 seconds now stops with a clear message and can be retried; slow downloads that keep moving are not cut off. This helps from the next update on. Thanks @SoroushRF (#9).
- Disconnecting KickBot also removes KickBot's own dashboard test tips; Kick subs, StreamElements tips and the app's own test alerts stay. Thanks @SoroushRF (#7).
- Verify this installer: `gh attestation verify .\Sahne-Plus-Setup-1.3.7.exe --repo AmirEyZed/sahne-plus`

### How to update
Sahne+ 1.3.1 and later show a notice inside the app: click **آپدیت**. From 1.3.0 or older, install this file manually once.

### Files in this release
- `Sahne-Plus-Setup-1.3.7.exe` — Windows installer (per-user, no admin rights needed)
- `SHA256SUMS.txt` — SHA-256 checksum of the installer (generated in the release workflow)
- `README-FA.txt` — راهنمای فارسی

### Notice
SHA-256 checksums verify the integrity of downloaded files; the provenance attestation proves the file was built by this repository's workflow from the public source. Neither is a security audit. The installer is not code-signed yet; Windows SmartScreen may warn — verify, then choose **More info → Run anyway**. Download Sahne+ only from this repository's Releases page.

Sahne+ is an independent third-party application and is not affiliated with, endorsed by, or sponsored by Kick, KickBot, StreamElements, baha24 or Bonbast. Privacy: [PRIVACY.md](https://github.com/AmirEyZed/sahne-plus/blob/main/PRIVACY.md) · Terms: [TERMS.md](https://github.com/AmirEyZed/sahne-plus/blob/main/TERMS.md) · Security: [SECURITY.md](https://github.com/AmirEyZed/sahne-plus/blob/main/SECURITY.md)
