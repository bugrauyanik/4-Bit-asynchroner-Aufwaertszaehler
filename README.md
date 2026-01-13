# 4-Bit asynchroner Vorwärtszähler

## Projektübersicht
Dieses Projekt umfasst den Entwurf und die Simulation eines **4-Bit asynchronen Vorwärtszählers** (Ripple-Counter). Es wurde als praktische Anwendung im Modul **Rechnerorganisation** entwickelt, um die Funktionsweise von sequenziellen Logikschaltungen und die Zeitverzögerungen in binären Zählersystemen zu untersuchen.

## Technische Spezifikationen
* **Zählertyp:** Asynchroner Binärzähler.
* **Zählbereich:** 0 bis 15 (Modulo-16).
* **Komponenten:** 4 kaskadierte Flipflops (J-K oder T-Typ).
* **Eingang:** Taktsignal (External Clock).
* **Softwareumgebung:** MATLAB/Simulink.

## Funktionsprinzip
Bei diesem asynchronen Zähler wird lediglich das erste Flipflop durch ein externes Taktsignal angesteuert. Jedes weitere Flipflop erhält seinen Taktimpuls vom Ausgang des jeweils vorhergehenden Flipflops. Dies führt dazu, dass die Zustandsänderungen zeitlich leicht versetzt nacheinander erfolgen (Ripple-Effekt), was für die Analyse von Laufzeitverzögerungen in der **Rechnerorganisation** von Bedeutung ist.

## Simulationsstruktur
Die beigefügte `.slx` Datei enthält das vollständige Schaltdiagramm in **Simulink**:
1. **Logikgatter:** Zur Steuerung der Flipflop-Zustände.
2. **Scopes:** Zur Visualisierung der Wellenformen und zur Überprüfung der Zählsequenz.
3. **Display:** Zur Anzeige des aktuellen Dezimal- oder Binärwerts.

---
*Akademisches Projekt - Rechnerorganisation.*
