🛡️ Sicherheit & Transparenz
Diese Datei informiert Nutzer darüber, warum der Device Manager Ultimate bestimmte Berechtigungen benötigt und wie das Programm mit Systemdaten umgeht. Als Werkzeug zur Systemoptimierung steht Sicherheit an erster Stelle.

🔑 Warum Administratorrechte?
Der Device Manager Ultimate benötigt zwingend Administratorrechte, um ordnungsgemäß zu funktionieren. Dies liegt an den folgenden technischen Notwendigkeiten:

Interaktion mit pnputil.exe: Dies ist ein systemeigener Windows-Dienst. Nur Administratoren dürfen Hardware-Treiber aus dem Treiber-Store (DriverStore) entfernen oder Geräte-Instanzen löschen.

Registry-Bereinigung: Der Zugriff auf den Pfad HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Enum ist für Standardnutzer gesperrt. Um "Leichen" in der Registrierung zu löschen, sind erhöhte Rechte erforderlich.

WMI-Abfragen: Der vollständige Hardware-Scan nutzt die Windows Management Instrumentation (WMI), die für bestimmte Hardware-Details Admin-Privilegien voraussetzt.

🔒 Datenschutz & Telemetrie
Keine Datenspeicherung: Das Programm speichert keine Informationen über deine Hardware lokal oder in der Cloud.

Keine Telemetrie: Es werden keine Nutzungsdaten, Klickpfade oder Fehlerberichte an den Entwickler (Malte Speck) gesendet.

Offline-Betrieb: Das Tool benötigt keine Internetverbindung. Alle Operationen finden lokal auf deinem Rechner statt.

⚠️ Sicherheitswarnungen von Windows
Da dieses Programm direkt in den Quellcode kompiliert wird und keine digitale Signatur einer teuren Zertifizierungsstelle (wie Symantec oder DigiCert) besitzt, kann Windows SmartScreen oder dein Antiviren-Programm beim ersten Start warnen.

Grund: Programme, die Systembefehle wie pnputil ausführen und Admin-Rechte verlangen, werden oft präventiv als "riskant" eingestuft.

🚀 Best Practices für Nutzer
Um maximale Sicherheit für dein System zu gewährleisten, empfehlen ich:

Backup: Erstelle einen Systemwiederherstellungspunkt, bevor du die "Nuklear-Option" für ein Gerät nutzt.

Vorsicht: Lösche nur Geräte, die du sicher als "Ghost" (versteckt/inaktiv) oder als fehlerhaft identifiziert hast.

Haftung: Wie in der Lizenz beschrieben, erfolgt die Nutzung auf eigene Gefahr.

📧 Sicherheitslücken melden
Solltest du eine Sicherheitslücke in der Logik des Programms finden, erstelle bitte kein öffentliches "Issue", sondern kontaktiere den Entwickler direkt oder dokumentiere es privat, um andere Nutzer nicht zu gefährden.

© 2025 | Malte Speck
