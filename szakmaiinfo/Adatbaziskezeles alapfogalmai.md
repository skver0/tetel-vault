# Adatbáziskezelés alapfogalmai
---
### Fogalmak
- információ
	- jelsorozat a hozzá kapcsolódó jelentéssel együtt
- adat
	- az információ hozdozója, a tények, fogalmak, számítsái feldolgozásra alkalmas reprezentációja
- séma
	- másnéven schema
	- felhasználói séma
		- közös tulajdonoshoz tartozó objektumok névvel ellátott együttese
		- alapesetben minden felhasználóhoz rendelődik egy séma, melynek megegyezik a felhasználó nevével
	- szerkezeti séma
		- az adatbázis elemek, objektumok szerkezetének leírása
- adatbázis
	- másnéven database
	- integrált adatszerkezet mely több különböző objektum előfordulási adatiat adatmodell szerint szervezetten perzisztens módon tárolja olyan segédinformációkkal úgynevezett metaadatokkal együtt hatékonyság, integritásőrzés, adatvédelem bíztosítását szolgálják
- Adatbázis kezelő rendszer
	- másnéven database management system
	- Programrendszer, melynek feladata az adatbázishoz történő hozzáférések biztosítása és az adatbázis belső karbantartási funkcióinak a végrehajtása
- adatbázisrendszer
	- másnéven database system
	- az adatbázis adatbázis-kezelő és az alkalmazások együtteséből álló információs rendszer
---
### Előnyei a adatbázis kezelő rendszereknek
- felhasználóknak nem kell ismernie a konkrét adattárolási módot
- nagymennyiségű adatot gyorsan lehet kezelni
- védelmi funkciókat is betölt (másolatok, naplózás)
- többfelhasználó egy időben (konkurens hozzáférés)
- integritási szabályok transzparens ellenőrzése
- hatékony program fejlesztés
---
### Ne használjunk adatbázis kezelő rendszert
- az adatszerkezet annyira egyszerű, hogy erőforrás pazarlás lenne
- ha real-time hozzáférés szükséges
- ha egy felhasználó kezeli csak az adatokat egy időben, mert a rendszer le tudja ellenőrizni az integritási feltételeit