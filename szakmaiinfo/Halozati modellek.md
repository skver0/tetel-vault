# Hálozati modellek
---
- a hálózati modelleket a hardver- és szoftver elemek együttesen határozzák meg
- legjelentősebb modellek
	- kliens-szerver
	- host-terminál
	- peer-to-peer
---
### Kliens-szerver modell
- másnéven ügyfél-kiszolgáló modell
- két számítógépes program közötti kapcsolat
	- egyik program valamilyen szolgáltatást kér a másiktól, amely eleget tesz a kérésnek
	- szolgáltatás kérő az a kliens
	- szolgáltatás nyújtó az a szerver
- olyan hálózati környezetben jelentős, ahol a programok egymástól fizikailag is távol illetve különböző számítógépeken futnak
- ha egy böngészőt tekinttünk kliensprogramnak, amely szolgáltatásokat kér egy másik számítógépen futó web-szervertől, az internet kliens-szerver kapcsolatról beszélünk
---
### Host-terminál modell
- másnéven vendéglátó-terminál modell
- általában telefonvonalon keresztül összeköttetésben lévő két számítógép közötti kapcsolat
- az elérhető adatokat tároló számítógép a host
- információ lekérő számítógép a terminál
---
### Peer-to-Peer modell
- lényege hogy a hálózatot egyenrangú gépek alkotják
	- mindenki szerver és munkaállomás egyszerre
- az adatok több helyen tárolhatók
---
### OSI modell rétegei
- 7 rétege van
	1. fizikai
	2. adatkapcsolati
	3. hálózati
	4. szállítási (átviteli)
	5. viszony (együttműködési)
	6. megjelenítési
	7. alkalmazási