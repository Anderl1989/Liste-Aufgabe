# Liste-Aufgabe

Erstelle eine Webseite, die dir eine ToDo-, Wunsch- oder Einkaufsliste (oder eine Beliebige andere Art von Liste, die nach dem selben Prinzip funktioniert) anzeigt.

## Anforderungen
* Es sollte die Möglichkeit geben, Einträge hinzuzufügen und zu entfernen.
* Die Einträge sollen im Browser gespeichert werden (localStorage oder indexedDB).
* Eigene Erweiterungen sind gerne gesehen ;)
* Die Lesbarkeit vom Code wird auch beurteilt, achte also auf ordentliche Formatierung / Einrückungen, und nutze sinnvolle Variablen- und Funktionsnamen.

## Wenn du nicht weiter weist
Wenn du dir nicht sicher bist, wie du vorgehen sollst, versuche es schrittweise wie folgt, die Bewertung richtet sich dann danach, wie weit du gekommen bist:

### Schritt 0:
* Lege eine HTML (index.html) und eine JS Datei an. Lade die JS Datei im HTML und prüfe mit einer Consolenausgabe, ob die JS Datei richtig eingebunden ist.

### Schritt 1:
* Lese so lange vom Nutzer mit prompt() Einträge ein, bis er auf "cancel"/"abbrechen" drückt (der von prompt zurückgegebene Wert ist dann `null`).
* Gebe die eingelesenen Einträge nun auf der Konsole aus.

### Schritt 2:
* Gebe die eingelesenen Einträge im HTML aus.

### Schritt 3:
* Lese die Einträge nicht mehr mit prompt ein.
* Erstelle ein Eingabefeld und Button zum Hinzufügen neuer Einträge.

### Schritt 4:
* Ermögliche das Löschen von Einträgen.

### Schritt 5:
* Speichere die Einträge im Browser (localStorage oder indexedDB), und lade sie beim erneuten Öffnen der Webseite daraus.

## Bonuspunkte
Bonuspunkte gibt es für besonders schöne Gestaltung und eigene Erweiterungen (je nach Komplexität)

### Ideen für Erweiterungen
* ermögliche nicht nur löschen, sondern auch Abhaken von Einträgen
* lass den Nutzer auch Mengenangaben hinzufügen
* ermögliche dem Nutzer zwischen light & dark theme zu wählen, speichere die Auswahl
* denk dir selbst etwas aus!
