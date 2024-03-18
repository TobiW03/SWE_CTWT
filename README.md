# SWE_CTWT
Softwareengineering Medtech Tilg &amp; Wannenmacher

# Leistungstest - SWE Repository
## Name und Identifikationsnummer
    UC 1.03 (Alarm bei zu hoher Herzfrequenz)
## Beschreibung
    Während dem Leistungstest wird beim Überschreiten eines Maximalspulses eine Warnung angezeigt, damit der Test abgebrochen werden kann.
## Beteiligte Akteure
    - Diagnostiker:in 
    - Proband:in
## Status
    In Arbeit
## Verwendete Anwendungsfälle
    UC 1.07 (Abbruch des Leistungstests)
## Auslöser
    Überschreitung des Maximalpulses von Proband:in
## Vorbedingungen
    UC 1.01 (Probandin anlegen), UC 1.02 (Leistungstest anlegen)
## Invarianten
    UC 1.01 (Probandin anlegen), UC 1.02 (Leistungstest anlegen), UC 1.04 (Alarm bei Leistungsabweichung), UC 1.05 (Laktatmessung eingeben), UC 1.06 (Anstrengungsbewertung mittels BORG-Skala durch Proband:in)
    Die Leistungsaufzeichnung bis zum Abbruch der Leistungsaufnahme
## Nachbedingung/Ergebnis
    Eine Warnung wird ausgegeben und der Test kann daraufhin abgebrochen werden.
## Standardablauf
    Der Leistungstest wird durchlaufen (UC1.01, UC1.02) 
    - Proband:in hat eine hohe Herzfrequenz 
    - ein Alarm wird ausgegeben und Diagnostiker:in kann den Test abbrechen
## Alternative Ablaufschritte
    Der Proband:in hat während dem ganzem Test eine Herzfrequenz im Normbereich und der Leistungstest wird ohne Alarmausgabe beendet.
## Hinweise
    Grenzwerte für die Frequenz sind noch zu klären, müssen jedoch voraussichtlich vor dem Leistungstest ermittelt werden.
## Änderungsgeschichte
    0.01; 18.03.2024.; Carina Tilg & Tobias Wannenmacher
