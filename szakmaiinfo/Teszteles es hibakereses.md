# Tesztelés és hibakeresés
### A teszt meghatározása
- szoftverfejlesztésben a tesztelés a programkód tesztelését jelent. Önmagában a tesztelés nem elegendő egy minőségi munkához, viszont ahoz elengedhetetlen. A célja a egy rendszer hibáinak, vagy hiánnyoságainak feltárása.
---
### A tesztelés típusai
- pozitív tesztelés: lényege hogy megerősítse, hogy a kifeljesztett termék a szándékoknak megfelelően működik-e.
- negativ tesztelés: lényege hogy biztosítsa a termék megbízhatóságát, biztonságát még akkor is ha váratlan inputokat illesztenek a termékbe.
---
### A Tesztelés szükségességei:
- Műszaki eset: ha nehéz megjósólni a rendszer viselkedését az összetevőiből, ezek a hibák eszközi meghibásodásokhoz vezethetnek.
- Üzleti eset: ha a hibákat nem a fejlesztési szakaszban veszik észre, hanem amikormár az ügyfelek használják a terméket. Ami kellemetlen, és ronthatja a hírnevét a cégnek. 
- Szakmai eset: ha a termék megtervezése nehéz, és kihivást jelent
---
### A hibakeresés meghatározása
- A tesztelés és hibakeresés ciklikus módon működik, ahol a tesztelés megállapítja a hibát, a hibakeresés meg kiküszöböli azt. Ebből adódóan a hibakeresés nem tesztelés, hanem a tesztelés eredményeként kialakuló, kereső tevékenység. 
- két eset van a hibakeresésnél: amikor a hiba okát azonosítják, javitják, vagy eltávoltják, és amikor az okot nem találják meg és nem is orvosolják.
---
### A hibakeresés lépései
1. hibák meghatározása
2. hibajelentés tervezése, és ábrázolása
3. hiba elemzés
4. hiba megoldásának tervezése
5. hiba javitása 
6. újabb tesztelés
---
### Következtetés
- A tesztelés és hibakeresés két különböző tevékenység. A hibakeresés a hibák eltávolítása a kódból, miközben a tesztelés csak a fel nem fedezett hibák felkutatása.
---
### Hibakeresésnél a debugger használata
- Ha kézzel kell hibakeresni, akkor debuggert szokás használni, amivel a programokat bizonyos pontokon le lehet állítani, ami megkönnyíti és fegyorsítja a hibakeresési folyamatot.