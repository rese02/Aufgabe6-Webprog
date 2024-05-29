### Test Webprogrammierung 29.05.2024

**Name:** René Senoner

**Anweisungen:** Beantworten Sie alle Fragen sorgfältig und vollständig. Die maximale Punktzahl für diesen Test beträgt 130 Punkte.

---

#### Teil 1: Planung eines Webprojektes (Relaunch)

**1.1.** Welchen wesentlichen Unterschied gibt es zwischen dem Relaunch einer bestehenden Webseite und der Planung einer neuen Webseite? (5 Punkte)

Bei den Relaunch einer website kann man auch nur das css und das ändern  und die darstellung verändern das html wird nicht oder nur leicht verändert, bei der erstellung einer neuen Website hingegen schreibt man das ganze code neu, sowol html als auch css als auch html.

**1.2** Beschreiben Sie die wesentlichen Schritte bei der Planung eines Website-Relaunchs. (10 Punkte)

Als erstes sollte man die alte website analysieren, dann Zielgruppe definieren, Moodboard erstellen und dann sollte man planen wie mann sie neu darstellen will und zwar einen verzweigungs dokument erstellen und die verchiedenen seite und unterseiten definieren. Dann kann mann anfangen sich über diese Idee mit dem Kunden auszutauschen (wireframe) und wenn es passt kann man in der Planung des sscreendesigns gehen und anschließsnd in der programmierung und in der Umsetzung.

**1.3** Warum ist es wichtig, eine Bestandsaufnahme der aktuellen Website durchzuführen? Nennen Sie zwei Gründe. (5 Punkte)

Mann sollte eine Bestandsaufnahme der Website machen, damit man weiß was genau bei der website nicht funktioniert hat und man diesen Fehler nicht wiederholt. Und als zweites sollte man eine. Und als zweitens sollte man es machen um genau zu sehen für wem die aktuelle Website angesehen ist also für welche Zielgruppe sie gerade ansprechend ist und eventuelle Fehler zu vermeiden.

**1.4** Welche Rolle spielt die Zielgruppenanalyse bei einem Website-Relaunch? (5 Punkte)

Die Zielgruppenanalyse spielt eine wichtige rolle, denn es kann sein das die Website vor 10 Jahren für eine andere Zielgruppe gedacht war die heutzutage nicht mehr deren eigentliche zielgruppe ist und somit sich die Besucher gar nicht mehr angesprochen auf der Website fühlen und somit die website auch nicht besuchern oder nicht Zeit auf ihr verbringen was ja eigentlich unser Ziel ist.

---

#### Teil 2: Git und Github

**2.1** Erklären Sie, was Git ist und wofür es verwendet wird. (5 Punkte)

Git ist ein Versionsverlauf system auf dem man die verschiedene Dateien aufladen kann.

**2.2** Was ist Github und wie unterscheidet es sich von Git? (5 Punkte)

Github ist ein Webbasiertes system in dem Man daten oder gits mit benutzern vereinfacht teilen kann.


**2.3** Erklären Sie jeden der folgenden Begriffe: (10 Punkte)

* Repository = Das ist das Name des Ordners wo sich die ganzen zweige befinden und alles befindet eine sektion praktisch.
* Branch = das ist sozusagen ein Zweig, sozusagen eine richtung wo eine Person was erledigt ein ( außenzweig ).
* Commit = commit bedeutet das die daten oder die objekte die sich lokal befinden bereit gemacht werden zu pushen.
* Merge = Das bedeutet wenn verschiedene Personen verschiedene eigene zweige haben und sie dann zu einem großen zusammengeführt werden.
* Pull = bedeutet das die aktualisierden daten auf dem lokalen datenträger heruntergeladen werden können.
* Push = bedeuter das man die lokalen daten auf git pushen kann also (raufladen).
* Clone =  das bedeutet einfach ein objekt duplizieren.
* Remote Repository / Origin = das ist das hauptzweig wo sich alle brachens befinden.
* Fetch = ist das Aktualisieren des systems.
* Konflikt = das trifft auf wenn es ein Problem gibt nnd zwar wenn zwei brachens ein konflift haben und man davor nicht gepusht oder  gefetcht hat.

---

#### Teil 3: CSS-Variablen nutzen

**3.1** Was sind CSS-Variablen und warum sind sie nützlich? (5 Punkte)

Eine Variable ist eine vereinfachte lösung um elemente die sich mehrmals in einem code befiden zu definieren und wenn diese hier ausgewechselt werden mpssen dann ändern sich alle variablen automatisch

**3.2** Überarbeite den folgenden CSS-Code, indem du redundante Werte identifizierst und entscheidest, welche in CSS-Variablen ausgelagert werden sollten. Achte auf sinnvolle Variablennamen. (10 Punkte)

```css

/* Farben */
body {
  background-color: var(white);
}

.root {
  --(white): #f0f0f0;
  --(black): rgba(0, 0, 0, 0.1);
  --(grey): #333;
  --(paddingNorm): 20px;
  --(fontMain): Arial, sans-serif;
}

.header {
  background-color: var(grey);
  color: var(white);
}

.button {
  background-color: var(white);
  color: var(black);
  border: none;
  border-radius: 5px;
  padding: 10px 20px;
  cursor: pointer;
}

.card {
  background-color: var(grey);
  box-shadow: var(black);
  border-radius: 10px;
  padding: var(paddingNorm);
}



/* Schriftarten */
h1 {
  font-family: var(fontMain);
}

p {
  font-family: var(fontMain);
}

/* Abstände */
.container {
  margin: 20px;
}

.header {
  padding: var(paddingNorm);
}

.card {
  margin-bottom: 20px;
}

/* Größen */
.button {
  font-size: 16px;
}

.card {
  width: 300px;
}

```

---

#### Teil 4: Komponentenbasierte Elemente für Websites entwickeln

**4.1** Was versteht man unter komponentenbasiertem Webdesign? (5 Punkte)

Unter Komponentenbasiertem Webdesign versteht man ein webdessign das immer sozusgen ähnliche komponenten hat und oft wiederholen. Sozusagen ein komponent einer sektion wiederholt sich sehr oft.

**4.2** Nennen Sie zwei Vorteile der Nutzung von komponentenbasierten Elementen. (5 Punkte)

Man arbeitet viel schneller und man erspart sich fehler den es wurde einmal geschrieben und dann eventuell müssen nur kleinigkeiten ausgeändert wewrden aber man mus nicht alles nochmal schreiben.

**4.3** Erstellen Sie ein einfaches Beispiel für eine komponentenbasierte HTML-Struktur (Kartenkomponente mit Bild, Titel, Text). (10 Punkte)

```html
<!-- Beispiel HTML-Struktur für eine Kartenkomponente -->
<div class="card">
  <div class="card__inside">
    <div class="card__image">img</div>
    <div class="card__title">
    <p class="card__text">tesafdss dfydfdsfsdf sdfsdfdf</p>
    </div>
  <div>
</div>

```

---

#### Teil 5: Container Queries

**5.1** Was sind Container Queries und wie unterscheiden sie sich von Media Queries? (5 Punkte)

Bei den container Queries handelt es sich praktisch um abfragen ob und wenn sich ein container in der responsiven webdesign wie und wann verhalten soll praktisch es handelt sich um den container ganz aussen, beim Mediaqueries hingegen handelt es sich um das ganze innere eines containers und das ganze.

**5.2** Beschreiben Sie eine Situation, in der Container Queries besonders nützlich sein können. (5 Punkte)

Container Queries können dann nützlich sein wenn sich viele cards auf einer Website befinden und man die genaue anordunng und responsivität von ihnenen beschreiben will.

**5.3** Erweitern Sie den folgenden **CSS-Code** um eine Container Query, sodass der Innenabstand eines Elements bis zu einer Containerbreite von 400px (width) 20px beträgt. (10 Punkte)

```css


@container (max-widt:400px) {
  padding: 20px;
}

/* Container Query */

```

```html
<div class="container">
  <div class="box">
    Dies ist eine Beispiel-Box mit variabler Schriftgröße.
  </div>
</div>
```

---

#### Teil 6: Praktische Aufgabe

Sie erhalten ein bestehendes Webprojekt auf Github und sollen einen Relaunch planen und teilweise umsetzen. Gehen Sie wie folgt vor: (30 Punkte)

0. Erstellen Sie ein Repository "Aufgabe6-Webprog" auf Ihren lokalen Rechner und kopieren Sie den Inhalt aus dem Ordner "Daten" hinein.
1. Erstellen Sie den "initial commit"
2. Erstellen Sie einen neuen Branch mit dem Namen "relaunch".
3. **Durchführen der folgenden Änderungen:**
   - **CSS-Variablen:** Definieren Sie sinnvolle CSS-Variablen und verwenden Sie diese in Ihrer CSS-Datei.
   - **Komponentenbasierte Elemente:** Entwickeln Sie eine einfache, komponentenbasierte HTML-Struktur für eine Kartenkomponente, die einen Titel, ein Bild und einen Text enthält.
   - **Container Queries:** Implementieren Sie eine Container Query, um die Schriftgröße der Kartenkomponente basierend auf der Containergröße anzupassen. Verwenden Sie eine Schriftgröße von 1rem bis zu einer Containerbreite von 540px.
4. **Committen Sie Ihre Änderungen:** Geben Sie nach jedem bedeutenden Schritt einen aussagekräftigen Commit-Namen an und committen Sie Ihre Änderungen.
5. **Merge:** Führen Sie einen Merge des "relaunch"-Branches zurück in den Haupt-Branch ("main") durch.
6. Erstellen Sie auf ihrem Github-Account ein neues öffentliches Repository mit dem Namen "Abgabe-Webprog".
7. Notieren Sie hier die URL zu Ihrem Repo auf Github:
8. Pushen Sie Ihr lokales Repository in das neu erstellte Remote-Repository.
9. Speichern Sie zusätzlich alle lokalen Dateien als ZIP-Datei "vorname-nachname.zip" und mailen diese an manuel@startmedia.at