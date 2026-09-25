# PhrovaUI (WIP)

### All that was lost, is now part of the music

<!-- <img width="1254" height="1254" alt="PhrovaUI Logo" src="https://github.com/user-attachments/assets/ee98ce1c-8d8a-4216-aa41-f4b42fea7329" />
-->

<div style="display: flex; align-items: center; justify-content: space-between; gap: 0px;">
  <div style="flex: 1;">
    <h3>Refined Android Experience</h3>
    <p><b>PhrovaUI</b> is a refined interface layer based on <b>AviumUI</b></p>
  </div>
  <div style="flex: 1; text-align: right;">
    <img src="[YOUR_IMAGE_URL_HERE](https://github.com/user-attachments/assets/ee98ce1c-8d8a-4216-aa41-f4b42fea7329)" alt="PhrovaUI Logo" style="max-height: 150px; width: auto; display: block; margin-left: auto;">
  </div>
</div>

**PhrovaUI** is a refined interface layer based on **AviumUI**

## ✨ Design Principles

- **Essence Preservation**: Maintain Android's core integrity.
- **Fluid Harmonics**: Optimize rendering frequencies for smoothness.
- **Purpose-Driven Enhancements**: Add meaningful features respecting battery and resources.

## 📥 Getting Started

Initialize your local compilation environment using the Android `repo` utility:

```bash
repo init -u https://github.com -b main
repo sync -c -j\$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

## 🛠️ Build Configuration Flags

Declare the following flags inside your device's makefile:

```makefile
PHROVA_MAINTAINER := yourName
WITH_GMS := true
IS_OFFICIAL := false
```

## 🤝 Community & Links (WIP)

- **Website:** phrova.vercel.app
- **Telegram Group:** t.me/PhrovaGroup 
- **Discord Server:** discord.gg/PhrovaUI
