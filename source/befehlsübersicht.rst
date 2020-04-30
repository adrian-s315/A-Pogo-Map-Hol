################
Befehlsübersicht
################

Hier findet ihr eine Vielzahl von Befehlen inkl. Erklärung.

|

Allgemein
"""""""""

Start
=====

::

    /start
    
Startet das Senden von Benachrichtigungen.

Stop
====

::

    /stop
    
Stoppt das Senden von Benachrichtigungen.

Area
====

::

    /area add holzminden
    
Schaltet euch für Benachrichtigungen in Holzminden frei. Sollten später weitere Regionen gescannt werden, können auch diese über den Befehl aktiviert werden.

Area remove
===========

::

    /area remove holzminden
    
Entfernt Benachrichtigungen innerhalb von Holzminden für euch.

Location
========

::

    /location holzminden
    
Setzt euren Standort auf Holzminden Zentrum.
Ausgehend von diesem Standort und der verwendeten Distanz (d3500) erhaltet ihr Benachrichtigungen.

::

    /location 51.826774,9.462102

Setzt euren Standort auf die angegebene Koordinate.

Restore
=======

::

    /restore list
    
Listet alle fertigen Track-Listen auf - siehe separates Kapitel.

::

    /restore iv96undpvp
    
Erstellt eine Kopie von der Track-Liste "iv96undpvp" für euch. Alle Pokemon, die Teil dieser Liste sind, werden zu eurer persönlichen Track-Liste hinzugefügt und eure bisherigen Track-Befehle werden überschrieben.

Tracking
""""""""

Track
=====

::

    /track kaumalat d3500
    
Aktiviert Kaumalat Benachrichtigungen im Radius von 3500m zu eurer gesetzten Position. Die Angabe dieser Distanz kann nach Belieben verändert werden, muss jedoch bei jedem Track-Befehl IMMER dabei sein!

Zusätzliche Filterkriterien - alle optional - können einzeln oder zusammen verwendet werden:

::

    /track kaumalat iv20 maxiv90 d3500
    
Benachrichtigung für Kaumalat ab 20% IV und maximal 90% IV.

::

    /track relaxo cp2000 maxcp2500 d3500
    
Benachrichtigung für Relaxo, die mindestens 2000 WP (engl. CP) haben jedoch nicht mehr als 2500.

::

    /track kaumalat level10 maxlevel20 d3500
    
Benachrichtigung für Kaumalat zwischen Level 10 und 20.

::

    /track wablu atk0 maxatk0 def10 maxdef15 sta15 maxsta15 d3500
    
Benachrichtung für Wablu mit dem IV Wert 0/10-15/15.

::

    /track karpador weight13130 d3500
    
Benachrichtigung für XL Karpador.

::

    /track rattfratz maxweight2410 d3500
    
Benachrichtigung für XS Rattfratz.

::

    /track wadribie female d3500
    
Benachrichtigung für weibliche Wadribie. Alternativ "male".

::

    /track everything iv100 d3500
    
Benachrichtigung für alle Pokemon mit 100% IV.

::

    /track gen5 d3500
    
Benachrichtigung für alle Generation 5 Pokemon.
    

Untrack
=======

::

    /untrack kaumalat
    
Entfernt alle Kaumat Benachrichtigungen.

::

    /untrack everything
    
Entfernt alle Pokemon Benachrichtigungen. Je nach Umfang der Liste muss dieser Befehl manchmal 2x verwendet werden um sie komplett zu leeren.

Tracked
=======

::

    /tracked
    
Gibt euch euren Standort und aktiviertes Gebiet zurück sowie eine Liste aller aktiven Track-Befehle. Lange Track-Listen werden auf einer Webseite hochgeladen da sie nicht in eine Nachricht passen. Es kommt vor, dass diese Webseite nicht zur Verfügung steht. Der Bot wird euch dies mitteilen. Versucht es zu einem späteren Zeitpunkt nochmal.

Raid und Quest
""""""""""""""

Raid
====

::

    /raid darkrai d3500

Benachrichtigung für Darkrai Raids.

::

    /raid level5 d3500
    
Benachrichtigung für alle 5er Raids.

::

    /raid everything d3500
    
Benachrichtigung für alle Raids.

::

    /raid gen5 d3500
    
Benachrichtigung für alle Raids mit Generation 5 Pokemon.

Raid remove
===========

::

    /raid remove darkrai
    
Benachrichtigung für Darkrai Raids entfernen.

::

    /raid remove everything
    
Benachrichtigung für alle Raids entfernen.

Egg
===

::

    /egg level5 d3500
    
Benachrichtigung für alle 5er Raideier.

::

    /egg everything
    
Benachrichtigung für alle Raideier.

Egg remove
==========

::

    /egg remove level5
    
Benachrichtigung für Level 5 Raideier entfernen.

::

    /egg remove everything
    
Benachrichtigung für alle Raideier entfernen.

Quest
=====

::

    /quest pandir stardust d3500
    
Benachrichtigung für Quest mit Pandir oder Sternenstaub als Belohnung.

::

    /quest all pokemon d3500
    
Benachrichtigung für alle Quests mit Pokemon als Belohnung.

::

    /quest all items d3500
    
Benachrichtigung für alle Quests mit Items als Belohnung.

Quest remove
============

::

    /quest remove everything
    
Benachrichtigung für alle Quests entfernen.

|

