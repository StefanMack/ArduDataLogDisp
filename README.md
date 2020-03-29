# Messdaten mit einem Arduino Uno aufnehmen und mit Python grafisch animiert darstellen oder in Datei loggen

Für das Erfassen von Sensormesswerten im Rapid Prototyping ist oft ein einfacher Arduino Uno Mikrocontroller völlig ausreichend. Die Messwerte können schon innerhalb der Arduino IDE in Texform und teils auch grafisch dargestellt werden, wenn sie vom Arduino über die serielle Schnittstelle an den PC übertragen werden.
Es gibt auch fertige Software, die Messdaten zusätzlich in eine Datei schreibt, also die Funktion eines Datenloggers erfüllt.

Beides, die animierte grafische Darstellung der Messdaten wie auch das Loggen, kann auch mit Python-Skripten bewerkstelligt werden. Nachfolgend wird jeweils ein Lösungsansatz hierfür inklusive des C-Quellcodes für den Arduino vorgestellt.

Wichtige Info:
Der Quellcode dieses Jupyter-Notebooks kann nicht innerhalb des Browsers ausgeführt werden. Zum Testen der Beispielprogramme sollte deren Quellcode z.B. in einer Python-Konsole oder unter der Python-IDE Spyder ausgeführt werden.

Zudem ist ein via USB angeschlossener Arduino mit der entsprechenden Firmware (C-Programm) nötig, dessen Schnittstelleninformation im Python-Code angepasst werden muss. Die vom Arduino im PC belegte Schnittstelle kann man z.B. in der Arduino-IDE nachschauen.  

> Hinweis: Wenn Sie oben im File Explorer auf eine der beiden Jupyter Notebooks (Endung ".ipnyb") klicken, dann wird lediglich ein Viewer geöffnet, in dem Sie das Notebook nur anschauen können. Oft funktioniert dieses Verfahren jedoch nicht fehlerfrei.  
**Zum Anschauen verwenden Sie daher bitte den speziellen Viewer für Jupyter-Notebooks "nbviewer" [über diesen Link](https://nbviewer.jupyter.org/github/StefanMack/ArduDataLogDisp/blob/master/ArduDataLogDisp.ipynb).**

**Das Ausführen der in diesem Jupyter-Notebook enthaltenen Python-Quellcodes ist leider nicht möglich, da eine serielle Verbindungen zu einem Arduino mit entsprechener Firmware dafür nötig ist.**

License
-----
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons Lizenzvertrag" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />Dieses Werk ist lizenziert unter einer <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Namensnennung - Weitergabe unter gleichen Bedingungen 4.0 International Lizenz</a>.
