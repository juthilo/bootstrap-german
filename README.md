# [Bootstrap (deutsch)](http://holdirbootstrap.de)
[![Bower-Version](https://badge.fury.io/bo/bootstrap.svg)](http://badge.fury.io/bo/bootstrap)
[![NPM-Version](https://badge.fury.io/js/bootstrap.svg)](http://badge.fury.io/js/bootstrap)

Bootstrap, ein umfangreiches und dennoch schlankes Mobile-First Frond-End-Framework für einfachere und schnellere Entwicklung im Web. Erdacht von [Mark Otto](http://twitter.com/mdo) und [Jacob Thornton](http://twitter.com/fat) und gepflegt vom [Hauptteam](https://github.com/twbs?tab=members) mit der großartigen Unterstützung der immer involvierten Community.

Dies ist eine inoffizielle Übersetzung der Dokumentation von Bootstrap auf Deutsch. Die enthaltenen Informationen sind unter Umständen nicht immer aktuell. Für die neuesten und zuverlässigsten Informationen solltest du die [Original-Dokumentation auf Englisch](http://getbootstrap.com) lesen. Auch diese README-Datei ist eine übersetzte Version des Originals mit einigen Ergänzungen bezüglich der Übersetzung.

Um direkt loszulegen, geh auf <http://holdirbootstrap.de>!

## Inhaltsverzeichnis

 - [Schnellstart](#schnellstart)
 - [Fehler und Funktionswünsche](#fehler-und-funktionswuensche)
 - [Dokumentation](#dokumentation)
 - [Mitmachen](#mitmachen)
 - [Community](#community)
 - [Versionen](#versionen)
 - [Erfinder](#erfinder)
 - [Copyright und Lizenz](#copyright-und-lizenz)

## Schnellstart

Es sind drei Optionen verfügbar, um direkt loszulegen:

- [Neueste Version herunterladen](https://github.com/twbs/bootstrap/archive/v3.1.1.zip).
- Repository klonen: `git clone https://github.com/twbs/bootstrap.git`.
- Mit [Bower](http://bower.io) installieren: `bower install bootstrap`.

Lies die Seite [Los geht's](http://holdirbootstrap.de/los-gehts/) für Informationen über die Inhalte des Frameworks, Vorlagen und Beispiele und mehr.

### Was zur Verfügung steht

Sobald du Bootstrap heruntergeladen hast, findest du im Paket die folgenden Verzeichnisse und Dateien, die die wichtigsten Ressourcen logisch gruppieren und sowohl kompilierte als auch minimierte Varianten bereitstellen. Du wirst etwas in dieser Art vorfinden:

```
bootstrap/
├── css/
│   ├── bootstrap.css
│   ├── bootstrap.min.css
│   ├── bootstrap-theme.css
│   └── bootstrap-theme.min.css
├── js/
│   ├── bootstrap.js
│   └── bootstrap.min.js
└── fonts/
    ├── glyphicons-halflings-regular.eot
    ├── glyphicons-halflings-regular.svg
    ├── glyphicons-halflings-regular.ttf
    └── glyphicons-halflings-regular.woff
```

Wir stellen sowohl kompiliertes CSS und JS (`bootstrap.*`), als auch kompiliertes und dann zusätzlich minimiertes CSS und JS (`bootstrap.min.*`) zur Verfügung. Schriften von Glyphicons sind auch dabei, sowie das optionale Bootstrap-Theme.



## Fehler und Funktionswünsche

Du hast einen Fehler gefunden oder möchtest eine neue Funktion vorschlagen? Bitte lies dir zunächst die Richtlinien für Fehlerberichte ([Übersetzung](https://github.com/juthilo/bootstrap-german/blob/master/CONTRIBUTING.md#fehlermeldungen-verwenden) / [Original](https://github.com/twbs/bootstrap/blob/master/CONTRIBUTING.md#using-the-issue-tracker)) durch und suche dann nach bereits existierenden und eventuell geschlossenen Meldungen. Falls wir uns noch nicht mit deinem Problem oder deiner Idee beschäftigt haben, [eröffne einen neuen Fehlerbericht](https://github.com/twbs/bootstrap/issues/new) auf Englisch im Original-Repository auf GitHub.


## Dokumentation

Bootstraps Dokumentation, die du in diesem Repository als Übersetzung findest, wird mit [Jekyll](http://jekyllrb.com) generiert und öffentlich auf GitHub Pages unter <http://holdirbootstrap.de> gehostet. Das Gleiche gilt auch für das Original, das du unter <http://getbootstrap.com> findest. Du kannst beide Versionen auch lokal auf deinem eigenen Computer laufen lassen.

### Dokumentation lokal ausführen

1. Falls notwendig, [installiere Jekyll](http://jekyllrb.com/docs/installation) (benötigt wird v2.0.x).
  - **Windows-Nutzer:** Lies [diesen unoffiziellen Ratgeber](https://github.com/juthilo/run-jekyll-on-windows/), um Jekyll ohne Probleme zum Laufen zu kriegen. Wir verwenden Pygments, um Code-Schnipsel zu gestalten und hervorzuheben, lies also unbedingt auch die Abschnitte zur Installation von Python und Pygments.
2. Öffne eine Befehlszeile im Wurzelverzeichnis `/bootstrap` und führe `jekyll serve` aus.
3. Öffne die Dokumentation in deinem Browser über <http://localhost:10006> (Übersetzung) bzw. <http://localhost:9001> (Original) und fertig!

Erfahre mehr über den Umgang mit Jekyll, indem du dessen [Dokumentation](http://jekyllrb.com/docs/home/) liest.

### Dokumentation für alte Versionen

Die englische Dokumentation für v2.3.2 ist fürs Erste unter <http://getbootstrap.com/2.3.2/> verfügbar, solange einige noch zu Bootstrap 3 wechseln müssen.

[Frühere Versionen](https://github.com/twbs/bootstrap/releases) und ihre zugehörigen Dokumentationen (auf Englisch) sind auch noch zum Herunterladen verfügbar.



## Mitmachen

Bitte lies dir unsere Richtlinien für Beiträge ([Übersetzung](https://github.com/juthilo/bootstrap-german/blob/master/CONTRIBUTING.md) / [Original](https://github.com/twbs/bootstrap/blob/master/CONTRIBUTING.md)) durch. Darin findest du Anleitungen zum Erstellen von Fehlerberichten, Programmier-Standards und Hinweise zur Entwicklung.

Außerdem denke bitte daran relevante Unit Tests beizufügen, wenn die Beiträge, die du über einen Pull Request einreichst, JavaScript-Verbesserungen oder -Funktionen enthalten. HTML und CSS sollte immer dem [Code Guide](http://github.com/mdo/code-guide) von [Mark Otto](http://github.com/mdo) folgen.

Voreinstellungen für Editoren / Textbearbeitungsprogramme sind in der Datei [.editorconfig](https://github.com/twbs/bootstrap/blob/master/.editorconfig) angegeben, damit du ganz einfach in gängigen Text-Editoren loslegen kannst. Lies mehr darüber und lade passende Plugins für Editoren auf <http://editorconfig.org> herunter.



## Community

Bleib auf dem Laufenden, was die Entwicklung und Neuigkeiten aus der Community angeht.

- Folge [@twbootstrap auf Twitter](http://twitter.com/twbootstrap).
- Lies und abonniere [Das Offizielle Bootstrap Blog](http://blog.getbootstrap.com).
- Chatte mit anderen Bootstrappern über IRC. Und zwar auf dem `irc.freenode.net`-Server, im Kanal `##twitter-bootstrap`.
- Hilfe bei der Umsetzung deiner Projekte findest du z.B. auf Stack Overflow (markiert mit [`twitter-bootstrap-3`](http://stackoverflow.com/questions/tagged/twitter-bootstrap-3)).



## Versionen

Um unsere Veröffentlichungen so klar wie möglich zu halten und Rückwärtskompatibilität zu gewährleisten, wird Bootstrap unter den [Richtlinien des Semantic Versioning](http://semver.org) entwickelt. Wir versuchen diese Regeln so gut wie möglich einzuhalten, doch manchmal kann uns dabei ein Fehler unterlaufen.



## Erfinder

**Mark Otto**

- <http://twitter.com/mdo>
- <http://github.com/mdo>

**Jacob Thornton**

- <http://twitter.com/fat>
- <http://github.com/fat>



## Copyright und Lizenz

Code und Dokumentation Copyright 2011-2014 Twitter, Inc. Code freigegeben unter [der MIT-Lizenz](https://github.com/twbs/bootstrap/blob/master/LICENSE). Dokumentation freigegeben unter den Bedingungen von [Creative Commons](LICENSE).
