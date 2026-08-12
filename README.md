# Dragon Repeller – JavaScript RPG

Ein browserbasiertes Text-RPG, entwickelt in Vanilla JavaScript (HTML, CSS, JS – ohne Frameworks oder Libraries), um die Grundlagen von DOM-Manipulation, Event Handling und State Management zu vertiefen.

## Über das Spiel

In **Dragon Repeller** schlüpfst du in die Rolle eines Helden, der die Stadt von einem Drachen befreien muss. Auf dem Weg dorthin kannst du im Dorfladen Ausrüstung und Heiltränke kaufen, in der Höhle gegen schwächere Monster kämpfen, um Erfahrung und Gold zu sammeln, und dich schliesslich dem finalen Kampf gegen den Drachen stellen.

**[Live-Demo spielen](https://facalfabian.github.io/RPG_Dragon_Game/)**

## Features

- **Kampfsystem** mit Angriff, Ausweichen und Flucht
- **Waffen-Upgrades** – von der Holzstange bis zum Schwert, inklusive Verkauf alter Waffen
- **Ressourcenmanagement** – Gesundheit, Gold und Erfahrungspunkte
- **Dynamische Zufallsmechaniken** – Trefferchance, Schadenswerte und ein zufälliger Waffenverschleiss
- **Verstecktes Bonusspiel** (Easter Egg) nach einem Monster-Sieg
- **Win-/Lose-Screens** mit Replay-Funktion

## Verwendete Technologien

- HTML5
- CSS3
- Vanilla JavaScript (ES6)

## Lokal ausführen

Da das Projekt keine Abhängigkeiten oder Build-Tools benötigt, reicht es, das Repository zu klonen und die `index.html` im Browser zu öffnen:

```bash
git clone https://github.com/facalfabian/RPG_Dragon_Game.git
cd RPG_Dragon_Game
open index.html
```

## Projektstruktur

```
├── index.html      # Struktur des Spiels
├── styles.css       # Styling
└── script.js         # Spiellogik (State, Kampfsystem, Navigation)
```

## Lernziele des Projekts

Dieses Projekt diente dazu, folgende JavaScript-Konzepte praktisch anzuwenden:

- DOM-Selektion und -Manipulation ohne Framework
- Event-Listener und dynamisches Umschreiben von Button-Verhalten
- Arbeiten mit Arrays und Objekten zur Repräsentation von Spielzuständen (Locations, Monster, Waffen)
- Bedingte Logik zur Steuerung des Spielflusses
- Grundlegendes State Management in Vanilla JS

## Mögliche Erweiterungen

- Speichern des Spielstands via `localStorage`
- Weitere Level, Waffen und Monster
- Responsive Design für Mobilgeräte
- Sound-Effekte und Animationen

## Lizenz

Dieses Projekt dient Lernzwecken und ist frei verwendbar.
