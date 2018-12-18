# Script-Develover-CCU


Features:
----------
Editor mit SyntaxHighlight und Vervollständiger.

Editor mit Undo / redo - Find - Replace

Scripte auf PC abspeichern und laden

Script ausführen

Ansicht der Ausgaben via WriteLine

Ansicht der verwendeten Scriptvariablen

Ansicht des Syslogs


Objectinspektor
---------------
DomScan nach Typen über die Rega

Listen nach Enums

Detailansichten der verschiedenen Objecttypen

Konsistenstests

Direktes Ändern von Daten

Löschen von Daten

Komplexe anwenderdefinierte Filtermöglichkeiten


Noch im Beta Status aber wird kontinuierlich erweitert

Black im November 2018

---------------------------------
Changelog 3.06.01
-----------------------------

BugFix Backup Sysvars (Alarme kann halt der Status nicht herstellt werden und 950er kann nicht rekontruiert werden. Dafür Sonderfunktionen

Bugfix Highlighter (in HM Script ist // kein kommentar)

Paramset Master Aufschlüsselung (ab Level 6)

Editor Zusatzfunktionen um Werte aus der Detailsicht in ein Script zu kopieren

DiagnoseBild

Restaurieren einer kaputten oder fehlenden 950er Präsenzvariable (ab Level 7)

Anzeigen aller Systemkonstanten

Rega Event Push auf DPs (ab level 7)

---------------------------------
Changelog 3.05.06
-----------------------------

Multithreading eingeführt für CCU Zugriff, Ping, etc (sollte keine Hänger mehr geben)

TSynHighlighterClass umgeschrieben, im Gegensatz zur originalen Version arbeitet meine nun CaseSensive wie auch die CCU

Weitere Methoden eingefügt in Highlighter, Autocomplete und Detailansicht.

Detailansicht für Datenpunkte, Alarme, Systemvariablen, Devices und Channels komplettiert

Auf Sonderwunsch unseres Stammtischs Programme schon mal provisorisch mit ProgramCopyID Test eingefügt

Ein paar Standartfilter geschrieben und der Version im Rar beigefügt (*flt Dateien)

Umbenennen von DeviceKanälen nach dem Namen des übergeordneten Devices

Backup und Restore von Devicekanälen

Temporäre Lizenzen nun möglich


---------------------------------
Changelog 3.05.04
-----------------------------
Hotfixes eingearbeitet

Einige Programmungenauigkeiten beseitigt

Threats eingeführt für http clients

definierbare Views eingeführt für erstmal devices und channels


---------------------------------
Changelog 3.05
-----------------------------
Einige Programmfehler beseitigt.

Endlich die Codierung zwischen LZL und dem WebServer richtig in Griff bekommen

Device Objekt in Auswahl hinzu und Detailansicht 

Systemvariablen Objekt vervollständigt

Alarm Objekt angelegt und vervollständigt

Metadaten Aufschlüsselung

Backup Methoden für Räume, Gewerke und Systemvariablen


---------------------------------
Changelog 3.04:
---------------------------------
Einige Programmfehler beseitigt.

Variable Fenstergössen im Inspektor

Anzeige zur CCU Nummer die Hinterlegte IP

Scriptnamen Anzeige ohne Pfade (Länge der Anzeige)

Löschen von Objekten

Selektionen aus Selektionen

Sichern und Zurückholen von Selektionsfeldern (PIN)

Merken von Selektionen und übernahme als Enum in den Scripteditor

Rekursives Auflösen der Detaildarstellung

Einige interne Änderungen, um die nächsten Steps der Roadmap effiktiver zu ermöglichen

----------------------------------
Changelog V3.03
---------------------------------
Listendarstellung Sortieralgorithmus geändert

Kleine programminkonsistenzen beseitigt.

Feld Objecttyp in Listendarstellugn hinzu

Schreibfehle rbei $src$ beseitigt.

ObjectSelektion hinzugefügt

