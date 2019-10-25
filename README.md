# Hópverkefni 1

Í þessu verkefni erum við að nota Node.js til að keyra vefsíðuna. Við notum pakkastjóra Node sem heitir Npm. Hann sér um að sækja alla pakka sem við notum tengda vefsíðunni. [Npm](https://www.npmjs.com).

## Hvernig keyra á verkefnið

Til að setja upp verkefnið þarf að byrja á að afrita Github svæðið sem hýsir skrárnar á bak við síðuna. Fara skal inn á eftirfarandi hlekk [Hópverkefni 1](https://github.com/solveigasfr/Hopaverkefni1) og smella á græna hnappinn þar sem stendur *"clone or download"*. Síðan skal afrita hnappinn til að fá hlekkinn að GitHub verkefninu.

Ræsa skal síðan upp skelina í tölvunni *(Terminal/Bash)* og skrifa  


```bash
git clone https://github.com/solveigasfr/Hopaverkefni1.git
cd Hopaverkefni1
```

Nú er komið inn í verkefnið. Næst þarf að hlaða niður öllum skrám verkefnisins. Þá skal skrifa

```bash
npm install
```

Nú þegar búið er að sækja allar skrár verkefnisins þarf aðeins að keyra upp sjálft verkefnið. Þá skal skrifað

```bash
npm run dev
```

Nú ætti settur vafri á tölvunni að opna verkefnið á port 3000. [localhost:3000](http://localhost:3000)

## Uppsetning verkefnis

Verkefnið er sett upp í mismunandi skjölum:
* stylelintrc með upplýsingum um hvernig stylelint eigi að haga sér.
* gitattributes sem kemur í veg fyrir ósamræmi sem geta komið upp þegar unnið er á milli stýrikerfa.
* gitignore sem hunsar almennar skrár.
* editorconfig sem samræmir notkun á tabs og spaces, bilum og fleira.
* package.json sem hýsir viðeigandi pakka með tæki og tólum fyrir virkni verkefnisins.
* grid.css til að sjá grind sem verkefnið er unnið eftir.
* index.html skráin er forsíða verkefnisins og er hýst í rót þess. Hún vísar í styles.css og grid.css.
* Mappan pages geymir aðrar html skrár verkefnisins, products.html, staff.html, course.html og cart.html.
* styles.scss skrá sem hýsir allar grunn upplýsingar verkefnis og er tengd við aðrar scss skrár sem stjórna útliti verkefnis. 
* styles.css skrá sem er beintengd við styles.css. 
* Mappan scss sem geymir scss skrár sem allar hafa virkni sem stjórna útliti verkefnisins.
* Mappan img geymir allar myndir sem finna má í verkefninu.

## Þeir sem unnu verkefnið

* Sólveig Ásta Friðriðriksdóttir 
saf10@hi.is

* Ingimar Logi Guðlaugsson
ilg5@hi.is

* Helga Gunndís Þórhallsdóttir
hth179@hi.is

## Verkefnislýsing
Verkefnið felst í því að smíða vef eftir forskrift.

Gefnar eru fyrirmyndir í 500px, 800px og 1500px með grind ásamt 1500px án grindar og yfirliti yfir virkni vefs í utlit/video.mp4.

Gögn fyrir síður eru í viðeigandi textaskrám (t.d. forsida.txt) undir efni/. Myndir fyrir síður eru gefnar undir img/. Afrita þarf öll gögn á milli síðna, ekki er krafa um að setja upp sameiginlegan haus/fót á síðum með einhverju kerfi eða forritun.

Efni síðu skal ekki vera breiðara en 1200px. Litir í haus og fæti skulu fylla út í allt lárétt pláss.

Síður hafa allar sama haus og sama fót. Vöruflokkar í fæti skulu allir vísa á pages/products.html. Námskeið í fæti skulu vís á pages/course.html

Grunn leturstærð er 16px og fylgja allar aðrar leturgerðir eftirfarandi skala: 12 14 16 18 21 24 36 48 60.

Litapalletta fyrir vef er #000000, #fffcf2, #ff5000 og #00b7ff.

Letur fyrir meginmál er Open Sans eða helvetica, arial eða sans-serif letur. Letur fyrir fyrirsagnir er Oswald, Verdana eða serif letur.

Flest allt er sett upp í 12 dálka grind með 20px gutter.

Öll bil eru hálft, heilt, tvöfalt eða þrefalt margfeldi af gutter.

Allar hreyfingar gerast á 200ms með ease-in-out hröðunarfalli.

Ekki þarf að útfæra neina virkni fyrir takka eða form.

