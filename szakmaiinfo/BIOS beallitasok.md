# BIOS beállítások
---
### A BIOS feladata
- olyan programok gyűjteménye, amely tartalmazza a programozható perifériák kezdeti inicializálását és alacsony szintű kezelését
- egy BIOS csak azon az alaplapon használható, amelyikre készült, mert teljes mértékben hardver specifikus
- az operációs rendszerek "gépfüggetlenek", a BIOS végzi el a szabványos szoftverilletszéseket
---
### A BIOS fajtái
- rendszer BIOS
	- az alaplapon található
	- csak olvasható típusú memória
		- kezdetben ROM, EPROM
		- később Flash
- video BIOS
	- a videókártyán helyezkedik el
	- minden EGA, illetve fejletteb videókártya rendelkezik egy kártya függő BIOS kiegészítéssel
		- biztosítja a vezérlőáramkörök sajátos képességeinek kezelését és illesztését a rendszerhez
- leggyakoribb gyártó cégek
	- AMI
	- AWARD
	- PHOENIX
---
### A BIOS funkcionális részei
- POST
	- power on self test (bekapcsoláski önteszt)
	- a számítógép bekapcsolásakor az alapvető hardveregységek működőképességét ellenőrzik
	- egyes egységek működését indítják
- BIOS Setup
	- lehetővé teszi a felhasználó számára a CMOS-RAM-ban tárolt konfigurációs paraméterek megtekintését, módosítását
	- csak a bekapcsolás követően, POST lezajlása után lehet belépni