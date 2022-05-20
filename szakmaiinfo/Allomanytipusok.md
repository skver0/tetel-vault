# Állománytípusok
---
Az állomány a számítógép háttértárolóin lévő információ tárolási egysége. A fájlban tárolt adat tetszőleges. Lehet szöveg, kép, hang. 
A fájl valamelyik háttértárolón tárolt, névvel és kiterjesztéssel azonosított adategyüttes-
A fáljrendszer az operációs rendszer telepítésekor, meglévő kötetek formázásakor, vagy új merevlemezes telepítésekor választható ki.

---
### Fájlrendszerek
- FAT
	- egyszerű, robosztus
	- MS-DOShoz lett fejlesztve
- FAT32
	- FAT továbbfejlesztése
- exFAT
	- FAT legújabb verziója
- NFTS
	- Windows NT és utódjainak szabvány fájlrendszere
	- jogosultsági rendszer
	- működés közbeni állománytömöríté
- EXT
	- legújabb: ext4
	- Linux szabvány fájlrendszer
---
Szempont | Tulajdonság
------------ | ------------
Fájlnév:|legalább 1, max 255 betű, szóköz és ékezet megengedett
Fáljkiterjesztés:| nem kötelező megadni
‎|végrehajtó fájlok: .exe, .bat, .com
‎|szövegfájlok: .txt, .docx
‎|adatfájlok: .dat, .xlsx
‎|képfájl: .bmp, .gif, .png
‎|tömörített fájlok: .zip, .rar
‎|hangfáljok: .waw, .ogg, .mp3
‎|videó fájlok: .avi, .mov
Fáljméret:|a fájl mérete bájtban (kB, MB)
Dátum|a fájl létrehozásának vagy utolsó módosításának dátuma
idő|a fájl létrehozásának vagy utolsó módosításának ideje
Fájl attribútumok:|archiv fájl (A)
‎|csak olvasható fájl (R)
‎|rejtett fájl (H)
‎|az operációs rendszerhez tartozó fájl (S)
___
Ha a fájl NFTS fájlrendszert használó meghajtón található, további biztonsági beállításokat is elvégezhetünk:
	- lehetőségünk van engedélyek kiadásáras
	- automatikus ki és betömörítés
	- titkosítás
	- indexelés
