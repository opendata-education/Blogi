
# Avoin data -työpaja

Datan määrä ja sen merkitys yhteiskunnalle kasvaa jatkuvasti. Suuria datasettejä käytetään alalla kuin alalla, ja netissä on useita paikkoja, joissa pääsy dataan on ilmaista. Eräs näistä sivuista on CERN, Euroopan hiukkasfysiikan tutkimuskeskus, jonka CMS-kokeesta on lähes 10 000 ilmaista datasettiä ilmaiseksi saatavilla. Pidimme työpajan siitä, kuinka lukio-opettajat voivat käyttää avointa dataa heidän tunneillaan. Työpaja oli osa CERNin International High School Teacher Programmea, jossa yli 40 opettajaa tutustuvat erilaisiin konsepteihin hiukkasfysiikassa ja opetuksessa.

Työpajan tavoitteena oli näyttää, kuinka helppoa oikean datan sisältäminen tehtäviin onkaan, ja miksi se on tärkeää. Alussa pidin esitelmän aiheesta, minkä jälkeen opettajat pääsivät harjoittelemaan koodaamista Jupyter Notebookeilla. Tämän jälkeen kävimme yhdessä läpi hieman vaikeamman esimerkin Higgsin bosonin löytymisestä. Kokonaisuudessaan työpaja kesti kaksi tuntia.

![](https://lh6.googleusercontent.com/mCS9D9hZZjMJ19tqKORG1KTaQKpUuwU5u7QRXg8B6tAdmiOSPhARPK7BUV8ymVdSoWuf28yHhUuHmYwJ_ukUw1uG_hj8omyyViFlmuf89pYTsLxHmeGk4jsJayWDL5vTbkItuJSHHwfKgvYYMJqWYUM)

  
### Mistä avoimessa datassa on kyse?
Miksi avoin data on hyödyllistä opetuksessa? Ensinnäkin se tarjoaa oppilaille autenttisen tilaisuuden kokea, kuinka tiedettä tehdään nykypäivänä. Toiseksi, sen avulla voi oppia hyödyllisiä taitoja, kuten ohjelmointi, data-analyysi ja kommunikointi. Nämä taidot varustavat oppilaat hyvin tulevaisuuden haasteita varten. Viimeiseksi, avoimen datan kanssa työskenteleminen auttaa erottamaan luotettavan informaation epäluotettavasta ja ohjaa oppilaita kehittämään heidän kykyä omatoimiseen tiedon rakentamiseen.

Käytämme tehtävissämme pohjana Jupyter notebookia. Jupyter notebookin avulla tekstiä, koodia, kuvia ja animaatioita voi vaivatta yhdistää samaan tiedostoon, ‘notebookiin’. Tämän ansiosta ohjeet ja tehtävät ovat kaikki samassa paikassa. Lisäksi oppilaiden tietokoneille ei tarvitse ladata mitään ohjelmia, sillä notebookeja voi avata ja editoida suoraan selaimessa. Näin säilyy aikaa ja vaivaa, ja itse tehtävien tekemiseen voi keskittyä paremmin.

### Työpajan kulku

Työpajassa käytiin läpi Jupyter notebookin perusteita: notebookin avaaminen selaimessa, solujen avaaminen ja editoiminen, Python-kirjastojen käyttö, datan hakeminen ja analysoiminen sekä kuvaajien piirtäminen. Oikean vaikeustason löytäminen oli haastavaa, sillä opettajien ohjelmointi- ja IT-taidot vaihtelivat paljon. Kaksi tuntia ei ole paljoa, jos ei ole aiemmin koodannut, mutta haluaa oppia, kuinka avointa dataa voi käyttää opetuksessa. Työpajan tavoitteena ei ollut opettaa ohjelmointia ohjelmoinnin vuoksi. Sen sijasta tavoitteena oli auttaa opettajia ymmärtämään tutkimuspohjaisten, dataan perustuvien tehtävien mahdollisuudet opetuksessa. Työpajan esimerkit olivat hiukkasfysiikasta, mutta fysiikka ei tietenkään ole ainoa aine, jossa dataa voi hyödyntää. Avoin data on aivan yhtä hyödyllistä myös muissa oppiaineissa, kuten biologiassa, maantieteessä ja yhteiskuntaopissa. 

![](https://lh6.googleusercontent.com/SOlmlL-y9RiDW-pdRs_JD3c3FAf-xWYtBmyz2uAG3BHAjHyAbBqF7quIahoYiQm1actmXsHP075E7xaK-nWH82xvQxzg3pjp7lD3HzBu9HUmynSaFP-1rdvn1-Yj4qPoXMMZkR5JANpJoyjPOr484ao)

### Autenttista oppimista

Tehtävän jälkeen kävimme läpi edistyneen esimerkin hiukkasfysiikasta. Käyttämällä CMS-kokeen dataa näytimme, kuinka Higgsin bosoni löydettiin kokeellisesti. Higgsin bosoni hajoaa hyvin nopeasti toisiksi hiukkasiksi, minkä vuoksi sitä ei voi havaita suoraan. Sen sijaan sen olemassaolo voidaan päätellä sen hajoamistuotteista. Standardimallin mukaan Higgsin bosoni voi muiden tapojen lisäksi hajota kahdeksi Z-bosoniksi, jotka puolestaan hajoavat neljäksi leptoniksi, kuten myoneiksi ja elektroneiksi. Mittaamalla näiden hajoamistuotteiden energiat ja liikemäärät, voidaan päätellä alkuperäisen hiukkasen massa. Tätä konseptia kutsutaan invariantiksi massaksi, ja sen avulla voidaan löytää uusia hiukkasia, kuten Higgsin bosonin. Käytännössä se tapahtuu simuloimalla erilaisia prosesseja, jotka tuottavat neljä leptonia. Kun ne piirretään samalle kuvaajalle kokeellisten tulosten kanssa, voimme nähdä, että simuloidut ja kokeelliset tulokset sopivat hyvin yhteen, jos oletetaan, että Higgsin bosonin massa on noin 125 GeV.

![](https://lh3.googleusercontent.com/DrfdphssGUen69jezkRQgOL9J0vZL5OIYHCLT1vCK7gZhR104o7Ibju1k-95rYlTJIcQeXaabZ7oWji1AklAlC0-z9bAGwk8n0SOVQCuMlLzTEHZcKrnX-cA0kWMbTvDmhb_eOerkKdFJbO_Cvld_CQ)

Esimerkin tavoitteena ei ollut saada opettajia ymmärtämään kaikkia Higgsin bosonin löytymiseen tarvittavan hiukkasfysiikan yksityiskohtia, eikä ohjelmoimaan syvällisesti. Sen sijaan tavoitteena oli antaa heille esimerkki tieteellisen metodin soveltamisesta oikeassa maailmassa. Tämän ajattelutavan sisällyttäminen opetukseen on tärkeää - lähestymistavassamme ohjelmointi on keino tieteen tekemiseen ja asioiden rakentamiseen, ei tavoite sinänsä. Ja hiukkasfysiikan monimutkaisiin yksityiskohtiin keskittymisen sijasta tavoitteena on ymmärtää tieteellisiin löytöihin kuuluvat haasteet.

Kaksi tuntia on lyhyt aika esittää avoimen datan mahdollisuudet opetuksessa, ja opettajien täytyi käsitellä paljon uutta tietoa. Palaute oli kuitenkin positiivista, ja moni opettaja oli valmis oppimaan lisää.

### Kirjoittajasta

Santeri Koivula opiskelee teknillistä fysiikkaa ja matematiikkaa Aalto-yliopistossa, pääaineenaan matematiikka ja systeemitieteet. Kesällä 2022 hän työskentelee kesäharjoittelijana Fysiikan tutkimuslaitoksella CERN:ssä. Työssään hän tekee materiaaleja ja pitää työpajoja tutkimuspohjaisen opetuksen sisällyttämiseksi luokkahuoneeseen. Vapaa-ajallaan Santerin voi löytää tanssimasta tai tekemästä vapaaehtoistöitä. 

<img src="../../kuvat/SanteriK_final.jpg" alt="Kuva Santerista">
