# Flashforge AD5X PrusaSlicer Settings

Configuration package for PrusaSlicer for the **Flashforge AD5X** 3D printer with **[ZMOD](https://github.com/ghzserg/zmod)** module installed.

## 📋 Contents

This repository contains a complete configuration for printing on the Flashforge AD5X printer with ZMOD module using PrusaSlicer software.

### What's in `AD5X_PrusaSlicer_config_bundle.ini`

- **Print Profiles** - Print profiles with various layer heights (0.08mm, 0.12mm, 0.2mm)
- **Filament Profiles** - Settings for different filament types and brands:
  - Aurapol Marble
  - Eryone Wood
  - ProLab PETG
  - ProLab PLA (multiple colors)
- **Printer Profiles** - Printer configuration with different nozzle sizes (0.4mm, 0.6mm)
- **Physical Printer Settings** - Specific settings for AD5X

## ⚠️ Requirements

- Flashforge AD5X with **[ZMOD](https://github.com/ghzserg/zmod)** module installed
- PrusaSlicer 2.9.4+ 

## 🚀 Installation

### Steps:

1. Download the `AD5X_PrusaSlicer_config_bundle.ini` file
2. Open PrusaSlicer
3. Go to menu **File → Import Configuration**
4. Select the downloaded `AD5X_PrusaSlicer_config_bundle.ini` file
5. Confirm import and restart PrusaSlicer


## 📝 Technical Details

- **PrusaSlicer Version:** 2.9.4+ (fork [pantata/PrusaSlicer](https://github.com/pantata/PrusaSlicer.git), branch `MoonrakerWebUI`)
- **Printer:** Flashforge AD5X with ZMOD installed (https://github.com/ghzserg/zmod)
- **Last Updated:** 2025-12-04

## 📋 Profiles

### Print Profiles
- **0.08 NORMAL@04** - High precision with 0.4mm nozzle
- **0.12 NORMAL@04** - Standard quality with 0.4mm nozzle
- **0.2 NORMAL@04** - Fast print with 0.4mm nozzle
- **0.2 NORMAL@06** - Fast print with 0.6mm nozzle

### Filament Profiles
Configured temperatures and parameters for:
- PLA
- PETG
- Special materials (Wood, Marble)

## 🔧 Printing Tips

- Select an appropriate profile based on desired quality and print time
- Adjust extruder temperatures according to the filament you're using
- Test with a small part when using a profile for the first time

## 📞 Contact

For issues or suggestions for improvement, create an **Issue** in this repository.

## 📄 License

These settings are freely available for personal and commercial use.

---

**Note:** These settings were created and tested on Flashforge AD5X. Results may vary depending on printer condition and filament quality.
