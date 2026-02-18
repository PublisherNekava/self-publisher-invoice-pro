# 📥 Installation & Setup

## Systemanforderungen

Bevor du startest, stelle sicher dass du hast:

- ✅ **Windows 10 oder 11** (64-bit)
- ✅ **.NET Framework 4.7.2** oder höher
- ✅ **~50 MB** freier Speicherplatz
- ✅ **KDP-Zugang** mit Export-Berechtigung

### .NET Framework prüfen

Öffne `cmd` und gib ein:
```
reg query "HKLM\SOFTWARE\Microsoft\NET Framework Setup\NDP\v4\Full" /v Release
```

Wenn die Zahl ≥ 461808 ist, hast du mindestens .NET 4.7.2 ✅

Falls nicht: [Download .NET Framework](https://dotnet.microsoft.com/download/dotnet-framework)

---

## Download

1. Gehe zu [Releases](https://github.com/PublisherNekava/self-publisher-invoice-pro/releases)
2. Lade die neueste Version herunter: `SelfPublisherInvoicePro-v1.0-beta.zip`
3. Speichere die Datei in einem Ordner deiner Wahl

---

## Installation

### Schritt 1: Entpacken

1. **Rechtsklick** auf die ZIP-Datei
2. **"Alle extrahieren..."** auswählen
3. Zielordner wählen (z.B. `C:\Programme\SelfPublisherInvoicePro`)
4. **"Extrahieren"** klicken

### Schritt 2: Windows SmartScreen

Beim ersten Start kann Windows SmartScreen warnen:
```
"Windows hat den PC geschützt"
```

Das ist normal für neue Software. Klicke:

1. **"Weitere Informationen"**
2. **"Trotzdem ausführen"**

**Warum diese Warnung?**
- Die Software ist noch nicht bei Microsoft signiert (kostet ~€300/Jahr)
- Das kommt in der finalen Version

---

## Erste Schritte

### 1. Software starten

Doppelklick auf `SelfPublisherInvoicePro.exe`

### 2. Disclaimer akzeptieren

Beim ersten Start erscheint ein **Disclaimer-Popup**:

⚠️ **Bitte lies ihn sorgfältig!**

Du musst bestätigen:
- ✅ Du verstehst, dass keine Steuerberatung erfolgt
- ✅ Du wirst Rechnungen von Steuerberater prüfen lassen
- ✅ Nutzung auf eigenes Risiko

### 3. Einstellungen konfigurieren

Gehe zum Tab **"Einstellungen"** und fülle aus:

#### Unternehmensdaten:
- Name
- Adresse
- Steuernummer / UID
- Bankverbindung

#### Land/Rechtsraum:
- 🇩🇪 Deutschland
- 🇦🇹 Österreich
- 🔄 Automatisch

⚠️ **WICHTIG:** Besprich mit deinem Steuerberater, welche Einstellung für dich korrekt ist!

#### Rechnungsnummern:
- Präfix (z.B. "RE", "RG", "INV")
- Jahr (aktuell, manuell, ohne)
- Ziffern (4-6 Stellen)

**Beispiel:** `RE20260001`

Klicke **"Einstellungen speichern"**

---

## KDP-Daten vorbereiten

### Schritt 1: Amazon KDP öffnen

1. Gehe zu [kdp.amazon.com](https://kdp.amazon.com)
2. Klicke auf **"Berichte"** → **"Zahlungen"**

### Schritt 2: Monat auswählen

1. Wähle den gewünschten **Monat** aus
2. ⚠️ **Wichtig:** Immer nur EIN Monat pro Report!

### Schritt 3: Report herunterladen

1. Klicke **"Bericht herunterladen"**
2. Datei wird als Excel gespeichert (`.xlsx`)
3. Merke dir den Speicherort (meist `Downloads`)

---

## Rechnungen erstellen

### Schritt 1: Excel importieren

1. Gehe zum Tab **"Rechnungen erstellen"**
2. Klicke **"Durchsuchen"** bei "Excel-Datei"
3. Wähle die heruntergeladene KDP-Datei
4. Klicke **"Öffnen"**

### Schritt 2: Output-Ordner wählen

1. Klicke **"Durchsuchen"** bei "Output-Ordner"
2. Wähle einen Ordner für deine Rechnungen
3. **Tipp:** Erstelle einen Ordner wie `C:\Buchhaltung\KDP-Rechnungen\2026`

### Schritt 3: Start-Nummer (bei Folge-Monaten)

Wenn du schon Rechnungen erstellt hast:

**Beispiel:**
- Januar: RE20260001 - RE20260008 (8 Rechnungen)
- Februar: Start-Nummer = **9** (RE20260009)

### Schritt 4: Vorschau oder Erstellen

**Option A: Vorschau** (empfohlen beim ersten Mal)
- Klicke **"Vorschau anzeigen"**
- Prüfe die Rechnungen
- Schließe die Vorschau

**Option B: Direkt erstellen**
- Klicke **"Rechnungen erstellen"**
- Warte bis "Fertig!"
- Öffne den Output-Ordner

### Schritt 5: Steuerberater prüfen lassen

⚠️ **KRITISCH:**

1. Öffne eine Beispiel-Rechnung
2. Zeige sie deinem Steuerberater
3. Frage ob Format/Inhalt korrekt ist
4. **Nutze die Software erst nach Freigabe!**

---

## Tipps & Tricks

### Mehrere Monate

Erstelle für **jeden Monat einzeln**:
- Januar → Rechnungen erstellen
- Februar → Start-Nummer anpassen → Rechnungen erstellen
- März → Start-Nummer anpassen → Rechnungen erstellen

### Übersichtlichkeit

Erstelle Unterordner pro Monat:
```
📁 KDP-Rechnungen
  ├── 📁 2026-01-Januar
  ├── 📁 2026-02-Februar
  └── 📁 2026-03-März
```

### Sicherung

**Sichere deine Rechnungen regelmäßig!**
- ☁️ Cloud (Dropbox, Google Drive)
- 💾 Externe Festplatte
- 📧 Email an dich selbst

---

## Problembehandlung

### "Die Anwendung konnte nicht gestartet werden"

**Lösung:** Installiere .NET Framework 4.7.2+
→ [Download](https://dotnet.microsoft.com/download/dotnet-framework)

### "Excel-Datei kann nicht gelesen werden"

**Mögliche Ursachen:**
- Datei ist geöffnet → Schließen
- Falsche Datei gewählt → Nur KDP Payment Reports
- Datei beschädigt → Neu herunterladen

### "Start-Nummer wird ignoriert"

**Lösung:** 
- Prüfe ob "(Format in Einstellungen konfigurieren)" angezeigt wird
- Speichere Einstellungen neu
- Starte Software neu

### Weitere Probleme?

📧 **Email:** info@nekava.eu
🐛 **GitHub Issues:** [Link](https://github.com/PublisherNekava/self-publisher-invoice-pro/issues)

---

## Nächste Schritte

- 📖 Lies den [Disclaimer](DISCLAIMER.md)
- ❓ Prüfe die [FAQ](FAQ.md)
- 🐛 Melde Bugs über [GitHub Issues](https://github.com/PublisherNekava/self-publisher-invoice-pro/issues)

---

**Viel Erfolg mit Self-Publisher Invoice Pro!** 🚀
