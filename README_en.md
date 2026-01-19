# Flashforge AD5X PrusaSlicer Settings

Configuration package for PrusaSlicer for the **Flashforge AD5X** 3D printer with **[ZMOD](https://github.com/ghzserg/zmod)** module installed.

## 📋 Contents

This repository contains a complete configuration for printing on the Flashforge AD5X printer with ZMOD module using **PrusaSlicer** and **OrcaSlicer** software.

### What's in `AD5X_PrusaSlicer_config_bundle.ini` (PrusaSlicer)

- **Print Profiles** - Print profiles with various layer heights (0.08mm to 0.30mm)
- **Filament Profiles** - Settings for different filament types and brands
- **Printer Profiles** - Printer configuration with different nozzle sizes (0.4mm, 0.6mm)
- **Physical Printer Settings** - Specific settings for AD5X

### OrcaSlicer Configuration

Configuration files for OrcaSlicer are available in the `orcaslicer/` directory:
- **filament/** - Filament profiles in JSON format
- **process/** - Process profiles in JSON format

## ⚠️ Requirements

- Flashforge AD5X with **[ZMOD](https://github.com/ghzserg/zmod)** module installed
- enabled [Bambufy](https://github.com/function3d/bambufy) plugin
- PrusaSlicer 2.9.4+ 

## 🚀 Installation

### PrusaSlicer Installation

1. Download the `AD5X_PrusaSlicer_config_bundle.ini` file
2. Open PrusaSlicer
3. Go to menu **File → Import Configuration**
4. Select the downloaded `AD5X_PrusaSlicer_config_bundle.ini` file
5. Confirm import and restart PrusaSlicer

### OrcaSlicer Installation

1. Copy files from `orcaslicer/filament/` directory to OrcaSlicer configuration directory (usually `~/.config/orca-slicer/filament/`)
2. Copy files from `orcaslicer/process/` directory to OrcaSlicer configuration directory (usually `~/.config/orca-slicer/process/`)
3. Restart OrcaSlicer


## 📝 Technical Details

- **PrusaSlicer Version:** 2.9.4+ 
- **Printer:** Flashforge AD5X with ZMOD installed (https://github.com/ghzserg/zmod)
- **Last Updated:** 2026-01-19

## 📋 Profiles

### Print Profiles (PrusaSlicer)
- **0.08 FINE@04** - High precision with 0.4mm nozzle
- **0.08 NORMAL@04** - Normal mode with 0.4mm nozzle
- **0.10 DETAIL@04** - Detail with 0.4mm nozzle
- **0.10 DETAIL FAST@04** - Fast detail with 0.4mm nozzle
- **0.12 NORMAL@04** - Standard quality with 0.4mm nozzle
- **0.15 QUALITY@04** - Quality with 0.4mm nozzle
- **0.15 STRUCTURAL@04** - Structural with 0.4mm nozzle
- **0.2 NORMAL@04** - Fast print with 0.4mm nozzle
- **0.2 NORMAL@06** - Fast print with 0.6mm nozzle
- **0.20 FINE SLOW@04** - Fine slow print with 0.4mm nozzle
- **0.20 NORMAL@04** - Normal print with 0.4mm nozzle
- **0.20 NORMAL@06** - Normal print with 0.6mm nozzle
- **0.20 SPEED@04** - High-speed print with 0.4mm nozzle
- **0.20 STRUCTURAL@04** - Structural print with 0.4mm nozzle
- **0.20mm BALANCED@0.4** - Balanced print with 0.4mm nozzle
- **0.28mm DRAFT@0.4** - Draft with 0.4mm nozzle
- **0.30 DRAFT@04** - Draft with 0.4mm nozzle

### Process Profiles (OrcaSlicer)
OrcaSlicer print profiles available in `orcaslicer/process/` with similar naming as PrusaSlicer profiles.

### Filament Profiles
Configured temperatures and parameters for:
- **PLA** - ProLab PLA (MatteGrey, Red, Transparent, Yellow)
- **PETG** - Aurapol PETG @ Natural, ProLab PETG @ Black
- **ASA** - Prusament ASA @ Sapphire Blue
- **TPU** - ProLab TPU @ White
- **Special materials** - Aurapol Marble, Eryone Wood
- **Premium PLA** - Prusament PLA @ Lipstick Red, Prusament PLA @ Royal Blue

## 🔧 Printing Tips

- Select an appropriate profile based on desired quality and print time
- Adjust extruder temperatures according to the filament you're using
- Test with a small part when using a profile for the first time

## 📞 Contact

For issues or suggestions for improvement, create an **Issue** in this repository.

## 📄 License

These settings are freely available for personal and commercial use.

---

**Note:** These settings were created and tested on the Flashforge AD5X. Results may vary depending on the condition of the printer and the quality and type of filament.
