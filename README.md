# Flashforge AD5X PrusaSlicer Settings

Konfigurační balíček PrusaSlicer pro 3D tiskárnu **Flashforge AD5X**.

## 📋 Obsah

Tento repozitář obsahuje kompletní konfiguraci pro tisk na tiskárně Flashforge AD5X pomocí software PrusaSlicer.

### Co je v souboru `PrusaSlicer_config_bundle.ini`

- **Print Profiles** - Profily pro tisk s různými tloušťkami vrstev (0.08mm, 0.12mm, 0.2mm)
- **Filament Profiles** - Nastavení pro různé typy a značky filamentu:
  - Aurapol Marble
  - Eryone Wood
  - ProLab PETG
  - ProLab PLA (více barev)
- **Printer Profiles** - Konfigurace tiskárny s různými velikostmi trysek (0.4mm, 0.6mm)
- **Physical Printer Settings** - Konkrétní nastavení pro AD5X

## 🚀 Instalace

### Postup:

1. Stáhněte soubor `PrusaSlicer_config_bundle.ini`
2. Otevřete PrusaSlicer
3. Přejděte do nabídky **Soubor → Importovat konfiguraci**
4. Vyberte stažený soubor `PrusaSlicer_config_bundle.ini`
5. Potvrďte import a restartujte PrusaSlicer

### Alternativa - Ruční instalace:

Soubor `PrusaSlicer_config_bundle.ini` zkopírujte do adresáře s konfigurací PrusaSlicer:

**macOS:**
```
~/Library/Application Support/PrusaSlicer
```

**Windows:**
```
%AppData%\PrusaSlicer
```

**Linux:**
```
~/.local/share/PrusaSlicer
```

## 📝 Technické detaily

- **PrusaSlicer verze:** 2.9.4+
- **Tiskárna:** Flashforge AD5X
- **Poslední aktualizace:** 2025-12-04

## 📋 Profily

### Print Profiles
- **0.08 NORMAL@04** - Vysoká přesnost s 0.4mm tryskou
- **0.12 NORMAL@04** - Standardní kvalita s 0.4mm tryskou
- **0.2 NORMAL@04** - Rychlý tisk s 0.4mm tryskou
- **0.2 NORMAL@06** - Rychlý tisk s 0.6mm tryskou

### Filament Profiles
Konfigurované teploty a parametry pro:
- PLA
- PETG
- Speciální materiály (Wood, Marble)

## 🔧 Tipy pro tisk

- Vyberte vhodný profil podle požadované kvality a tiskového času
- Přizpůsobte teploty extrudéru dle používaného filamentu
- Testujte s malou součástí při prvním použití profilu

## 📞 Kontakt

Pro problémy nebo návrhy na vylepšení vytvořte **Issue** v tomto repozitáři.

## 📄 Licence

Tyto nastavení jsou volně dostupná pro osobní i komerční použití.

---

**Poznámka:** Tato nastavení byla vytvořena a testována na Flashforge AD5X. Výsledky se mohou lišit v závislosti na stavu tiskárny a kvalitě filamentu.
