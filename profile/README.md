# # PhrovaUI (WIP)

### All that was lost, is now part of the music

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
