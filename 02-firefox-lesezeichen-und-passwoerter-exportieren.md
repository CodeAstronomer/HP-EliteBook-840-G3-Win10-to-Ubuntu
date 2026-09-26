# 2 · Firefox: Lesezeichen und Passwörter exportieren

**Ziel:** Lesezeichen und gespeicherte Passwörter als Dateien auf den Stick **„DATEN“** speichern.

⏱️ ca. 10 Minuten · 🟦 USB-Stick **„DATEN“** eingesteckt

> ℹ️ Die Texte in **fett** sind genau so in der deutschen Firefox-Version zu sehen.

---

## Teil A – Lesezeichen

### Schritt 1 – Bibliothek öffnen

⌨️ In Firefox **Strg** + **Umschalt** + **O** drücken (O wie **O**tto).

➡️ Ein neues Fenster **Bibliothek** öffnet sich.

### Schritt 2 – Export starten

1. 👉 Oben in der Bibliothek auf **Importieren und Sichern** klicken.
2. 👉 **Lesezeichen nach HTML exportieren…** anklicken.

### Schritt 3 – Auf dem Stick speichern

1. Fenster **Lesezeichendatei exportieren** erscheint.
2. 👉 Links auf **Dieser PC** → den **USB-Stick** → Ordner **Sicherung** klicken.
3. 👉 **Speichern** klicken.

### Schritt 4 – (Zusätzlich) Sicherungskopie

1. 👉 In der Bibliothek wieder **Importieren und Sichern** → **Sichern…**
2. 👉 Ebenfalls im Ordner **Sicherung** auf dem Stick **speichern**.

➡️ Jetzt liegen eine **.html**- und eine **.json**-Datei auf dem Stick. Bibliothek schließen.

---

## Teil B – Passwörter

### Schritt 5 – Passwort-Seite öffnen

1. 👉 Oben in die **Adressleiste** klicken.
2. ⌨️ `about:logins` eintippen und **Enter** drücken.

➡️ Die Seite mit deinen gespeicherten Passwörtern öffnet sich.

### Schritt 6 – Menü öffnen

👉 Oben rechts auf der Seite auf **⋯** (drei Punkte, **Menü öffnen**) klicken.

### Schritt 7 – Exportieren

1. 👉 **Passwörter exportieren…** anklicken.
2. Hinweis erscheint: **Ein Hinweis zum Export von Passwörtern**.
3. 👉 **Weiter mit Export** klicken.

### Schritt 8 – Mit Windows-Passwort bestätigen

🔑 Windows fragt nach deinem **Windows-Passwort** bzw. deiner **PIN** (die du beim Anmelden am Laptop eingibst). Eingeben und bestätigen.

### Schritt 9 – Auf dem Stick speichern

1. Fenster **Passwörter von Firefox exportieren** erscheint.
2. Vorgeschlagener Dateiname: **passwoerter.csv**
3. 👉 **Dieser PC** → **USB-Stick** → Ordner **Sicherung** wählen.
4. 👉 **Exportieren** klicken.

> 🔴 **Wichtig:** Die Datei **passwoerter.csv** enthält alle Passwörter **unverschlüsselt als lesbaren Text**!
> - Stick gut aufbewahren, nicht verleihen.
> - Datei **nicht** per E-Mail verschicken oder hochladen.
> - Nach dem Import in Ubuntu die Datei **löschen**.

---

## Teil C (optional) – Komplettes Firefox-Profil sichern

Enthält zusätzlich Verlauf, Erweiterungen, Einstellungen usw.

1. ⌨️ In der Adressleiste `about:support` eingeben → **Enter**.
2. Seite **Informationen zur Fehlerbehebung** erscheint.
3. 👉 In der Zeile **Profilordner** auf **Ordner öffnen** klicken. Ein Explorer-Fenster öffnet sich.
4. 👉 Oben in der Adresszeile des Explorers auf **Profiles** klicken (eine Ebene höher).
5. ❌ **Firefox komplett schließen.**
6. 👉 Den Ordner, der auf **.default-release** endet, kopieren (Rechtsklick → **Kopieren**) und auf dem Stick im Ordner **Sicherung** einfügen (Rechtsklick → **Einfügen**).

---

## ✅ Checkliste – im Ordner „Sicherung“ auf dem Stick

- [ ] Lesezeichen-Datei **.html**
- [ ] Lesezeichen-Sicherung **.json**
- [ ] **passwoerter.csv**
- [ ] (optional) Profilordner **….default-release**

➡️ Weiter mit [3 · balenaEtcher installieren](03-balenaetcher-herunterladen-und-installieren.md)
