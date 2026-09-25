# # PhrovaUI (WIP)

### All that was lost, is now part of the music

<table>
  <tr>
    <td valign="top" style="border: none;">
      <h3 style="margin-top: 0;">Refined Android Experience</h3>
      <p><b>PhrovaUI</b> is a refined interface layer based on <b>AviumUI</b></p>
    </td>
    <td valign="top" width="130" style="border: none; text-align: right;">
      <img src="https://github.com/user-attachments/assets/ee98ce1c-8d8a-4216-aa41-f4b42fea7329" alt="PhrovaUI Logo" width="120" style="display: block; margin-left: auto;">
    </td>
  </tr>
</table>


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
