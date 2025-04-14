# 🌱 Drop Rate Seed Adjuster (7 Days to Die Server Mod)

![Mod-Logo](./assets/mod_logo.png)

Diese Servermod für **7 Days to Die** (Version **1.4b**) passt die Drop-Rate von Baum-Samen beim Holzabbau an.

---

- [🌱 Drop Rate Seed Adjuster (7 Days to Die Server Mod)](#-drop-rate-seed-adjuster-7-days-to-die-server-mod)
  - [⚠️ Wichtiger Hinweis](#️-wichtiger-hinweis)
  - [📦 Installation](#-installation)
  - [⚙️ Funktion](#️-funktion)
  - [🛠️ Kompatibilität](#️-kompatibilität)
  - [📄 Changelog](#-changelog)
  - [🔮 Roadmap](#-roadmap)
  - [📝 Lizenz](#-lizenz)

---

## ⚠️ Wichtiger Hinweis

Aufgrund der aktuellen Handhabung von Baum-Samendrops im Spiel **funktioniert dieses Mod derzeit nicht wie vorgesehen**.  
Die Drop-Raten scheinen hart in der Spiel-Engine codiert zu sein und sind momentan **nicht über XML steuerbar**.

Wir verfolgen das Thema hier:  
🔗 [Steam-Community-Thread der Entwickler](https://steamcommunity.com/app/251570/discussions/5/506200114838160619/)

Das Repository bleibt online für zukünftige Updates – falls die Spielmechanik XML-basierte Steuerung zulässt, wird die Mod entsprechend angepasst.

---

## 📦 Installation

**Manuell:**

1. Ordner `DropRateSeedAdjuster` nach `<server-root>/Mods/` entpacken  
2. Server neu starten

**Alternativ mit Git:**

```bash
cd <server-root>/Mods/
git clone https://github.com/realAscot/DropRateSeedAdjuster.git
```

_(Hinweis: Git muss installiert sein, z.B. via `sudo apt install git`)_

---

## ⚙️ Funktion

Diese Mod editiert die Datei `blocks.xml` und setzt angepasste Drop-Wahrscheinlichkeiten für folgende Baumarten:

- 🌳 Eiche  
- 🌲 Kiefer  
- 🌿 Birke

---

## 🛠️ Kompatibilität

- Getestet mit Spielversion **1.4b**  
- **Rein serverseitig** – keine Client-Modifikation nötig  
- Implementiert als **XML-Patch**

---

## 📄 Changelog

_Keine Einträge vorhanden._

---

## 🔮 Roadmap

- Warten auf Engine-Support für XML-gesteuerte Samendrops  
- Mögliche Erweiterung auf andere pflanzliche Drops

---

## 📝 Lizenz

Veröffentlicht unter der **MIT-Lizenz**.  
Du darfst diese Mod frei verwenden, verändern und weitergeben.

---
