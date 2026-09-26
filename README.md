# HP EliteBook 840 G3: von Windows 10 zu Ubuntu

Anleitungen Schritt für Schritt, für alle mit Grundkenntnissen in Windows 10.

## Was du brauchst

| | Was | Wofür |
|---|---|---|
| 🟦 | **USB-Stick 1** (Daten) | Deine Dateien und Firefox-Daten sichern |
| 🟧 | **USB-Stick 2** (leer, mindestens **8 GB**) | Ubuntu-Installationsstick. **Wird komplett gelöscht!** |
| 💻 | HP EliteBook 840 G3 mit Windows 10 | |
| 🔌 | Netzteil | Laptop während allem **am Strom** lassen |

> ⚠️ Die beiden Sticks **nie verwechseln**. Am besten mit Klebeband beschriften: **„DATEN“** und **„UBUNTU“**.

## Reihenfolge

| Schritt | Anleitung |
|---|---|
| 1 | [Persönliche Ordner auf USB-Stick sichern](01-persoenliche-ordner-auf-usb-stick-sichern.md) |
| 2 | [Firefox: Lesezeichen und Passwörter exportieren](02-firefox-lesezeichen-und-passwoerter-exportieren.md) |
| 3 | [balenaEtcher herunterladen und installieren](03-balenaetcher-herunterladen-und-installieren.md) |
| 4 | [Ubuntu Desktop ISO herunterladen und auf USB-Stick schreiben](04-ubuntu-desktop-iso-herunterladen-und-auf-usb-stick-schreiben.md) |
| 5 | [HP EliteBook 840 G3: BIOS einstellen, vom USB-Stick starten und Ubuntu installieren](05-hp-elitebook-840-g3-bios-und-usb-start.md) |

> ℹ️ Installiert wird **Ubuntu Desktop 26.04.1 LTS** (mit grafischer Oberfläche und Firefox). Ubuntu nennt als Mindestanforderung u. a. **6 GB Arbeitsspeicher** und **25 GB** freien Festplattenplatz.

> 💡 Schritte 1 und 2 **zuerst** erledigen. Bei der Ubuntu-Installation wird Windows mit allen Dateien gelöscht.

## Über die Bilder

- Alle Bilder im Ordner [`bilder/`](bilder/) sind **echte Screenshots** (aufgenommen am 26.09.2026). Rote Rahmen und Nummern wurden nachträglich eingezeichnet.
- **Ubuntu-Startmenü und Installer**: aufgenommen vom echten Stick-Abbild `ubuntu-26.04.1-desktop-amd64.iso` in einer virtuellen Maschine.
- **balenaEtcher**: Die App sieht unter Windows und Linux gleich aus und ist nur auf Englisch. Die Screenshots zeigen **balenaEtcher 2.1.7**.
- **Windows 10, Firefox und das HP-BIOS** konnten hier nicht fotografiert werden. Dort stehen deshalb die **genauen Namen der Knöpfe und Menüs** in **fett**. Die deutschen Firefox-Texte stammen direkt aus Mozillas offiziellen Übersetzungsdateien.
