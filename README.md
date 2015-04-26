# OpenWebSoccer-Sim / TLC Version by Rolf Joseph / ErdemCan - Starten Sie Ihren eigenen Online-Fu�ball-Manager !

Mit dieser PHP-basierten Web-Anwendung k�nnen sie Ihren Website-Besuchern einen virtuellen Fantasy-Fu�ball-Manager anbieten.

Sie setzen die Taktik f�r das n�chste Spiel, erwerben oder bieten Spieler auf dem Transfermarkt, trainieren Ihre Mannschaft.
Suchen Sie nach neuen Talenten in der Jugendabteilung oder erweitern ihre Stadion.

Die Software simuliert alle Spiele automatisch und in Echtzeit. Der Spielbericht, einem Live-Ticker �hnlich, begleitet das
Live-Spiel, wo der User Live in das Spiel eingreifen kann.

Viele Optinonen und viele Einstellungsm�glichkeiten runden die Open Websoccer-Sim ab.

## Die TLC-Version beinhaltet zur Zeit folgende �nderungen bzw. Erweiterungen

Die neue Core-Struktur bietet eine einfache Entwicklung. �nderungen an den Orginal-Dateien bzw. Erweiterungen mittels extend
sind daher nicht mehr n�tig und erh�hen damit die Stabilit�t. Legen Sie eine bearbeitete Kopie der Datei in die �rspr�nglichen
Ordnern. So k�nnen auch Fremdmodule leicht eingebunden oder getestet werden.

- Die Null-Byte-Dateien wurden entfernt und in der lockfile.txt Versionsinformationen eingef�gt
- alle Dateien aus dem Verzeichniss classes wurden den Modulen im Ordner modules zugeordnet
- die Datei global.inc.php wurde angepasst und ersetzt die original Datei
- alle Dateein aus dem Verzeichnis templates/default wurden den Mmodulen im Ordner modules zugeordnet
- die Datei TemplateEngine.class.php wurde angepasst und ersetzt ebenfalls die original Datei
- f�r die Zuordnung der Dateien zu den Modulen wurde eine Batch-Datei ersellt, siehe im Ordner websoccer-tools
- die Installationsf�hrung wurde angepasst, so das sich nun Fragen dazu er�brigen d�rften
- entsprechend wurde die Datei websoccer/install/index.php angepasst
- alternative job.php im Hauptverzeichnis ( Parameter werden �ber die Konfiguration gesteuert )
- Anpassung der modul.xml und der adminmessages_de.xml im Modul core f�r die alternative job.php
- Anpassung in der layout.twig wegen des Hinweis auf die Version
- Anpassung der Datei websoccer/admin/config/version.txt auf Open Websoocer-Sim / TLC 1.0


Das Verzeichnis kann nun auch als Update genutzt werden. Die gesetzte Konfiguration wird nun nicht mehr �berschrieben, da die
Datei config.inc.php nicht mehr mitgeliefert wird.


## Dieser Ableger basiert auf der Open Websoccer-Sim, die sie hier bekommen:

** [Jetzt downloaden!] (Https://github.com/ihofmann/open-websoccer/releases) **


## Nachfolger des HSE WebSoccer-Sim

OpenWebSoccer-Sim ist der offizielle Nachfolger der kommerziellen Produkte _H & H WebSoccer_ und _HSE WebSoccer-Sim_.
Herr Ingo Hofmann ist ein professionellen Software-Ingenieur aus der Schweiz, der die erste Version der Software im Jahr 2003 entwickelt hat.

Die Unterst�tzung von anderen Entwicklern mit Erweiterungen oder Ideen ist der Grund das der Websoccer nun OpenSource ist.

Sie k�nnen �ber Ingo erreichen: Ingo (at) websoccer- sim.com.


## Dokumentation und Issue Tracker in englischer Sprache

Hinweise zur Installation, Konfiguration und zur Verbesserung der Software in der [Wiki] (https://github.com/ihofmann/open-websoccer/wiki/00.-Home).

Haben Sie einen Fehler gefunden oder haben eine Idee f�r ein neues Feature? Dann z�gern Sie nicht, ein Problem �ber der [Issue Tracker] zu er�ffnen (https://github.com/ihofmann/open-websoccer/issues).