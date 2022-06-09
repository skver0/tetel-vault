# Hálózati címek
### IPv cím fajták
- Ipv4 és mostani modernebb Ipv6
---
### IPv4 címek
- A hálózaton a számítógépeket egy egyedi cím, az IP cím azonosítja.
- Minden gépnek van legalább egy címe, de egy gépnek több címe is lehet (pl. minden szolgáltatásának egy-egy), illetve egyes címekhez több gép is tartozhat (céges hálózat), valamint egy gépnek lehet mindig másik címe (dinamikus IP).
- Minden gépnek van legalább egy címe, de egy gépnek több címe is lehet (pl. minden szolgáltatásának egy-egy), illetve egyes címekhez több gép is tartozhat (céges hálózat), valamint egy gépnek lehet mindig másik címe (dinamikus IP).
- Minden gépnek van legalább egy címe, de egy gépnek több címe is lehet (pl. minden szolgáltatásának egy-egy), illetve egyes címekhez több gép is tartozhat (céges hálózat), valamint egy gépnek lehet mindig másik címe (dinamikus IP). Ezért is jött az IPv6
---
### Címosztályok
Minden hálózatban az első cím, a hálózat címe, a legutolsó pedig szórási cím, ezeket nem lehet kiosztani egy eszköznek sem.
- A osztály: Az első 8 bitet használjuk a hálózat azonosítására, a maradék 24-et a hálózaton belüli hostok azonosítására. Az A osztály címtartománya így 1.0.0.0-tól 127.255.255.255-ig terjed.
- B osztály: itt az első 16 bit a hálózat címe, és a maradék 16 pedig a hálózaton belüli állomások címe. A B osztály tartománya 128.0.0.0-tól egészen 191.255.255.255-ig terjed.
- C osztály: ebben az osztályban az első 24 bitet használják a hálózat azonosítására, és a maradék 8-at az egyes hostok jelölésére. Az osztály címtartománya 192.0.0.0-tól 223.255.255.255-ig tart.
- D osztály: ezek az úgynevezett többes küldéses (multicast) címek, melyeknek speciális alakjuk van. A címtartomány 224.0.0.0-től 239.255.255.255-ig tart.
- E osztály: ez a tartomány speciális, jövőbeli felhasználásra szánt címek halmaza. Az elérhető tartomány 240.0.0.0-tól 255.255.255.255-ig tart.
---
### IPv4 és IPv6 különbségei 
- Az IPv6 128 bit-es címet használ a megszokott 32 bites IPv4-es címek helyett.
- Lényeges, hogy megszüntek különböző méretű hálózatokon alapuló tartományok (A, B és C tartományok).
- Az IPv6-tal sok lehetőség nyílt mint pl. a hitelesítés, ezzel a biztonság is nőtt.
- Az IPv6 megőrzi az IPv4 és protokoll alaptulajdonságait, alapelv, hogy az IP-címeket nem gépekhez, hanem halózati interfacekhez rendelik.
- Egy interfacenek viszont több címe is lehet, és ezt az új szolgáltatások ki is használják.
- Az új címeket a hozzárendelés elve szerint három alapvető csoportba oszthatjuk:
	- egycélú (unicast)
	- választható célú (anycast)
	- több célú (multicast)
---
### IPv6 címstruktúra
- Az új 128 bites címeket 8 darab 16 bites csoportra osztjuk, melyeket hexadecimális formában, egymástól kettősponttal elválasztva írjuk.
- Az IPv6-ban unicast, multicast és anycast címek vannak
- Az unicast cím egy állomás egy interface-ét jelöli, a multicast és anycast címek számos interfaceket jelölnek (többnyire különböző állomásokon)
- a multi és anycast-nél a feladott csomag mindegyik interface-re meg fog érkezni,  a unicast-nál pedig csak az egyik interface-re
- Az anycast címek szintaktikailag megkülönböztethetetlenek az unicast címektől, ez úgy működik, hogy egyszerre több állomásnak is kiosztjuk ugyanazt a címet, erről mindegyik állomásnak tudnia kell, ezeket aztán a router-ek terjeszteni fogják.
- Az anycast címek szintaktikailag megkülönböztethetetlenek az unicast címektől, ez úgy működik, hogy egyszerre több állomásnak is kiosztjuk ugyanazt a címet, erről mindegyik állomásnak tudnia kell, ezeket aztán a router-ek terjeszteni fogják.
- A következő előre definiált multicast címek léteznek:
	1.  Minden állomás (az állomáson belül: FF01::1, a link-en FF02::1)
	2. Minden router (az állomáson belül FF01::2, a link-en FF02::2)
	3. Minden DHCP server vagy ügynök (FF02::C a link-en)
	4. Megszólított állomás multicast cím (FF02::1:xxxx:xxxx)
	- A 0::0, vagy csak :: cím jelzi cím hiányát.
	- A 0::0, vagy csak :: cím jelzi cím hiányát.
---

