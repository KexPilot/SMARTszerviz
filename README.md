# SMART szervíz
_Készítette: Haász Menno, Juhász Imre, Novodonszki Zsolt_


## Elméleti működés a szoftver mögött
A SMART szervíz programunk fő célja az autó szervízelési folyamatok megkönnyítése és felhasználó által könnyen követhetővé tétele. Lehetővé teszi hogy az ügyfél egy kihelyezett terminál segítségével elvégezze a megfelelő adminisztrációkat, amiben regisztrál, bejelenti a jármű hibáját vagy szervízelés típusát, majd átadja járművét a szervíznek. A bemeneti paraméterek alapján egy költségbecslést is kaphat. Még nem létező hiba vagy szervízelési kategória esetén az egyéb kategóriában leírást adva egy szakember moderálhatja a megadott leírást, majd a leírás és vizsgálat alapján elhelyezheti a rekordot egy kategóriában, vagy ha a kategória tényleg nem létezik, létrehozhatja azt, ezzel bővítve a rendszert. 

Az adminisztráció elvégeztével egy garázsajtó kinyílik ahova a járművet, kulcsot és hozzá tartozó okmányokat eltárolja az ügyfél. 

Következő lépésben a szerelő átveszi a járművet és a rendszerbe felvitt adatok kiolvassa. A jármű átvizsgálása után a rendszerben felviheti a jármű pontos hibáit, ezzel információt eltárolva a szervízelés megkönnyítéséhez és az ügyfél informálásához. Ugyanekkor a szükséges és felhasznált alkatrészeket regisztrálhatja, hiány esetén megrendelve azokat, amiről az ügyfél szintúgy tájékoztatást kap, hogy az ügyfél tudja, hogy hosszabb időt vesz igénybe a javítás. Leszerződött árubeszerzőtől az általa megadott (és módosítható) árért lehet megrendeléseket tenni. Ha a beszerző nem rendelkezik ilyen alkatrészekkel, a szoftverrel lehet kérni árajánlatot alkatrészekre, melyre a beszerző akár több opciót és hozzá tartozó árat is megadhat. A beszerző a szervízhez kihelyezett elektronikus csomagszekrényt felhasználva akár a szervíz zárva tartási idejében is leadhat alkatrészeket a megrendeléshez járó kóddal. A tipikus fogyóeszközök (olaj, csavarok, gyertyák, stb.) folyamatos feltöltése a szerződött árubeszerző feladata. A javítás végeztével készre állítja a munkát amit a megrendelőnek SMS-ben jelez.

## Szereplők és eszközeik
### Ügyfél
* Regisztráció a rendszerbe
* Szervízelés kérése és kategória/hibák megadása
* Csereautó igénylése
* Javítás státuszának lekérése
* Számla lekérése
### Szerelő
* Munka átvétele
* Alkatrész felhasználása
* Alkatrész rendelése
* Ügyfél kapcsolattartási adatainak lekérése
* Munka leadása
### Árubeszerző
* Megrendelések lekérdezése
* Megrendelés elfogadása
* Fogyóeszközök számontartása
* Árajánlat adása
* Ár módosítása
