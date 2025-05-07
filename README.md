# Karmstrot Kernel for OPlus SM8250 Devices

![banner](https://github.com/user-attachments/assets/6acc7ee0-427b-42e9-8964-52ccf72b44df)


![crDroid Build](https://img.shields.io/github/actions/workflow/status/rohanbatrain/Karmstrot-Builds/Karmstrot_CR-OPlus-SM8250-Kernel.yml?label=crDroid)
![LineageOS Build](https://img.shields.io/github/actions/workflow/status/rohanbatrain/Karmstrot-Builds/Karmstrot_LO-OPlus-SM8250-Kernel.yml?label=LineageOS)
![NamelessOS Build](https://img.shields.io/github/actions/workflow/status/rohanbatrain/Karmstrot-Builds/Karmstrot_NO-OPlus-SM8250-Kernel.yml?label=NamelessOS)
![Anomaly-Kernel](https://img.shields.io/github/actions/workflow/status/rohanbatrain/Karmstrot-Builds/Karmstrot_AK-OPlus-SM8250-Kernel.yml?label=Anomaly-Kernel)


---

## 🔍 Overview

**Karmstrot** is a performance-tuned, modular kernel automation suite for **OnePlus SM8250** devices. It provides fully automated GitHub Actions workflows to compile, root (via **KernelSU**), and package the kernel using **AnyKernel3**. Ideal for developers and power users who want streamlined builds across multiple ROMs with minimal manual effort.

---

## 🌟 ROM Support

| Workflow File                          | ROM Name    | Kernel Type     |
| -------------------------------------- | ----------- | ----------------|
| `Karmstrot_CR-OPlus-SM8250-Kernel.yml` | [crDroid](https://github.com/rohanbatrain/Anomaly-Kernel)     | Karmstrot Build |
| `Karmstrot_LO-OPlus-SM8250-Kernel.yml` | [LineageOS](https://github.com/rohanbatrain/android_kernel_oneplus_sm8250)   | Karmstrot Build |
| `Karmstrot_NO-OPlus-SM8250-Kernel.yml` | [Nameless OS](https://github.com/rohanbatrain/kernel_oneplus_sm8250) | Karmstrot Build |
| `Karmstrot_AK-OPlus-SM8250-Kernel.yml` | [Anomaly-Kernel](https://github.com/rohanbatrain/Anomaly-Kernel)     | Karmstrot Build |

---

## ⚙️ Features

* 🛡️ Built-in **KernelSU** support (root without Magisk)
* 💡 YAML-powered **GitHub Actions** automation
* ⚡ Tuned for **performance** and **battery**
* 📦 Packaged using **AnyKernel3** — flash and go!
* 🔗 Based on **AOSP common kernel**
* 🔁 Extensible & modular CI for new ROMs/devices

---

## 🚀 Getting Started

To build your own Karmstrot-based kernel:

1. **Fork** this repository.
2. Navigate to `.github/workflows/` and edit your target YAML file (optional).
3. Go to the **Actions** tab and trigger a build.
4. Once done, download the **flashable ZIP** from the workflow artifacts.

✅ All builds run in the cloud via GitHub Actions — **no local setup** required.

---

## 📱 Target Devices

Karmstrot supports all **SM8250-based OnePlus** devices:

- OnePlus 8
- OnePlus 8 Pro
- OnePlus 8T

---

## 📂 Sources Used

This kernel automation project is a **compiled and integrated work** based on the original efforts of the following repositories:

- https://github.com/AzusaHana/KernelSU_Build_Test  
- https://github.com/jef00/kernel_oneplus_sm8250  
- https://github.com/Nameless-AOSP-OSS/kernel_oneplus_sm8250  
- https://github.com/LineageOS/android_kernel_oneplus_sm8250  
- https://github.com/The-Anomalist/Anomaly-Kernel  
- https://github.com/rsuntk/KernelSU  

---

## 🙌 Credits

All core credit goes to the original developers and maintainers of the above repositories.  
I take **zero credit** for the kernel source or rooting methods themselves — this project simply merges and automates them for easier use.

Special thanks to:

- 🧠 **KernelSU** Team  
- 📦 **AnyKernel3** by osm0sis  
- 🏗️ **GitHub Actions** for cloud automation  
- ❤️ ROM teams for crDroid, LineageOS, Nameless OS

---

## ⚠️ Disclaimer

> This is a **compiled and integrated effort**, not a kernel written from scratch.  
> My contribution lies in **researching**, **merging**, **automating**, and **testing** — assembling the puzzle from open-source pieces, and offering an easy-to-use GitHub Actions pipeline.  
> Full respect and appreciation to the original authors who made this possible. 🙏

---

## 📬 Contact

Have feedback or questions? Open an [Issue](https://github.com/rohanbatrain/Karmstrot-Builds/issues) or reach out via Discussions.

---
