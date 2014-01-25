# Bei der Übersetzung helfen

Du hast einen Fehler in der Übersetzung gefunden oder möchtest dich anderweitig
beteiligen? Bitte befolge auch für die Mitarbeit in diesem Repository,
wo angebracht, die unten aufgeführten (aus dem Original-Repository übersetzten)
Richtlinien.

Wenn du deine Beiträge zur Übersetzung einreichst, stimmst du zu, sie unter den
Bedingungen der [Creative Commons Lizenz](https://github.com/juthilo/bootstrap-german/blob/master/LICENSE)
der Dokumentation zu lizenzieren.

---------------------------------------

# Bei Bootstrap mitmachen

Du möchtest etwas zu Bootstrap beitragen? **Hier wird erklärt, wie du helfen kannst.**

Bitte nimm dir einen Augenblick Zeit, um dieses Dokument durchzugehen, damit
deine Beiträge einfach und effektiv bearbeitet werden können, was allen zu Gute
kommt.

Das Befolgen dieser Richtlinien zeigt, dass du die Zeit der Entwickler, die
dieses Open-Source-Projekt pflegen und entwickeln, wertschätzt. Im Gegenzug
sollten sie angemessenen Respekt zeigen, wenn sie dein Problem bearbeiten oder
Korrekturen und Funktionen beurteilen.


## Fehlermeldungen verwenden

Der [Issue Tracker](https://github.com/twbs/bootstrap/issues) ist der bevorzugte
Kanal für [Fehlermeldungen](#fehlermeldungen), [Funktionsvorschläge](#funktionsvorschl%C3%A4ge)
und [das Einreichen von Pull Requests](#pull-requests). Beachte allerdings bitte die
folgenden Einschränkungen:

* Der Issue Tracker ist **nicht** für persönliche Hilfe-Anfragen geeignet. Stack
  Overflow ([`twitter-boostrap-3`](http://stackoverflow.com/questions/tagged/twitter-bootstrap-3)-Label)
  oder [IRC](https://github.com/juthilo/bootstrap-german/blob/master/README.md#community)
  sind bessere Orte, um Hilfe zu erhalten.

* **Beachte und respektiere** Andere in Diskussionen zu Issues und **vermeide**
  einen unhöflichen Umgangston sowie Abschweifungen vom Thema.

* Bitte öffne **keine** Meldungen oder Pull Requests, die sich auf Code in
  [`Normalize`](https://github.com/necolas/normalize.css) beziehen (reiche diese
  Beiträge stattdessen im zugehörigen Repository ein).


## Fehlermeldungen

Ein Fehler ist ein _Problem, welches man reproduzieren kann_, das heißt, dass
das Problem durch den Code **von Bootstrap** verursacht wird und Anderen dieses
unter ähnlichen Umständen ebenfalls widerfährt. Gute Fehlermeldungen sind sehr
hilfreich, also vielen Dank an dieser Stelle!

### Richtlinien für Fehlermeldungen:

1. **Verwende die Suche auf GitHub** &mdash; sieh nach, ob der Fehler schon
   gemeldet wurde.

2. **Sieh nach, ob das Problem schon behoben wurde** &mdash; versuche, es mit
   dem neuesten Code aus dem Branch `master` oder einem Entwicklungszweig im
   Repository zu reproduzieren.

3. **Isoliere das Problem** &mdash; am besten ist ein [reduzierter Musterfall](http://css-tricks.com/6263-reduced-test-cases/)
   und ein Live-Beispiel.
   [Dieser JS Bin](http://jsbin.com/EBAwOkOK/1) ist eine hilfreiche Vorlage.


Eine gute Fehlermeldung sollte nicht dazu führen, dass Andere nach mehr
Informationen suchen müssen. Bitte versuche in deinem Bericht so genau wie
möglich zu sein:

- Welche Umgebung verwendest du?
- Welche Schritte führen zum Wiederauftreten des Problems?
- Mit welchem/n Browser(n) und welchem/n Betriebssystem(en) siehst du diesen Fehler?
- Zeigen andere Browser den Fehler anders an?
- Wie sollte es eigentlich sein?

All diese Informationen helfen Anderen dabei, potentielle Fehler im Code zu beseitigen.

### Beispiel:

> Kurzer, erklärender Titel einer Beispiel-Fehlermeldung

> Eine Zusammenfassung des Problems und der Browser-/Betriebssystem-Umgebung, in
> der dieser Fehler auftritt. Falls angebracht, ergänze die Schritte, die
> notwendig sind, um das Problem zu reproduzieren.
>
> 1. Dies ist der erste Schritt
> 2. Dies ist der zweite Schritt
> 3. Weitere Schritte usw.
>
> `<url>` - Ein Link zu einem reduzierten Musterfall
>
> Jegliche zusätzliche Informationen, die du weitergeben möchtest, die mit dem
> Problem zu Tun haben, das du gerade meldest. Dazu gehören vielleicht
> Codezeilen, von denen du schon weißt, dass sie den Fehler verursachen und
> mögliche Lösungen (und deine Einschätzung von deren Wert).


## Funktionsvorschläge

Wir freuen uns, wenn du neue Funktionen vorschlägst. Nimm dir aber bitte einen
Moment Zeit, um herauszufinden, ob deine Idee zu dem Umfang und den Zielen des
Projekts passt. Es liegt ganz an *dir*, die Entwickler des Projekt mit guten
Thesen von deiner vorgeschlagenen Funktion zu überzeugen. Bitte stelle so viele
Details wie möglich zur Verfügung und erkläre Zusammenhänge.


## Pull Requests

Gute Pull Requests—Korrekturen, Verbesserungen, neue Funktionen—sind eine große
Hilfe. Sie sollten immer fokussiert bleiben und keine Commits ohne Zusammenhang
enthalten.

**Bitte frage zuerst**, bevor du anfängst, an größeren Pull Requests zu arbeiten
(z.B., wenn es um neue Funktionen geht, oder du Code umschreiben oder portieren
willst). Andernfalls wirst du viel Zeit mit etwas verbringen, das die Entwickler
des Projekts vielleicht gar nicht einfügen wollen.

Bitte halte dich an die [Code-Richtlinien](#code-richtlinien) dieses Projekt
(Einrückung, Kommentare, usw.) und andere Anforderungen (z.B. Unit-Tests).

Der beste Weg, um deine Arbeit in das Projekt integriert zu bekommen, ist dem
folgenden Prozess zu folgen:

1. [Forke](http://help.github.com/fork-a-repo/) das Projekt, klone deine Fork
   lokal und richte die Remote-URLs ein:

   ```bash
   # Klone die Fork des Repository in das aktuelle Verzeichnis
   git clone https://github.com/<dein-benutzername>/bootstrap.git
   # Navigiere in das neue Verzeichnis
   cd bootstrap
   # Richte eine Remote-URL "upstream" zum Original-Repository ein
   git remote add upstream https://github.com/twbs/bootstrap.git
   ```

2. Falls es seit dem Klonen eine Weile her ist, hol' dir die neuesten Änderungen:

   ```bash
   git checkout master
   git pull upstream master
   ```

3. Erstelle einen neuen Thema-Branch, um deine Funktion, Änderung oder Korrektur
   zu beinhalten:

   ```bash
   git checkout -b <thema-branch-name>
   ```

4. Committe deine Änderungen in logischen Stücken. Bitte befolge die
   [Richtlinien für Commit-Nachrichten](http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html)
   oder dein Code wird wahrscheinlich nicht in das Hauptprojekt eingebunden.
   Verwende gits [interaktiven Rebase-Modus](https://help.github.com/articles/interactive-rebase),
   um deine Commits aufzuräumen, bevor du sie veröffentlichst.

5. Merge (oder rebase) den Entwicklungs-Branch vom Upstream in deinen Thema-Branch:

   ```bash
   git pull [--rebase] upstream master
   ```

6. Pushe deinen Thema-Branch hoch in deine Fork:

   ```bash
   git push origin <thema-branch-name>
   ```

7. [Öffne einen Pull Request](https://help.github.com/articles/using-pull-requests/)
   mit einem eindeutigen Titel und Beschreibung, für den `master`-Branch.

**WICHTIG**: Wenn du eine Korrektur einreichst, erlaubst du den
Projekteigentümern, deine Arbeit unter den Bedingungen der
[MIT-Lizenz](https://github.com/twbs/bootstrap/blob/master/LICENSE) weiterzuverbreiten.

## Code-Richtlinien

### HTML

- Zwei Leerzeichen für Einrückung, niemals Tabs.
- Immer doppelte Anführungszeichen (`"`), niemals einzelne (`'`).
- Verwende immer vernünftige Einrückung.
- Verwende Tags und Elemente für einen HTML5-Doctype (z.B. selbst-schließende Tags)
- Nutze CDNs und HTTPS für JS von Dritten, wenn möglich. Wir nutzen keine
  protokoll-unabhängigen URLs in diesem Fall, da diese nicht funktionieren,
  wenn die Seite lokal über `file://` angezeigt wird.

### CSS

- CSS-Änderungen müssen zuerst in den `.less`-Dateien gemacht werden,
  nie einfach nur in den kompilierten `.css`-Dateien.
- Befolge die [CSS-Eigenschaften-Reihenfolge](http://markdotto.com/2011/11/29/css-property-order/).
- Immer nur eine Eigenschaft und ein Wert pro Zeile.
- Immer ein Leerzeichen nach dem Doppelpunkt einer Eigenschaft (z.B. `display: block;` und nicht `display:block;`).
- Beende alle Zeilen mit einem Semikolon.
- Für mehrere, durch Kommas getrennte Selektoren, platziere jeden Selektor auf einer neuen Zeile.
- Attribut-Selektoren, wie `input[type="text"]`, sollten den Wert des Attributs
  immer in doppelten Anführungszeichen verpacken, der Einheitlichkeit und
  Sicherheit wegen
  (siehe diesen [Blogpost über unverpackte Attribut-Werte](http://mathiasbynens.be/notes/unquoted-attribute-values), die zu XSS-Angriffen führen können).
- Attribut-Selektoren sollten nur in Fällen ohne gute Alternative verwendet
  werden (z.B. Formularfelder) und bei eigenen Komponenten aus Gründen der
  Performance und Genauigkeit vermieden werden.
- Eine Reihe von Klassen für eine Komponente sollte eine Grundklasse
  (z.B. `.component`) enthalten und die Grundklasse als Präfix für
  Änderungsklassen und Unterkomponenten verwenden (z.B. `.component-lg`).
- Vermeide Vererbung und zu viele Verschachtelungen—verwende einzelne,
  explizite Klassen, wann immer möglich.

### JS

- Keine Semikolons
- Komma zuerst
- 2 Leerzeichen (keine Tabs)
- [strict mode](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions_and_function_scope/Strict_mode)
- "Attraktiv"


## Lizenz

Durch die Einreichung deiner Code-Beiträge stimmst du zu, deinen Beitrag unter
der [MIT-Lizenz](https://github.com/twbs/bootstrap/blob/master/LICENSE) zu lizenzieren.

Vor v3.1.0 war Bootstrap unter der Apache-Lizenz v2.0 freigegeben.
