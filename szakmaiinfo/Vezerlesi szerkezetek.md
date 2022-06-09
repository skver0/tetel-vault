# Vezérlési szerkezetek
### Fajtái
- While - elöltesztelő - Elöszőr kiértékeli a feltételt amely művelet egy boolean értéket ad vissza, amennyiben ez egy igaz érték, a végrehajtó blokkban lévő utasítások ismétlődően lefutnak amíg nem vált át hamisra a feltétel.
- Do-While - hátultesztelős ciklus - A feltételt a ciklus végrehajtása után értékeli ki, tehát egyszer biztosan lefog futni a végrahjtó blokkban lévő utasítások
- For - számláló ciklus - szintaxis: for (inicializálás, feltétel, növekmény) {utasítások}
	- inicializálás - kezdőérték
	- feltétel - meghatározza meddig kell futnia a ciklusnak 
	- növekmény - mennyivel nő ciklusonként az inicializált számláló, a feltétel felé
- kibővitett for / Foreach - tömb bejárós - szintaxis: for (elemtipus elem : tároló) {utasítás blokk} 
	- elemtípus  - pl int, vagy string
	- elem - neve az elemnek, ez bármi lehet
	- táróló - a táróló tömb azonosítója, ami pl tömb, vagy lista
	- nem minden esetben jó, mivel nem lehet tömbindexhez hozzájutni
- If - feltételes -  ha a feltétel boolean értéke igaz akkor lefut egyszer, egyébként meg nem - szintaxis: if (feltétel) {utasítás blokk}
- If-else - feltételes - ugyan az mint az if csak itt le lehet kezelni hogy mi történjen ha nem igaz a feltétel, az else ágban - szintaxis: if (feltétel) {utasítás blokk} else {alternativ utasítás blokk}
- Switch-case 
	- egy egész szám értéke alapján akarunk végrehajtani utasításokat
	- kiértékeli a kifejezést és lefuttatja a megfelelő case utasítást
	- minden case értéknek egyedinek kell lennie, és a vizsgált értékek csak konstansok lehetnek
	- minden case értéknek egyedinek kell lennie, és a vizsgált értékek csak konstansok lehetnek
	- Break utasítás megszakítja az épp bezáródó switch utasítást, és a vezérlés szála a switch-blokk utáni első utasításhoz kerül
	- Break utasítás megszakítja az épp bezáródó switch utasítást, és a vezérlés szála a switch-blokk utáni első utasításhoz kerül
	- Szintaxis: 
		switch ( int ) {
		case 1: utasítások; break;
		case 2: utasítások; break;
		default: utasítások; break; }
---
### Kivételkezelés
- hiba esetén, a program dob egy kivételt, és megpróbál találni egy kivételkezelő-blokkot, ami a hibát le tudja kezelni
- kivételkezelő-blokk megkíséreli a hiba kijavítását, vagy ha a hiba visszaállíthatatlan, akkor kilép a programból
- kivételkezelő utasítások: 
	- try - utasítás amit mindig megfog próbálni még a program futása közben, ha gond van
	- catch - utasítás akkor fog lefutni ha a try-ban gond van
	- finally - utasítás akkor is lefut ha nem volt, vagy volt kivétel
---