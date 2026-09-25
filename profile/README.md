# PhrovaUI (WIP)

<img width="1783" height="592" alt="image_70bc1a5d" src="https://github.com/user-attachments/assets/ed86a23e-f284-4f77-ac36-811b24e7ebb4" />

### All that was lost, is now part of the music

### Refined Android Experience

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
