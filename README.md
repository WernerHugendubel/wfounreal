![grafik](https://github.com/WernerHugendubel/wfounreal/assets/6709311/1881d7fb-cb66-49df-b675-073c35c92f89)# wfounreal
Entrepeneurshipwoche 23.01.24-26.01.24

Die Klasse 4A WI hat die Idee, in der Schule ein IOT-Projekt zu machen, mit dem alle Klassenräume mit einem Arduino NANO ESP32 und mehreren Sensoren überwacht werden können:
- Luftgüte
- Temperatur
- Feuchtigkeit
- Lautstärke
- ....
- ....
- ....
- ....
- ....

Die Daten sollen mit einem Raspberry PI 4 in einer Datenbank gespeichert werden, damit sie später analysiert werden können.

Vorgangsweise:

1. Tag
Einführung in Microcontroller mit Arduino Uno
  Led, Temperatursensor DHT 11 und 22, verschiedene Gassensoren, Mikrophon.
  Die Schüler bauen mit Breadboards mehrere Prototypen. Die Daten werden über Led visualisiert oder per seriellen Monitor angezeigt.

3. Tag
Einführung in die Geräteklasse ESP32, später in Arduino NANO ESP32 (Gerät hat den Vorteil dass es klein ist und WLAN und BT beherrscht.
Die Prototypen werden an die Arduino Nano ESP32 angepasst.

Die Datenbank (von ähnlichem Projekt vorhanden) auf dem Raspberry PI  wurde vorgestellt, eine Schülergruppe übernimmt die Anpassung an das Projekt wfounreal.
Eine weitere Gruppe testet den Code in Arduino, welcher Daten eines Sensors an die Datenbank per HTTP übermittelt.

Mit einem Schüler wurde das Protokoll I2S für die Audioverarbeitung mit dem MAX98573A (Verstärker für 4-8 Ohm - Boxen bis 3 Watt) getestet. 

3. Tag
Prof. Lochmann kommt in die Schule um den Schülern zur Seite zu stehen. Mit einem Schüler verwendet er das Programm KICAD um ein Platinenlayout für die Elektronik zu entwerfen mit der Open Source Software KiCAD.

Die Elektronik wird getestet, es sind drei Prototypen vorhanden.
Ein weiterer Schüler entwirft/sucht ein Gehäuse für die Elektronik.
Der endgültige Prototyp funktioniert, die Daten werden an die Datenbank übermittelt. Prof. Lochmann arbeitet mit zwei Schülern an der Erstelltung von SQL-Befehlen für die Analyse der Datenbank.
Fragestellungen waren u.A.: welches war die höchste Temperatur des Tages X, wie war die Luftqualität im EDV-Raum 3? usw.

4. Tag

Vorstellung des Projektes in einem 5 Minuten pitch.



Nice to have:
  Grafische Aufbereitung der Daten mit Chart.js
  Lärmmessung
  Audio-Übertragung über WLAN an die Klasen (Notrufe, Mitteilungen, Erinnerungen ...)
  ...
