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

## Erstellung von Lernzusammenfassungen (Lernunterlagen)

### 1. Zeitpunkt der Erstellung
- **Wann:** Kapitelübergreifende Zusammenfassungen (z. B. im Ordner `Lernunterlagen/` als `Lernzusammenfassung_Kapitel_X_...`) werden **ausschließlich nach expliziter Aufforderung** durch den Benutzer erstellt oder aktualisiert.
- **Vorheriger Workflow:** Neuer Input wird zunächst ausschließlich in Form von detaillierten, atomaren Einzelnotizen in den jeweiligen Band-Verzeichnissen (z. B. `Band_2/`) aufbereitet und im entsprechenden Index verlinkt.

### 2. Stil & Inhaltliche Anforderungen
- **Detailtiefe:** Zusammenfassungen dürfen nicht zu grob sein. Jedes Unterkapitel (z. B. 2.2.3, 3.1.3) und alle Unterpunkte (a, b, etc.) müssen mit ihren Kerninhalten vertreten sein.
- **Formeln:** Mathematische oder betriebswirtschaftliche Formeln und Kennzahlen (z. B. Anlagendeckung, Deckungsbeitrag, Mindestumsatz) sind im LaTeX-Format (`$$ ... $$` oder `$ ... $`) darzustellen.
- **Diagramme:** Visualisierungen (wie Mermaid-Flowcharts oder -Mindmaps) sind zur Veranschaulichung einzubauen.
  - **Syntax-Sicherheit:** Subgraphen und Knotennamen mit Sonderzeichen (z. B. `&`, `(`, `)`) müssen zwingend in doppelte Anführungszeichen gesetzt werden (z. B. `subgraph "Fachliche Gliederung (Berufsbezogen)"`), um Parser-Fehler in Obsidian zu vermeiden.
- **Tabellen:** Komplexe Unterschiede oder Gegenüberstellungen (z. B. Rechtsformen, Liquiditätsgrade) sind übersichtlich in Markdown-Tabellen aufzubereiten.

