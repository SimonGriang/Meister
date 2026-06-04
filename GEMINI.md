# Meisterkurs Teil 3 - Wissensdatenbank

Dieses Projekt dient dem Aufbau einer Wissensdatenbank in Form eines Obsidian Vaults für den Meisterkurs Teil 3 (Bayern).

## Grundregeln (Mandates)

1. **Quellenreue:** Informationen dürfen primär nur aus den bereitgestellten Buchpassagen stammen.
2. **Kontext:** Der Kurs findet in Bayern statt. Rechtliche oder regulatorische Details müssen diesen Kontext berücksichtigen.
3. **Struktur:** Die Datenbank ist in drei Hauptbereiche (Band 1, Band 2, Band 3) gegliedert.
4. **Ziel:** Erstellung einer fundierten Basis für eine spätere Abfragefunktion (Lernhilfe).
5. **Ergänzungen:** Externe Informationen sind auf ein Minimum zu beschränken und müssen zu 100% gesichert sein.

## Struktur & Organisation

1. **Inhaltsverzeichnisse (Indices):** Für jeden Band existiert eine zentrale Index-Datei (z.B. `Band_1_Index.md`). Diese wird dynamisch erweitert, sobald neue Kapitel hinzugefügt werden.
2. **Atomare Notizen:** Markdown-Dateien sollen kurz, prägnant und auf ein spezifisches Thema fokussiert sein.
3. **Vernetzung:** Aktive Nutzung von Wiki-Links (`[[Link]]`), um Zusammenhänge zwischen Kapiteln und Bänden herzustellen.
4. **Navigation:** Der Index dient als Einstiegspunkt und Map für den jeweiligen Themenbereich.

## Vault-Struktur

- `Obsidian_Vault/`
  - `Band_1/`
    - `Band_1_Index.md` (Dynamisches Inhaltsverzeichnis)
  - `Band_2/`
    - `Band_2_Index.md`
  - `Band_3/`
    - `Band_3_Index.md`
