# Eztabaida

Emaitzen eztabaidarekin hasteko, lehenik, neurketak egiteko erabiliko diren haizearen abiaduraren balioak behatuko dira. Neurketa hauen zatirik interesgarriena haize-makina metro erdi desplazatzeak haizearen abiaduran daukan eraginaz jabetzea da. Distantzia bakoitzean batezbesteko abiadura ondo desberdintzen da beste kasuetatik eta, beraz, egiten den probetan diferentziak behatzea posiblea izango da. Hala ere, sor daitezkeen fluktuazioek, balio maximoen bidez islatuak, muga kasuetan distantzia desberdinetara abiadura berdinak izatea posiblea egiten dute eta, beraz, fenomeno hau ondoren aztertuko diren neurketen emaitzak azaltzerakoan kontuan izan behar da. 

```{figure} ./Irudiak/Grafikak/HaizearenAbiadura.png
---
height: 200px
name: HaizearenAbiadura
---
2024-ko martxotik maiatzera Zorrotzako estazio meteorologikoan egunero neurtutako batezbesteko haizearen abiaduraren eta neurketak egiteko erabiliko diren abiaduren alderaketa. Datuak: [Euskalmet, Euskal Meteorologia Agentzia](https://www.euskalmet.euskadi.eus/behaketa/estazioen-datuak/#).
```

{numref}`HaizearenAbiadura` irudian aurkezten den konparaziotik ikusi dezakegu jarduera esperimentalak burutzeko erabili diren abiadurak ez direla errealitatean EAE-n dauzkagunetatik urruntzen. Abiadura altuena kenduta, besteek errealitatean izan daitezkeen abiadurak islatzen dituzte eta haize-makina hiru metrora kokatzean daukagun balioak aurreko grafikoan aztertzen diren hiru hilabeteetako neurketen batezbestekora ($3.2m/s$) asko hurbiltzen da.

Hau esanik, errotore desberdinekin egindako neurketen emaitzak alderatuko dira. Hasteko, biraketa-abiaduren grafikoetan argi ikusi daiteke estatore palen kutxak gehitzen duen estabilitatea, kasu hauetan erreboluzioek balio konstanteagoak hartzen baitituzte. Efektu hau nabaria da, batez ere, lehenengo errotorearekin egindako neurketetan. 

Bestalde, batez ere hirugarren errotoreen kasuan, errotore osoarekin eginiko neurketa batzuetan hasierako orientazio batzuetarako ez da biratzen hasten sorgailua. Aldiz, erdibitutako errotoreetan ez da fenomeno hau antzeman, hau baita azken hauen abantaila handiena, bi norabideetara orientatutako errotoreak ia edozein norabidetatik etorritako haizea jasoz hasi baitaitezke biratzen. Hala ere, kasu batzuetan eraginkortasun jeitsiera bat hauteman da errotorea erdibitzean eta, beraz, bi gertaerak balantzan jartzean errotore osoak irabazi dezake.

Grafikoetatik atera daitekeen beste datu garrantzitsu bat irteeran 5V inguruko tentsio jarraia izateko haizearen abiadura minimoa da. Lehenengo errotorearen kasuan, osoak haize-makina 2m-ra kokatzean jada nahiko tentsioa sortzen du eta, aldiz, honi estatore palak muntatzean lortzen den emaitza okertu egiten da eta irteerako tentsioak 5V-ren inguruan gehiago oszilatzen du. Bestalde, erdibituaren kasuan kontrako efektua gertatzen da, kutxarekin neurketak egitean emaitza hobeak lortzen ditugu. Portaera honen atzean egon daitekeen arrazoia, erdibitutako errotoreak bibrazio gehiago sortzean, estatore palen kutxak gehitutako egonkortasunak eragin positiboago eragitea izan daiteke. Aldiz, errotore osoaren kasuan, eragin hau txikiagoa izango litzateke eta egitura gehigarriak sorturiko turbulentzien eragin negatibo handiagoak hau gaindituko luke.

Bigarren errotorearen kasuan, errotore osoarekin nahikoa da haize-makinak 2.5m-ra sortzen duen fluxua 5V-ko irteera lortzeko. Erdibitutako kasuan, nahiz eta hurbil izan, ez da nahi dugun kopuru hori lortzen distantzia horretara, baina 2m-ra jada irteera guztiz konstante bat daukagu. Bi kasuetan estatore palen kutxak daukan eragina ez da handia, baina esan daiteke positiboa dela, osoari balio konstantea tarte luzeago batean lortzea eragiten baitio eta erdibituari 5V-ko baliotik hurbilago oszilatzen ibiltzen laguntzen diolako.

Hirugarren errotoreari dagokionez, lortutako balioa okerragoa da, 1.5m-ra kokatu behar baita haize-makina irteera konstante bat izateko. Hala ere, salbuespen bat dago, errotore osoari estatore palen kutxa gehitzean bai lortzen da 5V-ko irteera konstantea haize-makina 2m-ra kokatzean. Errotore honen kasuan, arrazoi honetaz gain, 3m-ko distantziara biratzen hasteko kutxa beharrezkoa denez, esan dezakegu estatore palen eragina oso positiboa dela eta haizea angelu zehatz batekin errotorera iristeak asko laguntzen diola.

Bestalde, errotore moten arteko konparaketa zehatzago bat egin al izateko, sorgailuak zuzenean sortutako tentsioak eta biraketa-abiaduren balioak aztertuko dira, batezbesteko balioak eta desbiderapen estandarrak kalkulatuz eta balio maximoak behatuz. Datu hauek hartzeko ez dira saiakeretako hasierako eta amaierako tarteak kontuan izango, hots, errotorea azeleratzen eta frenatzen ari den tarteak. Gainera, bakarrik errotore guztiekin behatutako haizearen abiadurak izango dira kontuan, hau da, haize-makina 1.5m-ra, 2m-ra eta 2.5m-ra kokatzen den kasuak.

```{table} : Lehenengo errotorea erdibiturik egon gabe sorgailuak sortutako tentsioen batezbesteko balioa, desbideratze estandarra eta balio maximoa, haizearen abiadura desberdinetara.
:name: my-table-ref1

| Estatore palen kutxa?    | Haize-makinarekiko distantzia (m) | Batezbesteko balioa (V) | Desbideratze estandarra (V) | Balio Maximoa (V) |
|--------------------------|-----------------------------------|-------------------------|-----------------------------|--------------------|
| BAI                      | 1.5m                              | 8.343                   | 0.847                       | 10.02              |
| BAI                      | 2m                                | 6.164                   | 0.797                       | 7.48               |
| BAI                      | 2.5m                              | 3.959                   | 0.583                       | 4.96               |
| EZ                       | 1.5m                              | 8.615                   | 1.114                       | 10.58              |
| EZ                       | 2m                                | 7.072                   | 0.839                       | 8.92               |
| EZ                       | 2.5m                              | 4.394                   | 0.532                       | 5.52               |
```

```{table} : Lehenengo errotorea erdibiturik egonik sorgailuak sortutako tentsioen batezbesteko balioa, desbideratze estandarra eta balio maximoa, haizearen abiadura desberdinetara.
:name: my-table-ref2

| Estatore palen kutxa?    | Haize-makinarekiko distantzia (m) | Batezbesteko balioa (V) | Desbideratze estandarra (V) | Balio Maximoa (V) |
|--------------------------|-----------------------------------|-------------------------|-----------------------------|--------------------|
| BAI                      | 1.5m                              | 9.287                   | 0.717                       | 10.39              |
| BAI                      | 2m                                | 6.945                   | 0.748                       | 8.09               |
| BAI                      | 2.5m                              | 4.6175                  | 0.5                         | 5.33               |
| EZ                       | 1.5m                              | 8.694                   | 0.979                       | 10.41              |
| EZ                       | 2m                                | 6.016                   | 0.684                       | 7.16               |
| EZ                       | 2.5m                              | 4.5526                  | 0.6242                      | 5.62               |
```

```{table} : Lehenengo errotorea erdibiturik egon gabe biratzean dauzkan erreboluzioen batezbesteko balioa, desbideratze estandarra eta balio maximoa, haizearen abiadura desberdinetara.
:name: my-table-ref3

| Estatore palen kutxa?    | Haize-makinarekiko distantzia (m) | Batezbesteko balioa (RPM) | Desbideratze estandarra (RPM) | Balio Maximoa (RPM) |
|--------------------------|-----------------------------------|-------------------------|-----------------------------|--------------------|
| BAI                      | 1.5m                              | 509.39                    | 5.44                          | 515.3                |
| BAI                      | 2m                                | 390.99                    | 6.84                          | 405.7                |
| BAI                      | 2.5m                              | 273.8                     | 7.26                          | 286.5                |
| EZ                       | 1.5m                              | 508.89                    | 19.2                          | 548.4                |
| EZ                       | 2m                                | 434.4                     | 26.64                         | 484.8                |
| EZ                       | 2.5m                              | 293.49                    | 23.73                         | 330.6                |
```

```{table} : Lehenengo errotorea erdibiturik egonik biratzean dauzkan erreboluzioen batezbesteko balioa, desbideratze estandarra eta balio maximoa, haizearen abiadura desberdinetara.
:name: my-table-ref4

| Estatore palen kutxa?    | Haize-makinarekiko distantzia (m) | Batezbesteko balioa (RPM) | Desbideratze estandarra (RPM) | Balio Maximoa (RPM) |
|--------------------------|-----------------------------------|-------------------------|-----------------------------|--------------------|
| BAI                      | 1.5m                              | 524.13                    | 7.64                          | 531.5                |
| BAI                      | 2m                                | 428.65                    | 9.05                          | 437.1                |
| BAI                      | 2.5m                              | 297.2                     | 7.07                          | 305.6                |
| EZ                       | 1.5m                              | 513.41                    | 17.68                         | 540.9                |
| EZ                       | 2m                                | 375.32                    | 11.1                          | 395.4                |
| EZ                       | 2.5m                              | 301.89                    | 16.56                         | 328.7                |
```

Lehenengo errotorearen datuetatik bi ondorio atera daitezke, lehenik, estatore palen kutxaren eragina negatiboa dela energia sortzeko gaitasunari dagokionez errotore osoaren kasuan eta positiboa erdibituarenean. Bigarrenik, kutxa ez muntatzeak emaitza ezegonkorragoak ematea dakarrala ondorioezta daiteke. Azken hau garbi ikusi daiteke desbideratze estandarretan, bereziki, {numref}`my-table-ref4` eta {numref}`my-table-ref3` tauletako balioetan. Balio maximoei dagokionez ikusi dezakegu ez direla egiturarentzat arriskutsuak izateko balioetara iristen. Interesgarria da ere behatzea ia neurketa guztietan balio hobeak lortu direla errotorea erdibituarekin. Guzti hau kontuan izanik, aztertutak izan diren aldaeretatik, estatore paladun errotore erdibituak izan du energia sortzeko kapazitate handiena.

```{table} : Bigarren errotorea erdibiturik egon gabe sorgailuak sortutako tentsioen batezbesteko balioa, desbideratze estandarra eta balio maximoa, haizearen abiadura desberdinetara.
:name: my-table-ref5

| Estatore palen kutxa?    | Haize-makinarekiko distantzia (m) | Batezbesteko balioa (V) | Desbideratze estandarra (V) | Balio Maximoa (V) |
|--------------------------|-----------------------------------|-------------------------|-----------------------------|--------------------|
| BAI                      | 1.5m                              | 12.54                   | 1.534                       | 19.11              |
| BAI                      | 2m                                | 9.5                     | 1.089                       | 11.17              |
| BAI                      | 2.5m                              | 6.961                   | 1.164                       | 13.54              |
| EZ                       | 1.5m                              | 13.126                  | 1.662                       | 20.21              |
| EZ                       | 2m                                | 9.015                   | 1.024                       | 10.46              |
| EZ                       | 2.5m                              | 7.028                   | 0.99                        | 8.68               |
```

```{table} : Bigarren errotorea erdibiturik egonik sorgailuak sortutako tentsioen batezbesteko balioa, desbideratze estandarra eta balio maximoa, haizearen abiadura desberdinetara.
:name: my-table-ref6

| Estatore palen kutxa?    | Haize-makinarekiko distantzia (m) | Batezbesteko balioa (V) | Desbideratze estandarra (V) | Balio Maximoa (V) |
|--------------------------|-----------------------------------|-------------------------|-----------------------------|--------------------|
| BAI                      | 1.5m                              | 11.494                  | 2.114                       | 19.77              |
| BAI                      | 2m                                | 8.633                   | 1.318                       | 15.69              |
| BAI                      | 2.5m                              | 6.104                   | 0.837                       | 8.31               |
| EZ                       | 1.5m                              | 11.873                  | 1.718                       | 21.07              |
| EZ                       | 2m                                | 8.663                   | 1.037                       | 10.41              |
| EZ                       | 2.5m                              | 6.022                   | 0.922                       | 7.99               |
```

```{table} : Bigarren errotorea erdibiturik egon gabe biratzean dauzkan erreboluzioen batezbesteko balioa, desbideratze estandarra eta balio maximoa, haizearen abiadura desberdinetara.
:name: my-table-ref7

| Estatore palen kutxa?    | Haize-makinarekiko distantzia (m) | Batezbesteko balioa (RPM) | Desbideratze estandarra (RPM) | Balio Maximoa (RPM) |
|--------------------------|-----------------------------------|-------------------------|-----------------------------|--------------------|
| BAI                      | 1.5m                              | 710.76                    | 5.93                          | 723.1              |
| BAI                      | 2m                                | 563.2                     | 14.65                         | 583.8              |
| BAI                      | 2.5m                              | 423.75                    | 8.09                          | 434.2              |
| EZ                       | 1.5m                              | 745.28                    | 10.62                         | 766.3              |
| EZ                       | 2m                                | 533.49                    | 6.89                          | 544.7              |
| EZ                       | 2.5m                              | 443.04                    | 12.94                         | 462.8              |
```

```{table} : Bigarren errotorea erdibiturik egonik biratzean dauzkan erreboluzioen batezbesteko balioa, desbideratze estandarra eta balio maximoa, haizearen abiadura desberdinetara.
:name: my-table-ref8

| Estatore palen kutxa?    | Haize-makinarekiko distantzia (m) | Batezbesteko balioa (RPM) | Desbideratze estandarra (RPM) | Balio Maximoa (RPM) |
|--------------------------|-----------------------------------|-------------------------|-----------------------------|--------------------|
| BAI                      | 1.5m                              | 639.2                      | 7.98                          | 648.3              |
| BAI                      | 2m                                | 499.74                    | 12.08                         | 517.2              |
| BAI                      | 2.5m                              | 375.82                    | 17.77                         | 399.6              |
| EZ                       | 1.5m                              | 657.47                    | 8.37                          | 665.8              |
| EZ                       | 2m                                | 512.29                    | 33.21                         | 542.9              |
| EZ                       | 2.5m                              | 360.67                    | 54.11                         | 426.4              |
```

Bigarren mota honen kasuan, aldaera desberdinek portaeran duten eragina ez da hain garbia. Kutxarekin eginiko neurketetan neurtutako balioak ez dira asko urruntzunen hau gabe eginikoetatik, nahiz eta egia izan neurketen gehiengoan gutxigatik batezbesteko balio altuagoak lortu diren estatore palarik gabe. Egonkortasunaren kasuan antzeko joera gertatzen da tentsioekin, bai estatore palen kutxarekin eta bai gabe antzeko balioak lortzen dira. Hala ere, aipatu beharra da desbideratze estandar hobeak lortzen direla gehienbat estatore palen kutxa instalatuta dagoenean eta azpimarratu behar da, erroboluzioen kasuan, egitura hau gabe desbideratze estandarraren balioa asko igotzen dela, ordenez aldatzera iritxiz.

```{table} : Hirugarren errotorea erdibiturik egon gabe sorgailuak sortutako tentsioen batezbesteko balioa, desbideratze estandarra eta balio maximoa, haizearen abiadura desberdinetara.
:name: my-table-ref9

| Estatore palen kutxa?    | Haize-makinarekiko distantzia (m) | Batezbesteko balioa (V) | Desbideratze estandarra (V) | Balio Maximoa (V) |
|--------------------------|-----------------------------------|-------------------------|-----------------------------|--------------------|
| BAI                      | 1.5m                              | 9.921                   | 1.041                       | 11.73             |
| BAI                      | 2m                                | 7.671                   | 0.86                        | 9.14              |
| BAI                      | 2.5m                              | 4.063                   | 0.583                       | 4.96              |
| EZ                       | 1.5m                              | 8.34                    | 0.837                       | 9.78              |
| EZ                       | 2m                                | 5.514                   | 0.725                       | 6.5               |
| EZ                       | 2.5m                              | 3.749                   | 0.77                        | 4.84              |
```

```{table} : Bigarren errotorea erdibiturik egonik sorgailuak sortutako tentsioen batezbesteko balioa, desbideratze estandarra eta balio maximoa, haizearen abiadura desberdinetara.
:name: my-table-ref10

| Estatore palen kutxa?    | Haize-makinarekiko distantzia (m) | Batezbesteko balioa (V) | Desbideratze estandarra (V) | Balio Maximoa (V) |
|--------------------------|-----------------------------------|-------------------------|-----------------------------|--------------------|
| BAI                      | 1.5m                              | 8.608                   | 1.07                        | 10.31             |
| BAI                      | 2m                                | 5.487                   | 0.734                       | 6.79              |
| BAI                      | 2.5m                              | 2.758                   | 0.526                       | 3.93              |
| EZ                       | 1.5m                              | 8.091                   | 1.021                       | 9.87              |
| EZ                       | 2m                                | 5.093                   | 0.642                       | 6.18              |
| EZ                       | 2.5m                              | 3.648                   | 0.476                       | 4.55              |
```

```{table} : Hirugarren errotorea erdibiturik egon gabe biratzean dauzkan erreboluzioen batezbesteko balioa, desbideratze estandarra eta balio maximoa, haizearen abiadura desberdinetara.
:name: my-table-ref11

| Estatore palen kutxa?    | Haize-makinarekiko distantzia (m) | Batezbesteko balioa (RPM) | Desbideratze estandarra (RPM) | Balio Maximoa (RPM) |
|--------------------------|-----------------------------------|-------------------------|-----------------------------|--------------------|
| BAI                      | 1.5m                              | 584.28                    | 9.38                          | 593.7                |
| BAI                      | 2m                                | 469.15                    | 10.8                          | 479.2                |
| BAI                      | 2.5m                              | 280.55                    | 12.67                         | 297.2                |
| EZ                       | 1.5m                              | 492.28                    | 20.67                         | 517.1                |
| EZ                       | 2m                                | 357.27                    | 12.35                         | 380.5                |
| EZ                       | 2.5m                              | 258.53                    | 28.24                         | 288.2                |
```

```{table} : Hirugarren errotorea erdibiturik egonik biratzean dauzkan erreboluzioen batezbesteko balioa, desbideratze estandarra eta balio maximoa, haizearen abiadura desberdinetara.
:name: my-table-ref12

| Estatore palen kutxa?    | Haize-makinarekiko distantzia (m) | Batezbesteko balioa (RPM) | Desbideratze estandarra (RPM) | Balio Maximoa (RPM) |
|--------------------------|-----------------------------------|-------------------------|-----------------------------|--------------------|
| BAI                      | 1.5m                              | 502.23                    | 13.96                         | 522.1                |
| BAI                      | 2m                                | 337.43                    | 9.31                          | 346.6                |
| BAI                      | 2.5m                              | 247.52                    | 15.34                         | 261.4                |
| EZ                       | 1.5m                              | 521.6                     | 11.71                         | 536.1                |
| EZ                       | 2m                                | 354.52                    | 26.21                         | 382.5                |
| EZ                       | 2.5m                              | 203.14                    | 22.29                         | 246.1                |
```

Hirugarren errotorearen kasuan, kontuan izan behar da estatore palen egiturarik gabe ez dela gai biratzen hasteko haize-makina 3m-ko distantzian jartzean lortzen den korrontearekin. Gainera, batezbesteko balioak ere altuagoak dira egitura honekin egindako kasuetan eta, aurreko kasuetan bezala, desbideratze estandarraren bidez islatutako egonkortasuna ere hobea da. Bestalde, errotore osoarekin eginiko neurketen batezbesteko balio guztiek erdibitutakoarekin lortutakoak gainditzen dituzte. Bi arrazoi hauengatik, baieztatu daiteke hirugarren errotore honen aldaera eraginkorrena errotore osoarekin eta estatore palen egiturarekin osatutakoa dela, nahiz eta aurretik aipatu bezala, zati bakarreko errotorearen kasu batzuetan biratzen hasteko arazoak izan orientazio zehatz gutxi batzukin.

Hiru mota desberdinen alderaketari dagokionez, tentsiorik altuena sortzen duen mota bigarrena da. Gainera, baldintza berdinetan beste bi motekin egindako ia proba guztietan lortutako diferentzia handia da, 2. motako errotoreek sortutako tentsioak oro har 2V-tik gorako aldea ateratzen diote beste bi motetako beraien neurketa baliokideei. Esperotako moduan, antzekoa gertatzen da biraketa-abiadurarekin, 200RPM inguruko aldea egonik bigarren motako eta beste bi motetako neurketa baliokideen artean. Hau oso diferentzia adierazgarria da, 2. errotorearekin osatutako aldaerek 1. eta 3. errotoreekin osatutakoek baino haize-abiadura maila bat baxuagoa behar dutela baieztatu baitaiteke. Beste hitz batzuetan, 2. errotorearekin haize-makina prototipotik metro erdi urrunago jarrita distantzia horretatik beste bi motekin lortu diren antzeko tentsioak neurtu dira.

Bestalde, lehenengo eta bigarrengo errotoreekin sortutako batezbesteko tentsioak alderatzen baditugu biek nahiko balio antzekoak sortzen dituztela ikusi dezakegu. Hala ere, emaitza egokienak dituen hirugarren errotorearen aldaera kontuan izaten bada, honekin lorturiko batezbesteko balioak beste neurketen gainetik daudela behatu daiteke, nahiz eta gutxigatik izan eta, batez ere, lehenengo errotorearen aldaera egokiena asko gerturatu balio horietara.

Egonkortasunari dagokionez, orokorrean, antzeko ordeneko emaitzak lortu dira hiru errotoreekin egindako frogetan. Azpimarratu behar da, salbuespenak salbuespen, pala finkoen kutxak egonkortasuna gehitzen duela eta, beraz,  desbiderapen estandar txikiagoak behatzen direla kasu horietan. Honetaz gain, diferentziak hobeto antzemateko biraketa-abiadurekin lortutako balioak behatzen badira, argi dago, kutxarik gabeko kasuetan bereziki, badirela kasu batzuk non desbiderapen estandarra asko handitzen den, ordenez igotzera iritsiz kasu okerrenetan. Bestalde, interesgarria da ikustea erreboluzioen desbiderapenak eta tentsioenak ez daudela zuzenean lotuta. Hau azaltzeko arrazoi logikoena biraketa-abiadura oszilakorrek antzeko tentsioak sortu ditzaketela da.

Balio maximoei dagokionez, tauletan erakusten diren distantzietara eginiko frogetan lehenengo eta bigarren errotoreen aldaera guztiek ez dituzte egitura apurtzeko nahikoa erreboluzio izan edo osagai elektronikoak kaltetzeko moduko tentsioak sortu eta, beraz, abiadura horiekin arazoren bat izatea ez da probablea. Aldiz, bigarren errotorearekin haize abiadura altuenera izandako biraketa-abiadura asko gerturatzen da beste kasuetan haustura eragin duen $800RPM$-etara. Hala ere, errotore mota honekin haize abiadura horretara egin diren froga gutietan ez da horrelako arazorik izan eta ondo eutsi ditu $750RPM$ baino erreboluzio azkarragoak. Hala ere, gutxienez zirkuitu elektronikoaren aldetik, neurturiko tentsio maximoa $20.21V$-koa da eta osagai elektronikoak badaude balio horren ingurukoak jasateko prestatuak.

Amaitzeko, bigarren errotorearekin muntatutako aldaera egokiena zein izan daitekeen eztabaidatuko da. Argi dago, bai egonkortasunaren aldetik eta bai energia sortzeko kapazitatearenetik, balio hobeak lortzen direla erdibitu gabeko errotoreekin. Aldiz, estatore kutxaren eragina positiboa edo negatiboa den jakitea zailagoa da dauzkagun datuekin. Bai haize abiadura altuenarekin eta bai geldoenarekin, datu hobeak lortzen dira gabe, baina abiadura ertainarekin, aldiz, datu zertxobait hobeak lortzen dira kutxarekin. Kontuan izanik, atal honen hasieran aipatu bezala, haize-makinaren kokalekuaren aldaketa txiki batek eragina izan dezakeela froga batean izandako haizearen abiaduran, suposatuko da abiadura altuenera eta abiadura baxuenera eginiko neurketek ematen dutela portaera erreala hobekien islatzen dituzten datuak eta 2m-ra neurtutako balio kontrajarriak salbuespen moduan hartuko dira. Gainera, errotore honekin eginiko laugarren neurketak (haize-makina 3m-ra jarrita eginikoak) ematen dituen balioak kalkulatzen badira hipotesi honekin bat datozela ikusten da. Hain zuzen ere, estatore palarik gabeko kasuan batezbestean $4.86V$-ko eta $330.92RPM$-ko balioak lortzen dira eta, aldiz, kutxa instalatuta $4.68V$-ko eta $305.51RPM$-ko balio zertxobait baxuagoak lortzen dira. Beraz, esan daiteke egin diren probek frogatu dutela behatu diren errotoreen aldaeretatik energia ekoizteko gaitasun handiena erakutsi duen errotorea bigarren motakoa izan dela, osorik eta estatore palen kutxa muntatu gabe.