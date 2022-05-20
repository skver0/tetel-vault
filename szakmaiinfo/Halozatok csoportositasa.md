# Hálózati topológiák
---
- első számítógép hálózatok kiépítésének célja az volt, hogy a távolságokat áthidalja
	- egy gépre több terminállal akartak csatlakozni
- egy-egy terminál a központi géptől akár több ezer km távolságban is lehettek
- emiatt lehet a napjainkban például külföldi adatokat elérni
- manapság nem a távolság a cél hanem az erőforrások elosztása, összekapcsolása és a kommunikáció

- topológia
	- a hálózati állomások különböző elrendezése, illetve összekapcsolása
---
### Topológiák
- teljesen összekapcsolt hálózat
	- minden számítógép minden számítógéppel össze van kötve
	- elönye hogy hiba esetén is működőképes a hálózat, nagy sebességel lehet információt közölni
	- hátránya hogy drága és nehéz bővíteni
- csillag topológia
	- munkaállomások külön-külön kábelen csatlakoznak az állomány szerverhez
	- hiba esetén csak egy állomás válik üzemképtelenné
	- drága és nehéz bővíteni
	- kommunikáció csak is a főszámítógépen keresztül történhet meg
- gyűrű topológia
	- az információ körbe jár
	- munkaállomások csak nekik szoló parancsot hajtják végre
		- ami nem nekik szól azt továbbítják a következő állomáshoz
- fa topológia
	- olcsó
	- hiba eseteén a hálózatok független alhálózatokra esnek szét
	- az állomány kiszolgálóhoz közelebbi adat-utak nagyobb hálózatterhelés esetekor könnyen túlterhelődhetnek
		- rendszer válaszidők megnövekedhetnek
- tisza fa topológiát elenyésző mennyiségben alkalmaznak, inkább kombináltan más topológiával
- a hálózati meghibásodás tekintetében egyre fontosabbak az elemek a piramis csúcsa felé

- manapság a hálózatok típusának egy nagyobb csoportja a LAN-ok (helyi hálózatok, Local Area Network)
- ezekutáni érdeklődés elsősorban a felismerés adja, hogy az intézmények ma már egyre nagyobb részét képezik olyan feldolgozások, amelyeket korlátozott hatáskörzeten belül kell elvégezni és ennek során központi adatbázishoz több munkahelyről kell majdnem egyidőben hozzáférni