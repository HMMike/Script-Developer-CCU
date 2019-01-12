# Script-Developer-CCU


Features:
----------
Editor mit SyntaxHighlight und vervollständiger.

Scripte auf PC abspeichern und laden

Script ausführen

Ansicht der Ausgaben via WriteLine

Ansicht der verwendeten Scriptvariablen

Ansicht des Syslogs

Mit der Version 3.07.01 kennt der HighLighter und der Vervollständiger 592 Methoden und Konstanten


Objectinspektor
---------------
DomScan nach Typen über die Rega

Listen nach Enums

Detailansichten der verschiedenen Objecttypen

Konsistenstests

Direktes Ändern von Daten

Löschen von Daten

Komplexe anwenderdefinierte Filtermöglichkeiten

Anwenderdefinierbare Methodensichten

Bearbeiten von Programmen

Übernahme von Scripten aus Programmen in Editor, Verändern und wider zurückladen in das Programm

Undo Stack fürRekursionsaufrufe,damit Browsing durch Ebenen möglich

Komplettes Zerlegen von Programmen in Rules, Conditions, SingleConditions, Destinations und SingleDestinations


Backup Restore
---------------
Backups (von Räumen, Gewerken, etc für Systemumzug)

Backups von Systemvariablen

Backups von Geräte/ Kanalnamen

Backups von Programmen (Milestone, coming in next versions)


Noch im Beta Status aber wird kontinuierlich erweitert

Black im Januar 2019

---------------------------------
Changelog 3.07.01
-----------------------------

Einige kleine Bugfixes

Vervollständigen von Zeitmodulen (CalendarDP)

Aufschlüssen von Programmen in Rules, Subrules, Condition, SingleCondition, Destination und Singledestinations

Detailansichten von Conditionsm Single Conditions, Destination und Singledestinations inkl rekursiver Auflösung

Erweitern der Methoden im Highlighter

Klartextübersetzung der Regakonstanten in der Detailansicht

Verfeinern des Undo Stacks (Browsing durch Programme)

Hinzufügen von Methoden beim User Object (Level 7)

Eine interne Änderungen zur Vorbereitung von Backup / Restore von Programmen


---------------------------------
Changelog 3.06.06
-----------------------------

Ab dieser Version Unterstützt der SDV die Neuen Eigenschaften der Raspberrymatik / CCU3: SSL Verbindungen und Authentifizierung über Nutzername-Password. Dazu mehr in einem separaten Kapitel

Verbessung des Undo Stacks im Inspektor

Kleinere interne Fixes und Veränderungen als Vorgriff auf die Kommenden Versionen

Bugfix bei Einstellungsspeichern, welcher dazu führte, das bei jedem neuen Speichern der Eintrag DPEnumUsagePrograms [R]=XXXX erneut geschrieben wurde.Da hatte sich ein Space ans Ende der Definition Table geschmuggelt. Bitte mal in die SDV.INI schauen und falls nötig, die überschüssigen Einträge löschen


---------------------------------
Changelog 3.06.04
-----------------------------

2 Bugfix aufgrund Rega Fehlern (DoubleQuotes und wissenschaftliche Notation)

TSynHighlighterClass angepasst: 2. KontantenTable eingeführt

Undo Stack eingeführt für den Inspektor, damit ist jetzt quasi Browsing durch die Rekursionsebenen 

Wegen Undo Stack Sicherheitsabfrage Rekursives Auflösen entfernt (geht ja nun via Undo wieder zurück)

Programme lösen nun Ihre Rules und Subrules auf (retriggern veränderbar)

Bei einem Script als SingleDestination ist dieses Script direkt in den Editor ladbar, dort veränderbar und auch wieder ins CCU Programm hochladbar.

Verzögert um dieses Scripts veränderbar aus dem SDV heraus

Diverse weitere Methoden und Konstanten hinzugefügt

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

