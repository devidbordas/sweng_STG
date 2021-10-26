**8. Tervezési korlátozások**


A mai világ elég rohanó tud lenni. Sokszor az embernek szüksége van pihenésre és a 21. században rohamosan népszerűsödik a videójátékokkal való aktív kikapcsolódás.
Az emberek régóta játszanak, hogy mindennapjaikat színesebbé és érdekesebbé tegyék. Az aktív kikapcsolódás ezen formája sokszor tanulással is jár. 
Ilyen például rengeteg játék esetében:

- Idege nyelv elsajátítása
- Reakció képesség fejlesztése
- Reakció idő

Amióta létezik számítógép, a számítógépes játékok is léteznek. Kezdetben nyilván elég egyszerű játékok voltak, de az akkori időkben ezek is áttörő erőjűek voltak az emberek számára. 
Azonban a kor és természetesen az informatika fejlődésével (elsősorban a hardver és perifériás eszközök iszonyatos nagy mértékű fejlesztése) lehetőség nyíl olyan szintű játékok megvalósításár is amelyek már már műalkotásnak számítanak.

A játékfejlesztés napjainkban kezd komolyabb iparággá válni(ha nem nagyobb már) mint a filmipar. 
Egy egy játék óriási költségvetéssel rendelkezik és akár több száza is dolgoznak rajta, mint pélául:

- Fejlesztők
- Tesztelők
- Grafikusok
- Szinkronok

**Java**

A mi játékunk esetében a fő programozási nyelv a java. Ugyan elég korlátozottak a lehetőségek azonban a mi játékunk elkészítéséhez talán a legmegfelelőbb választás. Mivel objektum orientált programról van szó nem állhat csupán egyetlen pogramból.
Ebben fog nekünk segíteni a java sajátossága ugyanis egy főosztályt kell készítenünk és ehhez kapcsolódó al és segédosztályok segítségével fogjuk tudni elérni a kívánt célt.

Főosztályunk lehet egyszerűen csak main.java ugyanakkor az egyes al és segédosztályokat célszerű elnevezni. A program érthetősége, követhetősége és munkánk megkönnyítése érdekében különböző változók és konstansok bevezetése ajánlott. 
Erre azért is van szükség mert a későbbi hivatkozások esetében egyértelműen meg tudjuk majd állapítani, hogy milyen változók milyen értékeket tárolnak és mivel ezek a definíciók az osztály elején vannak, ezeket a program készítése közben könnyen megváltoztathatjuk.
Erre azért van szükség, mert a program készítése közben könnyen előfordulhat, hogy egyes méreteket például meg kell majd változtatnunk. Az irányokhoz, a menüpontokhoz, valamint a játék főbb „helyszíneihez&quot; azért rendelünk szimplán számokat, hogy azokkal később könnyedén tudjunk műveleteket elvégezni.

Fejlesztő eszközök

**Grafikus motor:** A grafikos motor fog nekünk segíteni a játékban látottak „lerenderelésért&quot;. Mivel nem egy nagy gépigényű játékot szeretnénk készíteni így nem kell nagyon erős és nagy teljesítményű motort használnunk.
Saját grafikus motor írásra sincs szükségünk tekintettel a fent említettekre, ugyanis nagyon drága és hosszadalmas egy ilyen elkészítése ezért elég egy kész meglévő és egyszerű otor használata.

**Hálózati motor:** Mivel multiplayer játékot készítünk így a hálózati motor elengedhetetlen számunkra. Ez felel a hálózati kapcsolatért és az adatok cseréjéért. 
Például amikor egy másik játékos lő minket, akkor azokat az adatokat az ő számítógépének ki kell bocsájtani, a mi számítógépünknek pedig fogadnia kell azt.

**Audio motor:** A játékunk egyszerű hangokat fog használni, de mivel használ ezért audió motorra is szükségünk van.

**Script nyelv:** Ez már a fent említett és bővebben kidolgozott Java leírja. Fontos hogy a script nyelvet implementálni kell a játék motorjába.
