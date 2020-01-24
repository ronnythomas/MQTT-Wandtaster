# Mqtt Wandtaster für 55iger Rahmen

## Funktionen
- 6 Toutch Taster mit ja 3 verschiedenen Belegungen (18 verschiedene aktionen möglich)<br />
- je Toutch Taster eine RGB LED als Status<br />
- Vibra als Rückmeldung<br />
- eine RGB LED als Nacht oder Status Licht/Anzeige<br />
- Lichsensor<br />
- Temparatur / Feuche / Luftdruck Messung<br />

## Anbindung
- Mittels ESP8266 und ESPEasy können Daten z.b.per MQTT aus IoBrocker enfangen bzw. gesendet werden<br />
- Übertragung mittels Wifi<br />

## Stromversorgung<br />
- 8-25V DC oder 5V DC max.500mA<br />


## Bauteilliste komplett (Vorschlag)


| Pos      | Wert      | Bauform  | Bemerkung | Link |
| ---      | ---       | ---      | ---       | --- |
| D1       | 1N5819    |SOD-123   |           | [Link](https://de.farnell.com/diodes-inc/1n5819hw-7-f/gleichr-diode-schottky-1a-40v/dp/1773475?st=1N5819)
| D2       |	1N4001	 |	SOD-123 || [Link](https://de.farnell.com/taiwan-semiconductor/ll4001g/gleichrichter-1fach-1a-50-do-213aa/dp/2677336?st=LL4001)
| D3       |	1N5819	 |	SOD-123 | |[Link](https://de.farnell.com/diodes-inc/1n5819hw-7-f/gleichr-diode-schottky-1a-40v/dp/1773475?st=1N5819)
| C1       |	100nF	 |	0805  || [Link](https://de.farnell.com/avx/08051c104jat2a/kondensator-0-1-f-100v-5-x7r-0805/dp/2332715RL?st=100nF)
| C2       | 	10pF |		0805 | |[Link](https://de.farnell.com/kemet/c0805c100j5gactu/kondensator-10pf-50v-5-c0g-np0/dp/1414654?st=10pF)
|C3 |	100nF	|	0805 | | [Link](https://de.farnell.com/avx/08051c104jat2a/kondensator-0-1-f-100v-5-x7r-0805/dp/2332715RL?st=100nF)
|C4 |	10pF	 |	0805  | | [Link](https://de.farnell.com/kemet/c0805c100j5gactu/kondensator-10pf-50v-5-c0g-np0/dp/1414654?st=10pF)
|C5 |	10µF |		3216	 |	Tantalum Case A	 | [Link](https://de.farnell.com/kemet/t491a106k010ah/cap-tantalum-10uf-10v-case-a/dp/2676308) 
|C6 |	10pF	 |	0805  | | [Link](https://de.farnell.com/kemet/c0805c100j5gactu/kondensator-10pf-50v-5-c0g-np0/dp/1414654?st=10pF)
|C7 |	100nF |		0805  | | [Link](https://de.farnell.com/avx/08051c104jat2a/kondensator-0-1-f-100v-5-x7r-0805/dp/2332715RL?st=100nF)
|C8 |	100nF |		0805  | | [Link](https://de.farnell.com/avx/08051c104jat2a/kondensator-0-1-f-100v-5-x7r-0805/dp/2332715RL?st=100nF)
|C9 |	100nF |		0805  | | [Link](https://de.farnell.com/avx/08051c104jat2a/kondensator-0-1-f-100v-5-x7r-0805/dp/2332715RL?st=100nF)
|C10 |	100nF |		0805  | | [Link](https://de.farnell.com/avx/08051c104jat2a/kondensator-0-1-f-100v-5-x7r-0805/dp/2332715RL?st=100nF)
|C11 |	10pF |		0805  | | [Link](https://de.farnell.com/kemet/c0805c100j5gactu/kondensator-10pf-50v-5-c0g-np0/dp/1414654?st=10pF)
|C12 |	10pF |		0805  | | [Link](https://de.farnell.com/kemet/c0805c100j5gactu/kondensator-10pf-50v-5-c0g-np0/dp/1414654?st=10pF)
|C13 |	100nF |		0805  | | [Link](https://de.farnell.com/avx/08051c104jat2a/kondensator-0-1-f-100v-5-x7r-0805/dp/2332715RL?st=100nF)
|C14 |	10pF |		0805  | | [Link](https://de.farnell.com/kemet/c0805c100j5gactu/kondensator-10pf-50v-5-c0g-np0/dp/1414654?st=10pF)
|C15 |	100nF |		0805  | | [Link](https://de.farnell.com/avx/08051c104jat2a/kondensator-0-1-f-100v-5-x7r-0805/dp/2332715RL?st=100nF)
|C16 |	100nF	 |	0805  | | [Link](https://de.farnell.com/avx/08051c104jat2a/kondensator-0-1-f-100v-5-x7r-0805/dp/2332715RL?st=100nF)
|C17 |	10µF |		0805  | | [Link](https://de.farnell.com/avx/08053d106kat2a/kondensator-10-f-25v-10-x5r-0805/dp/1867958?st=10uf)
|C18 |	100pF	 |	0805  | | [Link](https://de.farnell.com/kemet/c0805c101j5gactu/kondensator-100pf-50v-5-c0g-np0/dp/1414656)
|C19 |	100µF	 |	3216	 |	Tantalum Case A  | [Link](https://de.farnell.com/kemet/t490a107m006ate800/kondensator-100-f-6-3v-20/dp/2688578?st=100%C2%B5F%203216)	
|C20 |	2.2µF 35V |	3216	 |	Tantalum Case A	  | [Link](https://de.farnell.com/vishay/tmcma1v225mtrf/kondensator-2-2-f-35v-20/dp/2491481)
|IC1 |	MC34063AD |	SOIC_8  |  | [Link](https://de.farnell.com/texas-instruments/mc34063ad/dc-dc-conv-buck-boost-inv-soic/dp/3007277?st=MC34063AD)
|IC2 |	TTP226	  |	SSOP-28	 |	TTP226-809SN 
|IC3 |	PCF8574T |	 SOIC-16_300mil  | 	PCF8574T/3,518  | [Link](https://de.farnell.com/nxp/pcf8574t-3-518/i-o-expander-8bit-8574-soic16/dp/1690393?st=PCF8574T/3,518)
|IC4 |	AMS1117-3.3 |	SOT-223  |  | [Link](https://de.farnell.com/on-semiconductor/ncp1117lpst33t3g/ldo-festspann-regler-3-3v-1a-sot/dp/2534283?st=NCP%201117)
|IC5 |	BME280	 |	LGA-8	 |	Heißluft nötig  | [Link](https://de.aliexpress.com/item/32950649541.html?spm=a2g0o.productlist.0.0.24a9298dzNO7gx&algo_pvid=48ae5f04-3659-4387-89c6-9dec3e903c76&algo_expid=48ae5f04-3659-4387-89c6-9dec3e903c76-23&btsid=ecb0f2d2-d1e5-4da8-9c8e-fb1363599ed2&ws_ab_test=searchweb0_0,searchweb201602_10,searchweb201603_55)
|IC6 |	BH1750FVI-TR |	WSOF-6I	 |	Lichtsensor  | [Link](https://de.farnell.com/rohm/bh1750fvi-tr/ambient-light-sensor-i2c-wsof/dp/2421284?ost=BH1750FVI-TR&ddkey=https%3Ade-DE%2FElement14_Germany%2Fsearch)
|IC7 |	ESP-12-F |	| | [Link](https://de.aliexpress.com/item/32633529267.html?spm=a2g0o.productlist.0.0.48a75762cpdhzn&algo_pvid=09d1558a-14d3-4b56-a71a-56b98706861d&algo_expid=09d1558a-14d3-4b56-a71a-56b98706861d-7&btsid=520697cc-a1af-4345-8cb6-de547c3f2113&ws_ab_test=searchweb0_0,searchweb201602_10,searchweb201603_55) 
|L1 |	22µH	 |	SMD,6x6x3mm  |min 500mA  | [Link](https://de.farnell.com/tdk/slf6045t-220m1r1-3pf/induktivit-t-22uh-1-8a-20-drahtgew/dp/2520685?st=SLF6045T-220M1R1-3PF)
|LED1 |	WS2812C	 |	5050  | | [Link](https://de.farnell.com/kingbright/kaaf-5050rgbs-13/led-smd-rgb-1400mcd-1400-420/dp/2335791?ost=WS2812&iscrfnonsku=true&ddkey=https%3Ade-DE%2FElement14_Germany%2Fsearch)
|LED2 |	WS2812C	 |	5050  | | [Link](https://de.farnell.com/kingbright/kaaf-5050rgbs-13/led-smd-rgb-1400mcd-1400-420/dp/2335791?ost=WS2812&iscrfnonsku=true&ddkey=https%3Ade-DE%2FElement14_Germany%2Fsearch)
|LED3 |	WS2812C	 |	5050  | | [Link](https://de.farnell.com/kingbright/kaaf-5050rgbs-13/led-smd-rgb-1400mcd-1400-420/dp/2335791?ost=WS2812&iscrfnonsku=true&ddkey=https%3Ade-DE%2FElement14_Germany%2Fsearch)
|LED4 |	WS2812C	 |	5050  | | [Link](https://de.farnell.com/kingbright/kaaf-5050rgbs-13/led-smd-rgb-1400mcd-1400-420/dp/2335791?ost=WS2812&iscrfnonsku=true&ddkey=https%3Ade-DE%2FElement14_Germany%2Fsearch)
|LED5 |	WS2812C	 |	5050  | | [Link](https://de.farnell.com/kingbright/kaaf-5050rgbs-13/led-smd-rgb-1400mcd-1400-420/dp/2335791?ost=WS2812&iscrfnonsku=true&ddkey=https%3Ade-DE%2FElement14_Germany%2Fsearch)
|LED6 |	WS2812C	 |	5050  | | [Link](https://de.farnell.com/kingbright/kaaf-5050rgbs-13/led-smd-rgb-1400mcd-1400-420/dp/2335791?ost=WS2812&iscrfnonsku=true&ddkey=https%3Ade-DE%2FElement14_Germany%2Fsearch)
|LED7 |	WS2812C	 |	5050  | | [Link](https://de.farnell.com/kingbright/kaaf-5050rgbs-13/led-smd-rgb-1400mcd-1400-420/dp/2335791?ost=WS2812&iscrfnonsku=true&ddkey=https%3Ade-DE%2FElement14_Germany%2Fsearch)
|R1 |	3k	 |	0805	 |	1/8W | [Link](https://de.farnell.com/vishay/crcw08053k00fkea/dickschichtwiderstand-3k-1-0-125w/dp/1469908?st=3k%200805)
|R2 |	1k	 |	0805	 |	1/8W | [Link](https://de.farnell.com/tt-electronics-welwyn/wcr0805-1k0fi/dickschichtwiderstand-1k-1-0-125w/dp/2422082?st=1k%200805)
|R3 |	0,3	 |	0805	 |	1/8W  | [Link](https://de.farnell.com/bourns/crl0805-fw-r300elf/dickschichtwiderstand-0r3-1-0/dp/2008298?st=0.3%20ohm%200805)
|R4 |	1k	 |	0805	 |	1/8W | [Link](https://de.farnell.com/panasonic/erj6enf1001v/dickschichtwiderstand-1k-1-0-125w/dp/2303550?st=1k%200805)
|R5 |	1K	 |	0805	 |	1/8W | [Link](https://de.farnell.com/panasonic/erj6enf1001v/dickschichtwiderstand-1k-1-0-125w/dp/2303550?st=1k%200805)
|R6 |	4k7	 |	0805	 |	1/8W  | [Link](https://de.farnell.com/vishay/crcw08054k70fkea/dickschichtwiderstand-4k7-1-0/dp/1469923)
|Vibra  | | | 3V  | [Link](https://de.aliexpress.com/item/32664414295.html?spm=a2g0o.productlist.0.0.663719b5eaxpAb&algo_pvid=2b26df5c-cf5e-46b2-b3b7-cf34572e0421&algo_expid=2b26df5c-cf5e-46b2-b3b7-cf34572e0421-11&btsid=d8b92c4b-5c7e-4afd-bff9-2a57968d0697&ws_ab_test=searchweb0_0,searchweb201602_10,searchweb201603_55)
|DS18B20 |	 | |				Temp Messung  | [Link](https://de.aliexpress.com/item/32224580172.html?spm=a2g0o.productlist.0.0.2a039dc6wd4MvK&algo_pvid=2ad521e6-5fa1-4473-a525-fa6cdadbe045&algo_expid=2ad521e6-5fa1-4473-a525-fa6cdadbe045-1&btsid=eccfa8c1-4a33-47a6-8f80-3325d400e8ff&ws_ab_test=searchweb0_0,searchweb201602_10,searchweb201603_55)
|Anschlussklemme | | |		AST 02 3,5 (Reichelt)  | [Link](https://de.farnell.com/weidmuller/1825640000/reihenklemme-wire-to-board-2pos/dp/2853040?st=klemme)

- Alles Links ohne Garantie!!!

* für Netzteil wird benötigt (nur bei 8-25V) <br />
IC1
C20
C18
L1
D1
R1
R2
R3


* für Toutch wird benötigt<br />
IC3
IC2
C2
C4
C6
C11
C12
C14

* für LEDs wird benötigt<br />
LED1
LED2
LED3
LED4
LED5
LED6
LED7
C15
C13
C10
C7
C3
C1
D2

* für lichtsensor wird benötigt<br />
IC6
R4
R5
C16

* Temaraturmessung DS18B20<br />
R6
ein oder mehrfach DS18B20

* Temaratur / Feuchte / Luftdruck<br />
IC5
C8<br />
Achtung! Es wird nicht die Raumtemp gemessen sonder die Gerätetemp!!

* Vibra<br />
D3<br />
Vibra 3V

////Sollte eine oder mehrere Funktionen nicht benötigt werden können die Bauteile weggelassen werden!////


[Kontakt via Facebook](https://www.facebook.com/ronny.thomas.83)

[Kontakt via Homematic Forum](https://homematic-forum.de/forum/memberlist.php?mode=viewprofile&u=13127)

## Platine wird in Weiß und mit Vergoldeten Kontakten ausgeliefert!!! 

![complete](Images/1.jpg)
![complete](Images/2.jpg)
![complete](Images/3.jpg)
![complete](Images/4.jpg)




