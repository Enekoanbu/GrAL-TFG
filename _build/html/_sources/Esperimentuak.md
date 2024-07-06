# Jarduera Esperimentala

Jarduera esperimentalean eraikitako prototipoaren jokaera behatu nahi da haize abiadura desberdinen eraginpean. Gainera, errotoreen formak izan dezakeen eragina neurtzeko diseinaturiko bost hego motetatik hiru inprimatu dira eta bakoitzarekin probak bi aldiz burutuko dira, lehenengo palak erdibiturik probatuko dira (altuera erdiko norabide desberdinetan orientatutako bi zatiz egongo da osatuta errotorea) eta, ondoren, erdiak pegatu eta pala osoekin lortutako errotorearekin egingo dira frogak.

::::{grid}
:gutter: 0

:::{grid-item}
```{figure} ./Irudiak/Anemometro.jpg
---
height: 150px
name: Anemometro
---
Haizearen abiadura neurtzeko erabiliko den anemometroa.
```
:::
:::{grid-item}
```{figure} ./Irudiak/TAC.jpg
---
height: 150px
name: TAC
---
Errotorean bira kopurua zenbatzeko erabiliko den takometroa.
```
:::
:::{grid-item}
```{figure} ./Irudiak/Soplador.jpg
---
height: 150px
name: Soplador
---
Prototipoa biraraziko duen haize fluxu konstantea sortzeko erabiliko den gailua.
```
:::
::::

{numref}`Soplador` irudiko haize-makina erabili da frogak egiteko. Potentzia altuko sorgailu honek abiadura bakarra duenez, haizearen abiada desberdinetara frogak egiteko errotoretik distantzia desberdinetara kokatuko da, $1m$-ra, $1.5m$-ra, $2m$-ra, $2.5m$-ra eta $3m$-ra. Egurrezko egitura sendo batean kokatuz beti altuera berdinera egotea ziurtatuko da, errotorearen zentrora zuzenduz.

Neurgailu moduan, {numref}`Anemometro` irudiko anemometroa eta {numref}`TAC` irudiko takometroa erabiliko dira. Lehenengoak sortutako haizearen abiadura neurtzea ahalbidetzen du eta bigarrenak errotorearen biraketa-aboadura neurtzeko balio du. Anemometroak $0.1m/s$-ko bereizmena eta $\pm5\%$-ko zehaztasuna dauzka. Aldiz, takometroak $0.1RPM$-ko bereizmena eta $\pm0.02\%$-ko zehaztasuna dauzka.

## Haizearen Abiaduraren Neurketa

```{figure} ./Irudiak/HaizeAbiaduraFrogak.png
---
height: 500px
align: left
name: HaizeAbiaduraFrogak
---
Haizearen abiaduraren neurketak.
```
Jarduera esperimentalaren lehenengo pausoa probak egiteko eremua markatzea da. Honetarako errotorearen oinarria jarriko den gunea markatu da eta marka hauetatik $1m$-ra, $1.5m$-ra, $2m$-ra, $2.5m$-ra eta $3m$-ra haize-makina kokatzeko beste bost marka jarri dira. Behin esperimentazio gunea prestaturik, haize-makinarekin sortzeko gai izango garen abiadurak neurtuko dira. Helburu hau betetzeko {numref}`HaizeAbiaduraFrogak` irudiko muntaia egin da, anemometroa sorgailu eolikoa kokatuko den tokian jarriz eta honen neurketak gordetzeko bideo-kamara bat ere jarriz.

Abiaduraren neurketa fidagarri bat lortu al izateko, haize-makina 4 edo 5 aldiz kokatu da posizio bakoitzean. Saiakera bakoitzean anemometroak ematen dituen datuak grabatu dira 15 segundu inguruko denbora tarte batean. Ondoren, saiakera bakoitzean lortutako batezbesteko balioa kalkulatzen da anemometroak segundu bakoitzean ematen duen balioa kontuan izanik eta, azkenik, errealtzat hartuko den balioa kalkulatzeko lortu diren emaitzen arteko batezbestekoa burutzen da berriro. Prozedura honen bidez haize-makinaren kokaleku edo orientazioa aldaketa txikiek haizearen abiaduran izan dezaketen eragina kontuan hartzea lortu da. 

## Erretore Desberdinekin Erreboluzio eta Tentsio Neurketak

Jarduera esperimentalaren zati garrantzitsuena errotore mota desberdinekin haize-makinak sortzen duen abiadura bakoitzeko eraikitako prototipoak hartzen duen abiadura neurtzea eta honen ondorioz sortu dezakeen tentsioa behatzea izango da. Horretarako, aztertuko diren errotore aldaera bakoitza, haizearen intentsitate bakoitzaren pean jarriko da 30 segundu inguruko tarteetan. Inprimatu beharreko pieza kopurua txikitzeko, lehenengo erdibitutako errotoreekin egingo dira probak eta, ondoren, bi erdiak itsatsiko dira pieza bakarreko errotoreak osatzeko.

```{figure} ./Irudiak/Proba2.png
---
height: 400px
align: left
name: Proba2
---
Erreboluzioen eta tentsioen neurketa egiteko muntaia.
```

{numref}`Proba2` irudian erakusten den muntaia egin da helburu hau betetzeko. Haize-korrontea ez eragozteko, neurketa tresna guztiak errotorearen alde batean kokatu dira. Takometroa errotoretik $20cm$ ingurura kokatu da eta neurketak ondo egiteko errotorean jarri den marka islatzailera zuzendu da. Bere balioak gordetzeko bere atzean jarri den bideo-kamera bat erabili da. Aldiz, tentsio datuak jasotzeko ordenagailua arduinora konektatu da eta aipaturiko **Putty** programa erabili da serie monitoreko datuak gordetzeko. Haize-makina aurreko atalean azaldu den posizioetan kokatuko da. Gainera, gehigarri moduan, errotorearen funtzionamendua hobeto aztertzeko eta edozein arazoren zergatia jakiteko aukera izateko, errotorearen goiko oinarrian kokatutako **GoPro** kamera bat erabili da egin diren esperimentuetan errotoreak izan duen jarrera grabatzeko eta, horrela, adibidez, errotoreren batek kolapsatzeko kasuan, hori eragin duen arrazoia zein izan den jakiteko informazio gehiago eskura izango da.

Errotore desberdinei dagokienez, {ref}`EDiseinua` atalean aurkeztutako {ref}`EDiseinua1`, {ref}`EDiseinua2` eta {ref}`EDiseinua3` probatuko dira. Gainera, aurretik aipatu bezala, errotore mota bakoitzeko bi muntai egingo dira, bata errotorea osorik muntatuta eta bestea errotorea erdibiturik, zati bakoitza norabide elkarzut bakoitzean orientatuz. Honetaz gain, estatore finkoen kutxa muntatzeak izan dezakeen eragina ere aztertuko da sei kasuetako bakoitzean.  Aldaera guztiak kontuan izanik, errotore mota bakoitzeko lau aukera desberdinekin egingo dira frogak, guztira 12 aukera desberdinekin egingo dira frogak.




