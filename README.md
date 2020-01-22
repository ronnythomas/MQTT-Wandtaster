# Mqtt Wandtaster für 55iger Rahmen

## Funktionen
-6 Toutch Taster mit ja 3 verschiedenen Belegungen (18 verschiedene aktionen möglich)
-je Toutch Taster eine RGB LED als Status
-Vibra als Rückmeldung
-eine RGB LED als Nacht oder Status Licht/Anzeige
-Lichsensor
-Temparatur / Feuche / Luftdruck Messung

##Anbindung
-Mittels ESP8266 und ESPEasy können Daten aus z.b. IoBrocker enfangen bzw. gesendet werden
-Übertragung mittels Wifi

##Stromversorgung
8-25V DC oder 5V DC max.500mA


##Bauteilliste komplett


<th>Pos</th>	Wert		Bauform		Bemerkung		

D1	1N5819		SOD-123 <br />
D2	1N4001		SOD-123 <br />
D3	1N5819		SOD-123 <br />
C1	100nF		0805 <br />
C2	10pF		0805 <br />
C3	100nF		0805 <br />
C4	10pF		0805 <br />
C5	10µF		3216		Tantalum Case A	 <br />
C6	10pF		0805 <br />
C7	100nF		0805 <br />
C8	100nF		0805 <br />
C9	100nF		0805 <br />
C10	100nF		0805 <br />
C11	10pF		0805 <br />
C12	10pF		0805 <br />
C13	100nF		0805 <br />
C14	10pF		0805 <br />
C15	100nF		0805 <br />
C16	100nF		0805 <br />
C17	10µF		0805 <br />
C18	100pF		0805 <br />
C19	100µF		0805		Tantalum Case A <br />	
C20	22µF 35V	0805		Tantalum Case A	 <br />
IC1	MC34063AD	SOIC_8 <br />
IC2	TTP226	 	SSOP-28		TTP226-809SN <br />
IC3	PCF8574T	SOIC-16 <br />
IC4	AMS1117-3.3	SOT-223 <br />
IC5	BME280		LGA-8		Heißluft nötig <br />
IC6	BH1750FVI-TR	WSOF-6I		Lichtsensor <br />
IC7	ESP-12-F	 <br />
L1	22µH		SMD,6x6x3mm <br />
LED1	WS2812C		5050 <br />
LED2	WS2812C		5050 <br />
LED3	WS2812C		5050 <br />
LED4	WS2812C		5050 <br />
LED5	WS2812C		5050 <br />
LED6	WS2812C		5050 <br />
LED7	WS2812C		5050 <br />
R1	3k		0805		1/8W <br />
R2	1k		0805		1/8W <br />
R3	0,3		0805		1/8W <br />
R4	1k		0805		1/8W <br />
R5	1K		0805		1/8W <br />
R6	4k7		0805		1/8W <br />
Vibra <br />
DS18B20					Temp Messung <br />
Anschlussklemme		AST 02 3,5 (Reichelt) <br />


* für Toutch wir benötigt
IC3
IC2
C2
C4
C6
C11
C12
C14

* für LEDs wird benötigt
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

* für lichtsensor wird benötigt
IC6
R4
R5
C16

* Temaraturmessung DS18B20
R6
ein oder mehrfach DS18B20

* Temaratur / Feuchte / Lüftdruck
IC5
C8
Achtung! Es wird nicht die Raumtemp gemessen sonder die Gerätetemp!!

* Vibra
D3
Vibra 3V

////Sollte eine oder mehrere Funktionen nicht benötigt werden können die Bauteile weggelassen werden!////


[Kontakt via Facebook](https://www.facebook.com/ronny.thomas.83)

[Kontakt via Homematic Forum](https://homematic-forum.de/forum/memberlist.php?mode=viewprofile&u=13127)



![complete](Images/1.jpg)
![complete](Images/2.jpg)
![complete](Images/3.jpg)
![complete](Images/4.jpg)




