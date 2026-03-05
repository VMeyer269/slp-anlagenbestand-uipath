# SLP Anlagenbestand – UiPath Bot Repo

## Ziel
Dieses Repository enthält die Struktur und Dokumentation für einen UiPath Bot zur Untersuchung/Bearbeitung einer Excel-Datei
(Anlagenbestände von Standardlastprofilen inkl. Zuordnungen und Weiterverarbeitung).

## Inhalt
- uipath/ – UiPath Projekt(e)
- src/InvokeCode/ – Platz für C# Invoke Code Snippets (später)
- docs/ – Dokumentation (Excel-Schema, Prozess, Entscheidungen)
- data/ – lokale Testdaten (nicht versionieren, außer .gitkeep)

## Workflow (geplant)
1. Excel einlesen
2. Validieren (Spalten, Pflichtfelder)
3. Normalisieren / Bereinigen
4. Regeln / Zuordnung
5. Reports & Output schreiben

## Hinweise
- Keine produktiven Daten committen
- Invoke Code Snippets werden später ergänzt

## Projektstruktur

slp-anlagenbestand-uipath
│
├─ docs
│ ├─ excel
│ ├─ process
│ └─ decisions
│
├─ src
│ └─ InvokeCode
│ (C# Snippets für UiPath Invoke Code)
│
├─ uipath
│ └─ SLP-Anlagenbestand-Bot
│ (UiPath Studio Projekt)
│
└─ data
├─ input
└─ output
