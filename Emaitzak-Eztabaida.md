# Emaitzak eta Eztabaida

## Emaitza Esperimentalak

### Haizearen Abiadura

Ondokoak dira aurreko atalean aurkeztutako metodoa erabiliz probak egiteko erabiliko den haizearen abiadura. Nahiz eta abiadura errealtzat batezbestekoa hartuko den, maximoa ere erakusten da abiadurek norarte fluktuatu dezaketen ikusi al izateko.

```{list-table} : Haize-makina distantzia desberdinetara jartzean errotorearen kokalekuan neurtutako batezbesteko haizearen abiadura eta balio maximoa.
:header-rows: 1
:name: HaizeAbiadurak

* - Errotorearekiko distantzia
  - Batezbesteko balioa
  - Balio Maximoa
* - $1m$
  - $10.76m/s$
  - $11.7m/s$
* - $1.5m$
  - $7.03m/s$
  - $9.8m/s$
* - $2m$
  - $6.39m/s$
  - $8.1m/s$
* - $2.5m$
  - $5.14m/s$
  - $6.1m/s$
* - $3m$
  - $4.07m/s$
  - $5.6m/s$
```

### Erreboluzio eta Tentsio Neurketak

#### 1. Errotorea

Hasteko, errotorea erdibiturik muntatu da eta pala finkoak jarri gabeko probak burutu dira. Lehenik, aipatu beharra da haize-makina 1m-ra kokatzean, hots, haizearen abiadura handiena den frogan, errotorea haustura puntura iritsi dela. Egiturak $800RPM$ arteko abiadurak arazorik jasaten duela frogatu da, baina, hortik gora, kolapsatu egiten du eta, gainera, abiadura horietan sortzen diren tentsioak arriskutsuak dira zirkuitu elektronikoan erabilitako osagaientzat, batez ere, bai sentsoreak ete erreguladoreak funditu ditzake. Arrazoi hauengatik, ez dira kontuan hartu haize-makina 1m-ra kokatutako kasuko emaitzak. Beste kasuetan lortutako tentsioen emaitzak ondorengoak dira:

::::{grid}
:gutter: 0

:::{grid-item}
```{figure} ./Irudiak/Konparazioa_SorgailuaZuzenean.png
---
height: 250px
name: Konparazioa_SorgailuaZuzenean
---
{ref}`EDiseinua1` erdibiturik erabiltzean sorgailuak sortzen duen tentsioa, haize-makina distantzia desberdinetara jartzean.
```
:::
:::{grid-item}
```{figure} ./Irudiak/Konparazioa_Irteeran.png
---
height: 250px
name: Konparazioa_Irteeran
---
{ref}`EDiseinua1` erdibiturik erabiltzean USB portuaren bidez ematen den tentsioa, haize-makina distantzia desberdinetara jartzean.
:::
::::

Bestalde, takometroaren bidez, tentsio neurtzen den aldi berean, erretorea biratzen ari den erreboluzio kopurua ere neurtu da:

```{figure} ./Irudiak/Erreboluzioak1.png
---
height: 300px
name: Erreboluzioak1
---
{ref}`EDiseinua1` erdibiturik erabiltzean errotorea biratzen ari den erreboluzio kopuruak, haize-makina distantzia desberdinetara jartzean.
```

Behaketa hauek amaiturik, estatore kutxa muntatu zaio prototipoari eta saiakera berdinak burutu dira ondorengo emaitzak lortuz:

::::{grid}
:gutter: 0

:::{grid-item}
```{figure} ./Irudiak/Konparazioa_Sorgailua_1.png
---
height: 250px
name: Konparazioa_Sorgailua_1
---
{ref}`EDiseinua1` erdibiturik erabiltzean, pala finkoen kutxa muntatuta duelarik, sorgailuak sortzen duen tentsioa, haize-makina distantzia desberdinetara jartzean.
```
:::
:::{grid-item}
```{figure} ./Irudiak/Konparazioa_Irteeran_1.png
---
height: 250px
name: Konparazioa_Irteeran_1
---
{ref}`EDiseinua1` erdibiturik erabiltzean, pala finkoen kutxa muntatuta duelarik, USB portuaren bidez ematen den tentsioa, haize-makina distantzia desberdinetara jartzean.

```
:::
::::

```{figure} ./Irudiak/Erreboluzioak2.png
---
height: 300px
name: Erreboluzioak2
---
{ref}`EDiseinua1` erdibiturik erabiltzean, pala finkoen kutxa muntatuta duelarik, errotorea biratzen ari den erreboluzio kopuruak, haize-makina distantzia desberdinetara jartzean.
```

Bestalde, ondorengoak dira errotorea erdibitu eta kutxa muntatu gabe erabiltzean lortzen diren emaitzak.

Azkenik, errotoreari berriro estatore palen kutxa gehitzean ondoko emaitzak lortzen dira:

#### 2. Errotorea

#### 3. Errotorea


## Eztabaida

Haizearen abiaduraren neurketaren zatirik interesgarriena haize-makina metro erdi desplazatzeak haizearen abiaduran daukan eraginaz jabetzea da. Distantzia bakoitzean batezbesteko abiadura ondo desberdintzen da beste kasuetatik eta, beraz, egiten den probetan diferentziak behatzea posiblea izango da. Hala ere, sor daitezkeen fluktuazioek, balio maximoek islatzen dituztenek, muga kasuetan distantzia desberdinetara abiadura berdinak izatea posiblea egiten dute eta, beraz, egin diren beste neurketetan hau kontuan izan beharko da emaitzak aztertzean.

Hau esanik, lehenengo errotorearekin egindako frogek...