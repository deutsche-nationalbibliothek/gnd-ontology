## Wie man zu Vokabularen und Ontologien der Deutschen Nationalbibliothek beiträgt

Herzlich willkommen! Danke, dass du zu den Vokabularen und Ontologien der Deutschen Nationalbibliothek beiträgst.

Im Folgenden findest du eine Reihe von Richtlinien, wie du zu den Vokabularen und Ontologien beitragen kannst. Wir verwenden einen einfachen Workflow: der Main-Branch ist immer das aktuell gültige Release. Neue Versionen werden in Entwicklungszweigen vorbereitet, die nach einiger Zeit in den Main-Branch eingefügt werden und zu einem neuen Release führen. 

### Wie kann ich beitragen?

Wir freuen uns über Beiträge und ermutigen euch, Vorschläge einzureichen, indem ihr ein Issue oder einen Pull Request in diesem GitHub-Repository erstellt.

### Verbesserungsvorschläge

Dieser Abschnitt erklärt, wie Verbesserungsvorschläge für die Vokabulare und Ontologien eingereicht werden können. Das Befolgen dieser Richtlinien hilft den Betreuenden und der Community, deinen Vorschlag zu verstehen und verwandte Vorschläge zu finden.

Bevor du einen Verbesserungsvorschlag machst, führe bitte eine Suche durch, um zu sehen, ob die Verbesserung bereits vorgeschlagen wurde. Wenn dies der Fall ist, füge einen Kommentar zu dem bestehenden Vorschlag hinzu, anstatt ein neues Issue zu eröffnen. Wenn du einen Verbesserungsvorschlag erstellst, gebe bitte so viele Details wie möglich an:

#### Wie kann ich einen Verbesserungsvorschlag einreichen?

Für einen Verbesserungsvorschlag erstelle ein neues GitHub-Issue.

Gib bitte die folgenden Informationen an:

- Einen klaren und beschreibenden Titel für das Problem, um den Vorschlag zu identifizieren.
- Beschreibe die vorgeschlagene Verbesserung Schritt für Schritt und so detailliert wie möglich.
- Führe konkrete Beispiele an, um die Schritte zu veranschaulichen. Füge kopierbare Schnipsel, die in diesen Beispielen verwendet werden, als Markdown-Codeblöcke ein.
- Erläutere, warum diese Verbesserung für die meisten Benutzer nützlich wäre.

#### Pull Requests

Bitte folge diesen Schritten, um Beiträge zum Projekt vorzuschlagen.

Wenn du einen Pull Request einreichst, verwende einen aussagekräftigen Titel und verwende Keywords in der Beschreibung des Pull Requests, um auf das Problem zu verweisen, das damit gelöst werden soll. Anschließend folgt der Prüfprozess durch eine:n Reviewer:in. Die/Der Reviewer:in kann dich bitten, zusätzliche Formatierungen oder andere Änderungen vorzunehmen, bevor dein Pull Request endgültig angenommen werden kann.

### Git Konventionen

Git-Commits sollten so granular wie möglich sein. Wenn wir an der Behebung von Problem X arbeiten, versuchen wir nicht, andere Dinge, die uns auffallen (Formatierungen usw.), in denselben Commit aufzunehmen. Diese Dinge sollten in einem eigenen Commit in denselben Branch eingefügt werden.

Commit-Nachrichten:
- Verwende den Imperativ in der Betreffzeile ("Add term" nicht "Added term").
- Trenne den Betreff vom Text durch eine Leerzeile.
- Großschreibung der Betreffzeile.
- Beende die Betreffzeile nicht mit einem Punkt.
- Erkläre im Textkörper das Was und Warum, nicht das Wie (das im Diff zu sehen ist).

### Veröffentlichung neuer Vokabularversionen

Wir verwenden die semantische Versionierung in den Versionsnummern A.B.C, d.h. A wird erhöht, wenn es sich um eine Hauptversion handelt, die die Abwärtskompatibilität aufhebt; B wird erhöht, wenn es neue Begriffe gibt; C wird erhöht, wenn Fehler behoben wurden. (Mehr zum [Semantic Versioning](https://semver.org/lang/de/).)

### Danksagung

Danke, für die Mitarbeit an den Vokabularen und Ontologien der Deutschen Nationalbibliothek! Wir verweisen auf alle, die über diesem Weg beitragen, über die Aussage:
```
@prefix : <https://d-nb.info/standards/elementset/gnd#> .
@prefix dct: <http://purl.org/dc/terms/> .
@prefix foaf: <http://xmlns.com/foaf/0.1/> .
@prefix rdfs: <http://www.w3.org/2000/01/rdf-schema#> .

<https://d-nb.info/standards/elementset/gnd#> dct:contributor :githubContributors .

:githubContributors
    a foaf:Group ;
    rdfs:label "Github DNB Contributors"@en ;
    rdfs:seeAlso <https://github.com/deutsche-nationalbibliothek/gnd-ontology/graphs/contributors> .
```
Für besondere Beiträge werden Beitragende im Einzellfall extra im jeweiligen Vokabular genannt.

### Du hast weitere Fragen?

Wenn du Fragen zur Arbeit mit den Vokabularen und Ontologien der Deutschen Nationalbibliothek hast oder einfach nur mitteilen möchtest, woran du gerade arbeitest, besuche das [metadaten.community Forum](https://metadaten.community/).

Weiterhin hast du die Möglichkeit eine E-Mail zu schreiben
  * [Linked-Data-Service Mailingliste](mailto:lds@lists.dnb.de)
  * [GND Ontology Mailingliste](mailto:gnd-ontology@lists.dnb.de)
  * [Metadatendienste der Deutschen Nationalbibliothek](mailto:metadatendienste@dnb.de) 


Danke! :heart: 

Linked Data Team
