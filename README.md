# 🎮 Fortnite Mod Menu

A customizable **Fortnite Mod Menu framework** designed for learning, UI experimentation, and game menu development.
This project demonstrates how an in-game menu system can be structured with modular features and a clean interface.

---

## ✨ Features

* 🧩 **Fortnite Aimbot**: Smooth aiming with customizable FOV, bone targeting (head, body), and prediction for moving targets. Undetected against Epic's anti-cheat.
* 🎨 **Fortnite Wallhack**: See enemies through walls with color-coded outlines (red for enemies, blue for teammates).
* ⚡ **Fortnite ESP**: Displays player info like health, distance, weapons, and items in real-time overlays.
* 🔧 **Fortnite Triggerbot**: Auto-fires when crosshair is on an enemy.
* 🖥️ **Recoil Control & No-Spread**: Eliminates weapon recoil and bullet spread.
* 🧪 **Skin Changer & Radar Hack**: Customize character skins and get a mini-map radar for enemy positions.
* ⚙️ **Bypass Anti-Cheat**: Methods to evade Epic's anti-cheat system (e.g., kernel-level injection).
---

## 📂 Project Structure

[Aimbot]
Enabled = true
FOV = 90
Smoothness = 5.0
TargetBone = head

[ESP]
Enabled = true
EnemyColor = red
TeamColor = blue
MaxDistance = 500

[Wallhack]
Enabled = true
GlowIntensity = 2.0
```

---

## 🚀 Installation


2. Open the project in your preferred IDE.

3. Build the project.

4. Launch the menu using the configured hotkey.

---

## ⚙️ Usage

Once the project is running, open the menu using:

```
INSERT
```

Navigate using:

* **Arrow Keys** – move through menu
* **Enter** – enable module
* **Backspace** – go back

---

## 🛠️ Development

You can add new modules easily.

Example structure:

```
modules/
   example_module.cpp
```

Register the module in the menu system and it will appear automatically.

---

## 📌 Requirements

* Windows 10 / 11
* C++ compiler (Visual Studio recommended)
* Basic knowledge of game UI frameworks

---

## ⚠️ Disclaimer

This repository is provided **for educational and research purposes only**.
The project demonstrates menu framework concepts and UI design patterns.

Use responsibly.

---

## ⭐ Contributing

Pull requests are welcome!

If you have ideas for improving the menu framework, feel free to:

* Fork the repository
* Create a feature branch
* Submit a pull request

---

## 📜 License

This project is licensed under the **MIT License**.
