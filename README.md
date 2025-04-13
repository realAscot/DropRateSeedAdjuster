# Drop Rate Seed Adjuster (7 Days to Die Server Mod)

This lightweight server-side mod for 7 Days to Die (version 1.4b) adjusts the drop rate of tree seeds during wood harvesting.

![Mod Logo](./assets/mod_logo.png)

---

## 📦 Installation

1. Extract the `DropRateSeedAdjuster` folder into your server's `Mods/` directory  
2. Restart your server  

**Alternatively using Git:**  

1. Navigate into your server's `Mods/` folder and run:  
2. 
   ```bash
  
   git clone https://github.com/realAscot/DropRateSeedAdjuster.git
   ```
   (Requires `git` to be installed – e.g., `sudo apt install git`)

---

## ⚙️ Functionality

This mod modifies the game's `blocks.xml` file and adjusts the drop probability for:

- Oak Seeds  
- Pine Seeds  
- Birch Seeds  

You can customize the drop rates by editing the `value` attributes in `Config/blocks.xml`.

---

## 🛠️ Compatibility

- ✅ Tested with version **1.4b**
- ✅ Server-side only – **no client installation required**
- ✅ Compatible with dedicated servers, Docker, and LGSM

---

## 📄 License

This mod is licensed under the **MIT License**.  
You are free to use, modify, and redistribute it.

---