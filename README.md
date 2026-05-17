# Android Device Manifest (klee)

This repository contains a **local manifest configuration** used for building Android-based ROMs for the Xiaomi POCO X8 Pro (codename: `klee`).

It defines all required device-specific repositories such as:
- Device tree
- Kernel source
- Vendor blobs
- Hardware abstraction layers (HALs)
- MediaTek and Xiaomi platform components

---

## 🚀 How to sync

After placing the manifest in:
```bash
.repo/local_manifests/klee.xml

Run:

```bash
repo sync -j$(nproc --all)

