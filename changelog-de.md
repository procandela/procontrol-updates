# Changelogs

## 2.1.6
 - Die Änderung gegenüber dem letzten Release ist die integrierte automatische Maskierung bzw. Ausblendung/Verzögerung bestimmter Fehler und das daraus resultierende automatische Reset der Feuer (Betrifft nur procontrol v2)

## 2.1.4-1	
 - Liol-E Taktausgang erlaubt Logik, wenn Turmfeuer Takt = off
 - Diverse Fixes bei FTP-Upload der Logdateien

## 2.1.4	
 - Generierung des Liol-E Takts mit externem GPS

## 2.1.3	
 - Kompatibilität für neue Feuer Firmware

## 2.1.2-2	
 - GPS-Meldungen werden verzögert ausgegeben

## 2.1.2-1	
 - Unterstützung für ältere Logikformate

## 2.1.2	
 - Lizenzsystem für neue Features integriert
 - Modbus/TCP und Modbus/RTU implementiert (ALI-Modus und Digitale Ein- und Ausgänge)

## 2.1.1	
 - Einpflegen neuer Feuertypen
 - Eingabe der WEA-Nummer und Anzeige in Parkübersicht

## 2.1.0	
 - Angleichung des Codes und der Optik beider proControls
 - Rücksetzen des Sichtweitenmessgeräts nach Säuberung
 - Verzögerung Turmfeuer Fehler (Zeitrelais entfällt)
 - Anpassung der Hilfedatei

## 2.0.0-4 (nur v2)
 - Fehlerbereinigung
  
## 2.0.0-3 (nur v2)
 - Überarbeitung der Logikcontroller-Firmware und dadurch Korrektur kleinerer Fehler
 - Verbesserung der Erkennung defekter bzw. fehlerhafter Konfigurationsdateien
 - Kleinere Korrekturen von Schreibfehlern im Webinterface (inkl. Übersetzung)
 - Aktualisierung der Taktcode-Bezeichnungen
 - Erkennung und Anzeige von RS485-Kommunikationsproblemen mit den Feuern
 - Erkennen und Anzeige von Kommunikationsproblemen mit Logikcontroller

## 1.0.4-12 (nur v1)
 - Fehlerbehebung
  
## 1.0.4-10 (nur v1)
 - Anpassung der Darstellung des Status der Feuer
 - Begrenzung der System-Logdatei auf 2 MB
 - Überprüfung und ggf. Reparatur der SD-Karte bei Start

## 1.0.4-8 (nur v1)
 - Überwachung der Lichtsensor Warnungen des Gefahrenfeuers
 - Optimierung RS485 Kommunikation Gefahrenfeuer

## 1.0.4-2 (nur v1)
 - Halten des Turmfeuer-Fehlers am Tag
 - Korrektur der Anzeige des GPS Offset unter "Control & Config" bei proFeuer-Typen (nicht bei Kombifeuern)
 - Anzeige von Taktcode 09 als "DAY: ICAO 20fpm, NIGHT: off"
 - Button "Warnungen und Fehler zurücksetzen" jetzt unter "Control & Config" und für alle eingeloggten Benutzer nutzbar

## 1.0.4-1 (nur v1)
 - Eingang DI14 Überspannungsschutz wird als Warnung angezeigt

## 1.0.4 (nur v1)
 - Unterstützung für Tag/Nachtfeuer pro20A/B/W
 - Es können jetzt unterschiedliche proFeuer-Varianten angeschlossen werden. Der jeweilige Typ wird über RS485 ausgelesen. In Abhängigkeit vom Typ wird intern ein entsprechendes "Konfigurationsdatenmodell" ausgewählt, das vor allem die unterschiedliche Anzahl und Zuordnung von Reglern definiert. Entsprechend des Modells werden im Webinterface unter "Systemeinstellungen" die passenden Reglereinstellungen angezeigt und können dort auch geändert werden
 - Zusätzlich wird im Status neben Feuer 1 und Feuer 2 der jeweilige erkannte Feuertyp angezeigt
 - Für die neuen Feuertypen wurden entsprechende vordefinierte Geräte in der Seriennummerneingabe ergänzt
 - Verbesserung der Geschwindigkeit des Webinterface, die einzelnen Seiten werden jetzt schneller geladen und angezeigt
 - Automatischer Reset angeschlossener proFeuer beim Neustart proControl
 - Umstellung von GET auf POST Requests um Caching-Probleme bei Verwendung des Internet Explorers zu vermeiden
 - Verbesserung der Zuverlässigkeit des Updateprozesses: Unvollständig entpackte Updatedateien (z.B. bei vorzeitigem Neustart) können jetzt nicht mehr dazu führen, dass aus Versehen ungültige Daten in das Flash geschrieben werden
 - Korrekturen und Verbesserungen bei der Anzeige des MOR-Status
 - Sichereres Schreiben von Konfigurationsdateien auf SD-Karte