# Prototipoaren Muntaia

Hasteko, prototipoaren oinarria eraikitzeko 54x54cm-ko egurrezko konglomeratuzko xafla pisutxu bat sortu da 165mm-ko lodierako bi elkarren gainean lotuz. Oinarri honen lau eskinetara goiko oinarria eutsiko duten lau hagaxka hariztatuak lotu dira. Beheko oinarriaren erdian diseinuan aurkezten den U itxurako egitura finkatu da, baina hau egiteko egurrezko xaflak erabili ordez 1.5mm-ko lodierako altzairuzko xafla mehe bat erabili da. Neurri egokiak izateko horrelako xaflak tolesteko makina bat bat erabili da eta tirafondo batzuen bidez lotu da oinarrira. Egitura honen barnean kokatuko da zirkuitu elektrikoa eta sorgailu bezala erabiliko dugun DC-ko motorra, azken hau hiru egurrezko xaflekin eta metalezko eskuadra batzuekin egin den tripode itxurako egitura baten bidez eutsia. Sorgailuaren ardatza eta errotorea konektatu ahal izateko altzairuzko xaflaren erdian 20mm-ko diametroko zuloa egin da.

Goiko oinarrirako {numref}`Prototipo3_1` irudian kolore urdinez azaltzen den egituraren antzeko bat sortu da altzairua erabiliz. Horretarako 6mm-ko lodierako altzairuzko hegaxka batzuk elkarrekin soldatu dira gurutze formako egitura osatuz eta zentroan errodamendu bat sartzeko 20mm-ko diametroko zuloa egin zaio. Gainera, errotorea marko moduan eraiki den egiturara lortzeko 3D inprimagailu bidez sorturiko ondorengo piezak erabili dira:

::::{grid}
:gutter: 0

:::{grid-item}
```{figure} ./Irudiak/GoraEuskarri.png
---
height: 150px
name: GoraEuskarri
---
Errotorearen goiko euskarria.
```
:::
:::{grid-item}
```{figure} ./Irudiak/BeraEuskarri.png
---
height: 150px
name: BeraEuskarri
---
Errotorearen beheko euskarria.
```
:::
:::{grid-item}
```{figure} ./Irudiak/RotorEuskarria.png
---
height: 150px
name: RotorEuskarri
---
Errotorea oinarrira finkatzen duen pieza.
```
:::
::::

{numref}`RotorEuskarri` irudian ikusi dezakegun pieza oinarrian jarri dugun U itxurako egituraren gainean eta zentroan kokatuko da eta bere egitekoa *61804ZZ* errodamendua finkatzea izango da. Errodamendu honen dimentsioak 20mm-ko barne-diametroa, 32mm-ko kanpo-diametroa eta 7mm-ko lodiera dira. Noski, errodamenduaren zuloa, oinarriaren zuloa eta pieza honen zuloa zehaztasun osoz bat etortzea ziurtatu da, errotorearen ardatza jartzean marruskadura minimoa izan dadin.

{numref}`BeraEuskarri` irudian aurkezten zaigu errotorea eta sorgailua lotzeko erabiliko den pieza. Honen ardatzaren kanpo-diametroa bat dator aurretik aipatu den zuloarekin, 20mm-ko diametroa baitu. Aldiz, barne diametroa 8mm-koa da eta honen barnean sartuko da sorgailutik ateratzen den ardatza. Azkenik, biak lotzeko 20mm-ko luzerako torloju bat erabili da pasadore moduan.

Azkenik, {numref}`GoraEuskarri` irudian errotorean goiko aldetik ardatz bat ateratzeko erabili den pieza erakusten da. Bestalde, goiko oinarrian jarri den errodamendua *699ZZ* motakoa da eta bere dimentsioak 9mm-ko barne-diametroa, 20mm-ko kanpo-diametroa eta 6mm-ko lodiera dira. Kanpo-diametroa eta lodiera goiko oinarri moduan erabili den gurutzearekin bat etortzen dira eta, errotorearen goiko ardatzaren diametroa 9mm-koa denez, barne-diametroa ere egiturarekin bat etorriko da.

Bestalde, errotorea eraikitzeko {numref}`GoraEuskarri` eta {numref}`BeraEuskarri` irudietako piezei 300mm-ko diametroko bi plataforma atxikiko zaizkie. Plataforma hauek egurrezko konglomeratuzko 6mm-ko lodiera duen xafla mehe batez eginak daude. Bi hauen artean eraikiko dira {ref}`EDiseinua` atalean aurkeztutako errotoreak. Aipatu beharra dago hauen hegoak edo palak 3D inprimagailu bidez sortu direla, baina, hego bakoitzaren altuera totala metro erdikoa izatea nahi zenez eta honek inprimagailuaren mugak gainditzen zituenez, pala bakoitza 125mm-ko altuerako lau piezetan inprimatu dela eta, ondoren, elkarri pegatu direla.

```{figure} ./Irudiak/PrototipoFinala.jpg
---
height: 400px
name: PrototipoFinala
---
Eraikuntza prozesuaren amaieran lortutako prototipoa, {ref}`EDiseinua1` erdibituta muntatuta dagoelarik.
```


# Zati Elektronikoa

Elektronikaren aldetik, prototipoak datuak lortu eta terminal batera bidaltzeko bi plaka base desberdin erabiliko dira, [Arduino UNO R3](https://docs.arduino.cc/hardware/uno-rev3/) eta [NodeMCU v3 ESP8266](https://www.nodemcu.com/index_en.html). Bi plaka hauen artean serie konexioa ezarri da datuak elkartrukatzeko.

::::{grid}
:gutter: 0

:::{grid-item}
```{figure} ./Irudiak/ArduinoUNO.jpeg
---
height: 250px
name: ArduinoUNO
---
*Arduino UNO R3* plaka basea.
```
:::
:::{grid-item}
```{figure} ./Irudiak/NodeMCU.jpg
---
height: 250px
name: NodeMCU
---
*ESP8266* txipa barne duen *NodeMCU v3* plaka basea.
```
:::
::::

Biak batera erabiltzeko arrazoi nagusia elkarren osagarriak direla da. Arduino UNO mota honetako plaka sinpleena da eta tentsioak neurtzeko behar ditugun 2 pin analogikoak izateko aukera ematen digu. Aldiz, NodeMCU-ak bakarrik pin analogiko bakarra dauka, baina ESP8266 txiparen bitartez WiFi bidezko konexioa izateko aukera ematen digu. Konexio honen bidez lortutako datuak automatikoki [ThingSpeak](https://thingspeak.com/) orrira bidaltzen ditu eta horrela edozein momentutan eta edonon gure errotorea sortzen ari den tentsioa ikusteko aukera daukagu. Hala ere, orri honek soilik 15 segunduro jaso dezake informazioa eta, beraz, nahiz eta sorgailu eolikoaren portaera denboran zehar nolakoa den jakiteko egokia izan, jarduera esperimentaleko behaketak egiteko neurketa tarte hau handiegia da. Arazo hau konpontzeko, Arduino UNO plaka zuzenean lotuko da ordenagailu batekin eta datuak behatzeko [Putty](https://www.putty.org/) programa erabiliko da.

## Arduino IDE Bidezko Programa