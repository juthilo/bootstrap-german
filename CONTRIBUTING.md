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

* Der Issue Tracker ist **nicht** für persönliche Hilfe-Anfragen geeignet.
  Stack Overflow ([`twitter-boostrap-3`](http://stackoverflow.com/questions/tagged/twitter-bootstrap-3)-Label)
  oder [IRC](README.md#community) sind bessere Orte, um Hilfe zu erhalten.

* **Beachte und respektiere** Andere in Diskussionen zu Issues und **vermeide**
  einen unhöflichen Umgangston sowie Abschweifungen vom Thema.

* Bitte öffne **keine** Meldungen oder Pull Requests, die sich auf Code in
  [`Normalize`](https://github.com/necolas/normalize.css) beziehen (reiche diese
  Beiträge stattdessen im zugehörigen Repository ein).


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

0. **Validiere und linte deinen Code** &mdash; [validiere dein HTML](http://html5.vaidator.nu)
   und [linte dein HTML](https://github.com/twbs/bootlint), um sicherzustellen, dass dein
   Problem nicht von einem einfachen Fehler in deinem eigenen Code verursacht wird.

1. **Verwende die Suche auf GitHub** &mdash; sieh nach, ob der Fehler schon
   gemeldet wurde.

2. **Sieh nach, ob das Problem schon behoben wurde** &mdash; versuche, es mit
   dem neuesten Code aus dem Branch `master` oder einem Entwicklungszweig im
   Repository zu reproduzieren.

3. **Isoliere das Problem** &mdash; am besten ist ein [reduzierter Musterfall](http://css-tricks.com/6263-reduced-test-cases/)
   und ein Live-Beispiel.
   [Dieser JS Bin](http://jsbin.com/lefey/1/edit?html,output) ist eine hilfreiche Vorlage.


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

### Browser-Bugs melden

Einige der Fehlermeldungen, die wir erhalten, beziehen sich auf Fehler, die von Bugs in den Browsern selbst und nicht von Bootstrap verursacht werden.
Wenn angebracht, versuchen wir diese Upstream-Fehler an die relevanten Browser-Hersteller zu melden und dann an unserer [Pinnwand für Browser-Bugs](http://holdirbootstrap.de/browser-bugs/) aufzuführen und [sie im MDN zu dokumentieren](https://developer.mozilla.org/de/docs/Web).

| Hersteller    | Browser                      | Rendering Engine | Seite für Fehlermeldungen                                                             | Hinweise                                            |
| ------------- | ---------------------------- | ---------------- | ------------------------------------------------------------------------------------- | --------------------------------------------------- |
| Mozilla       | Firefox                      | Gecko            | https://bugzilla.mozilla.org/enter_bug.cgi                                            | "Core" ist meistens die richtige Produktkategorie.  |
| Apple         | Safari                       | WebKit           | https://bugs.webkit.org/enter_bug.cgi?product=WebKit <br> https://bugreport.apple.com | In Apples Bug Reporter "Safari" als Produkt wählen. |
| Google, Opera | Chrome, Chromium, Opera v15+ | Blink            | https://code.google.com/p/chromium/issues/list                                        | Klick den Button "New issue".                       |
| Microsoft     | Internet Explorer            | Trident          | https://connect.microsoft.com/IE/feedback/LoadSubmitFeedbackForm                      |                                                     |


### Issues Bots

[@twbs-lmvtfy](https://github.com/twbs-lmvtfy) ist ein Bootstrap-Bot, der in unserem GitHub-Issue-Tracker herumhängt und automatisch alle Live-Beispiele (z.B. jsFiddles, JS Bins, Bootplys, Plunks, CodePens, usw.), die in Issue-Kommentaren gepostet werden, auf HTML-Validierungs-Fehler überprüft. Falls er irgendwelche Fehler findet, schreibt er einen Kommentar darunter und weist auf diese hin. Falls das mit einem Beispiel von dir passiert, behebe bitte die Fehler und poste eine aktualisierte Version deines Live-Beispiels. Falls du eine Fehlermeldung erstellt hast, überprüfe bitte, ob der Bug mit dem berichtigten Beispiel immer noch auftritt. Falls der Fehler nicht mehr auftritt, ist dieser wahrscheinlich auf dein ungültiges HTML zurückzuführen und nicht durch etwas in Bootstrap verursacht und wir würden es begrüßen, wenn du das Issue auf GitHub schließen könntest.


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

**Bearbeite `bootstrap.css`, `bootstrap-theme.css` oder `bootstrap.js` niemals
direkt!** Diese Dateien werden automatisch generiert. Du solltest stattdessen
die Quelldateien in
[`/bootstrap/less/`](https://github.com/twbs/bootstrap/tree/master/less)
und/oder [`/bootstrap/js/`](https://github.com/twbs/bootstrap/tree/master/js)
bearbeiten.

Genauso solltest du bei Beiträgen zu Bootstraps Dokumentation die Quelldateien im
[Verzeichnis `/bootstrap/docs/` der `master`-Branch](https://github.com/twbs/bootstrap/tree/master/docs)
bearbeiten. **Bearbeite niemals die `gh-pages`-Branch.** Diese Branch wird aus den
Quelldateien der Dokumentation generiert und wird vom Bootstrap-Hauptteam separat
verwaltet.

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

### Pull Request Bots

[@twbs-rorschach](https://github.com/twbs-rorschach) ist ein Bootstrap-Bot, der in unserem GitHub-Issue-Tracker herumhängt und automatisch alle Pull Requests auf einige übliche kleine Fehler überprüft. Es kann sein, dass Rorschach einen Kommentar bei deinem Pull Request hinterlässt und diesen dann schließt. Falls das passiert, behebe einfach die Probleme, die im Kommentar genannt werden (dieser sollte Links zu Detailinformationen zu den jeweiligen Problemen enthalten) und dann:

* Pushe die überarbeitete Version der Branch deines Pull Requests und schreibe einen Kommentar bei dem Pull Request, in dem du sagst, dass du das Problem behoben hast. Jemand aus dem Bootstrap-Hauptteam wird dann deinen Pull Request wieder öffnen.
* Oder du kannst einfach einen neuen Pull Request für deine überarbeitete Version öffnen.

[@twbs-savage](https://github.com/twbs-savage) ist ein Bootstrap-Bot, der automatisch Tests in verschiedenen Browsern (via [Sauce](https://saucelabs.com) und Travis CI) bei JavaScript-Pull Requests durchführt. Savage hinterlässt einen Kommentar bei Pull Requests und sagt, ob JS-Browsertests erfolgreich waren oder fehlgeschlagen sind, mit einem Link zu den vollständigen Travis-Build-Details. Falls dein Pull Request durchfällt, überprüfe das Travis-Log, um zu sehen, welche Browser- und Betriebssystem-Kombinationen die Tests nicht erfolgreich ausführen konnten. Jeder Browser-Test im Travis-Log enthält einen Link zu einer Seite bei Sauce mit Details über den Test. Auf diesen Detail-Seiten kannst du einen Bildschirmmitschnitt von dem Testlauf anschauen, um genau zu sehen, welche Unit Tests fehlgeschlagen sind.

## Code-Richtlinien

### HTML

[Befolge die Regeln aus dem Code Guide.](http://codeguide.co/#html)

- Verwende Tags und Elemente für einen HTML5-Doctype (z.B. selbst-schließende Tags)
- Nutze CDNs und HTTPS für JS von Dritten, wenn möglich. Wir nutzen keine protokoll-unabhängigen URLs in diesem Fall, da diese nicht funktionieren, wenn die Seite lokal über `file://` angezeigt wird.
- Verwende Attribute entsprechend [WAI-ARIA](https://developer.mozilla.org/de/docs/Web/Barrierefreiheit/ARIA) in Beispielen in der Dokumentation, um beim Thema Barrierefreiheit mit gutem Beispiel voranzugehen.

### CSS

[Befolge die Regeln aus dem Code Guide.](http://codeguide.co/#html)

- Wenn es nicht all zu umständlich ist, sollten Standard-Farbpaletten den [WCAG-Richtlinien für Farbkontrast](http://www.w3.org/TR/WCAG20/#visual-audio-contrast) folgen.
- Abgesehen von seltenen Einzelfällen, solltest du die Standard-Stile für `:focus` (also z.B. `outline: none;`) nicht entfernen ohne sinnvolle Alternativen bereitzustellen. Lies [diesen Artikel des A11Y Projects](http://a11yproject.com/posts/never-remove-css-outlines/) für mehr Informationen.

### JS

- Keine Semikolons (in JS für Endgeräte)
- 2 Leerzeichen (keine Tabs)
- [strict mode](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions_and_function_scope/Strict_mode)
- "Attraktiv"

### Code-Stil überprüfen

Du solltest `grunt test` ausführen, bevor du einen Commit erstellst, um sicherzugehen, dass deine Änderungen unseren Code-Richtlinien folgen.


## Lizenz

Durch die Einreichung deiner Code-Beiträge stimmst du zu, deinen Beitrag unter
der [MIT-Lizenz](https://github.com/twbs/bootstrap/blob/master/LICENSE) zu lizenzieren.

Vor v3.1.0 war Bootstrap unter der Apache-Lizenz v2.0 freigegeben.
