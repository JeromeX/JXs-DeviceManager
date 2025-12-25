# 🛠️ Device Manager Ultimate

**Device Manager Ultimate** ist ein leistungsstarkes Windows-Tool zur Zwangsentfernung hartnäckiger Geräte-Leichen, "Ghost"-Geräte und fehlerhafter Treiber-Stacks. 
Entwickelt von **Malte Speck**, bietet dieses Programm eine intuitive grafische Oberfläche, um Systembereinigungen durchzuführen, die über den Standard-Windows-Gerätemanager hinausgehen.

![Lizenz](https://img.shields.io/badge/Lizenz-Eigene-green)
![Platform](https://img.shields.io/badge/Platform-Windows-blue)
![Language](https://img.shields.io/badge/Language-C%23-purple)

---

## 🚀 Features

- **Deep Scan:** Findet alle Plug-and-Play-Geräte, einschließlich versteckter "Ghost"-Geräte.
- **Kategorisierung:** Automatische Sortierung der Hardware in übersichtliche Kategorien (Dropdown-Filter).
- **Nuklear-Option:** Nutzt den systemeigenen `pnputil`-Dienst, um Geräte-Instanzen inklusive Treiber-Referenzen hart zu löschen.
- **Modernes UI:** Klares Design mit Neon-Statusanzeigen und farblich hervorgehobenen IDs und Kategorien.
- **Standalone:** Keine Installation notwendig. Die Anwendung ist eine einzige `.exe` Datei.
- **Administrator-Zwang:** Die App prüft beim Start auf Privilegien und fordert diese ggf. an.

---

## 🎨 Design-Highlights

- **Neon-Status:** Ein leuchtendes Status-System zeigt den Systemzustand an:
  - <span style="color:#FF0066">**NEONROT**</span>: System bereit.
  - <span style="color:#00CCFF">**NEONBLAU**</span>: Scan erfolgreich abgeschlossen.
- **Farbcodierung:** - **Grün**: Aktive Geräteverbindungen.
  - **Orange**: Hardware-Kategorien.
  - **Rot**: Hardware-IDs.
  - **Gold**: Highlight-Markierung gewählter Geräte.

---

## ⚠️ Wichtiger Sicherheitshinweis (Disclaimer)

**DIE NUTZUNG ERFOLGT AUF EIGENE GEFAHR.**

Dieses Tool greift tief in die Windows-Systemkonfiguration ein. Das Entfernen kritischer Systemkomponenten kann dazu führen, dass das Betriebssystem **instabil oder unbrauchbar** wird. 
- Erstellen Sie vor der Nutzung einen **Wiederherstellungspunkt**.
- Der Entwickler übernimmt **keine Haftung** für Datenverlust, Hardware-Defekte oder Systemfehler.

---

## 📖 Anleitung

1. **System Scannen:** Klicke auf den blauen Button, um alle Hardware-Informationen zu laden.
2. **Filtern:** Nutze die Suchzeile oder das Kategorien-Menü, um das problematische Gerät zu finden.
3. **Nuklear-Entfernung:** Wähle das Gerät aus und bestätige die Entfernung. 
4. **Hilfe:** Klicke auf das rote **?** oben rechts für detaillierte Informationen.

---

## 👤 Autor

**Malte Speck** *Professional Windows Tools & System Optimization*

© 2025 | written by Malte Speck
