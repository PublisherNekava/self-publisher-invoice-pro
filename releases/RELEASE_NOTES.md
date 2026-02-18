# 📋 Release Notes

## v1.0-beta (Februar 2026)

**🎉 Erste Beta-Version!**

### ✨ Features

- ✅ KDP Excel-Import mit automatischer Verarbeitung
- ✅ Steuerlich korrekte Rechnungserstellung (DE/AT)
- ✅ Reverse-Charge für EU-Marktplätze (§13b UStG)
- ✅ §3a-Behandlung für Drittländer (UK, US, CA, AU, JP)
- ✅ Separate Positionen: KENP, Taschenbuch, eBooks
- ✅ PDF-Export
- ✅ Excel-Export
- ✅ Konfigurierbare Rechnungsnummern
- ✅ Unterstützung für alle Rechtsformen
- ✅ Disclaimer-System (Popup, Fußzeile, Info-Tab)
- ✅ Offline-Nutzung (keine Datenübertragung)

### 🐛 Bekannte Probleme

- ⚠️ Windows SmartScreen-Warnung beim ersten Start (normal, da nicht signiert)
- ⚠️ Nur Windows 10/11 unterstützt
- ⚠️ .NET Framework 4.7.2+ erforderlich

### 📥 Download

[SelfPublisherInvoicePro-v1.0-beta.zip](https://github.com/PublisherNekava/self-publisher-invoice-pro/releases/tag/v1.0-beta)

## Geplante Updates

### v1.1 (Q2 2026)

- 📋 Steuerberater-Checkliste
- 🌐 Englische Sprachversion
- 📊 Erweiterte Reporting-Funktionen
- 🔧 Bug-Fixes aus Beta-Feedback

### v1.2 (Q3 2026)

- 🎨 Anpassbare PDF-Layouts
- 📧 Email-Integration
- ☁️ Optionale Cloud-Sync
- 💾 Backup-Funktionen

### v2.0 (Q4 2026)

- 🍎 macOS-Version
- 💰 Freemium-Modell (3 Rechnungen/Monat kostenlos)
- 🔌 Plugin-System
- 🌍 Weitere Länder

---

**Feedback? Bugs? Ideen?**

📧 [info@nekava.eu]  
🐛 [GitHub Issues](https://github.com/PublisherNekava/self-publisher-invoice-pro/issues)
```

---

## 📝 **SCHRITT 7: LICENSE DATEI**

**Erstelle `LICENSE`:**
```
PROPRIETÄRE SOFTWARE-LIZENZ

Copyright © 2026 PublisherNekava. Alle Rechte vorbehalten.

Self-Publisher Invoice Pro ("die Software") ist urheberrechtlich geschützte,
proprietäre Software.

BETA-TESTER-LIZENZ:

Beta-Tester erhalten das Recht zur zeitlich unbegrenzten, nicht-exklusiven
Nutzung der Software für private und gewerbliche Zwecke.

EINSCHRÄNKUNGEN:

Die Software darf NICHT:
- Weiterverbreitet werden
- Verkauft werden
- Vermietet werden
- Modifiziert werden
- Reverse-engineered werden
- Dekompiliert werden

HAFTUNGSAUSSCHLUSS:

DIE SOFTWARE WIRD "WIE BESEHEN" BEREITGESTELLT, OHNE JEGLICHE AUSDRÜCKLICHE
ODER STILLSCHWEIGENDE GEWÄHRLEISTUNG. DER AUTOR ÜBERNIMMT KEINE HAFTUNG FÜR
SCHÄDEN JEGLICHER ART, DIE DURCH DIE NUTZUNG DER SOFTWARE ENTSTEHEN.

Für vollständigen Disclaimer siehe: docs/DISCLAIMER.md
```

---

## 📝 **SCHRITT 8: .gitignore DATEI**

**Erstelle `.gitignore`:**
```
# Python
__pycache__/
*.py[cod]
*$py.class
*.so
.Python
build/
develop-eggs/
dist/
downloads/
eggs/
.eggs/
lib/
lib64/
parts/
sdist/
var/
wheels/
*.egg-info/
.installed.cfg
*.egg

# Virtual Environment
venv/
ENV/
env/

# IDE
.vscode/
.idea/
*.swp
*.swo
*~

# OS
.DS_Store
Thumbs.db

# Compiled executables
*.exe
*.dll
*.pyd

# Settings & Data
*.json
!package.json
*.xlsx
*.pdf
*.log

# Releases
*.zip
releases/*.zip

# Secrets
.env
secrets.txt
credentials.json
