# Projekt archiviert
Aus Zeitgründen kann ich dieses Projekt schon lange nicht mehr pflegen. Daher schalte ich auch die deployte Webseite ab und archiviere dieses Repository.

# [Bootstrap (deutsch)](https://holdirbootstrap.de/)
[![Slack (englisch)](https://bootstrap-slack.herokuapp.com/badge.svg)](https://bootstrap-slack.herokuapp.com/)
![Bower-Version](https://img.shields.io/bower/v/bootstrap.svg?style=flat)
[![npm-Version](https://img.shields.io/npm/v/bootstrap.svg?style=flat)](https://www.npmjs.com/package/bootstrap)

Bootstrap, ein umfangreiches und dennoch schlankes Mobile-First Frond-End-Framework für einfachere und schnellere Entwicklung im Web. Erdacht von [Mark Otto](https://twitter.com/mdo) und [Jacob Thornton](https://twitter.com/fat) und gepflegt vom [Hauptteam](https://github.com/orgs/twbs/people) mit der großartigen Unterstützung der immer involvierten Community.

Dies ist eine inoffizielle Übersetzung der Dokumentation von Bootstrap auf Deutsch. Die enthaltenen Informationen sind unter Umständen nicht immer aktuell. Für die neuesten und zuverlässigsten Informationen solltest du die [Original-Dokumentation auf Englisch](https://getbootstrap.com/) lesen. Auch diese README-Datei ist eine übersetzte Version des Originals mit einigen Ergänzungen bezüglich der Übersetzung.

Um direkt loszulegen, geh auf <https://holdirbootstrap.de/>!

## Inhaltsverzeichnis

* [Schnellstart](#schnellstart)
* [Fehler und Funktionsanfragen](#fehler-und-funktionsanfragen)
* [Dokumentation](#dokumentation)
* [Mitmachen](#mitmachen)
* [Community](#community)
* [Versionen](#versionen)
* [Dank](#dank)
* [Erfinder](#erfinder)
* [Copyright und Lizenz](#copyright-und-lizenz)

## Schnellstart

Es sind einige Optionen verfügbar, um direkt loszulegen:

* [Neueste Version herunterladen](https://github.com/twbs/bootstrap/archive/v3.4.1.zip).
* Repository klonen: `git clone https://github.com/twbs/bootstrap.git`.
* Mit [Bower](https://bower.io) installieren: `bower install bootstrap`.
* Mit [npm](https://www.npmjs.com) installieren: `npm install bootstrap@3`.
* Mit [Meteor](https://www.meteor.com/) installieren: `meteor add twbs:bootstrap`.
* Mit [Composer](https://getcomposer.org) installieren: `composer require twbs/bootstrap`.

Lies die Seite [Los geht's](https://holdirbootstrap.de/los-gehts/) für Informationen über die Inhalte des Frameworks, Vorlagen und Beispiele und mehr.

### Was zur Verfügung steht

Sobald du Bootstrap heruntergeladen hast, findest du im Paket die folgenden Verzeichnisse und Dateien, die die wichtigsten Ressourcen logisch gruppieren und sowohl kompilierte als auch minimierte Varianten bereitstellen. Du wirst etwas in dieser Art vorfinden:

```
bootstrap/
├── css/
│   ├── bootstrap.css
│   ├── bootstrap.css.map
│   ├── bootstrap.min.css
│   ├── bootstrap.min.css.map
│   ├── bootstrap-theme.css
│   ├── bootstrap-theme.css.map
│   ├── bootstrap-theme.min.css
│   └── bootstrap-theme.min.css.map
├── js/
│   ├── bootstrap.js
│   └── bootstrap.min.js
└── fonts/
    ├── glyphicons-halflings-regular.eot
    ├── glyphicons-halflings-regular.svg
    ├── glyphicons-halflings-regular.ttf
    ├── glyphicons-halflings-regular.woff
    └── glyphicons-halflings-regular.woff2
```

Wir stellen sowohl kompiliertes CSS und JS (`bootstrap.*`), als auch kompiliertes und dann zusätzlich minimiertes CSS und JS (`bootstrap.min.*`) zur Verfügung. CSS [Source Maps](https://developer.chrome.com/devtools/docs/css-preprocessors) (`bootstrap.*.map`) sind für die Verwendung mit bestimmten Browser-Entwicklertools verfügbar. Schriften von Glyphicons sind auch dabei, sowie das optionale Bootstrap-Theme.


## Fehler und Funktionsanfragen

Du hast einen Fehler gefunden oder möchtest eine neue Funktion vorschlagen? Bitte lies dir zunächst die Richtlinien für Fehlerberichte ([Übersetzung](https://github.com/juthilo/bootstrap-german/blob/master/CONTRIBUTING.md#fehlermeldungen-verwenden) / [Original](https://github.com/twbs/bootstrap/blob/master/CONTRIBUTING.md#using-the-issue-tracker)) durch und suche dann nach bereits existierenden und eventuell geschlossenen Meldungen. Falls wir uns noch nicht mit deinem Problem oder deiner Idee beschäftigt haben, [eröffne einen neuen Fehlerbericht](https://github.com/twbs/bootstrap/issues/new) auf Englisch im Original-Repository auf GitHub.

Beachte, dass **Funktionswünsche sich auf [Bootstrap v4](https://github.com/twbs/bootstrap/tree/v4-dev) richten müssen,** weil Bootstrap v3 inzwischen nur noch sehr eingeschränkt gewartet wird und keine neuen Funktionen mehr erhält. So können wir uns auf Bootstrap v4 konzentrieren.


## Dokumentation

Bootstraps Dokumentation, die du in diesem Repository als Übersetzung findest, wird mit [Jekyll](https://jekyllrb.com/) generiert und öffentlich auf GitHub Pages unter <https://holdirbootstrap.de/> gehostet. Das Gleiche gilt auch für das Original, das du unter <https://getbootstrap.com/> findest. Du kannst beide Versionen auch lokal auf deinem eigenen Computer laufen lassen.

### Dokumentation lokal ausführen

1. Falls notwendig, [installiere Jekyll](https://jekyllrb.com/docs/installation) und andere Ruby-Dependencies mit `bundle install`.
   **Windows-Nutzer:** Lies [diesen Ratgeber](https://jekyllrb.com/docs/installation/windows/), um Jekyll ohne Probleme zum Laufen zu kriegen.
2. Öffne eine Befehlszeile im Wurzelverzeichnis `/bootstrap` und führe `bundle exec jekyll serve` aus.
3. Öffne die Dokumentation in deinem Browser über <http://localhost:10006> (Übersetzung) bzw. <http://localhost:9001> (Original) und fertig!

Erfahre mehr über den Umgang mit Jekyll, indem du dessen [Dokumentation](https://jekyllrb.com/docs/home/) liest.

### Dokumentation für alte Versionen

Die englische Dokumentation für v2.3.2 ist fürs Erste unter <https://getbootstrap.com/2.3.2/> verfügbar, solange einige noch zu Bootstrap 3 wechseln müssen.

[Frühere Versionen](https://github.com/twbs/bootstrap/releases) und ihre zugehörigen Dokumentationen (auf Englisch) sind auch noch zum Herunterladen verfügbar.


## Mitmachen

Bitte lies dir unsere Richtlinien für Beiträge ([Übersetzung](https://github.com/juthilo/bootstrap-german/blob/master/CONTRIBUTING.md) / [Original](https://github.com/twbs/bootstrap/blob/master/CONTRIBUTING.md)) durch. Darin findest du Anleitungen zum Erstellen von Fehlerberichten, Programmier-Standards und Hinweise zur Entwicklung.

Außerdem musst du [relevante Unit Tests](https://github.com/twbs/bootstrap/tree/master/js/tests) beifügen, wenn die Beiträge, die du über einen Pull Request einreichst, JavaScript-Verbesserungen oder -Funktionen enthalten. HTML und CSS sollte immer dem [Code Guide](https://github.com/mdo/code-guide) von [Mark Otto](https://github.com/mdo) folgen.

**Bootstrap v3 erhält keine neuen Funktionen mehr.** Es ist im eingeschränkten Wartungsmodus, damit wir uns auf [Bootstrap v4](https://github.com/twbs/bootstrap/tree/v4-dev) konzentrieren können, die Zukunft des Frameworks. Pull Requests, die neue Funktionen hinzufügen (und nicht Fehler beheben) sollten auf [Bootstrap v4 (die `v4-dev` Git Branch)](https://github.com/twbs/bootstrap/tree/v4-dev) ausgerichtet sein.

Voreinstellungen für Editoren / Textbearbeitungsprogramme sind in der Datei [.editorconfig](https://github.com/twbs/bootstrap/blob/master/.editorconfig) angegeben, damit du ganz einfach in gängigen Text-Editoren loslegen kannst. Lies mehr darüber und lade passende Plugins für Editoren auf <https://editorconfig.org/> herunter.



## Community

Erhalte Neuigkeiten über Bootstraps Entwicklung und chatte mit den Verantwortlichen des Projekts und der Community.

* Folge [@getbootstrap auf Twitter](https://twitter.com/getbootstrap).
* Lies und abonniere [Das Offizielle Bootstrap Blog](https://blog.getbootstrap.com/).
* Komm in den [offiziellen Slack-Room](https://bootstrap-slack.herokuapp.com/).
* Chatte mit anderen Bootstrappern über IRC. Und zwar auf dem `irc.freenode.net`-Server, im Kanal `##bootstrap`.
* Hilfe bei der Umsetzung deiner Projekte findest du z.B. auf Stack Overflow (markiert mit [`twitter-bootstrap-3`](https://stackoverflow.com/questions/tagged/twitter-bootstrap-3)).
* Entwickler sollten das Stichwort `bootstrap` bei Paketen verwenden, die die Funktionen von Bootstrap anpassen oder erweitern, wenn die Pakete über [npm](https://www.npmjs.com/browse/keyword/bootstrap) oder ähnliche Mechanismen verbreitet werden, um bestmöglich gefunden werden zu können.


## Versionen

Um unsere Veröffentlichungen so klar wie möglich zu halten und Rückwärtskompatibilität zu gewährleisten, wird Bootstrap unter den [Richtlinien des Semantic Versioning](https://semver.org) entwickelt. Wir versuchen diese Regeln so gut wie möglich einzuhalten, doch manchmal kann uns dabei ein Fehler unterlaufen.

Schau dir [die Releases in unserem GitHub-Projekt](https://github.com/twbs/bootstrap/releases) an, um Changelogs für jede veröffentlichte Version von Bootstrap zu lesen. Ankündigungen zu den einzelnen Releases im [offiziellen Bootstrap-Blog](https://blog.getbootstrap.com/) enthalten Zusammenfassungen der wichtigsten Änderungen.


## Dank

<img src="https://live.browserstack.com/images/opensource/browserstack-logo.svg" alt="BrowserStack-Logo" width="490" height="106">

Danke an [BrowserStack](https://www.browserstack.com/) für die Bereitstellung der Infrastruktur zum Testen in echten Browsern!


## Erfinder

**Mark Otto**

* <https://twitter.com/mdo>
* <https://github.com/mdo>

**Jacob Thornton**

* <https://twitter.com/fat>
* <https://github.com/fat>


## Copyright und Lizenz

Code und Dokumentation Copyright 2011-2022 Twitter, Inc. Code freigegeben unter [der MIT-Lizenz](https://github.com/twbs/bootstrap/blob/master/LICENSE). Dokumentation freigegeben unter den Bedingungen von [Creative Commons](LICENSE).
