Anforderungen Pico SDX
======================

Das soll es haben
-----------------

- Sendeleistung 20 W
- Betriebsarten:
    - SSB
    - WSPR
    - (CW)
- Bänder:
    - Kurzwelle
    - Unterstes Band: 80 Meter
    - Oberstes Band: 10 Meter
    - 4 bis 8 Bänder
- Stromversorgung:
    - Lithium-Akku (Rundzellen oder Modellbauakkus)
    - Ladeschaltung
    - USB-PD oder Rundstecker?
- Weitgehend tragbar (mindestens im Rucksack)
- Open Source Hardware, Firmware und Software
- PCB-Design in KiCAD

Damit würde ich beginnen, würde aber auch davon abweichen:
----------------------------------------------------------

- Microcontroller: RP2040
- Sprache:
    - Firmware: Micropython / Circuitpython
    - PC-Software: Python
- Antennenanschluss: BNC 50 Ohm
- Möglichst viele SMD-Komponenten / hybride Footprints
- Möglichst viele Komponenten aus dem  JLC Bestückungskatalog
- I2S Mikrophon und Lautsprecherverstärker
- Modularer Aufbau:
    - Stromversorgung
    - Filter
    - HF Platine
    - Digitalteil
    - Audioteil / PC-Verbindung
    - User Interface (Display, Schalter)

Offene Fragen:
--------------

* Gibt es gängige PC-Anwendungsschnittlstellen (USB-Soundkarte, UART-Protokoll, SDR-Treiber, ...)?
* Ist ein Wasserfalldiagramm umsetzbar?
