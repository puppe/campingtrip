# Camping-Ausflug

Hier soll es darum gehen, auszuprobieren, wie und ob man Git benutzen
kann, um ein gemeinsames Projekt zu planen. In unserem Fall planen wir
einen gemeinsamen Camping-Ausflug.

Weil noch unklar ist, wie ein sinnvolles Vorgehen am Ende aussehen
könnte, will ich zu Beginn erst mal nicht zu viele Regeln aufstellen.
Aber ein paar Sachen will ich doch festlegen.

## Aufgaben

### Einfache Aufgaben

* Jede Aufgabe soll in einer eigenen Datei stehen. Der Dateiname kann
  willkürlich gewählt werden.
* In der ersten Zeile der Datei, soll der Titel der Aufgabe stehen.
* In der zweiten Zeile steht `o`, wenn die Aufgabe noch offen ist, oder
  `x`, wenn sie erledigt ist.
* Ab der dritten Zeile können beliebige Notizen und Kommentare
  eingetragen werden.

### Aufgaben mit Unteraufgaben

* Aufgaben können auch Unteraufgaben haben. Statt einer Datei, wird
  dafür ein Verzeichnis verwendet.
* In dem Verzeichnis gibt es dann mindestens eine Datei `0dir`, in der Titel,
  Erledigt-Status und Notizen der Aufgabe stehen.

## Liste von Peers

Im Wurzelverzeichnis liegt die Datei `0peers`. Dort sollte jeder die
URL(s) seines Repositories eintragen. Die Idee ist, dass alle dann mehr
oder weniger regelmäßig den master-Branch der übrigen Peers pullen (bzw.
fetchen und dann mergen).
