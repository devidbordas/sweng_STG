Help rendszer
==============
A weboldalon ahonnan letölthető lesz a játék lesz egy help fül amelyen a játékosok különböző témákban kereshetnek választ a kérdésükre. Különböző topicok lesznek. 

Első topic a letöltéssel és telepítéssel lenne kapcsolatos. Itt segítséget találnának a felhasználók, hogy hogyan működik a letöltés, hogyan kell telepíteni a játékot. Segítséget nyújtunk különböző ábrákkal és a lehető legrészletesebben írjuk le mit hogyan kell, így aki még sosem csinált ilyet az is könnyedén el tudja majd végezni ezeket a feladatokat. 

Lesz egy topic amely a menüben való navigációban fog segíteni a játékosoknak. Lefogjuk írni, hogy a különböző menüpontokon belül mi található majd. 
* Play: Itt lehet elindítani a játékot, ezen a menüponton belül lehet választani, hogy solo vagy multiplayer módban szeretnénk megmérettetni magunkat. A solo-n belül még választhatunk, hogy a gép ellen szeretnénk játszani vagy esetleg ott ül mellettünk egy barátunk/családtagunk aki ellen akarunk játszani a lokális multiplayer mód által.
* Options: Lesz egy lehetőség(Invert up asis) mellyel megfordíthatjuk a célzás irányát, ezt úgy kell érteni hogyha például balra húzzuk az egeret a célzókereszt jobbra fog elmozdulni a játékban, a fényerősséget lehet majd állítani, az egér mozgásának érzékenységét(look sensitivity).
* Credits: itt a játék rövid stáblistája érhető el.
* Quit: ezzel a menüponttal lehet bezárni az alkalmazást.

Egy topic lesz azoknak is akik a multiplayer játékmód működésére kíváncsiak. Itt segítséget nyújtunk, hogy hogyan lehet Tcoint szerezni, feljebb kerülni a virtuális ranglétrán.

A játékkal való gondokra is gondolunk, a felhasználók megtalálják majd a megoldások sorát ha esetleg akadozna, lefagyna a játék bár ezeket megpróbáljuk a lehető leghatékonyabban kiküszöbölni.

A játékon belüli tartalmakra is lesz egy topic ahol a játékosok megismerhetik a különböző tankokat, lövedékeket, különleges képességeket.

Valamint kérdéseket is tehetnek fel a felhasználók ha valami speciális dolog érdekli őket.

![help_use-case](https://user-images.githubusercontent.com/79118853/144461555-52a82049-336c-4012-842e-18f0d0999880.png)

Felhasználó(Actor)
-----------
Olyan személy, aki megnyitja a játék weboldalát és segítséget keres.

Admin(Actor)
------------
A weboldal karbantartója.

Help rendszer(Use-Case)
-----------------------
Itt találnak a játékosok segítséget ha kérdésük merül fel a játékkal kapcsolatban.
*Prekondíciók: A játékosnak problémája akad a játékkal kapcsolatban
*Postkondíciók: A játékos problémája megoldódik
*Szokásos működés(Main Flow): Probléma megoldás
*Alternatív esetek(Alternative Flows): A játékos nem találja a választ a kérdésére
*Kivételes esetek: Internet probléma

Kérdées feltétele(Use-Case)
-----------------------
A játékost kérdést tehet fel ha nem találja a megoldást a problémájára.
*Prekondíciók: A játékos nem találja a választ a kérdésére
*Postkondíciók: Az admin megválaszolja neki
*Szokásos működés(Main Flow): Probléma megoldás
*Alternatív esetek(Alternative Flows): A játékosnak nem megfelelő az admin válasza sem
*Kivételes esetek: Internet probléma

Kérdés megválaszolása(Use-Case)
-----------------------
Az admin megválaszolja a kérdéseket amiket feltettek a játékosok
*Prekondíciók: Az admin válaszol a játékosnak
*Postkondíciók: A játékos megkapja a kérdésre a válaszát
*Szokásos működés(Main Flow): Probléma megoldás
*Alternatív esetek(Alternative Flows): A játékos feltesz még egy kérdést ha esetleg nem érthető még valamo
*Kivételes esetek: Internet probléma
