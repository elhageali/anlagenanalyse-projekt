Projektziel
Ziel des Projekts ist es, technische Anlagen eines Kundenprojekts mit einer Referenzanlagenliste abzugleichen, fehlende Systeme zu identifizieren und passende Artikelnummern aus dem EP-Katalog zuzuordnen. Dabei kommen automatisierte Datenanalysen und Fuzzy-Matching-Algorithmen zum Einsatz.

Datenquellen
Datei	           Beschreibung
Kundendatei	     Enthält Systeme aus realen Kundenprojekten (mehrere Gebäude).
Beispielobjekte	 Enthält vollständige Systemlisten typischer Gebäude (Referenz).
EP-Katalog	     Enthält Artikelnummern und Beschreibungen technischer Anlagen.

Vorgehensweise
Relevanzanalyse: Extraktion häufig vorkommender Systeme aus den Referenzdaten (z. B. ≥70 % der Gebäude).

Systemgruppenbildung: Gruppierung der Systeme je Kunden-Gebäude.

Fuzzy Matching (Teil 1): Abgleich der Kundensysteme mit der Referenzliste.

Fuzzy Matching (Teil 2): Zuordnung der nicht gematchten Systeme mit EP-Katalogeinträgen (Artikelnummern).

Genutzte Technologien
Python mit Jupyter Notebooks

Libraries: pandas, rapidfuzz, openpyxl

PowerPoint (pptx): Für Ergebnisvisualisierung

