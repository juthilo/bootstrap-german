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

* Bitte verwende den Issue Tracker **nicht** für persönliche Hilfe-Anfragen.
  Stack Overflow ([`twitter-bootstrap-3`](https://stackoverflow.com/questions/tagged/twitter-bootstrap-3)-Label),
  [Slack](https://bootstrap-slack.herokuapp.com/) oder [IRC](README.md#community) sind bessere Orte, um Hilfe zu erhalten.

* Bitte **nicht** Issues trollen oder entgleisen lassen. Bleib beim Thema und respektiere andere Meinungen.

* Bitte **nicht** Kommentare posten, die nur aus "+1" oder ":thumbsup:" bestehen. Nutze stattdessen
  [GitHubs "reactions"](https://blog.github.com/2016-03-10-add-reactions-to-pull-requests-issues-and-comments/).
  Wir behalten uns vor, Kommentare zu löschen, die diese Regel missachten.

* Bitte **nicht** Issues oder Pull Requests eröffnen, die sich auf Code in
  [`Normalize`](https://github.com/necolas/normalize.css) beziehen (reiche diese
  Beiträge stattdessen im zugehörigen Repository ein).
  
* Bitte **nicht** Issues eröffnen, die sich auf die offiziellen Themes auf <https://themes.getbootstrap.com/> 
  beziehen. Schreib stattdessen eine Email mit Fragen oder Feedback zu diesen Themes 
  an `themes AT getbootstrap DOT com`.


## Fehlermeldungen und Labels

Wir verwenden in unserem Issue Tracker verschiedene Labels, um Fehlermeldungen leichter organisieren und identifizieren zu können. Hier siehst du, was sie bedeuten und wie sie genutzt werden:

- `browser bug` - Probleme, die uns gemeldet werden, aber eigentlich das Ergebnis eines Browser-spezifischen Bugs sind. Diese Probleme werden mit reduzierten Musterfällen diagnostiziert und führen dazu, dass eine Fehlermeldung im eigenen Issue Tracker eines Browsers geöffnet wird.
- `confirmed` - Probleme, die mit einem reduzierten Musterfall bestätigt wurden und mit einem Bug in Bootstrap zusammenhängen.
- `css` - Probleme, die mit unserem kompilierten CSS oder Quell-Less-Dateien zusammenhängen.
- `customizer` - Probleme, die unseren webbasierten Customizer betreffen.
- `docs` - Issues für die Verbesserung oder Aktualisierung unserer Dokumentation.
- `examples` - Probleme im Zusammenhang der Beispiel-Vorlagen, die Teil unserer Dokumentation sind.
- `feature` - Vorschläge für neue Funktionen an sich oder als Ergänzung oder Veränderung einer bestehenden Komponente. Neue Funktionen machen eine höhere zweite Versionsnummer erforderlich (z.B. von `v3.0.0` auf `v3.1.0`).
- `grunt` - Probleme bei unserem JavaScript-basierten Gruntfile, das dazu dient, all unsere Tests laufen zu lassen, Quelldateien zusammenzuführen und zu kompilieren und mehr.
- `help wanted` - Probleme, für deren Lösung wir die Hilfe der Community brauchen oder willkommen heißen würden.
- `js` - Probleme in unseren kompilierten oder ursprünglichen JavaScript-Dateien.
- `meta` - Issues, die das Projekt selbst oder unser GitHub-Repository betreffen.

Für eine komplette Übersicht über unsere Labels kannst du dir die [Labels-Liste des Projekts](https://github.com/twbs/bootstrap/labels) ansehen.


## Fehlermeldungen

Ein Fehler ist ein _Problem, welches man reproduzieren kann_, das heißt, dass
das Problem durch den Code **von Bootstrap** verursacht wird und Anderen dieses
unter ähnlichen Umständen ebenfalls widerfährt. Gute Fehlermeldungen sind sehr
hilfreich, also vielen Dank an dieser Stelle!

### Richtlinien für Fehlermeldungen:

0. **Validiere und linte deinen Code** &mdash; [validiere dein HTML](https://html5.vaidator.nu/)
   und [linte dein HTML](https://github.com/twbs/bootlint), um sicherzustellen, dass dein
   Problem nicht von einem einfachen Fehler in deinem eigenen Code verursacht wird.

1. **Verwende die Suche auf GitHub** &mdash; sieh nach, ob der Fehler schon
   gemeldet wurde.

2. **Sieh nach, ob das Problem schon behoben wurde** &mdash; versuche, es mit
   dem neuesten Code aus dem Branch `master` oder einem Entwicklungszweig im
   Repository zu reproduzieren.

3. **Isoliere das Problem** &mdash; am besten ist ein [reduzierter Musterfall](https://css-tricks.com/reduced-test-cases/)
   und ein Live-Beispiel.
   [Dieser JS Bin](https://jsbin.com/lefey/1/edit?html,output) ist eine hilfreiche Vorlage.


Eine gute Fehlermeldung sollte nicht dazu führen, dass Andere nach mehr
Informationen suchen müssen. Bitte versuche in deinem Bericht so genau wie
möglich zu sein:

- Welche Umgebung verwendest du?
- Welche Schritte führen zum Wiederauftreten des Problems?
- Mit welchem/n Browser(n) und welchem/n Betriebssystem(en) siehst du diesen Fehler?
- Zeigen andere Browser den Fehler anders an?
- Wie sollte es eigentlich sein?

All diese Informationen helfen Anderen dabei, potentielle Fehler im Code zu beseitigen.

Beispiel:

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

### Browser-Bugs melden

Einige der Fehlermeldungen, die wir erhalten, beziehen sich auf Fehler, die von Bugs in den Browsern selbst und nicht von Bootstrap verursacht werden.
Wenn angebracht, versuchen wir diese Upstream-Fehler an die relevanten Browser-Hersteller zu melden und dann an unserer [Pinnwand für Browser-Bugs](https://holdirbootstrap.de/browser-bugs/) aufzuführen und [sie im MDN zu dokumentieren](https://developer.mozilla.org/de/docs/Web).

| Hersteller    | Browser                      | Rendering Engine | Seite für Fehlermeldungen                                                             | Hinweise                                            |
| ------------- | ---------------------------- | ---------------- | ------------------------------------------------------------------------------------- | --------------------------------------------------- |
| Mozilla       | Firefox                      | Gecko            | https://bugzilla.mozilla.org/enter_bug.cgi                                            | "Core" ist meistens die richtige Produktkategorie.  |
| Apple         | Safari                       | WebKit           | https://bugs.webkit.org/enter_bug.cgi?product=WebKit <br> https://bugreport.apple.com | In Apples Bug Reporter "Safari" als Produkt wählen. |
| Google, Opera | Chrome, Chromium, Opera v15+ | Blink            | https://code.google.com/p/chromium/issues/list                                        | Klick den Button "New issue".                       |
| Microsoft     | Internet Explorer            | Trident          | https://connect.microsoft.com/IE/feedback/LoadSubmitFeedbackForm                      |                                                     |


### Issues Bots

[@twbs-lmvtfy](https://github.com/twbs-lmvtfy) ist ein Bootstrap-Bot, der in unserem GitHub-Issue-Tracker herumhängt und automatisch alle Live-Beispiele (z.B. jsFiddles, JS Bins, Bootplys, Plunks, CodePens, usw.), die in Issue-Kommentaren gepostet werden, auf HTML-Validierungs-Fehler überprüft. Falls er irgendwelche Fehler findet, schreibt er einen Kommentar darunter und weist auf diese hin. Falls das mit einem Beispiel von dir passiert, behebe bitte die Fehler und poste eine aktualisierte Version deines Live-Beispiels. Falls du eine Fehlermeldung erstellt hast, überprüfe bitte, ob der Bug mit dem berichtigten Beispiel immer noch auftritt. Falls der Fehler nicht mehr auftritt, ist dieser wahrscheinlich auf dein ungültiges HTML zurückzuführen und nicht durch etwas in Bootstrap verursacht und wir würden es begrüßen, wenn du das Issue auf GitHub schließen könntest.


## Funktionsvorschläge

Wir freuen uns, wenn du neue Funktionen vorschlägst. Bitte beachte aber, dass 
diese sich **auf [Bootstrap v4](https://github.com/twbs/bootstrap/tree/v4-dev) 
beziehen müssen,** da Bootstrap v3 im eingeschränkten Wartungsmodus ist und keine
neuen Funktionen mehr erhält. So können wir uns auf Bootstrap v4 konzentrieren,
die Zukunft des Frameworks.

Nimm dir bitte, bevor du einen Funktionsvorschlag einreichst, einen
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

Insbesondere **werden Pull Requests, die neue Funktionen zu Bootstrap v3
hinzufügen, abgelehnt.** Bootstrap v3 ist im eingeschränkten Wartungsmodus und
erhält keine neuen Funktionen mehr. So können wir uns auf Bootstrap v4
konzentrieren, die Zukunft des Frameworks. Pull Requests, die neue Funktionen
hinzufügen, sollten sich stattdessen auf
[Bootstrap v4 (die `v4-dev` git branch)](https://github.com/twbs/bootstrap/tree/v4-dev)
beziehen, wo sie willkommen sind und ganz normal in Betracht gezogen werden.

Bitte halte dich an die [Code-Richtlinien](#code-richtlinien) dieses Projekt
(Einrückung, Kommentare, usw.) und andere Anforderungen (z.B. Unit-Tests).

**Bearbeite `bootstrap.css`, `bootstrap-theme.css` oder `bootstrap.js` niemals
direkt!** Diese Dateien werden automatisch generiert. Du solltest stattdessen
die Quelldateien in
[`/bootstrap/less/`](https://github.com/twbs/bootstrap/tree/master/less), [`/bootstrap/scss/`](https://github.com/twbs/bootstrap/tree/v4-dev/scss) (für Bootstrap v4), und/oder [`/bootstrap/js/`](https://github.com/twbs/bootstrap/tree/master/js)
bearbeiten.

Genauso solltest du bei Beiträgen zu Bootstraps Dokumentation die Quelldateien im
[Verzeichnis `/bootstrap/docs/` der `master`-Branch](https://github.com/twbs/bootstrap/tree/master/docs)
bearbeiten. **Bearbeite niemals die `gh-pages`-Branch.** Diese Branch wird aus den
Quelldateien der Dokumentation generiert und wird vom Bootstrap-Hauptteam separat
verwaltet.

Der beste Weg, um deine Arbeit in das Projekt integriert zu bekommen, ist dem
folgenden Prozess zu folgen:

1. [Forke](https://help.github.com/fork-a-repo/) das Projekt, klone deine Fork
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

4. Committe deine Änderungen in logischen Stücken. Bitte befolge diese
   [Richtlinien für Commit-Nachrichten](https://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html)
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
[MIT-Lizenz](https://github.com/twbs/bootstrap/blob/master/LICENSE)
(falls sie Code-Änderungen enthält) und unter der
[Creative Commons Attribution 3.0 Unported-Lizenz](LICENSE)
(falls sie Dokumentations-Änderungen enthält) weiterzuverbreiten.

## Code-Richtlinien

### HTML

[Befolge die Regeln aus dem Code Guide.](https://codeguide.co/#html)

- Verwende Tags und Elemente für einen HTML5-Doctype (z.B. selbst-schließende Tags)
- Nutze CDNs und HTTPS für JS von Dritten, wenn möglich. Wir nutzen keine protokoll-unabhängigen URLs in diesem Fall, da diese nicht funktionieren, wenn die Seite lokal über `file://` angezeigt wird.
- Verwende Attribute entsprechend [WAI-ARIA](https://developer.mozilla.org/de/docs/Web/Barrierefreiheit/ARIA) in Beispielen in der Dokumentation, um beim Thema Barrierefreiheit mit gutem Beispiel voranzugehen.

### CSS

[Befolge die Regeln aus dem Code Guide.](https://codeguide.co/#html)

- Wenn es nicht all zu umständlich ist, sollten Standard-Farbpaletten den [WCAG-Richtlinien für Farbkontrast](https://www.w3.org/TR/WCAG20/#visual-audio-contrast) folgen.
- Abgesehen von seltenen Einzelfällen, solltest du die Standard-Stile für `:focus` (also z.B. `outline: none;`) nicht entfernen ohne sinnvolle Alternativen bereitzustellen. Lies [diesen Artikel des A11Y Projects](https://a11yproject.com/posts/never-remove-css-outlines) für mehr Informationen.

### JS

- Keine Semikolons (in JS für Endgeräte)
- 2 Leerzeichen (keine Tabs)
- [strict mode](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions_and_function_scope/Strict_mode)
- "Attraktiv"
- Verwende keine [jQuery event alias Methoden](https://github.com/jquery/jquery/blob/master/src/event/alias.js) (wie z.B. `$().focus()`). Nutze stattdessen [`$().trigger(eventType, ...)`](https://api.jquery.com/trigger/) oder [`$().on(eventType, ...)`](https://api.jquery.com/on/), je nachdem ob du ein Event auslösen oder abhören willst. (Beispiel: `$().trigger('focus')` oder `$().on('focus', function (event) { /* focus event behandeln */ })`) Wir machen das, um mit selbsterstellten Builds von jQuery kompatibel zu sein, in denen das Modul für event aliases nicht enthalten ist.

### Code-Stil überprüfen

Du solltest `grunt test` ausführen, bevor du einen Commit erstellst, um sicherzugehen, dass deine Änderungen unseren Code-Richtlinien folgen.


## Lizenz

Durch die Einreichung deiner Code-Beiträge stimmst du zu, deinen Beitrag unter
der [MIT-Lizenz](https://github.com/twbs/bootstrap/blob/master/LICENSE)
zu lizenzieren.
Durch die Einreichung deiner Beiträge zur Dokumentation stimmst du zu, deinen
Beitrag unter der [Creative Commons Attribution 3.0 Unported-Lizenz](LICENSE)
zu lizenzieren.

Vor v3.1.0 war Bootstraps Code unter der Apache-Lizenz v2.0 freigegeben.
