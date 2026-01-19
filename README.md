# Flashforge AD5X PrusaSlicer Settings

Konfigurační balíček PrusaSlicer pro 3D tiskárnu **Flashforge AD5X** s nainstalovaným **[ZMOD](https://github.com/ghzserg/zmod)**.

## 📋 Obsah

Tento repozitář obsahuje kompletní konfiguraci pro tisk na tiskárně Flashforge AD5X s ZMOD modulem pro **PrusaSlicer** a **OrcaSlicer**.

### Co je v souboru `AD5X_PrusaSlicer_config_bundle.ini` (PrusaSlicer)

- **Print Profiles** - Profily pro tisk s různými tloušťkami vrstev (0.08mm až 0.30mm)
- **Filament Profiles** - Nastavení pro různé typy a značky filamentu
- **Printer Profiles** - Konfigurace tiskárny s různými velikostmi trysek (0.4mm, 0.6mm)
- **Physical Printer Settings** - Konkrétní nastavení pro AD5X

### OrcaSlicer Konfigurace

V adresáři `orcaslicer/` jsou k dispozici konfigurační soubory pro OrcaSlicer:
- **filament/** - Profily filamentu v JSON formátu
- **process/** - Profily tisku (process profiles) v JSON formátu

## ⚠️ Požadavky

- Flashforge AD5X s nainstalovaným **[ZMOD](https://github.com/ghzserg/zmod)** modulem
- povoleny plugin [Bambufy](https://github.com/function3d/bambufy)
- PrusaSlicer 2.9.4+ 

## 🚀 Instalace

### Instalace PrusaSlicer

1. Stáhněte soubor `AD5X_PrusaSlicer_config_bundle.ini`
2. Otevřete PrusaSlicer
3. Přejděte do nabídky **Soubor → Importovat konfiguraci**
4. Vyberte stažený soubor `AD5X_PrusaSlicer_config_bundle.ini`
5. Potvrďte import a restartujte PrusaSlicer

### Instalace OrcaSlicer

1. Zkopírujte soubory z adresáře `orcaslicer/filament/` do konfiguračního adresáře OrcaSlicer (obvykle `~/.config/orca-slicer/filament/`)
2. Zkopírujte soubory z adresáře `orcaslicer/process/` do konfiguračního adresáře OrcaSlicer (obvykle `~/.config/orca-slicer/process/`)
3. Restartujte OrcaSlicer```

## 📝 Technické detaily

- **PrusaSlicer verze:** 2.9.4+
- **Tiskárna:** Flashforge AD5X s nainstalovaným ZMOD (https://github.com/ghzserg/zmod)
- **Poslední aktualizace:** 2026-01-19

## 📋 Profily

### Print Profiles (PrusaSlicer)
- **0.08 FINE@04** - Vysoká přesnost s 0.4mm tryskou
- **0.08 NORMAL@04** - Normální režim s 0.4mm tryskou
- **0.10 DETAIL@04** - Detail s 0.4mm tryskou
- **0.10 DETAIL FAST@04** - Rychlý detail s 0.4mm tryskou
- **0.12 NORMAL@04** - Standardní kvalita s 0.4mm tryskou
- **0.15 QUALITY@04** - Kvalita s 0.4mm tryskou
- **0.15 STRUCTURAL@04** - Strukturální s 0.4mm tryskou
- **0.2 NORMAL@04** - Rychlý tisk s 0.4mm tryskou
- **0.2 NORMAL@06** - Rychlý tisk s 0.6mm tryskou
- **0.20 FINE SLOW@04** - Jemný pomalý tisk s 0.4mm tryskou
- **0.20 NORMAL@04** - Normální tisk s 0.4mm tryskou
- **0.20 NORMAL@06** - Normální tisk s 0.6mm tryskou
- **0.20 SPEED@04** - Vysokorychlostní tisk s 0.4mm tryskou
- **0.20 STRUCTURAL@04** - Strukturální tisk s 0.4mm tryskou
- **0.20mm BALANCED@0.4** - Vyrovnaný tisk s 0.4mm tryskou
- **0.28mm DRAFT@0.4** - Koncept s 0.4mm tryskou
- **0.30 DRAFT@04** - Koncept s 0.4mm tryskou

### Process Profiles (OrcaSlicer)
OrcaSlicer profily pro tisk dostupné v `orcaslicer/process/` s podobným pojmenováním jako PrusaSlicer profily.

### Filament Profiles
Konfigurované teploty a parametry pro:
- **PLA** - ProLab PLA (MatteGrey, Red, Transparent, Yellow)
- **PETG** - Aurapol PETG @ Natural, ProLab PETG @ Black
- **ASA** - Prusament ASA @ Sapphire Blue
- **TPU** - ProLab TPU @ White
- **Speciální materiály** - Aurapol Marble, Eryone Wood
- **Premium PLA** - Prusament PLA @ Lipstick Red, Prusament PLA @ Royal Blue

## 🔧 Tipy pro tisk

- Vyberte vhodný profil podle požadované kvality a tiskového času
- Přizpůsobte teploty extrudéru dle používaného filamentu
- Testujte s malou součástí při prvním použití profilu

## 📞 Kontakt

Pro problémy nebo návrhy na vylepšení vytvořte **Issue** v tomto repozitáři.

## 📄 Licence

Tyto nastavení jsou volně dostupná pro osobní i komerční použití.

---

**Poznámka:** Tato nastavení byla vytvořena a testována na Flashforge AD5X. Výsledky se mohou lišit v závislosti na stavu tiskárny a kvalitě a druhu filamentu.
