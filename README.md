# Projektseite 2

## Fuchsland

![bsp fuchslandNeu](Bilder.exe/fuchslandNeu.PNG)


## Inhaltsverzeichnis

* [Projektvorstellung](#projekt)
  * [Die Intention der App](#Intention)
* [Die App selber programmieren](#dssp)
  * [App Lab - Code.org](#al)
  * [Erste Schritte](#erste)
  * [Das Spiel programmieren](#Spiel)
  * [Den Test programmieren](#Test)
  * [Das Quiz programmieren](#Quiz)
  * [Weitere Screens](#weitere)


## Projektvorstellung <a name="projekt"></a>

Unser Projekt ist eine App, die wir mit App Lab-Code.org erstellt haben. Die App besteht aus einer Spiel-, Quiz- und Testebene, die unabhängig voneinander gespielt werden können und sich alle um das Thema Klimaschutz und Klimawandel drehen, damit der Nutzer auch etwas beim Spielen lernt. Man erreicht diese verschiedenen Ebenen vom Startscreen (siehe oben) aus, der das Fuchsland darstellt. Außerdem wird man von einem Fuchs durch die App begleitet.

### Die Quizebene

(BILD VON QUIZ FRAGE1, FFRAGE 1 UND RICHTIG)

![bsp quiz1](Bilder.exe/quiz1.png)

In diesem Teil der App gibt es 10 Fragen zum Klimawandel mit jeweils drei Antwortmöglichkeiten. Bei richtiger bzw. falscher Antwort wird man zum entsprechenden Screen weitergeleitet, wo es den passenden Erklärtext bzw. Ergänzungen zur richtigen Antwort gibt. Von dort aus kann man zur nächsten Frage weitergehen. SCORE?

### Die Testebene

![bsp test3](Bilder.exe/test3.PNG)

(BILD VON Test1, Endescreen)

In dieser Ebene kann der Spieler sich in 5 Fragen selber testen, ob er genug für den Klimaschutz tut. Oben in Screen steht die Frage, darunter die Antwortmöglichkeiten in Form von Bildern und darunter wiederum der Fuchs, der sich mithilfe der Pfeiltasten zum jeweiligen Bild steuern lässt.
Jenachdem, welche Antwort gewählt wird, wird dem Score 1 (gut für das Klima) oder 2 Punkte (schlecht für das Klima) hinzugefügt.
Nach den 5 Fragen wird dem Spieler sein Endergebnis und die entsprechende Bewertung angezeigt. 

### Die Spielebene

![bsp spiel1](Bilder.exe/spiel1.PNG)


Beim Spiel soll man innerhalb von 20 Sekunden so oft wie möglich auf eine Plastikflasche klicken, die nach jedem KLick ihre Position zufällig ändert. Außerdem hat man 3 Leben, die zusammen mit dem Score am oberen Bildschirmrand mitgezählt werden.

![bsp spiel2](Bilder.exe/spiel2.PNG)

Schafft man es, innerhalb der 20 Sekunden mindestens 10 Mal auf die Flasche zu klicken, ohne dabei 3 Leben zu verlieren, erscheint der Screen, dass man gewonnen hat. Von dort aus kann man nochmal spielen oder ins Fuchsland zurückkehren:

![bsp gewonnen](Bilder.exe/gewonnen.PNG)

Wenn man aber nach den 20 Sekunden weniger als 10 Klicks geschafft hat oder alle 3 Leben verloren hat, wird einem der Verloren-Screen angezeigt. Von dort kann man genauso fortfahren wie beim Gewonnen-Screen.

![bsp verloren](Bilder.exe/verloren.PNG)

## Die Intention der App <a name="Intention"></a>

Mit der App "Fuchsland" sollen der Spaß beim Spielen und das Erweitern des Wissens über das Thema Klimawandel miteinender vereint werden. Das Spiel soll somit zum Lernen motivieren, aber auch das Bewusstsein dafür stärken, in welcher aktuellen Lage die Erde steckt, und somit auch wir Menschen, und inwiefern unser Verhalten diesen Zustand bzw. den Klimawandel selbst beeinflusst. 
Durch das allgemein kindliche Design und das Spiel ist die App zwar für jüngere Kinder geeignet, das Quiz erfordert allerdings etwas mehr Allgemeinbildung. Somit ist die App generell für mehrere Zielgruppen geeignet.

## Die App selber programmieren <a name="dssp"></a>

## App Lab - Code.org <a name="al"></a>

![bsp code](Bilder.exe/code.PNG)

Bevor man mit dem Programmieren des Spiels beginnt, sollte man sich erst mit dem Programm vertraut machen.

Code.org ist ein gemeinnütziges Unternehmen aus den USA und wurde 2013 gegründet. Die Grundidee hinter der Programmierungswebsite besteht darin, jedem die Möglichkeit zu geben, Programmieren zu lernen. Außerdem soll die Programmierfähigkeit besonders in der Schule gefördert werden. 

MIT App Inventor ist online frei zugänglich, vor der ersten Anwendung muss man sich mit seiner E-mail-Adresse registrieren. Danach kann man begonnene Projekte online speichern, sodass man jederzeit darauf zugreifen kann und diese weiterbearbeiten kann.

Das Programmieren auf Code.org basiert auf Java, ist aber durch die Blocks, die sinnvoll zusammengefügt werden müssen, relativ einfach und somit für Anfänger geeignet. Dadurch, dass Code.org auf viele Sprachen eingestellt werden kann, kann man bei Verständnisschwierigkeiten auch z.B. auf Deutsch programmieren. Wenn man allerdings schon mit anderen Programmen gearbeitet hat, kann die Umstellung auch eher irritieren, da manche Befehle eher auf Englisch vertraut sind.

Ein Code.org-Projekt teilt sich in drei Ebenen auf, den Code-, Design- und den Data-Editor. Letzteres haben wir für unsere App nicht verwendet, da er genutzt werden kann, um Daten wie Highscores außerhalb der App zu speichern.

### Der Code-Editor:

![bsp code2](Bilder.exe/code2.PNG)

In dem Block Editor kann man per Drag and Drop verschiedene Blocks aus der Tool Box aus den verschiedenen Kategorien auf die rechte Fläche ziehen. Diese Blocks kann man beliebig miteinander kombinieren und bei einigen selber bestimmte Befehle oder Dinge wie Definitionen und Benennungen dazutragen. Man kann verschiedene Screens miteinander verknüpfen, die Bewegung der Objekte programmieren und entscheiden, was beim Anklicken bestimmter Buttons, Labels oder anderer Objekte passiert.

Zudem kann die Ansicht der Blocks gewchselt werden, indem man oben rechts auf "Show Text" klickt. Diese Ansicht kann weniger übersichtlich sein, aber das ist für jeden unterschiedlich. Wenn man allerdings in dieser Textansicht einen Fehler einbaut, kann man nicht zu Block-Ansicht zurückkehren, bevor der Fehler behoben wurde. 

![bsp showblocks](Bilder.exe/showblocks.PNG)

Das Besondere an Code.org ist aber auch, dass einem die Ursachen für Fehler angezeigt werden. Einmal direkt an den Blocks...

![bsp fehler](Bilder.exe/fehler.png)

...und in der Debug Console, wo auch längere Ausführungen über die Ursachen stehen können. Diese können häufig dabei helfen, den Fehler zu beheben und erleichtern somit das Programmieren.

![bsp debug](Bilder.exe/debug.PNG)

### Der Design-Editor:

![bsp design](Bilder.exe/design.PNG)

In dem Design Editor kann man Hintergründe, Images, Textlabels o.Ä. erstellen und sie oben rechts in dem Kasten *id* umbenennen,z.B. um bei der Programmierung dieser Objekte nicht den Überblick zu verlieren. Dazu kann man Bilder von seinem eigenen Computer oder aus dem Internet in das Projekt hochladen. 

Bei Code.org kann man so viele verschiedene Screens erstellen, wie man möchte und sie z.B. auch duplizieren, um sich Arbeit zu ersparen. Diese Möglichkeiten sind für unser Projekt sehr praktisch, da wir durch die Quiz-, Spiel-, und Testebene viele, ähnliche Screens brauchen.


## Erste Schritte <a name="erste"></a>

Zunächst muss ein neues Projekt gestartet werden. Bevor man mit dem Programmieren beginnt, sollte einem das allgemeine Konzept der App bereits bewusst sein. Generell hat Code.org den Vorteil, dass das Projekt, die Screens und alle Objekte wie Buttons, Labels und TextAreas zu jeder Zeit umbenannt werden können, was große Flexibilität ermöglicht, falls man neue Ideen bekommt oder Korrekturen vornehmen möchte.

Trotzdem sollte schon ab Erstellen des ersten Screens jedes Objekt sinnvoll benannt werden. Das verschafft Übersicht, sobald die Programmierung komplexer wird und ist auch für eventuelle Nachahmer nachvollziehbarer.

## Das Spiel programmieren <a name="Spiel"></a>

Das Spiel beginnt mit dem Startscreen, von dem man durch einen Button zum eigentlichen Spiel gelangt. Mit dem Anklicken des Buttons *startbs* werden außerdem die Textlabels score, lives und timer benannt und definiert, sodass auf dem Screen *Clicker* diese durch bestimmte Ereignisse sich wie Variablen verhalten und geändert werden können. Gleichzeitig wird *Clicker*  initialisiert.

   
    Bei diesem Programm bzw. der App ist es wichtig, Variablen zu definieren, 
    bevor sie in den eigentlichen Blocks verwendet werden.
    
So wird auch hier zuerst die Variable *timer* definiert und erhält den Wert 20 (Sekunden).   
Mit der Initialisierung des Screens *Clicker* wird dann der Timer aktiviert...1000.. und wird mit `timer-1` so programmiert, dass die Uhr rückwärts läuft und durch den Block `setText "timer" = timer` für den Spieler sichtbar ist.
 
Der Block `(if) timer==0` lässt den nächsten Block erst ausführen, wenn die Bedingung `x==y` true, also erfüllt ist. Ist der Timer auf 0 Sekunden abgelaufen, werden die Variablen score, lives und timer wieder auf ihre Anfangswerte festgelegt, der Timer gestoppt und der Screen *verloren* erscheint.
 
 
![bsp spielcode1](Bilder.exe/spielcode1.PNG)
![bsp verloren](Bilder.exe/verloren.PNG)

Die Programmierung für den Screen *Clicker* ist ähnlich. Auch hier wird der Text für lives und score festgelegt und diese zusätzlich noch definiert. Hinzu kommt, dass die Plastikflasche mit dem Block `setPosition (Müll), randomNumber(x,y)...` so programmiert wird, dass sie nach jedem Klick eine zufällige Position auf dem Bildschirm einnimmt. 

Auch hier wird wieder der true/false-Block `score==10`benutzt. Dementsprechend werden die folgenden Befehle erst ausgeführt, wenn der Spieler 10 Mal auf die Flasche geklickt hat und damit einen Score von 10 hat. Mit dieser erfüllten Bedingung wird der Screen *gewonnen* initialisiert, der Timer gestoppt und die Werte von score, lives und timer zurückgesetzt

![bsp spielcode2](Bilder.exe/spielcode2.PNG)
![bsp gewonnen](Bilder.exe/gewonnen.PNG)

Außerdem muss programmiert werden, was passieren soll, wenn der Spieler auf den Hintergrund statt auf die Flasche klickt. Dafür wird der (bei uns) häufig benutzte Block `onEvent ("background", "click"9..` eingesetzt. Auch die anderen Befehle ähneln den Vorherigen. So wird pro Klick auf den Hintergrund ein Leben abgezogen und sobald keine Leben mehr übrig sind, der Screen *verloren* angezeigt und die Werte zurückgesetzt.

![bsp spielcode3](Bilder.exe/spielcode3.PNG)

Auf dem *verloren*- und *gewonnen*-Screen sind Buttons programmiert, die mit dem eben genannten `onEvent`- Block ausgeführt werden können und den Spieler je nach Wunsch in das Fuchsland zurückkehren oder ihn das Spiel nochmal spielen lassen:

![bsp spielcode4](Bilder.exe/spielcode4.PNG)


## Den Test programmieren <a name="Test"></a>

Die folgende Blockkombination legt fest, dass bei der Initialisierung vom Screen *test1* die Variable *score3* definiert und den Wert 0 erhält. Dieser Score zeigt später durch das *label130* auf screen *testEnde* die Gesamtpunktzahl an.

![bsp testcode1](Bilder.exe/testcode1.PNG)

Für die nächsten, etwas aufwendigeren Programmierungen muss die Funktion von den beiden folgenden Blöcken bekannt sein:

![bsp addtestcode2](Bilder.exe/addtestcode2.PNG) ![bsp add2testcode2](Bilder.exe/add2testcode2.PNG)

Mit dem ersten kann man seine eigene Funktion aus mehreren Parametern erstellen, sie benennen und sie damit definieren (define). Gerade bei längeren Befehlen ist der Block also praktisch. Denn sobald man sie benannt hat, kann man diese mithilfe des zwieten blocks `myfunction(id)` bei anderen Blocks wie `if (id)`oder `onEvent(id)`einfügen, wo sie durch dieses Aufrufen (call) ausgeführt werden. So haben wird auch den größte Teil des Tests programmiert.

Die erste eigene Funktion heißt *movef* und beinhaltet die Parameter zur Steuerung des Fuchses. Hier werden die Variablen *xVel* und *yVel*, also die x- und y-Werte auf dem Koordinatensystem, definiert und gleich 0 gesetzt. 
Als nächstes folgt ein Statement-Block, also `if (...)`. Zusätzlich gibt es drei weitere `else if (...)`Befehle bzw. Bedingungen. Wird die Pfeiltaste nach oben auf der Tastatur gedrückt und damit die Bedingung `if (event.key==up)`wahr (true), wird der Befehl `yVel = -5`ausgeführt: Der Fuchs bewegt sich um 5 y-Einheiten vertikal aufwärts. Wird hingegen die Pfeiltaste nach rechts gedrückt, sind die anderen 3 Bedingungen falsch (false) und die Bedingung `if (event.key==right)`wahr, wird der x-Wert vom Fuchs um 5 x-Einheiten nach rechts verändert. Um die Steuerung möglich zu machen, muss mithilfe des letzten Blocks noch einmal festgelegt werden, dass die Position des Fuchses um diesen neu definierten x-/y-Wert ( `getXPosition (fuchs) + xVel/yVel` ) verändert wird.

![bsp testcode2](Bilder.exe/testcode2.PNG)

Die zweite eigene Funktion heißt *check* und beinhaltet die Variablen *fuchs*, *image1*, *image2*, *screen*, *point1* und *point2*. Mit der gesamten Funktion wird programmiert, was passiert wenn der Fuchs auf welchem Screen welches Bild (*image1* oder *image2*) berührt und wie viele Punkte (1 oder 2 Punkte) daraufhin dem Score hinzugerechnet werden. 

![bsp testcode3](Bilder.exe/testcode3.PNG)

![bsp testcode4](Bilder.exe/testcode4.PNG)


## Das Quiz programmieren <a name="Quiz"></a>

##### Die Fragen

![bsp quizcode1](Bilder.exe/quizcode1.PNG)


##### Programmierung des Scores


![bsp quizcode2](Bilder.exe/quizcode2.PNG)


![bsp quizcode3](Bilder.exe/quizcode3.PNG)

BILD VON ENDEQUIZ DESIGN

 

## Weitere Screens <a name="weitere"></a>










