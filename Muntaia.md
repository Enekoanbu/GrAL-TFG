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

{numref}`RotorEuskarri` irudian ikusi dezakegun pieza oinarrian jarri dugun U itxurako egituraren gainean eta zentroan kokatuko da eta bere egitekoa **61804ZZ** errodamendua finkatzea izango da. Errodamendu honen dimentsioak 20mm-ko barne-diametroa, 32mm-ko kanpo-diametroa eta 7mm-ko lodiera dira. Noski, errodamenduaren zuloa, oinarriaren zuloa eta pieza honen zuloa zehaztasun osoz bat etortzea ziurtatu da, errotorearen ardatza jartzean marruskadura minimoa izan dadin.

{numref}`BeraEuskarri` irudian aurkezten zaigu errotorea eta sorgailua lotzeko erabiliko den pieza. Honen ardatzaren kanpo-diametroa bat dator aurretik aipatu den zuloarekin, 20mm-ko diametroa baitu. Aldiz, barne diametroa 8mm-koa da eta honen barnean sartuko da sorgailutik ateratzen den ardatza. Azkenik, biak lotzeko 20mm-ko luzerako torloju bat erabili da pasadore moduan.

Azkenik, {numref}`GoraEuskarri` irudian errotorean goiko aldetik ardatz bat ateratzeko erabili den pieza erakusten da. Bestalde, goiko oinarrian jarri den errodamendua **699ZZ** motakoa da eta bere dimentsioak 9mm-ko barne-diametroa, 20mm-ko kanpo-diametroa eta 6mm-ko lodiera dira. Kanpo-diametroa eta lodiera goiko oinarri moduan erabili den gurutzearekin bat etortzen dira eta, errotorearen goiko ardatzaren diametroa 9mm-koa denez, barne-diametroa ere egiturarekin bat etorriko da.

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
**Arduino UNO R3** plaka basea.
```
:::
:::{grid-item}
```{figure} ./Irudiak/NodeMCU.jpg
---
height: 250px
name: NodeMCU
---
**ESP8266** txipa barne duen **NodeMCU v3** plaka basea.
```
:::
::::

Biak batera erabiltzeko arrazoi nagusia elkarren osagarriak direla da. Arduino UNO mota honetako plaka sinpleena da eta tentsioak neurtzeko behar ditugun 2 pin analogikoak izateko aukera ematen digu. Aldiz, NodeMCU-ak bakarrik pin analogiko bakarra dauka, baina ESP8266 txiparen bitartez WiFi bidezko konexioa izateko aukera ematen digu. Konexio honen bidez lortutako datuak automatikoki [ThingSpeak](https://thingspeak.com/) orrira bidaltzen ditu eta horrela edozein momentutan eta edonon gure errotorea sortzen ari den tentsioa ikusteko aukera daukagu. Hala ere, orri honek soilik 15 segunduro jaso dezake informazioa eta, beraz, nahiz eta sorgailu eolikoaren portaera denboran zehar nolakoa den jakiteko egokia izan, jarduera esperimentaleko behaketak egiteko neurketa tarte hau handiegia da. Arazo hau konpontzeko, Arduino UNO plaka zuzenean lotuko da ordenagailu batekin eta datuak behatzeko [Putty](https://www.putty.org/) programa erabiliko da.

Bi plakez gain, beste hiru osagaik osatuko dute zirkuitua, **FZ0430** tentsioa neurtzeko sentsorea, **KBP410** zubi artezgailua eta **L7805CV** tentsio erregulatzaile lineala.

::::{grid}
:gutter: 0

:::{grid-item}
```{figure} ./Irudiak/fz0430.png
---
height: 150px
name: FZ0430
---
**FZ0430** tentsioa neurtzeko sentsorea.
```
:::
:::{grid-item}
```{figure} ./Irudiak/KBP410.jpeg
---
height: 150px
name: KBP410
---
**KBP410** zubi artezgailua.
```
:::
:::{grid-item}
```{figure} ./Irudiak/L7805CV.jpg
---
height: 150px
name: L7805CV
---
**L7805CV** tentsio erregulatzaile lineala.
```
:::
::::

Sorgailuak sortutako tentsioa eta irteeran daukaguna neurtzeko bi tentsio-sentsore konektatu dira, bakoitza UNO R3 plakaren pin analogiko batera lotuta egonik. Nahiz eta gure sorgailua DC-ko iturri bat izan eta berez ez izan beharrezkoa zubi artezgailua, errotoreak aldatzerakoan errotoreak biraketa norabidez eta, hortaz, polarizazioz aldatu al direnez, artezgailuak sorgailuaren polo positiboa eta negatiboa beti berdinak izatea ziurtatzen digu. Azkenik, USB irteeran 5V-ko irteera konstantea eduki nahi denez eta tentsio altuagoek arazoak sor ditzaketenez kargatu nahi diren gailuetan erreguladorea konektatu da. Honek 5V-ko irteera ematen du, baina sarreran 7V-ko sarrera minimoa behar du. Honek arazoak sor ditzake ez badugu tentsio hori sortzen.


## Arduino IDE Bidezko Programa

`````{tab-set}
````{tab-item} Arduino UNO R3
```
#include <SoftwareSerial.h>

SoftwareSerial espSerial (5,6); //RX , TX
String str;
String str1;

const int sensorPin1 = A0;
const int sensorPin2 = A1;
int sensorValue1;
int sensorValue2;
float value1;
float value2;

void setup() {
  Serial.begin(9600);
  espSerial.begin(9600);
}

void loop() {
  sensorValue1 = analogRead(sensorPin1);
  sensorValue2 = analogRead(sensorPin2);
  
  value1 = fmap(sensorValue1, 0, 1023, 0.0, 25.0);
  value2 = fmap(sensorValue2, 0, 1023, 0.0, 25.0);
  
  str = String(value1)+String(",")+String(value2)+String("\n");
  espSerial.println(str);
  str1 = String(value1)+String(",")+String(value2);
  Serial.println(str1);

  delay(500);
}

// Eskalaz aldatzeko funtzioa.
float fmap(float x, float in_min, float in_max, float out_min, float out_max) {
  return (x - in_min) * (out_max - out_min) / (in_max - in_min) + out_min;
}

```
````

````{tab-item} NodeMCU
```
#include "ThingSpeak.h"
#include <ESP8266WiFi.h>
#include <SoftwareSerial.h>

SoftwareSerial ardSerial (D1,D2);
char ssid[] = "XXXXXXXXXXXXXX";
char pass[] = "XXXXXXXXXXXXXXXX";
char C;

int i;
int x;
int y;

float float1;
float float2;

String input_string;
String input_string_copia;
String str1;
String str2;

int status = WL_IDLE_STATUS;
WiFiClient  client;
unsigned long myChannelNumber = XXXXXX;
const char * myWriteAPIKey = "XXXXXXXXXXXXXXXX";

void setup() {
  Serial.begin(9600);
  ardSerial.begin(9600);
  Serial.println("Connecting to WiFi...");
  WiFi.begin(ssid, pass); 
  while (WiFi.status() != WL_CONNECTED) {
    delay(1000);
    Serial.println("Connecting...");
  }
  Serial.println("Connected to WiFi");
  ThingSpeak.begin(client);
}

void loop() {
  y=0;
  while (ardSerial.available()>0){
    C = ardSerial.read();
    if (C=='\n'){
      break;
    }
    else{
      input_string +=C;
      input_string_copia +=C;
    }
  }
  while (input_string.length()>0){
    x = input_string_copia.indexOf(".");
    if (x ==-1){
      break;
    }
    else{
      input_string_copia = input_string_copia.substring(x+1);
      y=y+1;
    }
  }
  if (y==2){
    i = input_string.indexOf(",");
    str1=input_string.substring(1,i-1);
    str2=input_string.substring(i+1);
    float1=str1.toFloat();
    float2=str2.toFloat();
    ThingSpeak.setField(1,float1);
    ThingSpeak.setField(2,float2);
    ThingSpeak.writeFields(myChannelNumber, myWriteAPIKey);
    Serial.println(input_string);
    delay(15000);
  }
  C=0;
  input_string = "";
  input_string_copia = "";
}

```
````
`````
Aurretik aipatu bezala, bi plaken artean serie konexio bat ezartzen da Arduinoko $5$ eta $6$ pinak eta NodeMCU-ko $D1$ eta $D2$ pinekin konektatuz. Gainera, *SoftwareSerial* librería erabiltzen da helburu honekin. Honetaz gaina, Arduinoak $A0$ eta $A1$ pin analogikoen bidez tentsioak jasotzen ditu, hauen balioak NodeMCU-ra bidaltzen ditu ondoren WiFi bidez transmitituak izan daitezen eta bere serie motitorean ere inprimatzen ditu.

Aldiz, NodeMCU-aren programa zertxobait konplexuagoa da. *SoftwareSerial* libreriaz gain, *ESP8266WiFi* libreria ere erabiltzen da WiFi bidezko konexioa ahalbidetzeko eta *ThingSpeak* ere erabiltzen da, web-orri honetara informazioa automatikoki eta modu erraz batean bidaltzea ahalbidetuz. Bestalde, programaren xedea Arduinotik jasotako informazioa ThingSpeak orrira bidaltzea da. Gainera, kode zati bat gehitu da serie konexiotik formatu desegokiarekin iristen diren datuak baztertzeko.
