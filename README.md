# Magoogles - Diablo IV Assistant
This software is standalone and does not "hook" into the game in any way. It emulates mouse/keyboard/controller inputs and should be safe.

Includes the following features:
  1. Masterworking Assistant (Will use all of your gold and materials if you let it)
  2. Belial Chest Opener with Boss selection

Upcoming features:
  - Controller support for Xbox and Playstation controllers. (Currently only works when the chest is opened via keyboard)


**The Diablo IV Assistant** automates the process of selecting and opening boss loot chests as well as handling masterworking. It uses OCR (Optical Character Recognition) and mouse automation to detect and click the correct options based on the boss you select.

---

## ⚙️ Features

- Automatically detects the "Modify Reward" chest screen.
- Scrolls through the boss list and selects the boss you specify.
- Clicks "Open" once the desired boss is selected.
- Works with mouse/keyboard input (controller coming soon).
- Supports debug mode to view OCR output and saved images.

---

## 🚀 How to Use

1. **Download the latest release** from the [Releases](https://github.com/magoogle/D4Assistant/releases/tag/Release) tab.
2. **Install** Run the MSI.
3. **Run** Desktop Shortcut for Magoogles - D4 Assistant.
4. On first launch, you'll be prompted to:
   - Set regions for: Modify button, Open button, Scroll arrow, and Boss list.
   - These are saved in `config.json` in the same folder.
5. **Select the boss name** from the dropdown list.
6. Click **Start** to begin the looter process.
7. Click **Stop** to end it at any time.

---

## 📝 Requirements

- Windows 10 or 11 (64-bit)
- .NET 6.0 or higher
- Microsoft Visual C++ Redistributable (x64): [Download Here](https://aka.ms/vs/17/release/vc_redist.x64.exe)
- Screen must be in **windowed mode** (recommended) and game window visible during use

---

## 🧪 Debug Mode

Enable **Debug Mode** to:
- View additional logging in the app
- Save OCR screenshots to `/ocr-debug/` for troubleshooting

---

## 📁 Files and Folders

- `D4Assistant.exe` – Main application
- `config.json` – Stores your saved screen region settings
- `tessdata/` – Folder containing OCR language data (must be included)
- `ocr-debug/` – Stores debug screenshots when enabled

---

## 📜 License

This is **closed-source software**. Redistribution, modification, or reverse engineering is **not permitted**.

See [LICENSE.txt](LICENSE.txt) for full terms.

---
