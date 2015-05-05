# OpenWebSoccer-Sim / TLC Version by Rolf Joseph / ErdemCan - Starten Sie Ihren eigenen Online-Fu�ball-Manager !

Mit dieser PHP-basierten Web-Anwendung k�nnen sie Ihren Website-Besuchern einen virtuellen Fantasy-Fu�ball-Manager anbieten.

Sie setzen die Taktik f�r das n�chste Spiel, erwerben oder bieten Spieler auf dem Transfermarkt, trainieren Ihre Mannschaft.
Suchen Sie nach neuen Talenten in der Jugendabteilung oder erweitern ihre Stadion.

Die Software simuliert alle Spiele automatisch und in Echtzeit. Der Spielbericht, einem Live-Ticker �hnlich, begleitet das
Live-Spiel, wo der User Live in das Spiel eingreifen kann.

Viele Optinonen und viele Einstellungsm�glichkeiten runden die Open Websoccer-Sim ab.

## Die TLC-Version beinhaltet zur Zeit folgende �nderungen bzw. Erweiterungen

Die neue Core-Struktur bietet eine einfache Entwicklung. �nderungen an den Orginal-Dateien bzw. Erweiterungen mittels extend
sind daher nicht mehr n�tig und erh�hen damit die Stabilit�t. Legen Sie eine bearbeitete Kopie der Datei in die urspr�nglichen
Ordnern. So k�nnen auch Fremdmodule leicht eingebunden oder getestet werden.

- Die Null-Byte-Dateien wurden entfernt und in der lockfile.txt Versionsinformationen eingef�gt
- alle Dateien aus dem Verzeichniss classes wurden den Modulen im Ordner modules zugeordnet
- alle Dateien aus dem Verzeichnis templates/default wurden den Mmodulen im Ordner modules zugeordnet
- f�r die Zuordnung der Dateien zu den Modulen wurde eine Batch-Datei ersellt, siehe im Ordner websoccer-tools
- die Installationsf�hrung wurde angepasst, so das sich nun Fragen dazu er�brigen d�rften
- alternative job.php im Hauptverzeichnis ( Parameter werden �ber die Konfiguration gesteuert )
- Anpassung der Datei websoccer/admin/config/version.txt auf Open Websoocer-Sim / TLC 1.0

29.04.2015 Neu:

- zus�tzliche Vor- und Nachnahme-Dateien f�r Frankreich, Japan M�nner & Frauen
- Actionlogs: mit Datumsanzeige & Uhrzeit
- Actionlogs: zus�tzlicher Seite im Frontend f�r den Admin zur Anzeige aller verf�gbaren Aktivit�ten
- die ursp�nglichen Ordner bleiben f�r Eure eigenen Anpassungen & Test leer
- Updates werden in den Core integriert und �berschreiben somit nicht Eure �nderungen und Erweiterungen

02.05.2015 Neu:

- automatisches entblocken von Spielen (default) Der Admin muss nicht das geblockte Spiel von Hand frei geben.

03.05.2015 Neu:

- Frontend: Statistik & Refresh Die Userz�hlung wird sofort anstatt erst nach 15 Minuten korrigiert.

04.05.2015 Neu:

- Seite: "Heutige Spiele" jetzt mit Auto-Refresh Endlich kann man auf dieser Seite die Spiele Live verfolgen ohne klicken zu m�ssen.

05.05.2015 Neu:

- Footer: feste Position & Bild m�glich Das der Footer bei wenig Content in der Bildmitte steht ist nun vorbei.


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