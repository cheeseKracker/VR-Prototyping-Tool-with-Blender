# 🧠 VR Prototyping Toolkit for Blender (UPBGE)

A **plug-and-play Blender project** built on **UPBGE** that enables designers to **rapidly prototype VR experiences** — no need to write interaction logic from scratch.

---

## 🧩 What’s Included?

- 🎮 **`playground.blend`**: A fully functional starter project
- 🕹️ Integrated locomotion (teleport, dash, climbing)
- 🤝 Hand and object interaction logic
- 🖱️ Custom pointer-based UI interaction
- 🌲 Assets: trees, textures, controllers, UI icons
- 🧠 No external scripts needed — all logic is embedded in the file

---

## 🚀 Getting Started

### ✅ Requirements

- [UPBGE 0.3+](https://upbge.org/) with VR support
- [SteamVR](https://store.steampowered.com/steamvr) installed and running
- A supported VR headset (Oculus, Vive, Index, WMR, etc.)
- Windows OS (recommended)

### 📥 Setup Steps

1. **Set SteamVR as your OpenXR Runtime**

    - Open SteamVR  
    - Go to: `Settings` → `Show Advanced Settings`  
    - Under the **Developer** tab, ensure:  
      `Current OpenXR Runtime = SteamVR`

2. **Copy the Controller Config File**

    - Paste the provided `default.py` file into the following path:  
      ```
      UPBGE_INSTALL_FOLDER/3.6/scripts/addons/viewport_vr_preview/configs/
      ```
      ⚠️ Note: `3.6` may vary depending on your UPBGE version.

3. **Open the Blender project**

    - Launch `playground.blend` in UPBGE.

4. **Enable the VR add-on**

    - Go to `Edit` → `Preferences` → `Add-ons`  
    - Search for **VR** and enable **Viewport VR Preview**

5. **Run the Prototype**

    - Start SteamVR and connect your headset  
    - Press `P` in Blender to begin the VR experience

---

## 🎮 Controls Overview

| Action              | Input                        |
|---------------------|------------------------------|
| Grab objects        | Grip button                  |
| Teleport            | Push thumbstick forward      |
| Climb               | Grab object with Climb prop  |
| Interact with menu  | Point + Trigger              |
| Jump                | A button (right controller)  |
| Toggle menu         | Y / B button                 |

---

## 🛠️ Customize or Extend

- Add new objects and assign them logic properties: `Grab`, `Climb`, `Use`
- Replace any material or sounds in `textures/` or `sounds/` folders
- Edit or expand logic from the **Text Editor** inside Blender:
  - File: `Vr Template V2.py`

---

🎉 Thank you

