# ⚽ TSV Plattenhardt – Interaktive Fußball-Taktiktafel (PWA)

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live%20Demo-brightgreen?style=flat&logo=github)](https://profengel.github.io/fussball-taktik/)
[![PWA](https://img.shields.io/badge/PWA-Offline%20Ready-blue?style=flat&logo=pwa)](https://profengel.github.io/fussball-taktik/)
[![Target](https://img.shields.io/badge/Zielgruppe-Juniorinnen%20%26%20Trainer-red?style=flat)](https://profengel.github.io/fussball-taktik/)

> **🌐 Live aufrufen:** **[https://profengel.github.io/fussball-taktik/](https://profengel.github.io/fussball-taktik/)**

---

## 🎯 Zwei zielgruppenspezifische Modi (1-Klick-Umschaltung)

Ganz oben im Kopfbereich kann zwischen zwei Betriebsmodi umgeschaltet werden:

1. **👧 Für Fußballerinnen (Juniorinnen / Kids):**
   - Große, übersichtliche Bedienelemente in kindgerechter Sprache.
   - Die 2 goldenen Regeln: **„Mach dich GROSS!"** (Ballbesitz) & **„Mach dich ENG!"** (Ballverlust) als anschauliche Animationen.
   - Wichtigste Zurufe auf dem Platz: *„LEO!"*, *„Du hast Zeit!"*, *„Gegner im Rücken!"*, *„Schulterblick!"*.
   - Abseits-Versteher und Freispiel-Quiz.

2. **📋 Trainer-Modus (Vollversion für Taktik & Coaching):**
   - Gegenüberstellung aller Spielsituationen in **🟢 Ideallösung (Best Case)** vs. **🔴 Typischer Fehler (Worst Case)**.
   - Vollständige Taktik-Tafel und interaktive Live-Simulationen.
   - Telestration & Zeichentools sowie DFB 5-Korridore (Halbräume).

---

## 🚀 Die Kern-Funktionen im Überblick

### 1. 🔵 Die 3 dynamischen Abseits-Linien
Auf dem Spielfeld werden 3 separate, dynamische Referenzlinien angezeigt:
- **1. Blaue Linie (Gegnerische Abseitslinie):** Liegt exakt beim vorletzten gegnerischen Verteidiger vor dem gegnerischen Tor. Die gesamte Abseitszone dahinter ist schattiert.
- **2. Gelbe / Rote Linie (Stürmer-Referenz):** Folgt unserer vordersten Angreiferin (Nr. 9) und zeigt sofort an:  
  * `✅ STÜRMERIN REGULÄR` (wenn sie vor der Abseitslinie steht) oder  
  * `⛔ STÜRMERIN IM ABSEITS (X m)` (wenn sie hinter der Abseitslinie steht).
- **3. Grüne Linie (Eigene Kettenhöhe):** Liegt bei unserer letzten Verteidigerin vor dem TSV-Tor und visualisiert, wie hoch unsere Kette steht und wo gegnerische Stürmer ins Abseits laufen.

---

### 2. ⚖️ Gegenüberstellung: Ideallösung vs. Typischer Fehler

Sowohl in der **Taktik-Tafel** als auch in der **Live-Simulation** sind die wichtigsten Spielsituationen mit Best- & Worst-Case nebeneinander aufgereiht:

| Situation | 🟢 Best Case (Ideallösung) | 🔴 Worst Case (Typischer Fehler) |
|---|---|---|
| **1. Spielaufbau über die 6** | Pass zur 6, Schulterblick & Aufdrehen, weiter Pass auf die freie Gegenseite | 6 versteckt sich im Schatten / IV spielt blinden Risikopass durchs Zentrum → Ballverlust & Gegentor |
| **2. Breite (Weit machen)** | Perfekt aufgefächert: AV an der Außenlinie, ST bindet IV, Raum für die 6 | Alle rennen zum Ball, kleben aufeinander, kein Passweg frei |
| **3. Kompaktheit (Eng machen)** | Kompakter Block: Kette rückt ein, Zentrum dicht, gegenseitiges Helfen | Kette zerrissen: Eine schläft hinten (hebt Abseits auf), Scheunentor im Zentrum |
| **4. Einwurf an der Linie** | LM löst sich mit Tempo **vor** die Gegnerin in die Schnittstelle → Ball gesichert | LM versteckt sich **hinter** der Gegnerin im Passschatten → abgefangen & Konter |
| **5. Flügelangriff & Flanke** | 1. Pfosten kreuzen, 2. Pfosten besetzen, Rückraum an Kante 16er → Tor! | Alle rennen blind auf einen Haufen zur Torhüterin, Rückraum leer für Gegenkonter |
| **6. Verteidigen am 16er** | Kompakte Box, Doppeln auf Außen, Zentrum vor Tor gesichert | IV stürzt blind an die Eckfahne → Lücke direkt vorm Tor frei |
| **7. Umschalten nach Ballverlust** | 3-Sekunden-Gegenpressing: Zu dritt jagen → Ball direkt zurückgewonnen | Kopf hängen lassen & Zuschauen → Gegner spielt freien Steilpass |

---

### 3. ⚡ Simulation ab individueller manueller Fehlstellung
- Verschiebe z. B. die Linksverteidigerin (LV Nr. 2) von Hand an eine falsche Position.
- Klicke auf **„🚨 Gegner-Angriff ab aktuellem Stand simulieren!"**:
  - Die Simulation erkennt *die reale Lücke auf der Tafel*, schlägt den Pass in den verwaisten Raum und spielt den Konter bis zum Torschuss durch.

---

### 4. 🕳️ Automatische Erkennung offener Löcher & verlassener Räume
- Wenn eine Spielerin (z. B. Linksverteidigerin Nr. 2 oder Sechserin Nr. 6) von Hand aus ihrer taktischen Verantwortungszone wegbewegt wird (z. B. blind nach vorne stürmt):
  - Markiert die Taktiktafel den verwaisten Raum rot-schraffiert als Gefahrenzone (**„LOCH: LV fehlt!"**).
  - Zeigt einen Geisterkreis am Soll-Standort sowie eine Bewegungslinie zur aktuellen Position.
  - Zeichnet den typischen gegnerischen Angriffs- / Konterpfeil ein, der genau in diese offene Lücke zielt.
  - Lässt sich über den Button **„🕳️ Löcher"** flexibel ein- und ausblenden.

---

### 5. 🔺 Moderner Passschatten (Cover Shadow)
- Jeder gegnerische Verteidiger wirft einen dynamischen Deckungskegel *vom Ball weg*.
- Spielerinnen, die im Schatten stehen, werden sofort als nicht anspielbar markiert.

---

### 6. 🎨 Zeichen- & Telestration-Tools
- **Freihand-Stift** (Gelb, Weiß, Rot).
- **Pass-Pfeile** (gestrichelt) und **Laufweg-Pfeile** (durchgezogen).
- **📊 5 Korridore:** Flügel links, Halbraum links, Zentrum, Halbraum rechts, Flügel rechts einblendbar.

---

### 7. 🎮 Interaktives Freispiel (Passen & freies Verschieben per Touch)
- **Kurz antippen:** Spielt den Ball zur Mitspielerin mit automatischer Live-Prüfung auf **Abseits**, **Deckungsschatten** und **Lücken in der Kette** inklusive Sprechblasen und Trainer-Analyse.
- **Touch & Schieben (länger berühren & ziehen):** Jede Spielerin (eigene rot, Gegner dunkelgrau) sowie der Ball können völlig frei über das gesamte Spielfeld verschoben werden.
  - Deckungsschatten, Abseitslinien und verlassene Abwehrlöcher passen sich in Echtzeit an.
  - Beim Antippen einer Gegnerin wird ein typischer Fehlpass mit direktem Konter simuliert.

---

## 📱 Offline-Nutzung auf iPad, iPhone & Android (PWA)

Die Taktiktafel ist als **Progressive Web App (PWA)** gebaut und benötigt dank des integrierten Service Workers **keine dauerhafte Internetverbindung auf dem Sportplatz**!

### 🍎 Auf dem iPad / iPhone (Safari):
1. Öffne die Seite in **Safari**: [https://profengel.github.io/fussball-taktik/](https://profengel.github.io/fussball-taktik/)
2. Tippe auf das **Teilen-Symbol** (Viereck mit Pfeil nach oben).
3. Wähle **„Zum Home-Bildschirm"** → **„Hinzufügen"**.
4. ✅ Die App startet ab sofort im Vollbild ohne Browserleiste und funktioniert komplett **offline**.

### 🤖 Auf Android (Chrome):
1. Öffne die Seite in **Chrome**: [https://profengel.github.io/fussball-taktik/](https://profengel.github.io/fussball-taktik/)
2. Menü (⋮) → **„App installieren"**.

---

## 📄 Verein

Entwickelt für den **TSV Plattenhardt – Abteilung Mädchenfußball**.
Frei nutzbar für Trainerinnen und Trainer zur taktischen Ausbildung im Jugendfußball.
