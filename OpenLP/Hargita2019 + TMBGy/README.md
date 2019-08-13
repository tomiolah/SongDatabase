# HARGITA 2019 & Tordai Magyar Baptista Gyülekezet

Ezen mappa tartalmazza a 2019-es hargitai ifihéten használt vetítési adatbázist, és a Tordai Magyar Baptista Gyülekezet adatbázisát (külön köszönet érte 🙂), OpenLP-kompatibilis formátumban.

A `./Songs` mappában található az összes ének az adatbázisból, XML-alapú, OpenLyrics formátumban (az OpenLP által használt formátum, a programból exportálva) - betöltésük menete (magyar nyelvű OpenLP-ben):

Fájl > Importálás > Dal (ez megnyit egy ablakot - ebben kell folytatni)
  - Következő
  - Formátum (legördülő lista): `OpenLyrics vagy OpenLP 2 exportált dal`
  - Fájlok hozzáadása (új ablak)
    - Navigáljunk a `./Songs` mappába
    - `Ctrl + A`
    - Open / Megnyitás
  - Következő
  - Várjuk meg, amíg betöltődnek az adatok
  - Befejezés

Az aktuális mappában (`.`) található még egy `settings.conf` fájl is - első ránézésre TOML szintaxisnak nézhet ki, de nem az. Ezt ne nagyon módosítsuk kézileg, mert ha hibásan importáljuk, akkor az elronthatja a teljes OpenLP-telepítésünket. Ellenben, ha helyes a konfigurációs fájl (alaphelyzetben biztosan az), akkor ezt importálni lehet a programban, a **Fájl > Importálás > Beállítások** menüpontban. Ezt majd a grafikus felületről lehet módosítani is. 🙂

A mappa továbbá tartalmaz egy előre konfigurált témát (`Worship.otz`), illetve egy egyszerű hátteret (`worship.jpg`) is - a témában lehetséges, hogy módosítani kell majd a háttérkép elérési útvonalát.