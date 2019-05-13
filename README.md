# System-Programmierung
## Hands-on zu Lektion 10
Für Slides und Code Beispiele, siehe [Lektion 10](../../../fhnw-syspr/blob/master/10/README.md)

> *Achtung: Arbeiten Sie nicht direkt auf diesem Repository.*<br/>
> *[Erstellen Sie eine persönliche Kopie, mit diesem GitHub Classroom Link](https://classroom.github.com/a/yLSOSh4Z).*

### a) *curses* Library, 30'
* Lesen Sie diese PDF Tutorials zur *curses* Bibliothek: http://heather.cs.ucdavis.edu/~matloff/UnixAndC/CLanguage/Curses.pdf und zu [Games mit ncurses](https://www.viget.com/articles/game-programming-in-c-with-the-ncurses-library/).
* Kompilieren und testen Sie die Beispielprogramme:<pre>
$ sudo apt-get install libncurses5-dev
$ gcc -o NAME NAME.c -lcurses</pre>
* Schreiben Sie ein eigenes Programm mit *ncurses*.

### b) Kilo.c Revisited, 15'
* Analysieren Sie den Source Code dieses Programms: https://github.com/antirez/kilo/blob/master/kilo.c
* Welche Terminal-spezifischen Calls werden im Code verwendet und wozu?

### Abgabe (optional)
* Lokale Änderungen [committen und pushen](#git).
* GitHub [Issue erstellen](../../issues/new) mit "Bitte um Review, @tamberg".
* Offene Fragen ausformulieren, was geht nicht, was haben Sie versucht.
* GitHub mailt mir (@tamberg) automatisch, ich versuche in weniger als 24h zu antworten :)

## Tools
### Git
Auf Ihrem Computer
* Zu Beginn jeder Lektion wird ein Hands-on Repository Link freigeschaltet
* Nachdem Sie das "Assessment" annehmen, bekommen Sie per Email ein Repository
* Die REPO_URL enthält Ihren GitHub Account USER_NAME und Ihre Klasse 3ia oder 3ib, z.B.<br/>
            https://github.com/fhnw-syspr-3ia/fhnw-syspr-work-10-tamberg

Auf dem Raspberry Pi
* Repository klonen<pre>
    $ cd ~
    $ git clone REPO_URL</pre>
* Neue Datei kreieren<pre>
    $ git add FILE</pre>
* Änderungen committen<pre>
    $ git commit FILE -m "Fixed all bugs"</pre>
* Änderungen hochladen<pre>
    $ git push</pre>

### Nano
Auf dem Raspberry Pi
* Neue oder bestehende Datei öffnen mit $ nano FILE
* Editieren (Achtung, nano hat kein Undo)
* Speichern mit `CRTL-X` `Y` `RETURN`

### SSH
Auf Ihrem Computer
* Terminal öffnen (Mac) oder `WINDOWS` `R` cmd `RETURN` (Windows)
* SSH Session starten mit<pre>
    $ ssh pi@raspberrypi.local</pre>

## Support
- [FHNW Syspr Slack](https://fhnw-syspr.slack.com/)
