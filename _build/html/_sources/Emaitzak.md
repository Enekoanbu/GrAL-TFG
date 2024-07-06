# Emaitza Esperimentalak

## Haizearen Abiadura

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

## Erreboluzio eta Tentsio Neurketak 

### 1. Errotorea

Hasteko, errotorea erdibiturik muntatu da eta pala finkoak jarri gabeko probak burutu dira. Lehenik, aipatu beharra da haize-makina 1m-ra kokatzean, hots, haizearen abiadura handiena den frogan, errotorea haustura puntura iritsi dela. Egiturak $800RPM$ arteko biraketa-abiadurak jasan ditzakeela frogatu da, baina, aldiz, erreboluzio kopuru horrek sortutako tentsioa zirkuituarentzat altuegia dela behatu da, esaterako, erabili diren tentsio sorgailuek 25V-rainoko tentsioa detektatzeko gai dira eta hortik gorakoek sentsorea erre dezaketela ikusi da. Arrazoi honengatik, errotore honekin eginiko probak lau izango dira, haize-sorgailua 3m, 2.5m, 2m eta 1.5m-ko distantzietara jarriz burutuko dira neurketak.

::::{grid}
:gutter: 0

:::{grid-item}
```{figure} ./Irudiak/Grafikak/1.ErrotoreaErdibitua_1.png
---
height: 260px
name: 1.ErrotoreaErdibitua_1
---
{ref}`EDiseinua1` erdibiturik erabiltzean sorgailuak sortzen duen tentsioa, haize-makina distantzia desberdinetara jartzean (urdinez haize-makina 1.5m-ra jartzean lortutako datuak, gorriz 2m-ra, horiz 2.5m-ra eta berdez 3m-ra).
```
:::
:::{grid-item}
```{figure} ./Irudiak/Grafikak/1.ErrotoreaErdibitua_2.png
---
height: 260px
name: 1.ErrotoreaErdibitua_2
---
{ref}`EDiseinua1` erdibiturik erabiltzean sorgailu eolikoaren irteeran, USB portuan, neurtzen den tentsioa erregulatzailetik igaro ondoren, haize-makina distantzia desberdinetara jartzean (urdinez haize-makina 1.5m-ra jartzean lortutako datuak, gorriz 2m-ra, horiz 2.5m-ra eta berdez 3m-ra).
:::
::::

Neurketa hauek amaiturik, estatore kutxa muntatu zaio prototipoari eta prozesu berdina burutu da ondoko emaitzak lortuz:

::::{grid}
:gutter: 0

:::{grid-item}
```{figure} ./Irudiak/Grafikak/1.ErrotoreaErdibituaKutxarekin_1.png
---
height: 260px
name: 1.ErrotoreaErdibituaKutxarekin_1
---
{ref}`EDiseinua1` erdibiturik eta estatore palen kutxa muntaturik duela erabiltzean sorgailuak sortzen duen tentsioa, haize-makina distantzia desberdinetara jartzean (urdinez haize-makina 1.5m-ra jartzean lortutako datuak, gorriz 2m-ra, horiz 2.5m-ra eta berdez 3m-ra).
```
:::
:::{grid-item}
```{figure} ./Irudiak/Grafikak/1.ErrotoreaErdibituaKutxarekin_2.png
---
height: 260px
name: 1.ErrotoreaErdibituaKutxarekin_2
---
{ref}`EDiseinua1` erdibiturik eta estatore palen kutxa muntaturik duela erabiltzean sorgailu eolikoaren irteeran, USB portuan, neurtzen den tentsioa erregulatzailetik igaro ondoren, haize-makina distantzia desberdinetara jartzean (urdinez haize-makina 1.5m-ra jartzean lortutako datuak, gorriz 2m-ra, horiz 2.5m-ra eta berdez 3m-ra).

```
:::
::::


Bestalde, aurreko neurketak burutzen ziren bitartean, takometroaren bidez, errotorearen biraketa-abiaduraren inguruko ondoko datuak lortu dira:

::::{grid}
:gutter: 0

:::{grid-item}
```{figure} ./Irudiak/Grafikak/1.ErrotoreaErdibitua_3.png
---
height: 260px
name: 1.ErrotoreaErdibitua_3
---
{ref}`EDiseinua1` erdibiturik erabiltzean errotorearen biraketa-abiaduraren neurketaren emaitzak, haize-makina distantzia desberdinetara jartzean (urdinez haize-makina 1.5m-ra jartzean lortutako datuak, gorriz 2m-ra, horiz 2.5m-ra eta berdez 3m-ra).
```
:::
:::{grid-item}
```{figure} ./Irudiak/Grafikak/1.ErrotoreaErdibituaKutxarekin_3.png
---
height: 260px
name: 1.ErrotoreaErdibituaKutxarekin_3
---
{ref}`EDiseinua1` erdibiturik eta estatore palen kutxa muntatuta duela erabiltzean errotorearen biraketa-abiaduraren neurketaren emaitzak, haize-makina distantzia desberdinetara jartzean (urdinez haize-makina 1.5m-ra jartzean lortutako datuak, gorriz 2m-ra, horiz 2.5m-ra eta berdez 3m-ra).
```
:::
::::


Behin erdibitutako errotorearen neurketak amaiturik, soilik metro erdiko bi palaz osatutakoa muntatu da. Kasu honetan, aurrekoarekin gertatu den moduan, distantzia txikienera, metro batera, haize-makina kokatzean errotoreak kolapsatu egiten du. Gainera, oraingo honetan, ez da zirkuitu elektrikoaren muga izan gainditu dena, baizik eta pala baten egitura izan da $700RPM$ inguruko abiaduran hautsi dena. Zehazki, takometroak egindako azkeneko neurketak $660.7RPM$-ko abiadura zuen, baina oso azkar hazten ari zenez, $700RPM$ inguruko abiadura batean kolapsatu duela suposatu da. Hau guztia esanik, aurreko kasuko distantzia berdinak erabiliko dira neurketak egiteko ondoko tentsioak neurtuz, estatore palen kutxarik gabe lehenengo eta, ondoren, kutxa muntatuta izanik.

::::{grid}
:gutter: 0

:::{grid-item}
```{figure} ./Irudiak/Grafikak/1.Errotorea_1.png
---
height: 260px
name: 1.Errotorea_1
---
{ref}`EDiseinua1` erabiltzean sorgailuak sortzen duen tentsioa, haize-makina distantzia desberdinetara jartzean (urdinez haize-makina 1.5m-ra jartzean lortutako datuak, gorriz 2m-ra, horiz 2.5m-ra eta berdez 3m-ra).
```
:::
:::{grid-item}
```{figure} ./Irudiak/Grafikak/1.Errotorea_2.png
---
height: 260px
name: 1.Errotorea_2
---
{ref}`EDiseinua1` erabiltzean sorgailu eolikoaren irteeran, USB portuan, neurtzen den tentsioa erregulatzailetik igaro ondoren, haize-makina distantzia desberdinetara jartzean (urdinez haize-makina 1.5m-ra jartzean lortutako datuak, gorriz 2m-ra, horiz 2.5m-ra eta berdez 3m-ra).
:::
::::

::::{grid}
:gutter: 0

:::{grid-item}
```{figure} ./Irudiak/Grafikak/1.ErrotoreaKutxarekin_1.png
---
height: 260px
name: 1.ErrotoreaKutxarekin_1
---
{ref}`EDiseinua1` estatore palen kutxa muntaturik duela erabiltzean sorgailuak sortzen duen tentsioa, haize-makina distantzia desberdinetara jartzean (urdinez haize-makina 1.5m-ra jartzean lortutako datuak, gorriz 2m-ra, horiz 2.5m-ra eta berdez 3m-ra).
```
:::
:::{grid-item}
```{figure} ./Irudiak/Grafikak/1.ErrotoreaKutxarekin_2.png
---
height: 260px
name: 1.ErrotoreaKutxarekin_2
---
{ref}`EDiseinua1` estatore palen kutxa muntaturik duela erabiltzean sorgailu eolikoaren irteeran, USB portuan, neurtzen den tentsioa erregulatzailetik igaro ondoren, haize-makina distantzia desberdinetara jartzean (urdinez haize-makina 1.5m-ra jartzean lortutako datuak, gorriz 2m-ra, horiz 2.5m-ra eta berdez 3m-ra).

```
:::
::::

Errotore mota honekin amaitzeko, aurreko neurketetan neurtutako erreboluzioen datuak ondorengoak dira:

::::{grid}
:gutter: 0

:::{grid-item}
```{figure} ./Irudiak/Grafikak/1.Errotorea_3.png
---
height: 260px
name: 1.Errotorea_3
---
{ref}`EDiseinua1` erabiltzean errotorearen biraketa-abiaduraren neurketaren emaitzak, haize-makina distantzia desberdinetara jartzean (urdinez haize-makina 1.5m-ra jartzean lortutako datuak, gorriz 2m-ra, horiz 2.5m-ra eta berdez 3m-ra).
```
:::
:::{grid-item}
```{figure} ./Irudiak/Grafikak/1.ErrotoreaKutxarekin_3.png
---
height: 260px
name: 1.ErrotoreaKutxarekin_3
---
{ref}`EDiseinua1` estatore palen kutxa muntatuta duela erabiltzean errotorearen biraketa-abiaduraren neurketaren emaitzak, haize-makina distantzia desberdinetara jartzean (urdinez haize-makina 1.5m-ra jartzean lortutako datuak, gorriz 2m-ra, horiz 2.5m-ra eta berdez 3m-ra).
```
:::
::::


### 2. Errotorea

Errotore mota honen kasuan aurreko mota aztertzean erabili diren 4 neurketa berdinak erabiliko dira. Haize-abiadura altueneko neurketak ez burutzearen arrazoia gainontzeko probetan neurtutako erreboluzioak aurreko motarekin lortutakoak baino handiagoak direla da eta, aurreko kasuan ikusi denez, $800RPM$ baino altuagoko abiadurek zirkuitu elektrikoa erre dezakete. Beraz, haize-makina 1m-ra jarritako probak ez dira burutu, 1.5m-ra jartzean, ondorengo grafikoetan erakutsiko den moduan, jada $800RPM$-ko mugara ia iristen delako errotorearen biraketa-abiadura. Aurreko errotore motarekin egin bezala, lehenengo errotorea erdibiturik dagoenean lorturiko neurketak egin dira, estatore kutxarik gabe eta hau muntaturik edukita.

::::{grid}
:gutter: 0

:::{grid-item}
```{figure} ./Irudiak/Grafikak/2.ErrotoreaErdibitua_1.png
---
height: 260px
name: 2.ErrotoreaErdibitua_1
---
{ref}`EDiseinua2` erdibiturik erabiltzean sorgailuak sortzen duen tentsioa, haize-makina distantzia desberdinetara jartzean (urdinez haize-makina 1.5m-ra jartzean lortutako datuak, gorriz 2m-ra, horiz 2.5m-ra eta berdez 3m-ra).
```
:::
:::{grid-item}
```{figure} ./Irudiak/Grafikak/2.ErrotoreaErdibitua_2.png
---
height: 260px
name: 2.ErrotoreaErdibitua_2
---
{ref}`EDiseinua2` erdibiturik erabiltzean sorgailu eolikoaren irteeran, USB portuan, neurtzen den tentsioa erregulatzailetik igaro ondoren, haize-makina distantzia desberdinetara jartzean (urdinez haize-makina 1.5m-ra jartzean lortutako datuak, gorriz 2m-ra, horiz 2.5m-ra eta berdez 3m-ra).
:::
::::

::::{grid}
:gutter: 0

:::{grid-item}
```{figure} ./Irudiak/Grafikak/2.ErrotoreaErdibituaKutxarekin_1.png
---
height: 260px
name: 2.ErrotoreaErdibituaKutxarekin_1
---
{ref}`EDiseinua2` erdibiturik eta estatore palen kutxa muntaturik duela erabiltzean sorgailuak sortzen duen tentsioa, haize-makina distantzia desberdinetara jartzean (urdinez haize-makina 1.5m-ra jartzean lortutako datuak, gorriz 2m-ra, horiz 2.5m-ra eta berdez 3m-ra).
```
:::
:::{grid-item}
```{figure} ./Irudiak/Grafikak/2.ErrotoreaErdibituaKutxarekin_2.png
---
height: 260px
name: 2.ErrotoreaErdibituaKutxarekin_2
---
{ref}`EDiseinua2` erdibiturik eta estatore palen kutxa muntaturik duela erabiltzean sorgailu eolikoaren irteeran, USB portuan, neurtzen den tentsioa erregulatzailetik igaro ondoren, haize-makina distantzia desberdinetara jartzean (urdinez haize-makina 1.5m-ra jartzean lortutako datuak, gorriz 2m-ra, horiz 2.5m-ra eta berdez 3m-ra).

```
:::
::::


Bestalde, aurreko grafikoetako datuekin bat datozen biraketa-abiadurak ondorengoak dira:

::::{grid}
:gutter: 0

:::{grid-item}
```{figure} ./Irudiak/Grafikak/2.ErrotoreaErdibitua_3.png
---
height: 260px
name: 2.ErrotoreaErdibitua_3
---
{ref}`EDiseinua2` erdibiturik erabiltzean errotorearen biraketa-abiaduraren neurketaren emaitzak, haize-makina distantzia desberdinetara jartzean (urdinez haize-makina 1.5m-ra jartzean lortutako datuak, gorriz 2m-ra, horiz 2.5m-ra eta berdez 3m-ra).
```
:::
:::{grid-item}
```{figure} ./Irudiak/Grafikak/2.ErrotoreaErdibituaKutxarekin_3.png
---
height: 260px
name: 2.ErrotoreaErdibituaKutxarekin_3
---
{ref}`EDiseinua2` erdibiturik eta estatore palen kutxa muntatuta duela erabiltzean errotorearen biraketa-abiaduraren neurketaren emaitzak, haize-makina distantzia desberdinetara jartzean (urdinez haize-makina 1.5m-ra jartzean lortutako datuak, gorriz 2m-ra, horiz 2.5m-ra eta berdez 3m-ra).
```
:::
::::


Aurreko motarekin egin den modu berean, erdibitutako errotorearen neurketak amaiturik, bi erdiak itsatsi dira eta errotore osoa eraiki da. Erdibituarekin egin den modu berean, errotorea kolapsatze puntura iristea ekiditeko neurketak aurreko kasuetan egin diren distantzia berdinetara burutuko dira. Ondorengoak dira neurtutako tentsioen datuak:

::::{grid}
:gutter: 0

:::{grid-item}
```{figure} ./Irudiak/Grafikak/2.Errotorea_1.png
---
height: 260px
name: 2.Errotorea_1
---
{ref}`EDiseinua2` erabiltzean sorgailuak sortzen duen tentsioa, haize-makina distantzia desberdinetara jartzean (urdinez haize-makina 1.5m-ra jartzean lortutako datuak, gorriz 2m-ra, horiz 2.5m-ra eta berdez 3m-ra).
```
:::
:::{grid-item}
```{figure} ./Irudiak/Grafikak/2.Errotorea_2.png
---
height: 260px
name: 2.Errotorea_2
---
{ref}`EDiseinua2` erabiltzean sorgailu eolikoaren irteeran, USB portuan, neurtzen den tentsioa erregulatzailetik igaro ondoren, haize-makina distantzia desberdinetara jartzean (urdinez haize-makina 1.5m-ra jartzean lortutako datuak, gorriz 2m-ra, horiz 2.5m-ra eta berdez 3m-ra).
:::
::::

::::{grid}
:gutter: 0

:::{grid-item}
```{figure} ./Irudiak/Grafikak/2.ErrotoreaKutxarekin_1.png
---
height: 260px
name: 2.ErrotoreaKutxarekin_1
---
{ref}`EDiseinua2` estatore palen kutxa muntaturik duela erabiltzean sorgailuak sortzen duen tentsioa, haize-makina distantzia desberdinetara jartzean (urdinez haize-makina 1.5m-ra jartzean lortutako datuak, gorriz 2m-ra, horiz 2.5m-ra eta berdez 3m-ra).
```
:::
:::{grid-item}
```{figure} ./Irudiak/Grafikak/2.ErrotoreaKutxarekin_2.png
---
height: 260px
name: 2.ErrotoreaKutxarekin_2
---
{ref}`EDiseinua2` estatore palen kutxa muntaturik duela erabiltzean sorgailu eolikoaren irteeran, USB portuan, neurtzen den tentsioa erregulatzailetik igaro ondoren, haize-makina distantzia desberdinetara jartzean (urdinez haize-makina 1.5m-ra jartzean lortutako datuak, gorriz 2m-ra, horiz 2.5m-ra eta berdez 3m-ra).

```
:::
::::

Kasu guztietan bezala, tentsioaren datuak jasotzen ziren bitartean neurtutako errotorearen erreboluzioak ondorengoak dira:

::::{grid}
:gutter: 0

:::{grid-item}
```{figure} ./Irudiak/Grafikak/2.Errotorea_3.png
---
height: 260px
name: 2.Errotorea_3
---
{ref}`EDiseinua2` erabiltzean errotorearen biraketa-abiaduraren neurketaren emaitzak, haize-makina distantzia desberdinetara jartzean (urdinez haize-makina 1.5m-ra jartzean lortutako datuak, gorriz 2m-ra, horiz 2.5m-ra eta berdez 3m-ra).
```
:::
:::{grid-item}
```{figure} ./Irudiak/Grafikak/2.ErrotoreaKutxarekin_3.png
---
height: 260px
name: 2.ErrotoreaKutxarekin_3
---
{ref}`EDiseinua2` estatore palen kutxa muntatuta duela erabiltzean errotorearen biraketa-abiaduraren neurketaren emaitzak, haize-makina distantzia desberdinetara jartzean (urdinez haize-makina 1.5m-ra jartzean lortutako datuak, gorriz 2m-ra, horiz 2.5m-ra eta berdez 3m-ra).
```
:::
::::


### 3. Errotorea

Aurreko bi kasuetan gertatu ez bezala, mota honetako errotoreen estatore palen kutxarik gabeko aldaerek ez dute nahikoa izan haize-makina 3m-ra kokatzean sortzen den haizea birarazten hasteko. Hau kontuan izanik eta beste kasuetan bezala gutxienez lau neurketa desberdin lortu nahi direnez, haize-makina aurretik aurkeztutako bost distantzietan kokatuz burutuko dira neurketak: 1m-ra, 1.5m-ra, 2m-ra, 2.5m-ra eta 3m-ra. Ondorengoak dira kutxarekin eta kutxarik gabe errotore erdibituarekin lorturiko datuak:

::::{grid}
:gutter: 0

:::{grid-item}
```{figure} ./Irudiak/Grafikak/3.ErrotoreaErdibitua_1.png
---
height: 260px
name: 3.ErrotoreaErdibitua_1
---
{ref}`EDiseinua3` erdibiturik erabiltzean sorgailuak sortzen duen tentsioa, haize-makina distantzia desberdinetara jartzean (urdinez haize-makina 1m-ra jartzean lortutako datuak, gorriz 1.5m-ra, horiz 2m-ra eta berdez 2.5m-ra).
```
:::
:::{grid-item}
```{figure} ./Irudiak/Grafikak/3.ErrotoreaErdibitua_2.png
---
height: 260px
name: 3.ErrotoreaErdibitua_2
---
{ref}`EDiseinua3` erdibiturik erabiltzean sorgailu eolikoaren irteeran, USB portuan, neurtzen den tentsioa erregulatzailetik igaro ondoren, haize-makina distantzia desberdinetara jartzean (urdinez haize-makina 1m-ra jartzean lortutako datuak, gorriz 1.5m-ra, horiz 2m-ra eta berdez 2.5m-ra).
:::
::::

::::{grid}
:gutter: 0

:::{grid-item}
```{figure} ./Irudiak/Grafikak/3.ErrotoreaErdibituaKutxarekin_1.png
---
height: 260px
name: 3.ErrotoreaErdibituaKutxarekin_1
---
{ref}`EDiseinua3` erdibiturik eta estatore palen kutxa muntaturik duela erabiltzean sorgailuak sortzen duen tentsioa, haize-makina distantzia desberdinetara jartzean (urdinez haize-makina 1m-ra jartzean lortutako datuak, gorriz 1.5m-ra, horiz 2m-ra, berdez 2.5m-ra eta granatez 3m-ra).
```
:::
:::{grid-item}
```{figure} ./Irudiak/Grafikak/3.ErrotoreaErdibituaKutxarekin_2.png
---
height: 260px
name: 3.ErrotoreaErdibituaKutxarekin_2
---
{ref}`EDiseinua3` erdibiturik eta estatore palen kutxa muntaturik duela erabiltzean sorgailu eolikoaren irteeran, USB portuan, neurtzen den tentsioa erregulatzailetik igaro ondoren, haize-makina distantzia desberdinetara jartzean (urdinez haize-makina 1m-ra jartzean lortutako datuak, gorriz 1.5m-ra, horiz 2m-ra, berdez 2.5m-ra eta granatez 3m-ra).

```
:::
::::


Tentsioen datuak aurkezturik, aurreko lau grafikoetako datuekin bat datozen erreboluzioen datuak ondorengoak dira. Kontuan izan kutxarik gabeko kasuan ez dela biraketa-abiadurarik antzeman, aurretik aipatu bezala.

::::{grid}
:gutter: 0

:::{grid-item}
```{figure} ./Irudiak/Grafikak/3.ErrotoreaErdibitua_3.png
---
height: 260px
name: 3.ErrotoreaErdibitua_3
---
{ref}`EDiseinua3` erdibiturik erabiltzean errotorearen biraketa-abiaduraren neurketaren emaitzak, haize-makina distantzia desberdinetara jartzean (urdinez haize-makina 1m-ra jartzean lortutako datuak, gorriz 1.5m-ra, horiz 2m-ra eta berdez 2.5m-ra).
```
:::
:::{grid-item}
```{figure} ./Irudiak/Grafikak/3.ErrotoreaErdibituaKutxarekin_3.png
---
height: 260px
name: 3.ErrotoreaErdibituaKutxarekin_3
---
{ref}`EDiseinua3` erdibiturik eta estatore palen kutxa muntatuta duela erabiltzean errotorearen biraketa-abiaduraren neurketaren emaitzak, haize-makina distantzia desberdinetara jartzean (urdinez haize-makina 1-ra jartzean lortutako datuak, gorriz 1.5m-ra, horiz 2m-ra, berdez 2.5m-ra eta granatez 3m-ra).
```
:::
::::


Erdibituarekin gertatu bezala, errotore osoarekin arazo berdina behatu da, haize-makina 3m-ra kokatzean sorturiko haizearen abiadura ez da nahikoa errotorea birarazten hasteko. Beraz, aurreko kasuan egin den bezala, gutxieneko neurketa kopurura iristeko bost distantziak erabiliko dira.

::::{grid}
:gutter: 0

:::{grid-item}
```{figure} ./Irudiak/Grafikak/3.Errotorea_1.png
---
height: 260px
name: 3.Errotorea_1
---
{ref}`EDiseinua3` erabiltzean sorgailuak sortzen duen tentsioa, haize-makina distantzia desberdinetara jartzean (urdinez haize-makina 1m-ra jartzean lortutako datuak, gorriz 1.5m-ra, horiz 2m-ra eta berdez 2.5m-ra).
```
:::
:::{grid-item}
```{figure} ./Irudiak/Grafikak/3.Errotorea_2.png
---
height: 260px
name: 3.Errotorea_2
---
{ref}`EDiseinua3` erabiltzean sorgailu eolikoaren irteeran, USB portuan, neurtzen den tentsioa erregulatzailetik igaro ondoren, haize-makina distantzia desberdinetara jartzean (urdinez haize-makina 1m-ra jartzean lortutako datuak, gorriz 1.5m-ra, horiz 2m-ra eta berdez 2.5m-ra).
:::
::::

::::{grid}
:gutter: 0

:::{grid-item}
```{figure} ./Irudiak/Grafikak/3.ErrotoreaKutxarekin_1.png
---
height: 260px
name: 3.ErrotoreaKutxarekin_1
---
{ref}`EDiseinua3` estatore palen kutxa muntaturik duela erabiltzean sorgailuak sortzen duen tentsioa, haize-makina distantzia desberdinetara jartzean (urdinez haize-makina 1m-ra jartzean lortutako datuak, gorriz 1.5m-ra, horiz 2m-ra, berdez 2.5m-ra eta granatez 3m-ra).
```
:::
:::{grid-item}
```{figure} ./Irudiak/Grafikak/3.ErrotoreaKutxarekin_2.png
---
height: 260px
name: 3.ErrotoreaKutxarekin_2
---
{ref}`EDiseinua3` estatore palen kutxa muntaturik duela erabiltzean sorgailu eolikoaren irteeran, USB portuan, neurtzen den tentsioa erregulatzailetik igaro ondoren, haize-makina distantzia desberdinetara jartzean (urdinez haize-makina 1m-ra jartzean lortutako datuak, gorriz 1.5m-ra, horiz 2m-ra, berdez 2.5m-ra eta granatez 3m-ra).
```
:::
::::

Emaitzen atalarekin amaitzeko, ondorengoak dira aurreko lau grafikoetako tentsioen neurketekin bat datozen erreboluzioak:

::::{grid}
:gutter: 0

:::{grid-item}
```{figure} ./Irudiak/Grafikak/3.Errotorea_3.png
---
height: 260px
name: 3.Errotorea_3
---
{ref}`EDiseinua3` erabiltzean errotorearen biraketa-abiaduraren neurketaren emaitzak, haize-makina distantzia desberdinetara jartzean (urdinez haize-makina 1m-ra jartzean lortutako datuak, gorriz 1.5m-ra, horiz 2m-ra eta berdez 2.5m-ra).
```
:::
:::{grid-item}
```{figure} ./Irudiak/Grafikak/3.ErrotoreaKutxarekin_3.png
---
height: 260px
name: 3.ErrotoreaKutxarekin_3
---
{ref}`EDiseinua3` estatore palen kutxa muntatuta duela erabiltzean errotorearen biraketa-abiaduraren neurketaren emaitzak, haize-makina distantzia desberdinetara jartzean (urdinez haize-makina 1m-ra jartzean lortutako datuak, gorriz 1.5m-ra, horiz 2m-ra, berdez 2.5m-ra eta granatez 3m-ra).
```
:::
::::

