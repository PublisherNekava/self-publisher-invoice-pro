# ❓ Häufig gestellte Fragen (FAQ)

## Allgemein

### Ist die Software kostenlos?

**Für Beta-Tester: JA!**

Beta-Tester erhalten **lebenslangen kostenlosen Zugang**.

Nach der Beta-Phase: €79,90 (Einmalzahlung)

---

### Für welche Länder ist die Software?

Optimiert für **Deutschland 🇩🇪** und **Österreich 🇦🇹**.

Andere Länder: Nicht getestet, Nutzung auf eigenes Risiko.

---

### Läuft die Software auf Mac/Linux?

**Nein, aktuell nur Windows 10/11.**

macOS-Version ist für v2.0 geplant.

**Workaround:** Virtuelle Maschine (Parallels, VirtualBox)

---

## Steuerliche Fragen

### Muss ich eine Zusammenfassende Meldung (ZM) machen?

**Das muss dein Steuerberater entscheiden!**

Die Frage ist rechtlich umstritten:
- Manche Steuerberater sagen: JA
- Andere sagen: NEIN (wegen §3a UStG)

**→ Kläre das mit deinem Steuerberater!**

Die Software erstellt nur Rechnungen, entscheidet aber NICHT über ZM-Pflicht.

---

### Sind die Rechnungen steuerlich korrekt?

**Die Software generiert Rechnungen nach gängigen Standards.**

**ABER:** Jeder hat individuelle steuerliche Anforderungen!

**→ ALLE Rechnungen MÜSSEN von deinem Steuerberater geprüft werden!**

Ich bin KEIN Steuerberater und gebe KEINE Steuerberatung.

---

### Welche Steuernummer soll ich angeben?

**Das hängt von deiner Situation ab:**

- Einzelunternehmer: Steuer-Nr. oder USt-IdNr
- GmbH: USt-IdNr
- Kleinunternehmer: Steuer-Nr. (meist)

**→ Frag deinen Steuerberater!**

---

### Was ist mit Drittländern (USA, UK)?

Die Software erstellt **separate Behandlung** für:

- **EU-Länder:** Reverse-Charge (§13b UStG)
- **Drittländer:** §3a UStG

**ABER:** Auch hier gilt:
**→ Mit Steuerberater besprechen!**

---

## Technische Fragen

### Wie oft kann ich die Software nutzen?

**Unbegrenzt!**

Erstelle so viele Rechnungen wie du willst, für alle deine KDP-Monate.

---

### Werden meine Daten gespeichert/hochgeladen?

**NEIN!**

Die Software arbeitet **komplett offline und lokal** auf deinem PC.

**Es werden KEINE Daten ins Internet übertragen!**

Deine Daten sind nur auf deinem Computer.

---

### Kann ich die Software auf mehreren PCs nutzen?

**JA!**

Als Beta-Tester kannst du die Software auf all deinen PCs nutzen.

Kopiere einfach die Dateien.

---

### Wo werden meine Einstellungen gespeichert?

In einer Datei: `%USERPROFILE%\.kdp_invoice_settings.json`

Typischerweise: `C:\Users\DeinName\.kdp_invoice_settings.json`

**Zum Zurücksetzen:** Diese Datei löschen.

---

## Nutzung

### Kann ich mehrere Monate auf einmal verarbeiten?

**NEIN - und das ist Absicht!**

Rechnungsnummern müssen **fortlaufend** sein (gesetzliche Anforderung).

**Workflow:**
1. Januar → Erstelle Rechnungen (RE001-RE008)
2. Februar → Start-Nummer auf 9 setzen → Erstelle (RE009-RE015)
3. März → Start-Nummer auf 16 setzen → Erstelle (RE016-RE023)

---

### Muss ich die Rechnungen an Amazon schicken?

**In der Regel: NEIN.**

Die Rechnungen sind für **deine Buchhaltung** und das **Finanzamt**.

Amazon verlangt manchmal Rechnungen für interne Zwecke – dann kannst du sie hochladen.

**Aber:** Musst du nicht aktiv verschicken.

---

### Was ist wenn ich einen Fehler gemacht habe?

**Kein Problem:**

1. Lösche die fehlerhaften Rechnungen aus dem Output-Ordner
2. Korrigiere die Einstellungen
3. Erstelle die Rechnungen neu

**Wichtig:** Falls du Rechnungen schon ans Finanzamt gegeben hast:
**→ Mit Steuerberater besprechen wie zu korrigieren!**

---

### Kann ich das Format der Rechnungen anpassen?

**Aktuell: Eingeschränkt**

Du kannst ändern:
- ✅ Firmendaten
- ✅ Rechnungsnummern-Format
- ✅ Land/Rechtsraum

Du kannst NICHT ändern:
- ❌ Layout der PDF
- ❌ Schriftart
- ❌ Farben

**v2.0:** Mehr Anpassungsmöglichkeiten geplant.

---

## Beta-Testing

### Wie werde ich Beta-Tester?

**Aktuell geschlossen** – aber vielleicht öffnen wir wieder!

Folge dem GitHub Repo für Updates.

---

### Was muss ich als Beta-Tester machen?

**Erwünscht (nicht Pflicht):**

- ✅ Software testen
- ✅ Bugs melden
- ✅ Feedback geben
- ✅ Verbesserungsvorschläge einreichen

**Dafür bekommst du:**

- ✅ Lebenslangen kostenlosen Zugang
- ✅ Dein Name in den Credits (optional)

---

### Ich habe einen Bug gefunden!

**Super! Danke fürs Testen!**

Bitte melde ihn:

1. **GitHub Issues:** [Link](https://github.com/PublisherNekava/self-publisher-invoice-pro/issues)
2. **Oder Email:** [deine-email@example.com]

**Bitte angeben:**
- Windows-Version
- .NET Version
- Was hast du gemacht?
- Was ist passiert?
- Screenshot (wenn möglich)

---

## Sonstiges

### Kann ich die Software weiterempfehlen?

**JA, gerne!**

Teile den Link zum GitHub Repo mit anderen Self-Publishern.

**Aber bitte:** NICHT die .exe-Datei direkt teilen (Viren-Scans!)

→ Nur Link zu GitHub Releases

---

### Plant ihr mehr Features?

**JA!**

**v1.1 (nächste Monate):**
- Steuerberater-Checkliste
- Englische Version
- Erweiterte Reports

**v2.0 (2026):**
- macOS-Version
- Freemium-Modell
- Cloud-Features

---

### Kann ich zur Entwicklung beitragen?

**Aktuell: Code ist closed-source**

**ABER:** Feedback, Ideen, Bug-Reports sind **sehr** willkommen!

---

### Noch Fragen?

📧 **Email:** info@nekava.eu
🐛 **GitHub:** [Issues](https://github.com/PublisherNekava/self-publisher-invoice-pro/issues)

---

**Letzte Aktualisierung:** Februar 2026
