# HyperCube-parameterized

**quick guide**

Build your own invidual HyperCube Evolution 3D-printer in just seconds in any size you want. Simply set the desired size of the building space in the spreadsheet. Your computer will calculate the right printer for you, with all the appropriate printed parts you need. (This printer is still in progress and not finished yet, but what is there works fine. It was constructed with FreeCAD 0.19)

**Anleitung in Deutsch**

Dieser 3d-Drucker ist mit der folgenden Betriebssystem und FreeCAD-Version konstruiert worden:<br>
OS: Windows 11 Professional<br>
Word size of OS: 64-bit<br>
Word size of FreeCAD: 64-bit<br>
Version: 0.19.24291 (Git)<br>
Build type: Release<br>
Branch: releases/FreeCAD-0-19<br>
Hash: 7b5e18a0759de778b74d3a5c17eba9cb815035ac<br>
Python version: 3.8.6+<br>
Qt version: 5.15.2<br>
Coin version: 4.0.1<br>
OCC version: 7.5.0<br>
Locale: German/Germany (de_DE)

Starteprozess:
Zum Starten die "HCE Printer asm 1l" Datei mit FreeCAD 0.19 öffnen. Die Datei findest du im Ordner: "Assembly Printer" > "Zusammenbau ganzer Drucker". Alle verlinkten Dokumente werden entsprechend geladen und verlinkt.

Ladeprozess: (partial geladene Dokumente)
Falls ein paar Dokumente nur partial geladen werden (sieht man daran, dass das Dokumentsymbol grau statt bund ist) einfach mit Doppelklick auf das entsprechende Symbol klicken. Es wird damit erneut aufgerufen und vollständig geladen.

Einstellungen der Parameter:
Die Parameter kann man unter dem Dokument "parametric contol" eingeben. Es kann man relativ weit oben im Baum finden. Klickt man dieses Dokument an, erscheint dann auch die entsprechende Tabelle. Nach der Eingabe der gewünschten Daten muss das "HCE Printer asm..."- Dokument durch Doppelklick aktiviert werden und durch den Button mit den zwei sich drehenden blauen Zeigern, aktualisiert werden. Je nach Rechenleistung des Computers, kann der Rechenvorgang einige Sekunden bis Minuten dauern.

Abspeicherprozess: (zum verhindern eventueller Programmabstürze)
Zum Abspeichern die Standart-Parameter-Werte in die Parametertabelle eingeben. Wenn dies nicht getan wird, kann das Programm abstürzen (Computer mit so vielen Änderungen überlastet?). Wenn man die Parameter-Standartdaten bleibend ändern möchte, sollte man vorerst jedes einzelne verlinkte Dokument einzeln abspeichern, dann die Paramterdatei und dann den gesamten Zusammenbau.
