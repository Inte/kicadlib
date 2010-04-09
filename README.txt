= KiCad-Bibliotheken =
Tobias Kral <tobias@kral.ws>
v0.0.1, April 2010

== Designregeln ==

=== component ===
# Rasterauswahl: 50mil

==== Referenz ====
# Feldwert: 
# Platzierung: Oben, links am Bauteil.
# Abstand zum Rand des Schaltzeichens: 25mil
# Horizontale Ausrichtung: _Links ausrichten_
# Vertikale Ausrichtung: _Unten ausrichten_
# Größe: 0,04"

==== Wert ====
# Feldwert: Bauteilbezeichnung
# Platzierung: Unten, links am Bauteil.
# Abstand zum Rand des Schaltzeichens: 25mil
# Horizontale Ausrichtung: _Links ausrichten_
# Vertikale Ausrichtung: _Oben ausrichten_
# Größe: 0,04"

==== Pin ====
# Platzierung
## Abstand zu anderen Pins: 100mil
## Abstand zum Rand des Schaltzeichens: 50mil
# Größe der Beschriftung: 0,025"
# Größe der Nummerierung: 0,05"
# Länge: 0,2"

=== module ===

=== 3D-Wings ===

== Bibliotheken ==

=== din_en_60617.lib ===

=== linear_technology.lib ===
* LT1302CN8

== Links ==
* http://kicad.sourceforge.net/[KiCad-Wiki]
* http://www.kicadlib.org/[Bibliotheken]
* http://library.oshec.org/[Bibliotheken]
* http://www.mikrocontroller.net/articles/KiCAD[KiCad bei mikrocontroller.net]
* http://de.wikipedia.org/wiki/Liste_der_Schaltzeichen_(Elektrik/Elektronik)[Liste der Schaltzeichen (Wikipedia)]

== Lizenz ==
http://creativecommons.org/publicdomain/zero/1.0[Creative Commons Zero 1.0]

The person who associated a work with this document has dedicated the work to
the Commons by waiving all of his or her rights to the work worldwide under
copyright law and all related or neighboring legal rights he or she had in the
work, to the extent allowable by law.

Works under CC0 do not require attribution. When citing the work, you should
not imply endorsement by the author.

== Dokumentation ==
Die aktuelle Dokumentation liegt im AsciiDoc-Format
footnote:[http://www.methods.co.nz/asciidoc/] vor. Alle anderen Formate (PDF,
HTML, DocBook, etc.) können daraus generiert werden.

* http://powerman.name/doc/asciidoc[AsciiDoc cheatsheet]

*Verwendete Tools*
* http://www.vim.org/[Vim]
* http://code.google.com/p/msysgit/[mysysgit - Git on Windows]

[glossary]
http://kicad.sourceforge.net/wiki/index.php/Circuit_board_CAD_Terms[Circuit board CAD Terms]

component::
	Schematisches Symbol oder Schaltzeichen - Ein standardisiertes grafisches
Symbol zur Darstellung von Elementen in einem elektrischen Schaltplan. Es
behinhaltet alle Informationen zu den elektrischen Anschlüssen (Pins), sowie
deren Eigenschaften (Eingang, Ausgang, Spannungsversorgung, etc.). In Deutschland
sind sie durch die DIN EN 60617 genormt.

module::
	Footprint oder land pattern - Detaillierte Informationen zu Bauform und
Abmessungen der Elemente, sowie die Lage und Größe der zugehörigen
Lötaugen.

----
// vim: set syntax=asciidoc:
// vim: set enc=utf8:
----
