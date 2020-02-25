# OpenSource - Manifest for Softwareprojects

Goal of this document is to provide some guidance on how to adapt to open source projects.

The initial version of thisa document was created at the un conference JSpirit in Germany.

## Please Read carefully
Dieses Dokument stellt in keinster Weise eine rechtliche Beratung oder Empfehlung dar. Hier werden lediglich Punkte genannt die einem als Leitfaden dienen sollen.
Ideen, Anregungen und weitere Punkte sind sehr gerne gesehen und wir bitten explizit um PR's um dieses Manifest weiter auszuarbeiten.

## Use of Open Source

Die Welt der Open Source Projekte ist sehr vielgestalltig und es gibt die unterschiedlichsten Wege sich daran zu beteiligen.

Der erste Schritt besteht für die meisten Entwickler daraus, dass ein Open Source Projekt in irgend einer Weise verwendet wird.

Beginne wir mit dem einfachsten Weg, der Verwendung von Open Source Projekten. Hier handelt es sich meist darum, dass zum Beispiel dem eigenen Softwareprojekt eine Abhängigkeit hinzugefügt wird um vorhandene Implementierungen zu nutzen und nicht selber mit der Synthese dieser Funktionalität zu beginnen.

Hier ist, so wie es in der Softwareentwicklung propagiert wird, der Ansatz; Benutze was vorhanden ist und erfinde das Rad nicht neu.

### Welche Lizenzen kommen in der Open Source Welt zum Einsatz?
-> Link zu einer Liste von vorhanden Lizenzen
-> Link

* Welche gibt es?
* Kann ich eine Eigene Lizenz erstellen?
* Ich möchte explizit KEINE Lizenz verwenden
Wenn Du keine Lizenz benennst, oder in den Qulltexten im den Header der Sourcen vermerkt ist kommen einige Dinge in der Verwendeung auf einen zu.

Firmen könne oftmals deine Quelltext dann nicht einsetzen, da der rechtlioche Status in manchen Ländern nicht geklärt oder auch risikobehaftet ist. (dies ist keine Rechtsberatung !!!)

* Die WTFPL Lizenz
 
Ein paar Anregungen welche Lic oft in der Industrie verwendet werden. 

### Welche dieser Lizenzen kann ich in meinem Projekt verwenden?

Die wichtigste Frage die sich zu Beginn stellt ist die der Verwendung und des Einsatzes der daraus resultierenden Produkte/Dienstleistungen.

Verwende ich die Software lediglich selber/in der Firma?

Biete ich einen Dienst auf der Basis an?

Liefer ich ein Produkt aus?

[Choose a License](https://choosealicense.com/) bietet eine einfache und gute Unterstützung bei der Lizenzfindung, wichtig ist, dass man sich der Aufgaben seines "Produktes" und deren Verwendung sicher ist

### Was muss ich sonst noch beachten bei der Verwendung?
Beispielhaft sind hier einige Punkte genannt die zum Tragen kommen können. Wichtig ist in diesem zusammenhang, die jeweils betrachtete Lizenz, da sich hieraus die Unterschiede ergeben.


Source muss freigegeben werden, Lizenz muss mit ausgeliefert werden, 
 Das eigene Projekt muss die selbe Lizenz haben.....


### geben und nehmen
Wenn man selber Open Source Projekte einsetzt muss man sich darüber im Klaren sein, das in diesen Projekten sehr viel Arbeit anderer Menschen steckt. Sehr oft werden solche Open Source Projekte in der Freizeit und unendgeldlich entwickelt.

Wie kann man etwas diesem Projekt zurückgeben?

## Contribute to Open Source
Es gibt sehr viele und auch sehr individuelle Wege und Möglichkeiten wie man sich für ein Open Source Projekt bedanken kann. 

### Anerkennung
Fast jeder freut sich wenn er für seine geleistete Arbeit Annerkennung in irgend einer Form bekommt. Das kann ein Tweet auf Twitter, das kann die Erwähnung auf dem eigenen Blog oder auch eine nette email sein.

### Publicity
Die meisten Open Source Projekte leben von der Sichtbarkeit in der Community. Wenn ein Projekt einen hohen Bekanntheitsgrad aufweist, ist die Wahrscheinlichkeit dass sich ein weiterer Unterstützer sich diesem Projkekt anschliessen wird wesentlich höher. 
Ebenfalls werden solche Projekte eine längere aktive Lebensdauer aufweisen, da dieses Projekt nicht mehr nur von einer Person abhägig ist.

Nicht zu vernachlässigen ist ebenfalls der Bezug zu der Qualität der zur Verfügung gestellten Lösung. Wenn sich mehrere Personen mit dieser Implementierung aktiv auseinander setzen und einbringen, werden technische Schulden eher erkannt und könne behoben werden.

Einige Open Source Projekte sind auf Grund ihrer Popularität Vorlage für Industriestandarts geworden.

### Find a BUG
In Open Source Projekten befinden sich wie in jedem anderen Projekt auch Fehler. Das kann in der Dokumentation genauso sein, wie in der Implementierung. Alle Verbesserungen, die in Form von Fehlerbeschreibungen oder dem anlegen von Issues in dem jeweiligen Issuetracker dem Projekt zu Gute kommen helfen.

* In der Dokumentation
Findet man in der Dokumentation einen Fehler, so kommt es darauf an in welchem Medium diese Dokumentation zur Verfügung gestellt worden ist. Der Fehler und die gewünschte Verbesserung muss dem Open Source Projekt gegeben werden. Hilfreich ist es, wenn man im selben Zuge darauf hinweist, das die Änderung frei von eigenen Ansprüchen dem Projekt übergeben wird. Nur so kann diese Änderung zügig und unkompliziert übernommen werden.

* In der Implementierung
Wird ein Fehler in der Implementierung gefunden, so hilft es dem Projekt nur wenn dieser Fehler auch der Projektteam bekannt ist. Dazu ist eine Fehlerbeschreibung notwendig die es einer anderen Person ermöglicht unabhängig diesen Fehler zu reproduzieren. Die Beschreibung die hierzu notwendig ist, sollte direkt in dem zum Einsatz kommenden Issuetracker hinterlegt werden.

Die Beschreibung des Fehlers kann unterschiedlich erfolgen. Zum einen kann es allgemein in einem Text beschrieben werden wie man die Fehlersituation provoziert.
Möglich ist es auch, ein Stück Quelltext zu hinterlegen das die selbe Aufgabe hat wie der zuvor genannte Text. (StackOverFlow : Link zu MVE)

Wer an dieser Stelle noch einen Schritt weiter gehen möchte, kann dem Projekt in dem zum Einsatz kommenden Testframework den notwendigen (noch fehlschlagenden) Testcase liefern.

### Fix the BUG
Die nächste Stufe ist die Erstellung des Bug-Fix selbst. Hierbei liefert man dem Open Source Projekt neben der Beschreibung des Fehlers, falls noch nicht vorhanden, die Lösung selbst. 
Wichtig ist hierbei, das die gestellten Anforderungen an den Quelltext und weitere Formalitäten, die von dem Projekt gefordert werden, erfüllt sind.
Das beinhaltet meistens die Quelltext -formatierung, -dokumentation und einiges mehr.
Da die meisten Open Source Projekte in der Freizeit gepflegt werden, muss man ein wenig Geduld aufbringen.
Reaktionen können mitunter Tage/Wochen dauern. Es besteht kein Anrecht auf die Übernahme der gelieferten Quelltexte. Auch hier ist es hilfreich, wenn man bei der Überstellung der Quelltexte ausdrücklich der von dem Projekt verwendeten Lizenz zustimmt.
 
### Add feature
Eine weitere Stufe ist die Bereitstellung eines neuen Features. Hier nutzt man OpenSource Software und ist sehr aktiv an der Weiterentwicklung des Projektes interessiert. Für den Einsatz im eigenen Unternehmen kann dies sehr von Vorteil sein, da man die Software aktiv nutzt. Auch hier ist es wichtig mit den Maintainer aktiv zu kommunizieren und das neue feature abzustimmen, damit dieses feature auch Teil des OpenSource Projektes wird.


### Add project


## Verwalten eines Open Source Projektes
Mit der Betreuung eines Open Source Projektes ist viel Arbeit verbunden. Ein Open-Source-Projekt endet nicht mit der Veröffentlichung des Quelltextes. Anwender und Unterstützer werden mit Fehlerberichten und Funktionswünschen an einen herantreten und auch Quelltextänderungen beisteuern. In diesem komplexen System aus Geben und Neben ist es wichtig klare Regeln zu definieren. Ziel sollte es sein das die Regeln des Projektes klar, nachvollziehbar und öffentlich zugänglich sind. Hierbei muss es sich um messbare Kriterien handeln, die nach Möglichkeit nicht von der persönlichen Empfindung abhängen. 

### zu definierende Richtlinien
#### Kommunikationswege
In der heutigen Welt gibt es viele Kommunikationsmittel und jedes Projekt setzt auf unterschiedliche Medien. Manche Projekte verwenden einen Issue-Tracker für Fragen und Fehlerberichte, andere bevorzugen Frage über Mailinglisten oder ähnliche Tools. Auch hier kann der Anwender ohne klare Richtlinien schnell ungewollten Mehraufwand auslösen. Umso wichtiger ist es, klare Kommunikationsrichtlinien zu definieren und klar zu kommunizieren.

#### Quelltextänderungen
Wichtig ist es die Regeln, die zur Annahme von Quelltextänderung führen, klar und deutlich zu beschreiben. Als gängige Praxis hat sich hierfür eine `CONTRIBUTING.md`-Datei im Basis-Verzeichnis der Projektdateien etabliert. Angeführt werden sollte:
- Welche Quelltextkonvetionen eingehalten werden müssen, z.b. Formattierung
- Was der Mindestanspruch an automatisierten Tests ist
- In welcher Art und Weise Änderungen übermittelt werden sollen
- Welchen Bestimmungen man zustimmt mit der Übermittlung von Änderungen (Contributor License Agreement)

#### Entscheidungen
Als Maintainer eines Softwareprojektes muss man Entscheidungen treffen. Da diese auch manchmal zu Unmut unter den Verwendern bzw. Unterstützer führen, muss auf eine klare und offene Kommunikation zur Entscheidungsfindung geachtet werden. Am Besten definiert man im Projekt selbst, wie Entscheidungen getroffen werden, und wer ein Stimmrecht hat.

#### Veröffentlichung
Um Verwirrungen und unnötigen Mehraufwand zu vermeiden sollte man als Maintainer im Vorfeld auch definieren welche Umstände  zu einer Veröffentlich des Projektes führen. Einigen Unterstützern kann es unter anderem nicht schnell genug sein, bis ihr Beitrag veröffentlicht wird. Immerhin kann es sich um einen Fehler oder ein Feature handlen welches für sie eine hohe Priorität darstellt, aber per Definition des Maintainers keinerlei Veröffentlichung außerhalb des normalen Zyklus zu lässt. Damit diese Ungereimtheiten im Vorfeld verhindert bzw. vermindert werden, ist es anzuraten, bei Beiträgen im Vorhinein klar zu erwähnen wann die geplant Veröffentlichung ist. So wie klar zu definieren, welche Bedingungen erfüllt sein müssen für vorzeitige Veröffentlichung bzw. wie sich der Standardprozess für Veröffentlichungen gestaltet.

### Anerkennung
So wie man sich selbst freut über Anerkennung, so freut sich auch jeder Unterstützer über Anerkennung. Daher sollte man sich die Zeit nehmen und Unterstützer Anerkennung zu kommen lassen egal ob als Erwähnung in den Release-Notes, einem Tweet oder persönlich per E-Mail. Jedoch empfehlen wir zu erst den direkten Kontakt mit dem Unterstützer zu suchen, denn nicht jedem ist es Recht öffentlich genannt zu werden.

Als "Verwalter" eines Open-Source-Projektes besteht auch die Möglichkeit sich mit realen Gütern zu bedanken, wie z.b. Sticker, Postkarten oder Sonstigem. Der Kreativität sind in diesem Fall keine Grenzen gesetzt.

