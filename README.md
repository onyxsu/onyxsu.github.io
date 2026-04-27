# Konoha Kernel for POCO F7 (onyx)

> A modern custom GKI kernel for **POCO F7 / onyx** with **KernelSU Next** and **SUSFS** support.  
> Built for performance, stability, root flexibility, and daily-driver reliability.

---

## ✨ Features

- ✅ **KernelSU Next** integrated
- ✅ **SUSFS** support
- ✅ Based on Android **6.6 GKI**
- ✅ Optimized for **POCO F7 (onyx)**
- ✅ Balanced performance profile
- ✅ Improved responsiveness
- ✅ Better thermal behavior
- ✅ Daily-driver stable
- ✅ AnyKernel3 flashable package
- ✅ Compatible with rooted power users

---

## 📱 Device Support

| Device | Codename | Status |
|--------|----------|--------|
| POCO F7 | onyx | Supported |

---

## ⚙️ Included Technologies

### KernelSU Next
Modern kernel-based root solution with better integration than traditional userspace root methods.

### SUSFS
Advanced filesystem hiding / stealth enhancements for supported environments.

### GKI Base
Uses modern Android Generic Kernel Image architecture for better compatibility.

---

## 📦 Release Package

Flashable ZIP includes:

- `Image.gz`
- AnyKernel3 installer
- Auto patching tools
- Boot image repack support

---

## 🚀 Installation

### Method 1 — AnyKernel ZIP (Recommended)

1. Download latest release ZIP
2. Boot to custom recovery or use kernel flashing tool
3. Flash ZIP
4. Reboot

### Method 2 — Manual boot.img Patch

1. Extract stock `boot.img`
2. Replace kernel with included `Image.gz`
3. Repack boot image
4. Flash using fastboot

---

## 💻 Fastboot Flash Example

```bash
fastboot flash boot boot.img
fastboot reboot
