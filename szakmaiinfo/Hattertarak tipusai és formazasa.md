# Háttértárak és formázása
---
Olyan elektronikus eszköz, amely képes adatok tárolására, visszakereséésére és feldolgozására. Az adatok a számítógép kikapcsolása után is megmaradnak.

- jellemzők
	- tárolási kapacitás
	- elérési idő
	- adatátviteli sebesség
- csoportosítás
	1. elektronikus
		-  csak olvasható memória (ROM)
			- nem törölhető 
			- nem módosítható
			- gyárilag rárakott
		- véletlen elérésű olvasható és írható memória (RAM)
			- számítógép kikapcsaloásával elveszíti a tartalmát
	2. papír alapú
		- lyukkártya
		- lyukszalag 
	3. mágneses
		- mágnes szalagok, lemezek
			- biztonságos tárolás
		- mágneses lemezek
			- hajlékony lemez
			- merevlemez
		- merevlemez
			- légmentesen lezárt 
			- egy tengelyen több fémlemez
	4. optikai
		- az optikai tárak optikai elven működnekj
			- lézerfényt használnak
			- a működési felületre eső fénynyaláb visszaverődik vagy szétszóródik
		- CD-fajtái
			- CD-ROM
				- csak olvasható
			- CD-R
				- csak egy írható lemez
			- CD-RW
				- újraírható lemez
			- max kapacitás: 700 MB
		- DVD
			- CD továbbfejlesztett változata
				- kapacitása: 4.7 GB, 8.5 GB
			- fajtái
				- DVD-R
					- egyszer írható
				- DVD-RW
					- újraírható
---
### Formázás
Formázás közben jönnek az adatok tárolására szükséges rétegek, ekkor jönnek létre a sávok és a szektorok. A formázást egy bizonyos partícióra hajtjuk végre. Formázáskor az adott partíción lévő fájlok törlődnek.

---
### Felépítése
A merevlemezben elhelyezkedő lemezek sávokra, a sávok pedig szektorokra vannak beosztva. A merevlemezek nem egy szektort, hanem egyszerre többet kezelnek. A több egységből álló szektort klaszternek nevezzük.
Az adatok lemezre írásakor azz író-olvasó fejbe áramot vezetnek attól függően, hogy a jel egyes vagy nulla. Ez az áramimpulzus az író-olcasó fejben mágneses teret gerjeszt. A mágneses tér megmágnesezi a kör alakú lemez egy adott pontjhát. Az adatok beolvasásakor az író-olvasó fej repül a mágneses lemezfelület felett. Ha a lemez egy mágneses pontja a fej alá kerül, akkor a fejben a mágneses tér miatt egy pillanatra áram keletkezik. Ez az áram erősebb vagy gyengébb így a jel egyes vagy nulla lesz.  