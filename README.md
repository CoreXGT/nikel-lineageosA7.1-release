# LineageOS 14.1 — Xiaomi Redmi Note 4 MTK (nikel, MT6797)
 
Distribution repo for custom-built LineageOS 14.1 (Android 7.1.2) for the Xiaomi Redmi Note 4 MTK `nikel`.
 
This repo only contains **built binaries** and release notes.
 
## Downloads
Releases are published via **GitHub Releases**.
 
See the **Releases** tab for:
- `lineage-14.1-YYYYMMDD-UNOFFICIAL-nikel.zip`
- `boot.img`, `recovery.img`
 
MD5 checksums for each file are listed in the release notes.
 
## Sources / dev
- Device tree: https://github.com/CoreXGT/android_device_xiaomi-nikel-lineage-14.1
- Vendor blobs: https://github.com/CoreXGT/android_vendor_xiaomi_nikel
- Fixes documented in: `BUGFIXES.md` (in the device tree)
 
## Notes
- Voice calls do not work on this build (C2K modem MD3 crash) — use VoIP apps.
- Rear camera tuning is based on IMX258 data (see camera/3A notes in BUGFIXES.md).
- **New in this build:** zRAM swap (1 GB, lzo) enabled by default.
- if you want Google Applications install **OpenGApps**
 
## Disclaimer
This ROM contains proprietary MediaTek/Xiaomi blobs. Use at your own risk. Flashing may cause data loss or device malfunction. This project is not affiliated with Xiaomi or LineageOS.
