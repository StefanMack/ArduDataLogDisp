# Messdaten mit einem Arduino Uno aufnehmen und mit Python grafisch animiert darstellen oder in Datei loggen

Für das Erfassen von Sensormesswerten im Rapid Prototyping ist oft ein einfacher Arduino Uno Mikrocontroller völlig ausreichend. Die Messwerte können schon innerhalb der Arduino IDE in Texform und teils auch grafisch dargestellt werden, wenn sie vom Arduino über die serielle Schnittstelle an den PC übertragen werden.
Es gibt auch fertige Software, die Messdaten zusätzlich in eine Datei schreibt, also die Funktion eines Datenloggers erfüllt.

Beides, die animierte grafische Darstellung der Messdaten wie auch das Loggen, kann auch mit Python-Skripten bewerkstelligt werden. Nachfolgend wird jeweils ein Lösungsansatz hierfür inklusive des C-Quellcodes für den Arduino vorgestellt.

Wichtige Info:
Der Quellcode dieses Jupyter-Notebooks kann nicht innerhalb des Browsers ausgeführt werden. Zum Testen der Beispielprogramme sollte deren Quellcode z.B. in einer Python-Konsole oder unter der Python-IDE Spyder ausgeführt werden.

Zudem ist ein via USB angeschlossener Arduino mit der entsprechenden Firmware (C-Programm) nötig, dessen Schnittstelleninformation im Python-Code angepasst werden muss. Die vom Arduino im PC belegte Schnittstelle kann man z.B. in der Arduino-IDE nachschauen.
