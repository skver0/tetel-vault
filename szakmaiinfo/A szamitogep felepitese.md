# A számítógép felépítése
---
#neumann-elvek, #neumann-principle 

##### A számítógépek a Neumann elveken alapul
1. A számítógép legyen soros működésű
2. A számítógép a kettes számrendszert használja
3. A számítógép legyen teljesen elektronikus
4. A számítógépnek legyen belső memóriája
5. A számítógép legyen univerzális
6. A tárolt program elve
	- A programot alkotó utasítások kifejezhetők számokkal, azaz adatként kezelhető.
---
### Számítógép részei
- hardver: a számítógép alkotó fizikai elemek összessége
- szoftver: a számítógépen lévő programok, adatok és azok dokumentációja.

### Főbb részei
- processzor (CPU)
	- a számítógép központi vezérlő egysége
	- ez hajtja végre minden utasításunkat
	- főbb részei
		- vezérlőegység
			- irányítja a müveleteket
		- regiszterek
			- műveletek elvégzéséhez szükséges adatokat tárolják
		- aritmetikai és logikai egység (ALU)
			- matematikai valamint logikai műveletek végrehajtása
- alaplap
	- megszabja
		- processzor jellegét
			- sebességét
		- bötvíthető kártyák számát
			- fajtáját
		- felhasználható memória jellegét
		- az adott gép által kezelhető maximális memória méretet
		- a számítógépházat
		- tápegységet
	- méretét általában ATX (régebbi nevén AT) szabvány szerint alakítják ki
	- a számítógép legfontosabb illetve legterjedelmesebb, a processzort kiszolgáló része a gépnek
	- rajta található
		- processzor foglalat
		- memória helyek
		- sínredszerek (buszok)
		- bővítőkártyák csatlakozói
		- BIOS ROM
		- CMOS RAM
		- akkumulátor
		- órajel generátor
		- külső csatlakozók lehetnek
			- usb
			- ps2
			- integrált hangkártya esetén 3.5mm-es jackek
			- integrált grafikus kártya esetén
				- VGA
				- D-SUB
				- DVI
				- HDMI
			- integrált hálókártya esetén, RJ45 szabványú de akármilyen sebességű UTP csatlakozó
- memória
	- tárolja 
		- a cpu által végrehajtandó programokat
		- feldolgozásra váró adatokat
	- memória elemek rendeltetés szerint két fő csoportra bonthatók
		- RAM (Random Access Memory)
			- tetszőleges hozzáférésű, a processzor által írható-olvasható
			- operatív tár
				- nagy kapacitású de lassú
				- tartalmazza a háttértárolókról és a beviteli perifériákról beolvasott programokat és adatokat
			- cache
				- gyorsítótár
				- kis kapacitású és gyors
				- rövid elérési idő alatt tud biztosítani a processzor számára szükséges adatokat
		- ROM (Read-Only Memory)
			- csak olvasható memória
			- BIOS
				- bekapcsolás után lefutó tesztprogramot és az alapvető hardverkezelő rutinokat tartalmazó, alaplapon elhelyezett memória, a setupot is ez tartalmazza
	- külön kategóriába tartoznak a hordozható gépekben esetleg kéziszámítógépekben (PDA-kban) használt flash-memóriák
- tápegység
	- árramforrás
	- feladatai
		- stabil feszültség előállítása
		- figyeli az általa előállított feszültséget
		- esetleg saját áramköreinek hőmérséklete alapján vezérelheti a hűtő ventilátorokat