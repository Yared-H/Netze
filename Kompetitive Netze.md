# Kompetitive Netze
<img style="float: right;" src="http://www.neuronalesnetz.de/nnbilder/large/patternassociator_large.gif" title="Schematische Darstellung eines kompetitiven Netzes mit 4 Input- (rot) und 3 Output-Units (grün).">

 - Kompetitive Netze laufen normalerweise mit einer Input- und einer Outputschicht, ohne Hidden-layer. <br>Die implementierung von einem oder mehrerer Hidden-layer ist jedoch möglich.
 - Kompetititive Netze "lernen" unüberwacht d.h. sie brauchen keine korrekte Output Vorgabe
 - Dieses Netz nutzt die "Kompetitiven Lernregeln".<br>Die Lernphase findet in 3 Schritten statt:
  1. Erregung
  2. Wettbewerb
  3. Anpassung der Gewichte

- Es kann passieren das die Gewichte einer oder mehrerer Outputunits so "stark" werden das sie den Wettbewerb gewinnen, unabhänging von ihrer input Information.Dies führt dazu das eine "sinvolle" Kategoriesierung nicht statt findet.<br>Um dem vorzubeugen kann man eine Begrenzung der Gewichtsvektoren für die Output units voher vornehmen.

### Anwendungsbereiche
- Filtern von Redundanzen, Alternative zur Faktorenanalyse
- Als vorgeschaltetes Netz für andere Netztypen z.b vor einen "Pattern Associator"


