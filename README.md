# Magoogles - Diablo IV Assistant
This software is standalone and does not "hook" into the game in any way. It emulates mouse/keyboard/controller inputs and should be safe.

Includes the following features:
  1. Masterworking Assistant (Will use all of your gold and materials if you let it)
  2. Belial Chest Opener with Specific, Round-Robin, or, Random boss selection
  3. Enchant Assistant (Will use all of your gold if you let it)
  4. Kurast Tribute Automation - When interacting with the Obelisk, it will automatically grab a tribute from inventory, and if you choose, a bargin of your choice
  5. Auto Party Creator (Still in progress) - Monitors your current party, and attempts to invite players that are online automatically
  6. Diablo 4 Monitor - Monitors D4 game, detects disconnects, crashes, etc and automatically restarts game, selects last logged in character, and starts game. (Supports Steam, BNET, and, GamePass)
  7. Pit Opener - Monitors for Pit Obelisk interaction, allows you to choose Pit level, will automatically select level and open pit.
  8. Pit Portal Monitor - Mainly for alt accounts, Monitors for entry portal, and Boss portal. Will automatically interact with portal when detected.
  9. Auto Party Acceptor - Mainly for alts, but its monitors for Return to World State, Teleport to Party Leader, Start Dungeon, Party Votes (Reset Dungeons), and, Difficulty change prompts. Auto accepts them based on player who initiated it using a white list (if enabled).
  10. Pushover Notifications - Many of the modules all have the logging pushed to the notifier also. This means if configued with the Pushover app, you will get Mobile notifications of the assistants actions. Such as masterworking. You can walk away and get notified when its done.
  11. Discord Notifications, same as push over but with Discord webhook support

Things im working on adding:
Paragon/Skill selection


**The Diablo IV Assistant** automates the process of selecting and opening boss loot chests as well as handling masterworking, enchanting and Kurast Tribute selection. It uses OCR (Optical Character Recognition) and mouse automation to detect and click the correct options based on the boss you select.

---

## ⚙️ Features

- Automatically detects the "Modify Reward" chest screen.
- Scrolls through the boss list and selects the boss you specify.
- Clicks "Open" once the desired boss is selected.
- Works with mouse/keyboard/controller.

---

## 🚀 How to Use
(Uninstall previous release first if you have it from Add/Remove Programs)
1. **Requires** C++ 2015-2022 x64 Redistributables: https://aka.ms/vs/17/release/vc_redist.x64.exe
2. **Download the latest release** from the [Releases](https://github.com/magoogle/D4Assistant/releases/tag/Release) tab.
3. **Install** Run the MSI.
4. **Run** Desktop Shortcut for Magoogles - D4 Assistant.
5. **Choose** a module to load.
   - Masterworking
   - Enchanting
   - Belial Chest Opener
   - Kurast Tribute Selector/Opener
7. Click **Start** to begin
8. Pressing "P" will end it at any time.

---

## 📝 Requirements

- Windows 10 or 11 (64-bit)
- .NET 6.0 or higher
- Microsoft Visual C++ Redistributable (x64): [Download Here](https://aka.ms/vs/17/release/vc_redist.x64.exe)

---

## 🧪 Debug Mode

Use **Debug Tools** to:
- Have standalone tools to check/verify click points/OCR Scanning regions/Pixel colors for manual config file changes
- Use the built in Overlay option to edit config graphically.

---

## 📁 Files and Folders

- `D4Assistant.exe` – Main application
- `config.json` – Stores your saved screen region settings
- `tessdata/` – Folder containing OCR language data (must be included)

---

## 📜 License

This is **closed-source software**. Redistribution, modification, or reverse engineering is **not permitted**.

See [LICENSE.txt](LICENSE.txt) for full terms.

---
