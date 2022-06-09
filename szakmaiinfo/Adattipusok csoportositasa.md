# Adattípusok csoportosítása
### Pirimív adattipusok 
egyszerű értékeket képesek tárolni mint pl. számok, karakterek, logikai értékek
- byte - 8 bit 
- short - rövid egész, 16 bit
- int - egész, 32 bit 
- long - hosszú egész, 64 bit
- float - egyszeres pontosságú lebegőpontos, 32 bit
- double - dupla pontosságú, 64 bit
- char - 16 bit, Unicode karakter
- boolean - Logikai, igaz vagy hamis értéket tárol
---
### Összetett adattípusok
Az összetett adattípusnál az értékhalmaz mellett a szerkezet is lényeges, egyik-másik típus ábrázolása már magasabb szintet igényel, mert elég bonyolult.
- sorozat / vektor / egydimenziós tömb
	- értékhalmaza azonos típusú adatok összegsége pl. int tömb
	- müveletek az elemeire vonatkozóan, alaptípussal megegyezően lehet, pl. egy elem kiválasztása: azonosító[index], azaz a tömb/sorozat/vektor indexedik eleme
-  mátrix / többdimenziós tömb
	- értékhalmaza itt is azonos típusú adatok összesége
	- itt is ugyan az van csak elem kiválasztása pl. azonosito [index1,...,indexN]
- rekord / struktúra
	- értékhalmaza különböző típusú lehet, de logikailag összetartozónak kell lennie
	- müveletek közé tartozik az értékatád, relációs műveletetk, elem kiválasztás pl: azonosito.adatazonosito
- szöveg (karaktersorozat)
	- karaktertípusú adatok tömbje / sorozata
	- müveletei közé tartozik az összefűzés, karakterek vizsgálata, elem/karakterek kiválasztás pl. azonositó[index] 
---