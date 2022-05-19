# Operációs rendszerek
---

Olyan szoftver ami kulcsfontosságú egy számítógép működtetéséhez, bekapcsolástól kikapcsolásig fut. Egy kezelőfelületet szólgál a felhasználó részére ami biztosítja a géppel valo kapcsolatot.

Egy számítógép az operációs rendszert bekapcsoláskor a BIOS indítja el, az elérhető adattárolókon keres egy BOOT jelzővel rendelkező adattárolót.

---
### Operációs rendszerek feladatai

- gép hardverének kezelése és működtetése
	- minden egyes hardver elemhez szolgáltatási felületet kell biztosítson, ezekhez vannak a driverek vagy másnéven a vezérlő programok, amik a hardver működtetéséhez ad adatot a rendszernek.
- alkalmazások indítása és futtatása
	- ki kell szolgálja az alkalmazásokat a rendszer
- feldolgozás, ütemezés, erőforrások megosztása
	- erőforrások elosztása igazságosan alkalmazások számára
	- idő osztásos technika
		- egyszerre több feladatot tud elvégezni a processzor (multi-tasking)
- adatok kezelése, átvétele (memória kezelés)
- tevékenység megjelenítése
	- felhasználói felületen működik
	- minden tevékenységet, illetve minden olyan tevékenységet amit meg akart tenni a számítógép mutatnia kell
- adatok biztonságos tárolása
- állomány operációk lehetővé tétele
- működési zavarok jelzése és kezelése
	- akár háttértár sérülés, hibás program
	- fel kell készüljön a rendszer hogy hiba esetén nem volna szabad lefagynia
- hálózatok kezelése
---
### Operációs rendszer csoportosítási szempontjai

- felhasználói felület alapján
	- szöveges
		- felhasználó által begépelt parancs megjelenik egy felületen, illetve az adott parancsra a rendszer válasza
		- ha egy parancs programot indít el akkor csak annak a programnak a felhasználói felülete jelenhet meg, bezárás esetén vissza kell térjen az operációs rendszer felülete
		- régebbi operációs rendszerekre ez igaz is (DOS, UNIX)
		- új operációs rendszerekben is van lehetőség elérni ezt az üzemmódot (pl.: GNU + Linux)
	- grafikus
		- pl. Windows
		- képernyő grafikus módban van
		- több beviteli eszköz használható
			- egér, billentyűzet
		- legtöbbször egy nyíl alakú jelenik meg amivel rá lehet vinni a képernyőn található objektumokra és valamelyik egér kattintásával lehet parancsot kiadni a rendszernek
		- előnye hogy könnyebb használni viszon a nagyobb a programkód és a memória használata miatt lasabb mint egy szöveges felület
- felhasználók száma alapján
	- lényege hogy képes-e a rendszer az operációs rendszer megkülönböztetni két felhasználót egymástól
	- singleuser (egyfelhasználós)
		- csak egy felhasználó létezik
		- egy azonosító van a rendszerbe
		- pl.: DOS, Win9x
	- multiuser (többfelhasználós)
		- több felhasználó létezik
		- több azonosító van a rendszerbe
			- azonosító mellé van egy jelszó, ezzel azonosítja magát a felhasználó
			- egyéni beállítások elérése
			- többi felhasználótól elrejtett adatokat tárolhat
			- kommunikálhat a gépen keresztül a többi felhasználóval
		- pl.: Windows NT, GNU + Linux