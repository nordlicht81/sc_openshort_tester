Smartcard Open Short Tester
============================

Mit dem Smartcard Open Short Tester wird eine Schaltunf mit dazughöriger Firmware implementiert, die dazu dient die wire bond Verbindungen von Chipmodulen in ISO 7816 konformen Smartcards zu testen. Die meisten handelsüblichen Chipkarten besitzen an allen Pins je eine Schutzdiode gegen Vcc und eine gegen GND. Werden diese Dioden in Durchlassrichtung mit einem konstanten Strom durchströmt, kann am Pin der übliche Spannungsabfall über die Diode von 0.5-0.7V gemessen werden. Werden diese Spannungsabfälle in allen  Kombinationen gemessen, kann man daraus für alle Pins ableiten, ob die Bondverbindungen durchgängig sind.

Funktionen
----------

Folgende Funktionen sollen von der Schaltung realisiert werden.

* Ansteuerung aller 8 Chipkontakte (C1-C8)
* Durchgängikeit Prüfen Einprägung eines Stroms und Messen einer Spannung
 * GND -> CLK
 * GND -> RST
 * GND -> I/O
 * CLK -> Vcc
 * RST -> Vcc
 * I/O -> Vcc
 * GND -> Vcc

### Commands

tbd

Schnittstelle
-------------

* RS232 Serial UART
* Versorgungsspannung +5V, GND

Anzeige über LEDs ?
