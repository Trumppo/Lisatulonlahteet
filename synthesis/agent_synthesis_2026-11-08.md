# Kahden agenttitutkimuksen synteesi ja 500 €/kk -mahdollisuusmatriisi

**Päivä:** 8.11.2026  
**Tavoite:** Vähintään 500 €/kk alustakulujen jälkeen, ennen henkilökohtaisia tuloveroja. Aloitusbudjetti enintään 300 €; käynnistysvaiheen jälkeen mieluiten enintään 2–3 h/viikko ylläpitoa. Ei omaa verkkokauppaa eikä asiakaskohtaista konsultointia.

## 1. Yhteenveto

**Valinta ensimmäiseksi liiketoimintatestiksi: laitemallikohtaiset, käytännössä testatut korjaus-/varaosa-STL:t ja tarkat yhteensopivuusadapterit Etsyssä.** Tämä on *tuoteperhestrategia*, ei oletus yhden tiedoston 500 €/kk myynnistä. Toisena testinä tekniset, parametroidut työpajajigit STEP+STL-muodossa (Cults3D). Kolmantena, erillisenä hypoteesina Superhiven Blender-työnkulun mikrolisäosa, jos ensin löytyy maksuhalukkaiden Blender-käyttäjien toistuva ongelma.

Grok painottaa OpenSCADia, parametrisuutta ja vähäistä ylläpitoa; tutkimus-kansion raportti nostaa esiin todellisen maksullisen myyntinäytön (Superhive) ja mallikohtaisen korjauksen. Syntetisoitu päätöskriteeri on: **ostetaanko tätä, löytääkö ostaja tämän ilman omaa markkinointikonetta, ja paljonko tilauksia tarvitaan?** Ilmainen lataus ei ole ostos.

**Tärkein rajoitus:** nykyisen aineiston perusteella ei voida arvioida luotettavaa prosenttitodennäköisyyttä sille, että uusi toimija saavuttaa 500 €/kk. Alla oleva pisteytys on suhteellinen päätöksentekoindeksi, **ei empiirinen todennäköisyys**.

## 2. Pisteytysmalli

Kaikki kriteerit pisteytetään 1–5, suurempi on parempi.

| Kriteeri | Paino | Tarkoitus |
|---|---:|---|
| Maksullisen kysynnän näyttö | 25 % | Erottaa oikeat ostot ilmaisesta kiinnostuksesta |
| Orgaaninen löydettävyys alustalla | 25 % | Keskeinen, koska omaa verkkosivustoa tai laajaa yleisöä ei oleteta |
| Kate ja 500 €/kk myyntikynnys | 15 % | Hintataso, alustakulut ja tarvittavat ostot |
| Erottuvuus / AI-kestävyys | 10 % | Mitat, oikea laitetestaus, dokumentaatio, vaikea kopioitavuus |
| Ylläpidon keveys | 10 % | Päivitykset, reklamaatiot ja tukipyynnöt |
| Osaamisen soveltuvuus | 10 % | IT/tietoturva, OpenSCAD, 3D-tulostus, tekninen testaus |
| Käynnistämisen helppous | 5 % | Ensituotteen kehityspanos |

*Luottamusluokka* A = julkinen toteutunut maksullinen tuotemyynti; B = kaupallinen listaus, tuote-arvioita tai ostokäytöstä mutta ei määrää; C = ilmaiset lataukset/asennukset; D = hypoteesi. A-luokka **ei** tarkoita, että vastaava uusi tuote myisi hyvin. B/C tarkoittaa näyttösekoitusta. Pisteet eivät ole riippumattomia; herkkyysanalyysi pitää tehdä myöhemmin.

## 3. Yhdistetty ranking

| Sija | Tuoteryhmä | Piste / 5 | Näyttö | Ensisijainen kanava | Esimerkkihinta | Arvioitu kate/tilaus | Myyntiä 500 €/kk | Aloitus | Ylläpito/kk |
|---:|---|---:|---|---|---:|---:|---:|---:|---:|
| 1 | Mallikohtaiset korjaus- ja varaosa-STL:t, katalogi | 4,05 | B | Etsy | 12 € | 10,24 € | 49 | 60 h | 1 h |
| 2 | Tarkat työpajajigit ja -kiinnikkeet STEP+STL | 3,75 | B/C | Cults3D | 18 € | 14,40 € | 35 | 45 h | 1 h |
| 3 | Blenderin työnkulun mikrolisäosa | 3,63 | A (historiallinen) | Superhive | 24 € | noin 15,56 € | 33 | 80 h | 2,5 h |
| 4 | Home-lab-räkkien täsmäadapterit | 3,63 | B/C | Etsy | 14 € | 12,03 € | 42 | 45 h | 1 h |
| 5 | 3D-tulostimen mallikohtaiset modifikaatiot | 3,60 | B | Etsy | 12 € | 10,24 € | 49 | 40 h | 1,5 h |
| 6 | Kamera- ja sensoriadapterit, täsmämallit | 3,50 | B/C | Etsy | 14 € | 12,03 € | 42 | 40 h | 1 h |
| 7 | Elektroniikan PCB-jigit ja testatut kotelot | 3,45 | C | Cults3D | 18 € | 14,40 € | 35 | 45 h | 1 h |
| 8 | Home Assistant -paneelit ja automaatiot | 3,42 | B | Etsy | 25 € | 21,88 € | 23 | 35 h | 3 h |
| 9 | STEM/CAD-opetusaineistot | 3,30 | B | Teachers Pay Teachers | 12 € | 9,18 € | 55 | 50 h | 2 h |
| 10 | Pk-yrityksen tietoturvan perustason toolkit | 3,12 | B/D | Gumroad, suora | 39 € | 33,17 € | 16 | 40 h | 2 h |
| 11 | Modulaariset työkalujen säilytysjärjestelmät | 3,12 | C/B | Printables Store | 12 € | 8,95 € | 56 | 35 h | 1 h |
| 12 | Yleinen parametrinen OpenSCAD-generaattori | 3,08 | C | Printables Store | 10 € | 7,41 € | 68 | 30 h | 0,5 h |
| 13 | Blenderin tekniset asset-paketit | 3,05 | B | Fab | 29 € | 25,52 € | 20 | 50 h | 1,5 h |
| 14 | IT-ylläpidon automaatioskriptit ja runbookit | 2,98 | B/D | Gumroad, suora | 49 € | 41,88 € | 12 | 60 h | 3 h |
| 15 | Home Assistantin custom-integraatio | 2,55 | C | Gumroad, suora | 25 € | 20,97 € | 24 | 100 h | 6 h |

Hinnat, tunnit, pisteet ja myyntiluvut ovat **skenaario-oletuksia**, eivät toteutunutta uusien myyjien myyntiä. Myyntimäärä = pyöristä ylöspäin (500 € / arvioitu tilauskate). Mukana markkinapaikka- ja tavanomaiset maksunkäsittelykulut, mutta **ei** omaa työaikaa, mainontaa, valuuttakurssiriskiä, palautuksia, kiinteitä kustannuksia, ALV-kysymysten vaikutusta tai henkilökohtaisia tuloveroja. Superhive myy USD-hinnoilla, joten €-esimerkki on likimääräinen valuuttamalli.

## 4. Tutkimusten tietolaatuhavainnot

1. `research/`-tutkimuksen 30 havainnon otanta on pieni mutta jäljitettävämpi; se erottaa toteutuneet maksut, arviot ja ilmaiset lataukset. Grokin noin 50 havainnon listassa useita rivejä on luokkia, epämääräisiä proxyja tai linkittömiä esimerkkejä eikä yhtä vahvaa tuotetason todentamista.
2. **Superhive ei takaa 500 €/kk**: Drag & Drop Import on myynyt 2 300+ kappaletta **yli kolmen vuoden aikana**, ja tuotesivu ilmoittaa toiminnon siirtyneen Blenderiin natiiviksi. Asset Management 1 800+ on ollut tarjolla yli kymmenen vuotta. Blender Scenes Manager -lisäosalla on 10 myyntiä yli vuoden ajalta. Nämä havainnot näyttävät sekä mahdollisuuden että pitkän häntäpään riskin.
3. **Etsy-arvioiden sekaannus**: esimerkiksi Mirra 1 Headrest Adapter -STL:n yksittäisellä tuotesivulla näkyy noin 11 tuotearvostelua; noin 100 arvostelun luku koskee myyjäkauppaa. Kaupan historiallisia arvioita ei pidä kirjata tuotekohtaiseksi myynniksi.
4. **Printables Store vs Club**: Store ottaa ilmoitetusti 20 % sekä ulkoisen maksunkäsittelyn kulut; Clubilla on erilliset ehdot. Ilmaiset Printables-lataukset eivät todista maksuhalukkuutta.
5. Alkuperäisessä `research/`-materiaalissa Blenderin 24 € / tilaus nettolaskelma vaihtelee raportin (noin 13,5 €/tilaus, 38 ostoa) ja CSV:n (14,99 €, 34 ostoa) välillä. Tässä käytetään Superhiven omaa Free-tason kaavaa `(hinta − 5,5 % − 0,49 USD) × 70 %`. Suuntaa-antava €24-esimerkki tuottaa noin 15,56 €/tilaus ja 33 ostoa, jos USD-kiinteä kulu mallinnetaan noin €0,45:ksi. Valuuttakurssit ja mahdolliset lisäkulut voivat muuttaa lukua.
6. **Gumroad ei tarjoa Etsyyn rinnastettavaa orgaanista ostoliikennettä**: vahvan tietoturvaosaamisenkaan tuotteita ei löydetä automaattisesti. Direct ja Discover ovat eri tulokanavia, eri kuluilla.
7. Grokin kärkeen nostama yleinen OpenSCAD-generaattori nojaa enimmäkseen ilmaisten latausten kiinnostukseen. Se on **halpa testata**, mutta heikompi ensisijainen tulostrategia kuin tarkasti yhteensopivat tuotteet.

## 5. 500 €/kk -skenaariot

- **Yhden tuotteen skenaario:** €12 Etsy-STL tarvitsee noin 49 maksullista tilausta kuukaudessa. Tätä ei pidä olettaa uuden, kapean korjausosan normitasoksi.
- **Katalogiskenaario:** 15 tuotetta × 4 maksullista tilausta/tuote/kk × 10 € kate = **600 €/kk**. Tämä on tavoitetta havainnollistava herkkyyslaskelma, ei markkinadataan perustuva ennuste. Tuoteportfolion rakentaminen, testaus ja ylläpito muodostavat oman kertatyömääränsä.
- **Korkeamman hinnan skenaario:** 25 € Etsyssä myytävä Home Assistant -paketti vaatii noin 23 ostoa/kk, mutta merkittävästi enemmän yhteensopivuustukea.
- **Asiantuntijatuotteen skenaario:** 39 € tietoturvatyökalupakki Gumroadin suoramyynnissä vaatii noin 16 tilausta/kk. Sen pullonkaula on ensisijaisesti **asiakkaiden hankinta**, ei tuotteen tekninen rakentaminen.

## 6. Seuraavat kolme maksuhalukkuustestiä

**Testi A — ensisijainen (30–45 päivää).** Valitse rajattu laite- tai varaosaryhmä, josta on korjauskyselyitä, saatavuusongelma ja mitoitus/3D-tulostustestausmahdollisuus. Julkaise **3 oikeasti testattua tiedostoa** Etsyssä, käytä osanumeroita ja selkeitä mittakuviin perustuvia yhteensopivuustietoja. Jatka, jos kokonaisuutena vähintään 5 ostoa ja tukipyynnöt/palautukset pysyvät vähäisinä. Jos näkyvyyttä ei synny, arvioi otsikkoja/hakuja ennen kuin päätät kysynnän puuttuvan.

**Testi B — rinnakkainen pieni koe (30–45 päivää).** Tee yksi aidosti käyttökelpoinen parametrinen jigipaketti STEP+STL-muodossa Cultsiin. Mittaa maksetut ostot, ei vain ilmaisia latauksia. Rajallinen työbudjetti 20–35 h. Erityisesti tarkasta, löytyykö jo saman tehtävän ratkaiseva ilmainen malli.

**Testi C — varalla.** Blender-lisäosa vasta, kun käyttäjähaastattelut tai tehtävän omakohtainen käyttö osoittaa tietyn toistuvan tuskan. Korkeampi kehityskustannus ja Blender-versioiden ylläpitovaade edellyttävät parempaa ennakkonäyttöä.

**Päätössääntö:** 1–2 ostoa on heikko ensisignaali; 5+ ostoa pienestä testijoukosta on syy jatkotestata; 10–20 ostoa useammalta riippumattomalta asiakkaalta on parempi jatkoinvestoinnin peruste. Ei-käyntejä ja nollamyyntejä ei saa sekoittaa huonoon konversioon. Dokumentoi käynnit, tilaukset, palautukset, tuki, tuntimäärä sekä nettoraha.

Vältä turvallisuuskriittisiä 3D-varaosia sekä toisten suunnitelmien, tavaramerkkien ja käyttöoikeuksien loukkaamista. Yhteensopivuusmerkinnät on kirjoitettava täsmällisesti.

## 7. Lähteet

**Repositorion lähteet**
- [Tutkimus 1, raportti](../research/markkinatutkimusraportti.md)
- [Tutkimus 1, havainnot](../research/marketplace_product_observations.csv)
- [Tutkimus 1, scorecard](../research/top20_opportunity_scorecard.csv)
- [Tutkimus 1, kokeet](../research/three_demand_tests.csv)
- [Grokin raportti](../grok/market_research_report_2026.md)
- [Grokin scorecard](../grok/scoring_table_20_niches.csv)
- [Grokin havaintokanta](../grok/products_database_sample.csv)

**Tarkistetut ulkoiset esimerkit**
- [Superhive: Free/Pro-palkkiokaava](https://support.superhivemarket.com/article/32-how-commission-earnings-are-calculated)
- [Superhive: Drag & Drop Import](https://superhivemarket.com/products/drag-n-drop-import)
- [Superhive: Asset Management](https://superhivemarket.com/products/asset-management)
- [Superhive: Blender Scenes Manager](https://superhivemarket.com/products/blender-scenes-manager)
- [Etsy: Mirra 1 Headrest Adapter STL](https://www.etsy.com/listing/1247603710/herman-miller-mirra-1-headrest-adapter)
- [Etsy: Suomen maksunkäsittelykulut](https://help.etsy.com/hc/en-us/articles/115015628847-What-are-Payment-Processing-Fees-for-Selling-on-Etsy?segment=selling)
- [Prusa: Printables Store](https://blog.prusa3d.com/printables-store_87810/)
- [Gumroad: maksut](https://gumroad.com/help/article/66-gumroads-fees)

**Johtopäätöksen luottamus:** keskitasoinen suhteellisen kokeilujärjestyksen osalta, **matala** sille, että mikään yksittäinen testituote saavuttaisi 500 €/kk. Päivitä järjestys ensimmäisten maksullisten testien perusteella.
