# Vorgehensmodelle zur Projektdurchführung

## Definition und Charakterisierung von Vorgehensmodellen
Ziel einer Projektorganisation ist es, eine Software unter Berücksichtigung der Gesichtpunkte von Kosteneinhaltung, Termineinhaltung und Qualitätserfüllung zu liefern. Vorgehensmodelle dienen dabei als Werkzeuge für die Projektorganisation, indem sie die Grundlage für die Planung, Überwachung und die Steuerung des Projekts bilden.

## Klassische Vorgehensmodelle
Zu den klassischen Vorgehensmodellen (auch sequenzielle Vorgehensmodelle oder Phasenmodelle genannt) zählen Wasserfall- und Schleifenmodelle. Diese teilen das Projekt in Phasen ein, die (streng) sequenziell ablaufen. Im Wesentlichen werden folgende Phasen in den verschiedenen Phasenmodellen beschrieben:

* Problemanalyse und Grobplanung
* Systemspezifikation und Planung
* System- und Komponentenentwurf
* Implementierung und Komponententest
* System- und Integrationstest
* Betrieb und Wartung

Als Grundlage nutzen klassische Vorgehensmodelle einen Top-Down-Ansatz, d. h. man startet mit einer abstrakten Beschreibung des Problems und konkretisiert dieses mit jedem Schritt. Dabei sind die einzelnen Phasen strikt voneinander getrennt und ein Übergang von einer Phase in die nächste Phase setzt den Abschluss der gegenwärtigen Phase voraus. Nach erfolgreicher Beendigung einer Phase liegen Dokumente und Fortschrittsberichte vor. Diese werden in der nächsten Phase als Grundlage genutzt und verarbeitet. Rücksprünge in vorherige Phasen sind nur an zuvor definierten Zeitpunkten oder Projektabschnitten zulässig.

### Wasserfallmodell
Das Wasserfallmodell wurde 1970 von Winston W. Royce vorgestellt und zählt zu einem der ersten Vorgehensmodelle. Es wurde im Laufe der Zeit an aktuelle Softwareanforderungen angepasst, wodurch es Abweichungen bei der Anzahl sowie der Einteilung der inhärenten Phasen zwischen den verschiedenen Spezialisierungen gibt. Abbildung 1 zeigt eine Spezialisierung, die insgesamt acht Phasen beinhaltet, wobei jede Phase mit einer Qualitätskontrolle abschließt. Ist diese Qualitätsprüfung nicht zufriedenstellend, sieht das Modell entweder ein erneutes Durchlaufen der Phase oder einen Rücksprung in eine vorherige Phase vor. Werden durch die Validierung keine erheblichen Qualitätsmängeln festgestellt, erfolgt auf Basis der Arbeitsergebnisse der Übergang in die nächste Phase.

<figure style="width:600px;">
    <img src="https://raw.githubusercontent.com/ProjektManagementGruppe3/Ausarbeitung/master/include/daniel/wasserfallmodel2.PNG"  />
    <figcaption>
        Abbildung 1: Wasserfallmodell zur Softwareentwicklung nach Aichele
    </figcaption>
</figure>

Das Wasserfallmodell minimiert den Mehraufwand bei der Planung, weil die gesamte Planung schon im Voraus erledigt werden kann. Es liegen keine Ergebnisse in Form von Software bis zum Ende des Lebenszyklus vor, jedoch kann die erstellte Dokumentation für jemanden, der mit ihr vertraut ist, ein aussagekräftiger Hinweis auf den Fortschritt des Projekts sein. Ein großer Nachteil des Wasserfallmodells ist seine mangelnde Flexibilität. So müssen zu Beginn des Projekts die Anforderungen vollständig spezifiziert werden, was Monate oder Jahre vor dem Zeitpunkt sein kann, an dem überhaupt irgendwelche lauffähige Software vorliegt. Infolgedessen kann auf spät erkannte Risiken auch nur schwer Rücksicht genommen werden.


### Spiralmodell
Eine Verfeinerung des Wasserfallmodells stellt das Spiralmodell dar, welches erstmals im Jahre 1988 durch Barry W. Boehm vorgestellt wurde. Beim Spiralmodell handelt es sich um ein evolutionäres Modell, dass einerseits den Gesamtaufwand des Projektes und andererseits den Projektfortschritt in den einzelnen Spiralzyklen darstellt. Das Spiralmoddell ist ein risikoorientiertes Vorgehensmodell, das ein Projekt in Miniprojekte aufteilt. Jedes Miniprojekt beschäftigt sich mit einem oder mehreren großen Risiken bis alle großen Risiken behandelt wurden. Ein Risiko ist dabei grob definiert und kann sich auf schlecht erfasste Anforderungen, eine schlecht erfasste Architektur, potentielle Performanceprobleme, Probleme in der zu Grunde liegenden Technologie oder Ähnliches beziehen. Nachdem alle Hauptrisiken behandelt wurden, endet das Spiralmodell wie das Wasserfallmodell.

<figure style="width:600px;">
    <img src="https://raw.githubusercontent.com/ProjektManagementGruppe3/Ausarbeitung/master/include/daniel/spiralmodell.PNG"  />
    <figcaption>
        Abbildung 2: Spiralmodell zur Softwareentwicklung nach Aichele
    </figcaption>
</figure>

### Vor- und Nachteile der klassischen Vorgehensmodelle

**Vorteile**
* Einfache und klare Vorgehensweise.
* Gute Komplexitätsbeherrschung und damit auch für große Projekte geeignet.
* Hohe Effizienz bei bekannten und konstanten Anforderungen.
* Erhöhte Transparenz.

**Nachteile**
* Planungs- und Entwicklungsfehler können erst spät erkannt werden.
* Risiken sammeln sich am Ende des Prozesses („Big Bang“).
* Durch den starren Ablauf sind Änderungen an den Projektanforderungen oftmals nicht mehr möglich oder nur schwer zu bewerkstelligen und mit hohen Kosten verbunden.

## Moderne Vorgehensmodelle
Im Gegensatz zu den klassischen Vorgehensmodellen zeichnen sich moderne Vorgehensmodelle durch eine höhere Flexibilität gegenüber auftretenden Änderungen, die bessere Transparenz der Projekte und Ergebnisse sowie die verstärkte Einbindung des Endnutzers in den gesamten Projektverlauf aus. Zu den modernen Vorgehensmodellen zählen u. a. das V-Modell und das Rational-Unified-Process-Modell (RUP-Modell).

### V-Modell
Das V-Modell wurde ursprünglich für das Deutsche Bundesministerium für Verteidigung und das Bundesamt für Wehrtechnik und Beschaffung konzipiert (V-Modell 97). Neben dem Einsatz in Bundeseinrichtungen konnte das V-Modell, durch die organisationsneutrale Konzeption des Modells, weiterhin in Unternehmen verschiedener Branchen, z. B. Banken oder Versicherungen, zur Entwicklung von Informations- oder Softwaresystemen integriert werden. Geprägt wird das V-Modell durch eine V-ähnliche Architektur, welche auf die Begriffe Validierung und Verifikation zurückzuführen ist. Die Verifikation überprüft dabei die Korrektheit des Systems (= Übereinstimmung mit der Spezifikation), während die Validierung die Angemessenheit des Systems an die Problemstellung sicherstellen soll. Hierzu spezifizieren die potenziellen Nutzer des Systems Anwendungsszenarien, anhand derer das Gesamtsystem validiert wird. Die Phasenergebnisse sind wie beim Wasserfallmodel bindende Vorgaben für nächsttiefere Projektphase. Des Weiteren folgt das V-Modell einer Unterteilung in die drei Ebenen Vorgehensweise (Was ist zu tun?), Methode (Wie ist es zu tun?) und Werkzeuganforderungen (Womit ist etwas zu tun?). Danach folgt jeweils eine Zuordnung dieser Ebenen zu den vier Submodellen Projektmanagement, Systemerstellung, Qualitätssicherung und Konfigurationsmanagement. In jedem der Submodelle sind die drei grundsätzlichen Rollen des Managers, des Verantwortlichen und des Durchführenden vertreten, die abhängig vom Submodell zu verschiedenen Verantwortungsbereichen und entsprechenden Stellen führen.

<figure style="width:600px;">
    <img src="https://raw.githubusercontent.com/ProjektManagementGruppe3/Ausarbeitung/master/include/daniel/v-modell.PNG"  />
    <figcaption>
        Abbildung 3: V-Modell zur Softwareentwicklung nach Aichele
    </figcaption>
</figure>

V-Modell 97 wurde 2004 durch das V-Modell XT ersetzt. In dieser Version wurde verstärkt auf eine flexiblere Anpassbarkeit des Modells eingegangen woraus sich auch die Bezeichnung XT ableitet, die für Extreme Tailoring steht, also der Fähigkeit stark an die jeweiligen Bedürfnisse anpassbar zu sein.

### Rational-Unified-Process-Modell
Das Rational-Unified-Process-Modell ist ein iteratives ist ein kommerzielles Produkt der Firma Rational Software. Es beinhaltet sowohl ein Vorgehensmodell zur Softwareentwicklung als auch die dazugehörigen Softwareentwicklungsprogramme. IBM entwickelt den RUP und die zugehörige Software weiter. RUP liefert eine Methode zur Softwareentwicklung auf Basis der Unified Modeling Language. Im Kern folgt der RUP den folgenden drei Grundprinzipien:
* RUP ist anwendungsfallgetrieben.
* Die Architektur steht im Zentrum der Planung.
* Das Vorgehen zur Entwicklung ist inkrementell/iterativ.

Zur Visualisierung wird ein zweidimensionales Koordinatensystem verwendet, in dem die Phasen auf der horizontalen Achse und die Disziplinen auf der vertikalen Achse eingetragen werden. Durch die Schwerpunkte in den einzelnen Phasen und die Anzahl der damit verbundenen Tätigkeiten entsteht das typische „RUP-Gebirge“.

Das RUP-Modell teilt den Ablauf eines Projektes in vier zeitlich geordnete Phasen auf, die in mehreren Iterationen behandelt werden können:

* Inception (Projektsetup/Konzeption)
Diese erste Konzeptionsphase hat das Ziel einer gemeinsamen Vision, eines klaren Zieles sowie der Erstellung eines rudimentären Anwendungsfallmodells, welches die wesentliche Funktionalität beschreibt sowie einer tentativen/provisorischen Architektur. Darüber hinaus werden die wesentlichsten Risiken identifiziert und die Ausarbeitungsphase geplant.

* Elaboration (Ausarbeitung/Entwurf)
In dieser Phase wird ein Architekturprototyp sowie eine grobe Beschreibung der Anwendungsfälle ausgearbeitet. Planung der Konstruktionsphase, Machbarkeitstests, Systemevaluierung und erste Programmteile von Schlüsselkomponenten sind Teil der Elaborationsphase.

* Construction (Implementierung)
Nachdem die Architektur ausgearbeitet wurde, konzentriert sich diese Phase auf die Entwicklung und das Testen des Produktes. In dieser Phase werden sämtliche Anforderungen unter laufender Abstimmung mit dem Kunden realisiert.

* Transition (Inbetriebnahme)
Übergabephase und Freigabe der Software an den Kunden. 

<figure style="width:600px;">
    <img src="https://raw.githubusercontent.com/ProjektManagementGruppe3/Ausarbeitung/master/include/daniel/rup-modell.PNG"  />
    <figcaption>
        Abbildung 4: Rational-Unified-Process-Modell zur Softwareentwicklung nach Aichele
    </figcaption>
</figure>

### Vor- und Nachteile moderner Vorgehensmodelle:

**Vorteile**
* Projektrisiken können früh erkannt werden.
* Volatile Anforderungen können besser berücksichtigt werden.
* Hohe Effizienz bei bekannten und konstanten Anforderungen.
* Erhöhte Transparenz

**Nachteile**
* Aufwand für alle Projektbeteiligten ist sehr hoch.
* Komplexes Projektmanagement, da eine Anpassung an das jeweilige Projekt notwendig ist.
* Ergebnisse sind schwer messbar, da keine Qualitätssicherung im Modell vorgesehen ist.

## Agile Vorgehensmodelle
Agile Vorgehensmodelle zur Softwareentwicklung entstanden wegen der Lean-Management-Bewegung in der japanischen Automobilindustrie. Nach diesen Ansätzen wird versucht, die Bearbeitung eines Projektes durch die systematische Vermeidung von Ressourcenverschwendung zu verbessern und zu beschleunigen. Tätigkeiten, welche keinen direkten Nutzen für den Kunden bzw. keine Verbesserung des Projektfortschritts bewirken, sollen in diesem Zusammenhang nicht durchgeführt werden. Durch die Vermeidung dieser Arbeitsschritte soll der Kundennutzen fokussiert und der Mehrwert des Produktes gesteigert werden. Agile Vorgehensmodelle sollen, insbesondere in Domänen mit sich schnell ändernden Anforderungen, die genannten Vorteile aus der japanischen Automobilindustrie auf die Softwareentwicklung übertragen. Die Grundidee der agilen Vorgehensweise besteht in der Reduktion der Entwurfsphase auf ein Mindestmaß, der Erzeugung früh ausführbarer Softwareprodukte sowie in der Kundennähe.33 Diese Idee wurde maßgeblich im Jahr 2001 durch eine Gruppe von Softwareentwicklern geprägt, die einen Erfahrungsaustausch im Zuge von Entwicklungsprojekten vornahmen. Das Ergebnis dieses Erfahrungsaustauschs war ein „agiles Manifest“, das aus verschiedenen Grundsätzen bestand, die durch zwölf weitere Prinzipien konkretisiert wurden. Die Grundsätze dieses Manifests waren im Folgenden:

* Personal mit hoher Qualifizierung sowie die effiziente Zusammenarbeit zwischen den Personen ist eine höhere Bedeutung zuzumessen als Prozessdefinitionen und Werkzeugen.
* Software, die den Anforderungen der Anwender entspricht und eine gute Funktionalität aufweist, ist bedeutender als eine ausführliche Dokumentation.
* Eine verstärkte Zusammenarbeit mit den Endanwendern hat eine größere Bedeutung gegenüber einem ausführlichen Vertragswerk.
* Vorschläge für notwendige Änderungen einbringen zu können weist eine höhere Relevanz auf als das ausschließliche Befolgen eines vordefinierten Plans.

Im Gegensatz zu klassischen Vorgehensmodellen zeichnen sich agile Vorgehensmodelle in der Softwareentwicklung durch relativ kurze Iterationen aus, wobei nach jeder Iteration ein für den Kunden greifbares Resultat erreicht wird, z. B. lauffähige Software. Diese Vorgehensweise wirkt sich insbesondere auf das Anforderungsmanagement aus, da der Umgang mit Anforderungen in solchen einfachen Vorgehensmodellen grundsätzlich auf einer anderen Basis stattfindet als bei komplexeren Vorgehensmodellen. Auf dieser Grundlage können Anforderungsveränderungen bei jeder Iteration neu berücksichtigt werden, sodass keine Grenze für die Aufnahme von Change Requests (CR) existiert. Bei jeder neuen Iteration erfolgt demnach die Entscheidung, welche Anforderungen in der aktuellen Iteration realisiert werden können.

## Extreme Programming (XP)
Ein Vertreter der agilen Vorgehensmodelle ist Extreme Programming (XP), welches 1999 von Kent Beck vorgestellt wurde. XP beschränkt sich weitgehend auf die Betrachtung des Prozesses der Softwareerstellung und blendet die Planungsvorgänge aus. In Situationen, in denen eine Entwicklung durch unklare Anforderungen und häufige Änderungen gekennzeichnet ist, stellt XP Werte und Prinzipien zur Verfügung, die insbesondere die _Kommunikation_ innerhalb eines Projekts vereinfachen sollen. XP teilt die Arbeit dahingehend auf, dass der Kunde für die Planung und Beschreibung von Vorgängen zuständig ist, während die Entwicklung an der Umsetzung der Prozesse zu einem Softwareprodukt arbeiten und Rückmeldung über Erfolg oder Misserfolg geben. Die Kommunikation erfolgt mit Hilfe von User Stories, die getrennt entwickelt und getestet werden können und auf verschiedenen Abstraktionsebenen beschreiben, wie sich die zu erstellende Software verhalten soll. Zur Vermeidung von Missverständnissen sieht das Konzept vor, dass zumindest ein Vertreter der Kundenseite die Entwicklung der Software ständig begleitet und somit als Kunde vor Ort bzw. on-site customer agiert. Zusätzlich wird im XP die Idee des Pair Programming umgesetzt, bei der während der Programmierung zwei Entwickler zusammen an einem Computer den Prozess entwerfen und so Fehler früher erkennen als auch Prozesswissen austauschen. Neben der Kommunikation über User Stories wird die Koordination durch die Rolle eines Managers unterstützt, der die Aufgabe hat, alle politischen und organisatorischen Hindernisse einer Entwicklung zu klären.

<figure style="width:600px;">
    <img src="https://raw.githubusercontent.com/ProjektManagementGruppe3/Ausarbeitung/master/include/daniel/xp.PNG"  />
    <figcaption>
        Abbildung 5: Extreme Programming zur Softwareentwicklung nach Aichele
    </figcaption>
</figure>

Geeignet ist XP besonders für kleine Projekte, die eine intensive persönliche Kommunikation voraussetzen. Die Erstellung und Überarbeitung der User Stories eignet es sich für die schnelle Erstellung von Teilprogrammen und ermöglicht bereits nach kurzer Zeit Ergebnisse vorliegen zu haben. Wegen der meist mangelnden Entwurfsplanung sowie der ständigen Beteiligung des Kunden bestehen zahlreiche Kritikpunkte an der Vorgehensweise des XP.

## Scrum
Scrum basiert, wie bei agilen Vorgehensmodellen üblich, auf der Grundannahme, dass Projekte aufgrund ihrer Komplexität von Anfang an nicht detailliert planbar sind. Es gibt in Scrum keine starren Templates oder Verfahrensanweisungen. Der Prozess und die Arbeitsweise werden in Reviews und Retrospektiven immer wieder begutachtet und gegebenfalls angepasst, um Verbesserungen zu erreichen. In maximal 1 Monat langen Zyklen (sog. "Sprints") werden iterativ (möglichst auslieferbare) Produkt-Inkremente erstellt. Für diesen Zweck wird ein selbstorganisierendes Team definiert, das im Wesentlichen durch drei Rollen bestimmt wird:
Der Product Owner vertritt die Stakeholder des Produkts, ist zuständig für den Product Backlog und verantwortlich für de Maximierung des Nutzens des Produkts. Er priorisiert die Anforderungen des Kunden und steuert den Entwicklungsprozess.
Das Team ist zuständig für die Umsetzung der Anforderungen in auslieferbare Produktinkremente. Dabei bestimmt es selbstorganisierend, welche Elemente des Product Backlogs es innerhalb eines bestimmten Zeitraums (Sprints) umgesetzen will. Das Team hat das Recht, eine Auswahl zu treffen, verpflichtet sich dafür aber auch, das durch die Auswahl gesetzte Ziel zu erreichen.
Der Scrum Master hat die Aufgabe die Einhaltung des Scrum-Prinzips zu überprüfen. Er darf nicht Product Owner oder Teil des Teams sein. Insbesondere muss er auch verhindern, dass der Product Owner zu viele Planungsvorgaben macht. Er unterstützt das Team, fördert Lernprozesse und moderiert Besprechungen und bei Konflikten.


**Scrum Artefakte**
* Product Backlog 
Enthält alle (bis zum jeweiligen Zeitpunkt) bekannten Anforderungen an die Software. Wird durch den Product Owner erstellt und gepflegt.
* Sprint Backlog
Wird durch das Projektteam erstellt und spiegelt durch eine Auswahl der Inhalte des Product Backlog die Zielvorgaben für einen Sprint wieder. Während eines Sprints wird das Sprint Backlog nicht um neue Einträge erweitert.
Release
* Jeder Sprint schließt mit einem lieferfähigen Release ab, welches in der Regel durch den Kunden geprüft wird.

<figure style="width:600px;">
    <img src="https://raw.githubusercontent.com/ProjektManagementGruppe3/Ausarbeitung/master/include/daniel/scrum.PNG"  />
    <figcaption>
        Abbildung 6: Scrum zur Softwareentwicklung nach Aichele
    </figcaption>
</figure>


### Vor- und Nachteile agiler Vorgehensmodelle:

**Vorteile**
* Gute Einsetzbarkeit bei unklaren Zielen und sich ändernden Anforderungen.
* Hohe Flexibilität und verringerte Komplexität der Projektverwaltung.
* Erhöhte Transparenz auf den Projektstand und mögliche Risiken.

**Nachteile**
* Eigenverantwortlichkeit des Projektteams kann zu Schwierigkeiten führen.
* Erhöhter Kommunikations- und Abstimmungsaufwand.
* Häufig fehlende Dokumentation der Ergebnisse.




