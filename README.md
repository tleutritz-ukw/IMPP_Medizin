# IMPP_Medizin
Darstellung der Ergebnisse von M1 und M2 in ausführlicher und interaktiver Weise für den Vergleich von Ergebnissen an verschiedenen Hochschulstandorten.

Aktuelle Daten zu Prüfungsergebnissen im Fach Medizin vom [IMPP](https://www.impp.de/pruefungen/medizin/l%C3%B6sungen-und-ergebnisse.html) bzw. aus dem [Archiv](https://www.impp.de/pruefungen/medizin/archiv-medizin.html) - manuell aus den PDF-Dateien kopiert und im Notepad++-Editor Leerzeichen durch Tabulatoren ersetzt mit folgenden regulären Ausdrücken: 

([\w|\d])([ ])(\d) 

ersetzen durch

\1\t\3

Anschließend Daten rechts anfügen mit geänderten Spaltenüberschriften in Zeile 4 (enthalten jeweils die "Phase" als Suffix - s. Blätter mit Suffix "Bestehen"), zusammenfassende Daten (Anzahl gwerteter Aufgaben, Bestehensgrenzen, Anzahl Aufgabentypen bzw. Aufgaben pro Fach) in vorgenanntem Blatt.
