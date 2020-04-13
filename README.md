# Script-Developer-CCU


## Objektinspektor

![TITLE](https://user-images.githubusercontent.com/42892466/72174814-dc4ad400-33da-11ea-9565-21640b63a84f.jpg)

## Editor

![TITLE](https://user-images.githubusercontent.com/42892466/72174888-0dc39f80-33db-11ea-8a6f-3a201ab0a8dc.jpg)

![TITLE](https://user-images.githubusercontent.com/42892466/72174939-2df35e80-33db-11ea-9295-08b4ef87d9f0.jpg)


Bis auf weiteres ist hier pas Package weg und bis auf weiteres vergebe ich auch keine neuen Keys mehr.




Ab V3.09.XX:
------------
Ab V3.09.XX wird der SDV als 64bit targetsystem compiliert. Damit müssen auch die DLLs einer vorhandenen Installation gegen die des Packages ausgetauscht werden. die 32 bit Vorgängerversiopn V3.08.13 lasse ich erstmal noch Online. 


Features:
----------
Editor mit SyntaxHighlight und vervollständiger.

Scripte auf PC abspeichern und laden

Script ausführen

Ansicht der Ausgaben via WriteLine

Ansicht der verwendeten Scriptvariablen

Ansicht des Syslogs

Mit der Version 3.07.qq kennt der HighLighter und der Vervollständiger 620 Methoden und Konstanten

Markup im Editor 

Suchen von Systemvariablen, Geräten, Channels, Räumen und Gewerken in Scripten nach Namen

Suchen von Channels und Devices nach Seriennummern in Scripten

Programme Testen Option (Systaxcheck)


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

Suchen in Scripten (Namen oder freier Text, auch regular expressions


Backup Restore
---------------
Backups (von Räumen, Gewerken, etc für Systemumzug)

Backups von Systemvariablen

Backups von Geräte/ Kanalnamen

Backups von Programmen 

Backup von Mastersets von Geräten

Backup von Linksets von Geräten

Backup von WEBUI Einträgenvon Geräten (Kanalnamen, Räume, gewerke, Favoriten, verwendete Frogramme)


Kopieren von Geräten
--------------------
Kopie des Masterparametersatzes von einem Gerät in ein anderes (Auch HMIP)

Kopie der Wochenprofile innerhalb von HmIP Aktoren

Kopie von Heizprofilen zwischen Hmclassic,HmIP geräten und virtuellen Heizgruppen




Black im Januar 2020


---------------------------------
Aktuelle Version V3.10.02  (64bit Version)
---------------------------------


Ein paar kleinere Bugfixes

Gerätekopien Mastersets zwischen gleichen und ähnlichen Devices

Gerätekopien IP-Wochenprofile auch zwischen unterschiedlichen IP Geräten

Gerätekopien Heizprofile übergreifend zwischen HM, HMIP und Heigruppen möglich


---------------------------------
Changelog V3.09.05  (64bit Version)
---------------------------------


Ein paar kleinere Bugfixes

Programmkonsistenstest verschärft (Zeitmodule und Scripte und geisterChannel verweise)

Backup von Räumen Gewerken Fix eingeführt (Enumtypes sind durchgegangen)

Korrekturlauf für enums eingeführt, die diese Bezüge reparieren können

Fix bzw ungenauigkeit bei BackUp Linkset für ein gerät beseitigt

Aus Mastersets / Linkssets lassen  sich Werte markieren  und zum Auslesen der entsprechende Scriptcode generieren

Korrekturlauf CheckObjects (Richtiger Verweis und korrekter Gegenverweis)

Möglichkeit nach Name () oder Adress () eines Gerätes/Channel  in Scripten zu suchen

Möglichkeit in einem Programm die verwendeten Systemvariablen zu suchen

CheckDevices gegen XMLRPC Scnittstellenprozess eingeführt

Löschmöglichkeit von Devices nun auch xmlroc.DeleteDevices ()

Backup Device und Channelnamen nun über  die Selektieren Devices, nicht mehr über alle.


---------------------------------
Changelog V3.09.04
---------------------------------

Mittlerweile 64 Bit Compiliert (verwendete RAD: 2.0.4)

Diverse kleinere Bugfixes

Auflösen von Linksets möglich

Ändern von Namen und Beschreibungvon Linksets

Backup eines Linkssets 

Parameter im Linkset können markiert werden und automatischer Editorcodeerzeugt werden

Editor kann mit Human friendly JSON umgehen

Auflösen von Direktverbindungen selektierte Geräte

Sortieren derDirektverbindungen nach Sender, Empfänger

Finden Gleichartiger Geräte

Echtzeithilfe eingefügt

Automatische Codegenerierung für Datenpunkte (Vollsymbolischer Zugriff)

Konfigurierbarer Threatkill Timeout

Für die jeweiligen CCUs separates BackupDir eingefügt

Restore Möglichkeit, wenn ein Device gelöscht wurde, um sämtliche Punkte der WEBUI wieder zu rekonstruieren

Linkset Auflösen von Level6 auf Level 5 herabgesetzt

Master und Linkset Level von 6 auf 5 heruntergesetzt

Logmöglichkeit für Backup programme eingeführt


---------------------------------
Changelog V3.08.13
---------------------------------

- Verbesserung im Editor (Stringdelimiter angabe nicht mehr nötig)

- Highlighter verbessert in Hinsicht auf String und Kommentarverarbeitung

- Ansatz von Echtzeit Hilfe zu Methoden

- Möglichkeit ungültiger Dateinamen durch ein Backup-Programme beseitigt

- Diverse Kleinere Bugfixes

- B-Hash Berechnung entfernt, EQ3 kriegt unter bestimmten Vorraussetzungen keine valide B-Ausgabe hin)

- Filter für HUE und Lightify Geräte dem Package hinzugefügt

- Möglichkeit 10 Eigener Methoedenhilfen mit Tastenkurzanwahl

- Inspektor: Device mit allen Kanälen aus Raumlisten löschen

- Inspektor: Device mit allen Kanälen aus Gewerkelisten löschen

- Konsistenzcheck History DPS (Ungültige und verwaiste History DPs aufspüren und beseitigen)


---------------------------------
Changelog V3.08.10
-----------------------------

- Bugfix : Backup von Räumen / Gewerken und Sysvars speicherte nicht als Datei. (behoben)

- Neu: - SDV kann SingleConditons auch so bearbeiten, das indirekte Vergleiche möglich sind. (Patch für Konsistenzcheck fehlt aber noch !)

- Editor und Listendarstellung Schrift und Grösse änderbar

- History Datapoints hinzu

- Sortieralgorithmus der Listendarstellung optimiert

- Erkennen und Beseitigen von Conditionchannel und Destinationchannel Inkonsistenzen hinzugefügt

- ein kleiner Bugfic bei einem Ausgabetext

- Interne Modifikationen, so das für Scriptausführen nun nicht mehr ein interner Aufruf con CUXD gebraucht wird

- Wahlmöglichkeit über INI Datei: SSH Funktionalität über pling oder über CUXD

- Ein paar kleinere Fixes zur Verbereitung auf den Syntax checker

- Menügesteuerter RTU Upate

- Für Raspberrymatik muss die CUXD version Ungleich 2.3.0 sein !!!! aktuell heute 2.3.1

- SynchoEdit eingefügt

- Parallele Completitions eingefügt

- Echtzeit Completition für definierte Variablen eingefügt


---------------------------------
Changelog 3.08.04
-----------------------------

- ein paar weitere Methoden hinzugefügt (auch die neuen der aktuellen RMMatik)

- Backup Restore Funktionalität nun auch für Programme (Einzelne oder mehrere)

- Möglichkeit nun mehrere Instanzen des SDV zu öffnen, ohne dass sich die INI Dateien in die Quere kommen (Nur die erste   geöffnete Instanz, (Main) hat Schreibrechte auf die INI)

- Möglichkeit, dem SDV als Kommendozeilenparameter einen Dateinamen mitzugeben, damit ist bei Doppelklicken auf eine Datei automatisches öffnen des Scriptes im SDV möglich

- ein paar Änderungem in der internen Abarbeitung als Vorbereitung für die nächsten Steps

- Selektionshandling verbessert (ist nun schneller und Bildaufbau ist ruhiger, sor allem bei Multiselektionen

- Condition Inkonsistenz beseitigen verbessert (hat nun auch mein Produktivsystem glattgezogen)

- SSH kommt nun mit CUxd Aus und braucht plink nun doch nicht mehr (auch im Hinblick auf irgendwann mal Linux)

- Ein paar Methoden und Konstanten noch hinzugefügt

- Editor hat Funktion bekommen für Block auskommentieren und Auskommentieren entfernen (fand ich nützlich für Programmeentwickeln zum Testen)

- Masterparameter können direkt in den Editor als programmCode übernommen werden (Level 6) (unter Berücksichtung vom Gerät, dem Kanal und dem ValueType des Parameters)

- aus einer Selektierten Singledestination kann der Editor unter Seleketiert mit dem Neuen Menüpunkt "Singledestination Zugriff" direkt den programmcode zum selektireen der SDest erzeugen, um verzögert um in einem eigenen Script zu bearbeiten

- unter Methodenhilfe kann der Code zum Berechnen der "verzögert um" zeit direkt abgerufen werden.

- Sichten für Systemvariablen nun endlich fertig ausprogrammiert

- Favoritenansicht eingefügt Favoriten können aus der Listenübersicht übernommen werden, ein Doppelklick in der Favortienansicht auf ein Object führt zum Laden der Favoritenansicht in di Listenübersicht mit detaildarstellung des Selektierten Objectes (undo redo Browsing ist dabei berücksichtigt)


---------------------------------
Changelog 3.07.11
-----------------------------

Tab Scriptausgabe entfernt, dafür sitzt die Scriptausgabe nun in einem Fenster unter dem Editor (Grösse anpassbar)

Neue Keys eingeführt, um Script Run und Script Test auch über FKeys zu starten

Mit dieser Version kennt der SDV 620 Rega-Methoden und Konstanten

Methodenhilfe eingeführt

---------------------------------
Changelog 3.07.10
-----------------------------

Properties von Zeitmodulen und Singledestination / Singleconditions über Dropboxes änderbar

Systemvariablen Metadaten Check und Reparatur eingeführt

Systemvariablen NirvanaChannel Check und Reparatur eingeführt

---------------------------------
Changelog 3.07.07
-----------------------------

Ein Paar Methoden hinzugefügt

Reiter Scriptsuche fertiggestellt (ab level 6)

Damit nun möglich: Volltextsuche in allen Scripten

Selektiertbar, auch suchen in GeisterDestinations möglich

Suchen auch als Regular Expression möglich

Beschleunigte Suche in Ram möglich

ProgrammObjektanalyse


---------------------------------
Changelog 3.07.04
-----------------------------

Auflösung geändert und ein wenig das Design

Programm Testen hinzugefügt

Suchen in Scripten nach Seriennummern von Devices / Kanälen

Ein paar weiterer Methoden eingepflegt


---------------------------------
Changelog 3.07.02
-----------------------------

Bugfix (Bei aufgelösten Programmen funktionierte das Rückschreiben des Scriptes in das Programm nicht)

BugFix Beim Ändern von Strings in der Detailansicht wurde der Ursprungswert nicht als Vorschlag genommen

Umstellen der Dialoge auf TTaskDialog und Rauswerfen der Unit Windows, damit ist die Tür in Richtung Linus wieder spaltbreit auf

Class TSynEditMarkupHighlightAllCaret  ein wenig modifiziert, damit gehen nun Markups,

Setup für MarkUps und Anwählbar / Abwählbar

Suchen innerhalb von Scripten nach Namen von Systemvariablen, Geräten, Kanäle, Räumen und Gewerken

Reihenfolge von Singledestinations sind nun verschiebbar


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

