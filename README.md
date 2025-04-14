# 🌱 Drop Rate Seed Adjuster (7 Days to Die Server Mod)

![Mod Logo](./assets/mod_logo.png)

This server-side mod for **7 Days to Die** (version **1.4b**) adjusts the drop rate of tree seeds when harvesting wood.

---

- [🌱 Drop Rate Seed Adjuster (7 Days to Die Server Mod)](#-drop-rate-seed-adjuster-7-days-to-die-server-mod)
  - [⚠️ Important Notice](#️-important-notice)
  - [📦 Installation](#-installation)
  - [⚙️ Functionality](#️-functionality)
  - [🛠️ Compatibility](#️-compatibility)
  - [📄 Changelog](#-changelog)
  - [🔮 Roadmap](#-roadmap)
  - [📝 License](#-license)

---

## ⚠️ Important Notice

Due to how the game currently handles tree seed drops, **this mod does not function as intended**.  
Tree seed drops appear to be hardcoded into the game engine and are **not currently controllable via XML**.

We're tracking the issue here:  
🔗 [Steam Community Developer Thread](https://steamcommunity.com/app/251570/discussions/5/506200114838160619/)

This repository will remain available for future updates if XML-based control over seed drops becomes supported.

---

## 📦 Installation

**Manual:**

1. Extract the `DropRateSeedAdjuster` folder to `<server-root>/Mods/`  
2. Restart your server

**Using Git (optional):**

```bash
cd <server-root>/Mods/
git clone https://github.com/realAscot/DropRateSeedAdjuster.git
```

_(Note: Git must be installed, e.g. via `sudo apt install git`)_

---

## ⚙️ Functionality

This mod patches the `blocks.xml` file to modify drop probabilities for the following tree seed types:

- 🌳 Oak  
- 🌲 Pine  
- 🌿 Birch

---

## 🛠️ Compatibility

- Tested with game version **1.4b**  
- **Server-side only** – no client installation required  
- Implemented as an **XML patch**

---

## 📄 Changelog

_No entries yet._

---

## 🔮 Roadmap

- Awaiting game engine support for XML-based control over tree seed drops  
- Possible extension to other plant-related drops

---

## 📝 License

This mod is released under the **MIT License**.  
You are free to use, modify, and distribute it.

---
