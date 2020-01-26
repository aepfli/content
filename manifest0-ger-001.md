# OpenSource - Manifest for Softwareprojects

Goal of this document is to provide some guidance on how to adapt to open source projects.

The initial version of thisa document was created at the un conference JSpirit in Germany.

## Please Read carefully
Dieses Dokument stellt in keinster weise eine rechtliche Beratung oder empfehlung dar. Hier werden lediglich Punkte genannt die einem als Leitfaden diehnen sollen.
Ideen, Anregungen und weitere Punkte sind sehr gerne gesehen und wir bitten explizit um PR's um dieses manifest weiter auszuarbeiten.

### Use of Open Source

Die Welt der Open Source Projekte ist sehr vielgestalltig und es gibt die unterschiedlichsten Wege sich daran zu beteiligen.

Der erste Schritt ist für die meisten Entwickler der, dass ein Open Source Projekt in irgend einer Weise verwendet wird.

Beginne wir mit dem einfachsten Weg, der Verwendung von Oepn Source Projekten. Hier handelt es sich meist darum, dass zum Beispiel dem eigenen Softwareprojekt eine Abhängigkeit hinzugefügt wird um vorhandene Implementierungen zu nutzen und nicht selber mit der Synthese dieser Funktionalität zu beginnen.

Hier ist, so wie es in der Softwareentwicklung propagiert wird, der Ansatz; Benutze was vorhanden ist und erfinde das Rad nicht neu.

#### Welche Lizenzen kommen in der Open Source Welt zum Einsatz?
-> Link zu einer Liste von vorhanden Lizenzen
* Welche gibt es?
* Kann ich eine Eigene Lizenz erstellen?
* Ich möchte explizit KEINE Lizenz verwenden
Wenn Du keine Lizenz benennst, oder in den Qulltexten im den Header der Sourcen vermerkt ist kommen einige Dinge in der Verwendeung auf einen zu.

Firmen könne oftmals deine Quelltext dann nicht einsetzen, da der rechtlioche Status in manchen Ländern nicht geklärt oder auch risikobehaftet ist. (dies ist keine Rechtsberatung !!!)


* Die WTFPL Lizenz
 

#### Welche dieser Lizenzen kann ich in meinem Projekt verwenden?
Die wichtigste Frage die sich zu Beginn stellt ist die der Verwendung und des Einsatzes der daraus resultierenden Produkte/Dienstleistungen.

Verwende ich die Software lediglich selber/in der Firma?

Biete ich einen Dienst auf der Basis an?

Liefer ich ein Produkt aus?


#### Was muss ich sonst noch beachten bei der Verwendeung?
Beispielhaft sind hier einige Punkte genannt die zum Tragen kommen können. Wichtig ist in diesem zusammenhang, die jeweils betrachtete Lizenz, da sich hieraus die Unterschiede ergeben.


Source muss freigegeben werden, Lizenz muss mit ausgeliefert werden, 
 Das eigene Projekt muss die selbe Lizenz haben.....


#### geben und nehmen
Wenn man selber Open Source Projekte einsetzt muss man sich darüber im Klaren sein, das in diesen Projekten sehr viel Arbeit anderer Menschen steckt. Sehr oft werden solche Open Source Projekte in der Freizeit und unendgeldlich entwickelt.

Wie kann man etwas diesem Projekt zurückgeben?

### Contribute to Open Source
Es gibt sehr viele und auch sehr individuelle Wege und Möglichkeiten wie man sich für ein Open Source Projekt bedanken kann. 

#### Annerkennung
Fast jeder freut sich wenn er für seine geleistete Arbeit Annerkennung in irgend einer Form bekommt. Das kann ein Tweet auf Twitter, das kann die Erwähnung auf dem eigenen Blog oder auch eine nette email sein.

#### Publicity
Die meisten Open Source Projekte leben von der Sichtbarkeit in der Community. Wenn ein Projekt einen hohen Bekanntheitsgrad aufweist, ist die Wahrscheinlichkeit dass sich ein weiterer Unterstützer sich diesem Projkekt anschliessen wird wesentlich höher. 
Ebenfalls werden solche Projekte eine längere aktive Lebensdauer aufweisen, da dieses Projekt nicht mehr nur von einer Person abhägig ist.

Nicht zu vernachlässigen ist ebenfalls der Bezug zu der Qualität der zur Verfügung gestellten Lösung. Wenn sich mehrere Personen mit dieser Implementierung aktiv auseinander setzen und einbringen, werden technische Schulden eher erkannt und könne behoben werden.

Einige Open Source Projekte sind auf Grund ihrer Popularität Vorlage für Industriestandarts geworden.

#### Find a BUG
In Open Source Projekten befinden sich wie in jedem anderen Projekt auch Fehler. Das kann in der Dokumentation genauso sein, wie in der Implementierung. Alle Verbesserungen, die in Form von Fehlerbeschreibungen oder dem anlegen von Issues in dem jeweiligen Issuetracker dem Projekt zu Gute kommen helfen.

* In der Dokumentation
Findet man in der Dokumentation einen Fehler, so kommt es darauf an in welchem Medium diese Dokumentation zur Verfügung gestellt worden ist. Der Fehler und die gewünschte Verbesserung muss dem Open Source Projekt gegeben werden. Hilfreich ist es, wenn man im selben Zuge darauf hinweist, das die Änderung frei von eigenen Ansprüchen dem Projekt übergeben wird. Nur so kann diese Änderung zügig und unkompliziert übernommen werden.

* In der Implementierung
Wird ein Fehler in der Implementierung gefunden, so hilft es dem Projekt nur wenn dieser Fehler auch der Projektteam bekannt ist. Dazu ist eine Fehlerbeschreibung notwendig die es einer anderen Person ermöglicht unabhängig diesen Fehler zu reproduzieren. Die Beschreibung die hierzu notwendig ist, sollte direkt in dem zum Einsatz kommenden Issuetracker hinterlegt werden.

Die Beschreibung des Fehlers kann unterschiedlich erfolgen. Zum einen kann es allgemein in einem Text beschrieben werden wie man die Fehlersituation provoziert.
Möglich ist es auch, ein Stück Quelltext zu hinterlegen das die selbe Aufgabe hat wie der zuvor genannte Text. (StackOverFlow : Link zu MVE)

Wer an dieser Stelle noch einen Schritt weiter gehen möchte, kann dem Projekt in dem zum Einsatz kommenden Testframework den notwendigen (noch fehlschlagenden) Testcase liefern.

#### Fix the BUG
Die nächste Stufe ist die Erstellung des Bug-Fix selbst. Hierbei liefert man dem Open Source Projekt neben der Beschreibung des Fehlers, falls noch nicht vorhanden, die Lösung selbst. 
Wichtig ist hierbei, das die gestellten Anforderungen an den Quelltext und weitere Formalitäten, die von dem Projekt gefordert werden, erfüllt sind.
Das beinhaltet meistens die Quelltext -formatierung, -dokumentation und einiges mehr.
Da die meisten Open Source Projekte in der Freizeit gepflegt werden, muss man ein wenig Geduld aufbringen.
Reaktionen können mitunter Tage/Wochen dauern. Es besteht kein Anrecht auf die Übernahme der gelieferten Quelltexte. Auch hier ist es hilfreich, wenn man bei der Überstellung der Quelltexte ausdrücklich der von dem Projekt verwendeten Lizenz zustimmt.
 
#### Add feature


### Aus der Sicht des Maintainers

Ziel sollte es sein das die Regeln, die zur Annahme von Quelltextänderung führen, bakannt und deútlich beschrieben sind. Hierbei muss es sich um messbare Kriterien handeln, die nach Möglichkeit nicht von der persönlichen Empfindung abhängen.


Wie kommt das Team zu Entscheidungen: Regeln und ..

Tips:

Postkarte für coole Änderungen 
