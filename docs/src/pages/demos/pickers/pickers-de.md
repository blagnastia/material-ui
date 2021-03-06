---
title: Datums-Auswahl, Zeit-Auswahl React Komponenten
components: TextField
---
# Pickers

<p class="description">Pickers bieten eine einfache Möglichkeit, um einen einzelnen Wert aus einem vorher festgelegten Satz auszuwählen.</p>

- Auf dem Handy sind Pcikers am besten für die Anzeige im Bestätigungsdialogfeld geeignet.
- Für die Inline-Anzeige, z. B. in einem Formular, sollten Sie kompakte Steuerelemente wie segmentierte Dropdown-Schaltflächen verwenden.

#### Benachrichtigung

Wir greifen auf **native Eingabesteuerelemente** zurück.

⚠️ Unterstützung von systemeigenen Eingabesteuerelementen durch Browser [ist nicht perfekt](https://caniuse.com/#feat=input-datetime). Sehen Sie sich die [ergänzenden Projekte](#complementary-projects) an, um bessere Lösungen zu erhalten.

## Datums-Auswahl

Ein natives Datumsauswahlbeispiel mit `type="date"`, es kann auch als Kalender verwendet werden.

{{"demo": "pages/demos/pickers/DatePickers.js"}}

## Datum & Zeitauswahl

Ein natives Datum & Zeitauswahlbeispiel mit `type="datetime-local"`.

{{"demo": "pages/demos/pickers/DateAndTimePickers.js"}}

## Zeitauswahl

Ein natives Datum Zeitauswahlbeispiel mit `type="time"`.

{{"demo": "pages/demos/pickers/TimePickers.js"}}

## Ergänzende Projekte

Für fortgeschrittenere Anwendungsfälle können Ihnen folgende Projekte helfen.

### material-ui-pickers

![stars](https://img.shields.io/github/stars/dmtrKovalenko/material-ui-pickers.svg?style=social&label=Stars) ![npm downloads](https://img.shields.io/npm/dm/material-ui-pickers.svg)

[material-ui-pickers](https://material-ui-pickers.firebaseapp.com/) enthält Steuerelemente für Datum und Uhrzeit, die der Material Design-Spezifikation entsprechen.

{{"demo": "pages/demos/pickers/MaterialUIPickers.js"}}

### Sonstiges

- [material-ui-time-picker](https://github.com/TeamWertarbyte/material-ui-time-picker): Zeitauswahl.
- [material-ui-next-pickers](https://github.com/chingyawhao/material-ui-next-pickers): Datums- und Zeitauswahl.