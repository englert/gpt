# Pong – feladatsor Python Turtle használatához

**Célcsoport:** 12. évfolyam  
**Kiindulás:** a `pong.py` működő programja  
**Munkamódszer:** minden módosítás után indítsd el a játékot, és ellenőrizd a változtatást.

## 1. Ismerkedés a kóddal

1. Indítsd el a játékot a `python3 pong.py` paranccsal.
2. Próbáld ki mindkét ütő irányítását.
3. Keresd meg, hol állítjuk be az ablak méretét és háttérszínét.
4. Keresd meg, hol tároljuk a két játékos pontszámát.
5. Magyarázd el, mire szolgál a `make_paddle()`, a `draw_score()` és az `update_game()` függvény.
6. Rajzold fel, milyen sorrendben történik egy képkocka frissítése az `update_game()` függvényben.

## 2. Könnyű módosítások

1. Változtasd meg az ablak méretét 1000 × 700 képpontra.
2. Állítsd át a háttérszínt sötétkékre.
3. Változtasd meg a pontszám színét.
4. Módosítsd a `WINNING_SCORE` értékét 10-re.
5. Állítsd át az ütők méretét. Figyeld meg a `shapesize()` paramétereit.
6. Módosítsd a labda kezdeti sebességét a `BALL_STEP` változóval.

## 3. Mozgás és ütközések

1. Növeld vagy csökkentsd az ütők lépésközét. Melyik értéknél könnyű, illetve nehéz irányítani?
2. Keresd meg a felső és alsó falról történő visszapattanás feltételét. Magyarázd el, miért változik meg a `ball.dy` előjele.
3. Módosítsd az ütőkkel való ütközés feltételét úgy, hogy a labda csak az ütő középső részét találhassa el.
4. Vizsgáld meg, hogyan befolyásolja a labda irányát az, hogy az ütő melyik részét találja el.
5. Próbáld meg elérni, hogy a labda sebessége minden ütőtalálat után növekedjen. Figyeld meg, mikor válik túl gyorssá.

## 4. Pontozás és játékmenet

1. Módosítsd a játékot úgy, hogy 3 ponttal is lehessen nyerni.
2. Jelenítsd meg a képernyő közepén a „Kezdődik a játék!” feliratot, majd töröld, amikor elindul a játék.
3. Gól után várjon a program egy rövid ideig, mielőtt a labda újra elindul.
4. Készíts olyan megoldást, amely kiírja, hogy melyik játékos szerezte az utolsó pontot.
5. Adj hozzá egy billentyűt, amellyel a játék szüneteltethető és folytatható.

## 5. Függvények és programstruktúra

1. Magyarázd el, miért függvény a `make_paddle()`, és miért ad vissza egy Turtle objektumot.
2. Készíts `reset_paddles()` nevű függvényt az ütők kezdőhelyzetbe állítására, és használd fel az új játék indításakor.
3. Készíts `reset_scores()` nevű függvényt a pontszámok nullázására.
4. Keress minden olyan helyet, ahol a program a `score_left` vagy `score_right` értékét módosítja.
5. Gondold át, hogyan lehetne a globális változók számát csökkenteni.

## 6. Önálló fejlesztési feladatok

Válassz legalább egyet!

- **Nehézségi szintek:** legyen lassú, normál és gyors játékmód.
- **Egyszemélyes mód:** a jobb oldali ütőt a program mozgassa automatikusan.
- **Legjobb eredmény:** tárold a játékosok eddigi legmagasabb pontszámát a futás idejére.
- **Színes labda:** a labda színe minden ütőtalálatkor változzon meg.
- **Hangjelzés:** ütközéskor vagy gólnál szólaljon meg egy hang, ha a használt rendszer ezt támogatja.
- **Kezdőképernyő:** a játék induljon egy rövid menüből.
- **Szabályválasztás:** lehessen kiválasztani, hogy 5, 7 vagy 10 pontig tartson a mérkőzés.

## 7. Hibakeresés

1. Mi történik, ha a labda túl gyorsan mozog? Milyen módosítással lehet stabilabbá tenni a játékot?
2. Miért fontos a labda irányát is vizsgálni az ütővel való ütközésnél?
3. Próbálj ki szélsőséges értékeket a sebességre és az ütő méretére. Jegyezd fel a tapasztalataidat.
4. Készíts egy hibajegyzéket: írd le a jelenséget, a feltételezett okot és a javítást.

## 8. A ChatGPT és a GitHub használata

1. Kérd meg a ChatGPT-t, hogy magyarázza el a `pong.py` egyik függvényét.
2. Kérj tőle egyetlen, jól körülhatárolt fejlesztést.
3. Mielőtt elfogadod a módosítást, olvasd át a kódot, és próbáld meg saját szavaiddal elmagyarázni.
4. Futtasd a programot, és ellenőrizd, hogy a módosítás működik-e.
5. A GitHubon ellenőrizd a változtatásokat és a commit üzenetét.
6. Írj rövid beszámolót arról, melyik részt készítetted önállóan, miben segített a ChatGPT, és hogyan ellenőrizted az eredményt.

## Beadandó

- A módosított `pong.py` program.
- Legalább három megoldott feladat.
- Rövid leírás a változtatásokról.
- Egy képernyőkép a működő játékról.

**Fontos:** ne csak másold a kódot. Minden módosításnál tudd elmagyarázni, mit csinál, és ellenőrizd futtatással.
