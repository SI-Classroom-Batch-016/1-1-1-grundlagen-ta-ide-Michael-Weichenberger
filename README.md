<h1 align="center">Grundlagen der Programmierung</h1>
<h2 align="center">IDE</h2>
<br>

#### Beschreibung:

Yeah! du hast es geschafft dein erstes Repository zu klonen! Hier geht es jetzt ans Eingemachte, du wirst heute noch
deine ersten Zeilen Code schreiben!

---

<details>
<summary> <b>  Das Vorlesungs-Repository klonen </b> </summary>

Ihr werdet künftig jeden Tag in der Vorlesung gemeinsam mit dem Dozenten Code erarbeiten. Damit ihr auch nach der
Vorlesung diesen Code einsehen könnt, wird der Dozent den Code auch in ein GitHub Repository pushen. Ihr könnt dann
jeden Tag einfach in diesem Projekt einmal die "Pull"-Operation ausführen und bekommt automatisch den neuen Code auf
euer Gerät.

Damit dies funktioniert müsst ihr nun einmal dieses Projekt klonen. Das funktioniert erneut über "File" -> "New" -> "
Project from Version Control"
Den Link zum Repository findet ihr in Slack an unseren Channel angehängt.

Wichtig fürs Verständnis: Das Vorlesungs-Repository und die Aufgaben sind jeweils eigenständige Projekte. Es gibt also
ein Repository in dem ihr jeden Tag den Vorlesungs-Code bereitgestellt bekommt und jeden Tag ein eigenes Repository für
die Aufgaben des jeweiligen Tages.

</details>

---

<details>
<summary> <b> Anwendung kompilieren und ausführen </b> </summary>

Als Nächstes wollen wir eine Kotlin Datei kompilieren und ausführen.
Nimm die "01_KompilierenUndAusfuehren.kt" (du findest diese unter src/main/kotlin) aus dem gerade von dir geklonten Projekt.
Das Beispielprogramm ist eine einfache Konsolenanwendung, die einige Zeilen Text ausgibt, wonach du dann deinen Namen
eingeben kannst.

<img width="1434" alt="Screenshot 2023-03-13 at 11 11 11" src="https://user-images.githubusercontent.com/101104769/224685712-3483b5ab-74ad-427c-a4b9-44c7387453d5.png">

Versuche den Code nicht nur auszuführen, sondern diesen auch zu verstehen. Fasse ihn in deinen eigenen Worten zusammen.
**Hinweis**: Die ausgegrauten Zeilen sind Kommentare, diese beschreiben den Code. Wenn eine Zeile // am anfang hat, dann wird sie vom Computer ignoriert.

</details>

---

<details>
<summary> <b> Fachbegriffe lernen und verstehen </b> </summary>

Gehe nun die Datei `02_FachbegriffeVerstehen.kt`. Dort findest du einen mehrzeiligen Kommentar mit einem Quiz.

Du hast heute verschiedene Fachbegriffe kennengelernt. Sieh dir zur Wiederholung die folgenden Aussagen an und überlege,
welche wahr sind und welche nicht. Bei jeder Aufgabe gibt es mindestens eine wahre Aussage, es sind aber auch mehrere
wahre Aussagen möglich. Kreuze die wahren Aussagen an. Setze hierzu ein 'X' in die eckigen Klammern

</details>

---

<details>
<summary> <b> Vorhersagen, was Programm ausgibt </b> </summary>

In dieser Aufgabe bekommst du einige Zeilen Programmcode, der etwas in der Konsole ausgibt.
Überlege, wie diese Ausgabe genau aussieht und schreibe deine Antwort unterhalb des Quiz in die
Datei `02_FachbegriffeVerstehen.kt`.

```kotlin
println("Hello World!")
println("Heute ist ein schöner Tag!")
println("Sehr gut! Ihr habt es fast geschafft. \n Jetzt könnt ihr schon eure ersten Zeilen Code lesen.")
```

</details>

---

<details>
<summary> <b> Deine Lösungen abgeben </b> </summary>

Um deine bearbeiteten Dateien abzugeben, müssen wir deine Ergebnisse zurück auf GitHub pushen. Dadurch werden die
Änderungen, die du hier im Projekt vorgenommen hast auf GitHub übertragen.
Dafür sind zwei Schritte nötig:

- Commiten: Das bedeutet so viel wie "Änderungen speichern und zum Hochladen vorbereiten". Klicke hierfür oben in der
  Leiste auf "Git" und dann auf "Commit". Ein neues Fenster öffnet sich rechts un denen du alle Dateien siehst, an denen
  du Änderungen vorgenommen hast. Gehe sicher, dass alle Dateien mit Änderungen angehakt sind. Anschließend musst du
  noch eine Commit-Nachricht hinterlegen. Schreibe hierfür einfach "Aufgaben bearbeitet" in das Fenster unterhalb der
  Dateien. Wenn du dies alles erledigt hast, klicke "commit". Es kann sein, dass IntelliJ dich darauf aufmerksam macht,
  dass es Warnungen in deinem Code gibt. Diese kannst du mit einem Klick auf "commit anyway" ignorieren.
- Pushen: Pushen lädt nun den gerade erstellten Commit auf GitHub hoch. Klicke hierfür oben erneut auf "Git" und dann
  auf "Push". Es öffnet sich ein Fenster in welchem du unten rechts "Push" klickst. Sollte alles richtig funktionieren
  sollte dein Code jetzt gepusht sein!

</details>

---

<details>
<summary> <b> Neues Projekt erstellen </b> </summary>

Nun sollst du dich an deinem eigenen Projekt probieren!
Als Erstes wollen wir ein erstes Projekt in IntelliJ anlegen. Drücke dazu einfach im Willkommenfenster auf "New
Project", gebe dem Projekt einen Namen, lege einen Speicherort fest und lege los. Alternativ kannst du auch über Datei → neues Projekt ein neues Projekt erstellen.
<br>

**Wichtig:** Achte darauf dass als Language "Kotlin" ausgewählt ist.

</details>

---

<details>
<summary> <b> Hello World! </b> </summary>

Öffne nun die Datei `Main.kt`, diese findest du unter src -> main -> kotlin -> `Main.kt`. Falls diese Datei nicht
existiert, lege sie unter dem zuvor genannten Pfad an. Gegebenenfalls musst du noch eine main-Funktion hinzufügen, um
das Programm zu starten.

  ```kotlin
  fun main() {
    //Schreibe hier deinen Code
  }
  ```

Schreibe nun innerhalb dieser Datei deine erste Zeile Code, welche dafür sorgt das ein "Hello World" auf der Konsole
ausgegeben wird.
Nutze hierfür `println()`.

<img width="179" alt="Bildschirm­foto 2023-03-13 um 09 35 05" src="https://user-images.githubusercontent.com/97530544/224648476-c33423d3-db9d-400d-b989-4dea3871a324.png">

</details>

---

<details>
<summary> <b>  Hello "Name" </b> </summary>

Wir wollen nun nicht mehr komplette Welt grüßen, sondern nur die Person die unser Programm bedient. </b>
Das Programm soll dazu den Nutzer nach seinen Namen fragen und ihm, nach Eingabe dessen, begrüßen. </b>
Um deinen Namen in der Konsole eingeben zu können, kannst du diesen mit dem folgenden Code in der Variable `name`
speichern.

  ```kotlin
  var name = readln()
  ```

<img width="347" alt="Bildschirm­foto 2023-03-13 um 09 28 40" src="https://user-images.githubusercontent.com/97530544/224648178-70773e14-3015-432d-bed0-1deb0ec041e7.png">
</details>


---

<details>
<summary> <b>  Nutzeralter </b> </summary>

Nun soll das Programm den Nutzer zusätzlich noch nach seinem Alter fragen und auch dies auf der Konsole ausgeben.

<img width="343" alt="Bildschirm­foto 2023-03-13 um 09 32 05" src="https://user-images.githubusercontent.com/97530544/224648226-9f071410-22bb-4006-8693-9773e0dd1dd9.png">

**Hinweis**: Das zweite Projekt musst du nicht auf Github pushen.
</details>

---

Viel Erfolg!
