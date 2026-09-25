# # PhrovaUI (WIP)

### All that was lost, is now part of the music

<div style="display: flex; align-items: center; justify-content: space-between; gap: 0px; flex-wrap: wrap;">
  <div style="flex: 1; min-width: 250px; padding-right: 10px;">
    <h3 style="margin-top: 0;">Refined Android Experience</h3>
    <p style="margin-bottom: 0;"><b>PhrovaUI</b> is a refined interface layer based on <b>AviumUI</b></p>
  </div>
  <div style="flex: 0 0 auto; text-align: right;">
    <img src="https://github.com/user-attachments/assets/ee98ce1c-8d8a-4216-aa41-f4b42fea7329" alt="PhrovaUI Logo" width="120" style="display: block; margin-left: auto;">
  </div>
</div>


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
