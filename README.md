# ⚽ TSV Plattenhardt – Interaktive Fußball-Taktiktafel (PWA)

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live%20Demo-brightgreen?style=flat&logo=github)](https://profengel.github.io/fussball-taktik/)
[![PWA](https://img.shields.io/badge/PWA-Offline%20Ready-blue?style=flat&logo=pwa)](https://profengel.github.io/fussball-taktik/)
[![Target](https://img.shields.io/badge/Zielgruppe-Juniorinnen%20%26%20Trainer-red?style=flat)](https://profengel.github.io/fussball-taktik/)

> **🌐 Live aufrufen:** **[https://profengel.github.io/fussball-taktik/](https://profengel.github.io/fussball-taktik/)**

---

## 🎯 Wofür ist diese Taktiktafel gedacht?

Diese Web-App wurde speziell für das Training, die Mannschaftsbesprechung und das Coaching an der Seitenlinie im **Juniorinnen-Fußball (TSV Plattenhardt)** entwickelt. Sie verbindet intuitive Bedienung auf dem iPad/Tablet mit modernen Konzepten der professionellen Fußballanalyse (bekannt aus Tools wie *TacticalPad* und *KlipDraw*).

---

## 🚀 Die Kern-Funktionen im Überblick

### 1. 📋 Reiner Taktik-Modus mit 1-Click-Ausgangslagen (Presets)
Schnelle Umschaltung typischer Spielsituationen für die Taktikschulung:
- **🏟️ Grundordnung (3-1-3-1):** Das bewährte TSV-Basissystem für die D-Jugend (9er-Feld).
- **🟢 Ballbesitz: Groß machen!** Außenverteidigerinnen ganz an die Auslinie, Tiefe schaffen, Räume für die 6 öffnen.
- **🔴 Ballverlust: Eng machen!** Kette rückt ein, Zentrum schließen, sofortige Ballorientierung.
- **🛡️ Gegner im Strafraum (Tief stehend):** Kompakter Defensivblock um den 16er, Flankensicherung & Doppelung auf den Außen.
- **📐 Einwurf TSV (Richtig vs. Falsch):**
  - *Richtig:* Anspielstation löst sich aktiv **vor** die Gegenspielerin oder in die Schnittstelle.
  - *Falsch:* Spielerin versteckt sich **hinter** der Gegnerin im Passschatten → Ball wird abgefangen.
- **↔️ Spielverlagerung über die 6:** Ball auf einer Seite festgerannt → Rückpass zur Schaltzentrale (Nr. 6) → weiter Pass auf die freie Außenbahn.

### 2. ⚡ Freie manuelle Positionierung & Simulation ab aktuellem Stand
- **Jede Spielerin und der Ball können frei per Finger/Maus verschoben werden.**
- **Didaktischer Clou für Trainer:** Verschiebe z. B. die Linksverteidigerin (LV) mitten ins Feld. Klicke dann auf **„🚨 Gegner-Angriff ab aktuellem Stand simulieren"**:
  - Die Simulation erkennt *die reale Lücke auf der Tafel*.
  - Der Gegner spielt den Pass gezielt in den verlassenen Raum und schließt ab!
  - Perfekt, um Spielerinnen die Konsequenzen von Fehlstellungen direkt vor Augen zu führen.
- **„⬡ Spielaufbau über die 6":** Reagiert dynamisch auf die aktuelle Position der 6 – muss sie erst aus dem Schatten treten, macht sie den Schritt zur Seite und verlagert dann.

### 3. 🔺 Moderne Taktikanalyse: Passschatten (Cover Shadow) & Lückenerkennung
- **Echter ballbezogener Passschatten:** Jeder verteidigende Gegner wirft in Echtzeit einen Deckungskegel *vom Ball weg*. Befindet sich eine Mitspielerin in diesem Schatten, ist der direkte Passweg versperrt!
- **⚠️ Automatische Ketten-Lückenerkennung:** Wenn der Abstand zwischen zwei Abwehrspielerinnen zu groß wird (> 17m), warnt die Tafel automatisch mit einer blinkenden Gefahrenmarkierung.
- **🔵 Automatische Abseits-Linie:** Berechnet dynamisch den vorletzten Verteidiger und schattiert die Abseitszone.

### 4. 🎮 Freispiel-Modus (Interaktive Passprüfung)
- Tippe die ballführende Spielerin an → tippe das gewünschte Passziel an.
- Die App bewertet den Pass sofort:
  - **✅ Grün:** Freie Spielerin, Pass kommt sicher an.
  - **⚠️ Gelb:** Spielerin steht im gegnerischen Passschatten (Riskant!).
  - **⛔ Rot:** Abseits oder geblockt – Pass wird abgewehrt.

### 5. 🎨 Zeichen- & Telestration-Tools
- **Freihand-Stift** (Gelb, Weiß, Rot) zum Einkreisen und Notieren.
- **Pass-Pfeile** (gestrichelt) und **Laufweg-Pfeile** (durchgezogen).
- **📊 5 Korridore (DFB-Standard):** Blendet Flügel, Halbräume und Zentrum ein (nach Pep Guardiola / modernem Positionsspiel).

---

## 📱 Offline-Nutzung auf iPad, iPhone & Android (PWA)

Die Taktiktafel ist als **Progressive Web App (PWA)** gebaut und benötigt dank des integrierten Service Workers **keine dauerhafte Internetverbindung auf dem Sportplatz**!

### 🍎 Auf dem iPad / iPhone (Safari):
1. Öffne die Seite in **Safari**: [https://profengel.github.io/fussball-taktik/](https://profengel.github.io/fussball-taktik/)
2. Tippe auf das **Teilen-Symbol** (Viereck mit Pfeil nach oben).
3. Wähle **„Zum Home-Bildschirm"**.
4. Tippe auf **„Hinzufügen"**.
5. ✅ Die App startet ab sofort ohne Browser-Leiste im Vollbild (Querformat) und funktioniert komplett **offline**.

### 🤖 Auf Android (Chrome):
1. Öffne die Seite in **Chrome**: [https://profengel.github.io/fussball-taktik/](https://profengel.github.io/fussball-taktik/)
2. Tippe auf das Banner **„App installieren"** oder oben rechts im Menü (⋮) auf **„App installieren"**.
3. ✅ Startet als eigenständige Vollbild-App und ist sofort offline-fähig.

---

## 💻 Lokale Entwicklung

Kein Build-Schritt erforderlich! Einfach die `index.html` in einem modernen Browser öffnen:

```bash
# Im Browser öffnen
start index.html
```

---

## 📄 Lizenz & Verein

Entwickelt für den **TSV Plattenhardt – Abteilung Mädchenfußball**.
Frei nutzbar für Trainerinnen und Trainer zur taktischen Ausbildung im Jugendfußball.
