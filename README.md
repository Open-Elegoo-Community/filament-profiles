# 🎛️ OrcaSlicer Filament Profile Repository

This repository contains a structured collection of **filament**, **machine**, and **process** profiles for use with [OrcaSlicer](https://github.com/SoftFever/OrcaSlicer). These profiles are intended to streamline the setup of slicer configurations for various materials and printer setups.

---

## 📁 Directory Structure

The repository is organized into three top-level directories:

### `filament/`
Contains custom filament profiles for different materials and brands.

- Each filament profile includes **two files**:
  - `*.json` — the main profile configuration
  - `*.info` — a metadata file for the json 

> 📝 **Important:** Both files must be copied together to be recognized by OrcaSlicer.

### `machine/`
Contains machine profiles for various 3D printers, defining bed size, kinematics, and firmware configurations.

### `process/`
Contains print process profiles defining speeds, layer heights, temperatures, retractions, and other print settings. These are printer-agnostic and meant to be paired with a filament + machine profile.

---

## 🛠️ How to Use These Profiles

1. **Find your desired filament, machine, and process profiles** in their respective directories.
2. **Copy the relevant files** into your local OrcaSlicer configuration folders:

### 📂 OrcaSlicer Config Directory (Default Paths)

#### Windows:
C:\Users<YourUsername>\AppData\Roaming\OrcaSlicer

#### macOS:
~/Library/Application Support/OrcaSlicer


### 🗃️ Subfolders:

| Profile Type | Destination Folder                       |
|--------------|-------------------------------------------|
| Filament     | `.../OrcaSlicer/filaments/`              |
| Machine      | `.../OrcaSlicer/printers/`               |
| Process      | `.../OrcaSlicer/print/`                  |

> ⚠️ **Be sure to restart OrcaSlicer after copying the files** to make them appear in the interface.

---

## ✅ Example: Adding a New PETG Filament

1. Copy both files from:

  filament/IEMAI/`IEMEI matte green.json`

  filament/IEMAI/`IEMAI matte green.info`

3. Paste them into:    C:\Users\<YourName>\AppData\Roaming\OrcaSlicer\filaments\

4. Open OrcaSlicer → Choose `IEMAI matte green` from the Filament dropdown.

---

## 📬 Contributions

Feel free to open issues or submit pull requests if you want to add or improve a profile!

---

## 📜 License

This repository is open-source under the [MIT License](LICENSE).


