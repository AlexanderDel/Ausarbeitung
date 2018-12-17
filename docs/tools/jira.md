# Jira
## Was ist Jira?
Es gibt für Projektmanagement verschiedene Tools um zum Beispiel Meilensteine zu verwalten, Diagramme erstellen zu lassen und oder auch Probleme aufzulisten und zu erstellen (Issues). Jira wurde von Atlassian entwickelt und erschien im Jahr 2002.

*Wikipedia:*
> „Jira ist eine Webanwendung zur Fehlerverwaltung, Problembehandlung und operativem Projektmanagement. Jira wird auch in nicht-technischen Bereichen für das Aufgabenmanagement eingesetzt. Sie wurde von Atlassian entwickelt. Primär wird Jira für die Softwareentwicklung eingesetzt. Dort unterstützt es das Anforderungsmanagement, die Statusverfolgung und später den Fehlerbehebungsprozess. Jira ist durch seine Funktionen zur Ablauforganisation („Workflow-Management“) verwendbar für Prozessmanagement und Prozessverbesserung. „

## Installation
In unserem Fall wurde die Cloud Variante benutzt. Der Vorteil an der Cloud Variante, es wird keine aufwendige Installation benötigt, wo auf jeden Client eine Client-Software installiert werden muss. Jeder Benutzer kann einfach die Website per Browser aufrufen und die Applikation benutzen. Falls man sich für die Cloud-Variante entschieden hat, werden zunächst paar Grundlegende Fragen zu dem Projekt gestellt. Aus diesen Fragen heraus wird eine Vorgehens Modell ermittelt und vorgeschlagen. In unserem Fall wurde „Scrum“ vorgeschlagen. Natürlich lassen sich auch andere Vorgehensmodelle manuell auswählen. 

## Dashboard
Nachdem Jira installiert wurde, wird man auf das „System-Dashboard“ weiter geleitet. Hier erhält man Informationen über die verschiedene Projekte bzw. Aktualisierungen, die innerhalb eines Projektes geschehen sind. Außerdem werden einem die zugewiesen Meilensteine angezeigt. 
<figure role="group">
    <img src="https://raw.githubusercontent.com/ProjektManagementGruppe3/Ausarbeitung/master/include/justin/dashboard.PNG" alt="dashboard.png" />
    <figcaption>
        Abbildung 1: Vorinstalliertes "System-Dashboard"
    </figcaption>
</figure>

Es lassen sich außerdem weitere Dashboards erstellen, die mit eigen ausgewählten Gadgets konfiguriert werden können. Hierfür muss man oben rechts die Schaltfläche "..." klicken und den Punkt "Dashboard erstellen" auswählen.
<figure role="group">
    <img src="https://raw.githubusercontent.com/ProjektManagementGruppe3/Ausarbeitung/master/include/justin/dashboard_erstellen.PNG" alt="dashboard_erstellen.png" />
    <figcaption>
        Abbildung 2: Dashboard erstellen
    </figcaption>
</figure>

## Projektauswahl:
Wenn man sich auf den Dashboard befindet, befindet sich an der linken Seite eine Navigationsbar, die den Punkt „Projects“ beinhaltet. Hierunter können die verschiedene Projekte gesehen werden und ausgewählt werden. Zudem können hier auch neue Projekte angelegt werden, in man auf die Schaltfläche "Projekt erstellen" klickt.
<figure role="group">
    <img src="https://raw.githubusercontent.com/ProjektManagementGruppe3/Ausarbeitung/master/include/justin/projekt_auswahö.PNG" alt="projekt_auswahl.png" />
    <figcaption>
        Abbildung 3: Projekteübersicht - und Auswahl
    </figcaption>
</figure>

## Projekt erstellen
Nachdem man unter der Projektauswahl die Schaltfläche „Projekt erstellen“  betätigt hat, kommt nun eine Seite, wo man nun das Projekt einen Namen vergeben kann und man das Vorgehensmodell einstellen kann. 
<figure role="group">
    <img src="https://raw.githubusercontent.com/ProjektManagementGruppe3/Ausarbeitung/master/include/justin/projekt_name.PNG" alt="projekt_name.png" />
    <figcaption>
        Abbildung 4: Projekt erstellen
    </figcaption>
</figure>

> Da wir „Scrum“ als Vorgehensmodell besitzen, werden wir auf die Seite „Backlog“ weiter geleitet.

## Backlog und Aufgaben
Unter Backlog lassen sich die Meilensteine bzw. Aufgaben anlegen indem man unter dem Textfeld **„Was muss gemacht werden?“** die gewünschte Tätigkeit definiert oder unter **„+ Vorgänge erstellen“**. 

Wenn man nun eine erstellte Tätigkeit klickt, lässt sich die Tätigkeit nun spezifischer einstellen.

- Status
  - Ist es schon in Arbeit oder erledigt?
- Beschreibung
  - Beschreibung der Tätigkeit
- Zugewiesene Person
  - Welche Person bekommt die Tätigkeit zu gewiesen?
- Ersteller
  - Ersteller der Tätigkeit
- Label
  - Name des gewünschten Labels
- Story point estimate
  - Falls man mit einer Gewichtung arbeitet, kann hier die Punktzahl der Tätigkeit vergeben werden
- Priorität
  - Die Priorität der Tätigkeit lässt sich einstellen
<figure role="group">
    <img src="https://raw.githubusercontent.com/ProjektManagementGruppe3/Ausarbeitung/master/include/justin/backlog_erstellen.PNG" alt="backlog_erstellen.png" />
    <figcaption>
        Abbildung 5: Blacklog Page - Aufgabe Beschreibung rechte Seite
    </figcaption>
</figure>

## Sprint erstellen
Wenn  man nun ein Sprint erstellen möchte, muss man unter der Seite „Backlog“ auf die Schaltfläche „Sprint erstellen“ drücken. Nun erscheint eine Fläche, wo sich die Tätigkeiten hineinziehen lassen, um die gewünschten Tätigkeiten zu einem Sprint zu verfassen. 

Wenn man nun über dem eben erstellten Sprint auf die Schaltfläche „...“ klickt, lässt sich der Sprint löschen oder aber auch bearbeiten. Unter „Sprint bearbeiten“ lässt sich dann der Sprintname einstellen und das  Sprint-Ziel kann erläutert werden.
<figure role="group">
    <img src="https://raw.githubusercontent.com/ProjektManagementGruppe3/Ausarbeitung/master/include/justin/sprint_namen.PNG" alt="backlog_erstellen.png" />
    <figcaption>
        Abbildung 6: Sprint bearbeiten
    </figcaption>
</figure>
Wenn nun der Sprint aktiv werden soll, muss die Schaltfläche „Sprint starten“ betätigt werden.
Hier lässt sich dann die Dauer des Sprintes einstellen und das Startdatum. Das Enddatum wird anhand der Dauer ermittelt. Falls noch nicht angeben, lässt sich hier nochmals das Sprint-Ziel einzustellen bzw. zu erläutern.
<figure role="group">
    <img src="https://raw.githubusercontent.com/ProjektManagementGruppe3/Ausarbeitung/master/include/justin/sprint_starten.PNG" alt="sprint_starten.png" />
    <figcaption>
        Abbildung 7: Wenn ein Sprint gestartet wird
    </figcaption>
</figure>

## Aktive Sprints
Wenn man nun aktive Sprints sehen möchte, muss links in der Navigationsleiste der Punkt „Aktive Sprints“ ausgewählt werden. Hier sieht man nun die aktive Sprints und die Tätigkeiten lassen sich dann in einen gewünschten Zustand ändern per Drag and Drop. 
<figure role="group">
    <img src="https://raw.githubusercontent.com/ProjektManagementGruppe3/Ausarbeitung/master/include/justin/aktive_sprints.PNG" alt="aktive_sprints.png" />
    <figcaption>
        Abbildung 8: Aktive Sprints
    </figcaption>
</figure>