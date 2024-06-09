# Zergatik Savonius motako sorgailu eolikoak aukeratu?

## Savonius Haize-Sorgailuak

Sigurd J. Savonius ingeneari finlandiarrak XX. mendearen 20. hamarkada erdialdean asmatu zituen bere izena daramaten errotoreak. 1929. urtean atera zuen patentean {cite:ps}`SavOriginal` ikusi ditzakegu hasiera batean bururatu zitzaizkion diseinuak. Kasu sinpleena, {numref}`Sav1`-an ikusi dezakeguna, kontrako norantzkoan orientatutako bi zirkulu erdiz osatuta dago. 

```{figure} ./Irudiak/RotorSavonius3.png
---
scale: 30%
align: center
name: Sav1
---
Savonius errotore sinple baten adierazpen eskematikoa. a) 2D-ko bista errotorea erditik ebakitzen badugu. b) 3D-ko irudikapena. c) Haizearen eraginpean errotoreak duen portaeraren eskema. {cite:ps}`AKWA20123054`
    
```

Bere funtzionamendua sinplea da, herrestatze-indarretan, "*drag*" delakoetan, oinarritzen da. Errotorearen palen forma kurbatua dela eta haizearen norantzaren aurka biratzen duen hegoak alde biratzen duenak baino herrestatze-indar gutxiago jaaten du eta indar diferentzia hau da errotorea birarazten duena. Beste hitz batzuetan, haizearengandik indar gehiago jasoko du bere norantzarekiko forma ahurra duen hegoak, indar-diferentzia bat sortuz eta biraketa abiatuz. Bestalde, nahiz eta bere eragina txikia izan, sustentazio indarrek, "*lift*" delakoek, ere ekarpen bat egingo dute.

## Beste Sorgailu Motekiko Konparaketa

Savonius motako sorgailuaren inplementazioa zein testuingurutan interesgarria den jakiteko, lehenik beste aerosorgailuekiko dituen abantailak zeintzuk diren kontuan izan behar dugu. Bi multzotan sailkatzen dira haize-errotak, ardatz bertikaldunak (**VAWT**-ak, "*Vertical Axis Wind-Turbine*"-ak), zeinen artean Savonius motakoak kokatzen diren, adibidez,  eta ardatz horizontaldunak (**HAWT**-ak, "*Horizontal Axis Wind-Turbine*"-ak). Mota desberdinen portaera aztertzeko literaturan (batzuk aipatzearren, {cite:ps}`AKWA20123054` , {cite:ps}`UPV2019` eta {cite:ps}`chimaldiseno` artikuluetan) gehien zabalduta dagoen konparaketa grafikoa batazbesteko eraginkortasun-koefizientea puntako abiaduraren proportzioarekin alderatzen duena da. Lehenengoa, $C_p$ ikurrarekin adierazi ohi dena, turbinak haizetik ateratzea lortzen duen potentziaren eta haizearen beraren potentziaren arteko erlazioa da. Beste hitz batzuetan, turbinak haizetik energia ateratzeko duen gaitasuna kuantifikatzen du. Bigarrena, $\lambda$ ikurrarekin edo TSR ("*Tip Speed Ratio*") siglekin adierazten dena, errotorearen palen puntako abiaduraren eta haizearenaren arteko erlazioa da eta, beraz, matematikoki $\lambda=\frac{wr}{V_0}$ moduan kalkulatzen da, non w abiadura angeluarra, r errotorearen erradioa eta $V_0$ eragozpenik gabeko haizearen abiadura diren. 

```{figure} ./Irudiak/DiferentesTipos.png
---
scale: 50%
align: center
name: HaizeErrotaMotak
---
Aerosorgailu mota desberdinen funtzionamenduaren analisia, $C_p$ eraginkortasun-koefizientea $\lambda$ puntako abiaduraren eta haizearen abiaduraren proportzioaren menpe irudikatuz. {cite:ps}`AKWA20123054`
```

{numref}`HaizeErrotaMotak`-an ikusi dezakegu bai *TSR*-a eta eraginkortasun-koefiziente baxueneko errotoreak direla Savonius motakoak. Hala ere, *TSR* baxukoen artean asmakuntza berrikoena duena dela aipatu behar da eta, beraz, oraindik eraginkortasuna handitzeko diseinu eraldaketak aurkitzea posiblea da. Esaterako, beste iturri batzuetan ageri diren grafikak begiratzen baditugu, Savonius motakoen $C_p$-a Herbeheretar haize errotena eta multipala sorgailuena baino gainetik jartzen dute, {numref}`HaizeErrotaMotak2`-an erakusten den bezala.

```{figure} ./Irudiak/DiferentesTipos2.png
---
scale: 50%
align: center
name: HaizeErrotaMotak2
---
Haize-sorgailu mota desberdinen $C_p$ eta TSR-en konparaketa, *Betz* muga ere adieraziz. {cite:ps}`GOLECHA2012`
```

Gainera, azken irudian *Betz-Joukowsky Muga* {cite:ps}`BETZ2011` ere irudikatzen da. Muga honek $C_p$ eraginkortasunaren balio maximoa irudikatzen du. Teoria honek esaten duenez, edozein haize-sorgailuk sortu dezakeen koefizienterik altuena $0.593$ da eta balio maximo hau lortuko litzateke haizearen errotore barneko abiadura bere eragozpenik gabeko abiaduraren herena denean. 

Kontuan izan behar den beste propietate bat errotoreak sorturako momentua da. Propietate hau kuantifikatzeko, momentu-koefizientea ($C_t$) erabiltzen da. Koefiziente honek turbinak sortutako momentuaren normalizatutako neurria ematen du, haizean eskuragarri dagoen energia zinetikoa kontuan hartuz. Gainera, $C_p$ eta $C_t$ arteko erlazioa $C_p=\lambda\cdot C_t$ {cite:ps}`7281688` da.

```{figure} ./Irudiak/MomentuKoefizienteak.png
---
scale: 50%
align: center
name: MomentuKoefizienteak
---
Aerosorgailu mota desberdinen $C_t$ momentu-koefizienteak, $\lambda$-ren funtzioan. {cite:ps}`AKWA20123054`
```

{numref}`HaizeErrotaMotak`, {numref}`HaizeErrotaMotak2` eta {numref}`MomentuKoefizienteak` grafikak konparatzen baditugu, ikusi dezakegu $C_p$ altuko haize-sorgailu motek $C_t$ baxua dutela. Beraz, sorgailu motari dagokionez, bi propietate garrantzitsu hauek elkar konpentsatuko dira.


## Savonius Haize-sorgailuen Propietate Nagusiak

### Abantailak

- Diseinua sinplea da eta eraikitzeko zailtasun baxua dauka, beste sorgailu eolikoekin konparatuz gero.
- Momentu koefiziente altua dauka, beraz, bai momentu dinamiko eta bai estatiko altua sortzeko gai da. Honek biratzen hasterakoan beste errotoreek baino momentu altuagoa sortzea ahalbidetzen du eta momentu handia beharrezkoa den erabiletarako egokia izan daiteke, adibidez, ura ponpatzeko.
- Haizea edozein norabideetatik jasotzeko aukera daukate. Propietate honek, **VAWT** motakoekin alderatuz, inplementazio erraztasun handiagoa ematen dio, ez baita beharrezkoa errotorea haizearen norantzkoan orientatzeko sistema automatiko konplexurik ezartzea edo, eskala txikiko erabiletarako, ez da beharrezkoa denbora eta esfortzua sorgailua ondo orientatzen xahutzea.
- {numref}`HaizeErrotaMotak`, {numref}`HaizeErrotaMotak2` eta {numref}`MomentuKoefizienteak` grafika guztietan behatu dezakegu mota honetako generadoreak **TSR** baxuenekoak direla. Honek eragin zuzena dauka sortutako zaratan, Savoniusak izanik zarata maila baxuenetakoa sortzen duten errotoreak. Hau oso propietate garrantzitsua da gizakion bizilekuetatik hurbil instalazioa ahalbidetzeko.

### Desabantailak

- Errotorearen palen azaleraren eta proiektatutako errotore osoarenaren arteko proportzioa (ingelesez "*Solidity Ratio*" delakoa) ia unitatearen parekoa da eta, beraz, errotorearen egiturak bultzada indar handiak jasaten ditu.
- Aurreko arrazoi berdinagatik, errotorearen tamaina handia da muntai osoaren tamainarekin konparatuz. Hots, prototipoaren eskala haundituz gero, errotorearen tamaina eraikinezina bilakatu daiteke, esaterako, hiru paladun haize-errota ezagun eta handien eskalako Savonius sorgailuak eraikitzea ezinezkoa da.
- Azkenik, Savonius haize-sorgailuen desabantailarik handiena eraginkortasun edo potentzia koefiziente baxua izatea da.

## Savonius-ak Erabilgarriak diren Testuinguruak.

Aurkeztutako bere aldeko argudioak eta kontrakoak ikusiz erretore honen erabilera abantalagarria izan daitekeen testuinguruak zeintzuk diren ondorioeztatu daiteke. Esaterako, bere diseinu sinpleak garapen bidean dauden herrialdeetan horrelako sistemak inplementatzeko aukera ematen du, ez baita beharrezko makineria astuna behar euren produkziorako. Gainera, nahiz eta lan honetan aerosorgailu bezalako aplikazioa soilik landu, mota honetako errotoreek uraren indarraz bultzatuta ere funtziona dezakete eta, beraz, ura ponpatzeko egokiak dira.

Bestalde, herrilade garatuetan ere abantaila handiak ematen dizkigute mota honetako aerosorgailuek. Sarreran aipatu bezala, norbanakoen bizitokietan energia berriztagarrien erabilera eta instalazioa sustatzea da gaur egungo gizartearen ardura nagusienetako bat. Horretarako, abantailetan adierazi den bezala, oso garrantzitsua da sorgailuak zarata maila baxuak izatea, izan ere, haize-errota handien desabantaila nagusienetako bat sortzen duten kutsadura akustikoa da. Zarata honek gertu bizi diren gizakiengan, adibidez, antsietatea bezalako osasun arazoak agertarazi ditzake eta, hortaz, garrantzitsua da zarata mailak ondo kontrolatzea eta parke eolikoen kokaera egokia aukeratzea, {cite:ps}`Soinu` artikuluan proposatzen den moduan. Arrazoi honegaitik bereziki da beharrazkoa TSR baxua izatea, errotore batek sortutako zarata eta bere palen abiadura proportzionalak baitira. Savonius motako errotoreek baldintza hau oso ondo betetzen dute, gorago aurkeztutako hiru grafiketan ikusi daitekeen bezala.

Horrelako erabiletarako ere garrantzitsua da ahalik eta automatikoena izatea sistema, adibidez, ardatz bertikaleko aerosorgailuen kasuan, energia sortzeko ez dutela haizearen norantzkoan orientaturik egon beharrik eta, beraz, ez da beharrezkoa euren orientazioa aldatzea edo hau automatikoki egiten duen sistema konplexu bat eraikitzea.

Beraz, Savonius motako aerosorgailuek aurreko bi kasuetan, nagusiki, izango dituzte abantailak beste haize-erroten aurrean. Kontextu hauek buruan izanik burutuko da jarduera esperimentala, aipatutako kasuetarako egokitasuna frogatze aldera eta mota honetako errotoreen palen forma egokiena bilatzeko helburuarekin.



