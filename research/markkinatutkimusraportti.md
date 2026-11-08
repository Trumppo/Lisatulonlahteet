# Digitaalisten markkinapaikkojen kysyntä- ja mahdollisuustutkimus

**Tarkasteluhetki:** 8.11.2026. **Maantiede:** Suomessa asuva yksinyrittäjä, globaali digitaalinen myynti.

## Tiivistelmä

Julkisesti todennettavaa maksullista menestystä löytyi selvästi parhaiten **Superhivesta** (entinen Blender Market): alusta julkaisee kokonaismyyntimäärän ja osa tuotesivuista myös tuotekohtaiset myyntiluokat. Yksittäisistä työkaluista esimerkiksi Drag & Drop Import ilmoittaa 2 300+ myyntiä ja Asset Management 1 800+ myyntiä; markkinapaikka kertoo 5,78 miljoonasta myydystä tuotteesta ja 53,4 miljoonan dollarin tekijätilityksistä. Tämä on harvinainen A-luokan markkinasignaali, mutta ei lupaus uuden tuotteen menestyksestä. genui{"citation":{"refs":["turn3search10","turn3search11","turn6search0"]}}

Etsyssä näkyy ostajien arvosteluja, kauppojen myyntimääriä ja maksettuja digitaalisia tuotteita, mutta tuotekohtaiset myynnit eivät yleensä ole julkisia. Paljon arvosteluja saanut mallikohtainen korjaustiedosto tai fyysinen varaosa todistaa ostokäyttäytymisestä, mutta arvostelujen lukumäärä ei ole myyntimäärä. Digitaalisten korjaus-STL:ien, Home Assistant -pakettien ja mallikohtaisten adapterien kysyntä on siksi B-luokan näyttöä. genui{"citation":{"refs":["turn6search3","turn6search5","turn7view10","turn7view14"]}}

**Johtopäätös:** en löydä riittävää julkista näyttöä, jonka perusteella 500 €/kk olisi todennäköinen lähtötilanne. Jos valitsisin yhden testattavan tuoteryhmän, aloittaisin Superhivessä pienellä Blender-työnkulkulisäosalla, koska alusta paljastaa todellisia myyntimääriä ja tarjoaa jo ostavan työkalukäyttäjäkunnan. En kuitenkaan käyttäisi 300 € budjettia enkä tekisi pitkää tuotekehitystä ennen maksullista testiä. Ensimmäinen tuote olisi pieni, rajattu Blender-lisäosa, joka ratkaisee yhden toistuvan tiedoston/assetin järjestelytyövaiheen ja sisältää testimatriisin Blender-versioille.

## Menetelmä ja aineiston rajat

- Tarkistin ensisijaisesti alustojen omia hinnoittelu-, ohje- ja tuotesivuja sekä varsinaisia listauksia. Havaintopäivä kaikissa aineistoriveissä on 8.11.2026.
- Tuotetietokantaan saatiin **30 todellista tuote- tai ekosysteemihavaintoa** (10 Superhive, 15 Etsy, 1 Creative Market, 1 Fab, 1 Printables, 1 Obsidian ja 1 Home Assistant). Näistä 10 on Superhiven julkisesti raportoitavia myyntilukuja, 15 Etsy-listauksia/tuotteita ja loput ekosysteemiesimerkkejä. Tuotteita ei keksitty.
- 300–500 tuotteen tavoite **ei täyttynyt**. Alustojen monilla osilla ei ole julkista tuotekohtaista ostodataa eikä yhtenäistä luvallista API:a; hakukoneen tuotekortit eivät anna kaikkia vaadittuja sarakkeita, ja osa sivuista palauttaa osittaista tai kirjautumista vaativaa sisältöä. Aineistoa ei kasvatettu arvaamalla tai luvattomalla keruulla. CSV on päivitettävä osanäyte, ei kattava tuotetietokanta.
- Markkina-arviot eivät muunna latauksia liikevaihdoksi. A = julkinen tuotekohtainen maksullinen myyntiluku; B = maksullisia tuotteita ja arvostelu-/kauppasignaalia, myyntimäärä ei tiedossa; C = ilmainen lataus/käyttö-/kiinnostussignaali; D = hypoteesi.
- Kilpailijoiden määrää ei ilmoiteta tarkkana lukuna, ellei luotettavaa lukua ole nähtävissä. Hakuosumien määrä ei ole kelvollinen markkina-arvio.

## Markkinapaikkojen vertailu

| Alusta | Julkinen toteutunut myyntidata | Näkyvät signaalit | API / keruu | Keskeiset kulut ja soveltuvuus |
|---|---|---|---|---|
| Printables | Ei yleisesti maksullisten tuotekohtaisten myyntien lukuja. | Ilmaisten mallien latauksia, tykkäyksiä, arvioita ja käyttäjien toteutuksia; nämä eivät todista maksuhalukkuutta. | Prusan käyttöehdot kuvaavat yhteisöpalvelun. Löytynyt API-tarjonta on kolmannen osapuolen, ei virallinen mallitietokannan API. | Maksullinen Club: 10 % Prusalle + Stripe; ehtoesimerkissä Stripe 2,9 % + $0,30. Clubiin pääsy vaatii hyväksynnän. Vahva ilmaiselle yleisön rakentamiselle, heikko myynnin mittaamiseen. genui{"citation":{"refs":["turn4view7","turn6search9","turn6search10"]}} |
| Cults3D | Tuotekohtainen myyntimäärä ei tavallisesti näy. | Ilmaiset/maksulliset mallit, arvostelut ja yhteisötoiminnot. | Virallista julkista tuoteluettelon API:a ei löytynyt tässä haussa; käytä manuaalista julkista tarkastelua. | Tekijälle 80 % myynnistä; alusta ilmoittaa 20 % komission sisältävän maksuliikennekuluja. Suora STL/CAD/DXF-jakelu. genui{"citation":{"ref":"turn0search4"}} |
| MakerWorld | Julkinen mallikohtainen käteismyynti ei ole yleisesti saatavilla; palkkio-ohjelmat vaihtelevat. | Tulosteet, lataukset, tykkäykset ja boostit; osa pisteistä sidottu ohjelmiin/ehtoihin. | Ei löytynyt vakaata julkista myynti-API:a. | Creator-ohjelman rahallisuus ja kelpoisuus on ohjelmakohtaista; pisteitä ei pidä rinnastaa myyntiin. Sopii näkyvyyteen ja ilmaiseen jakeluun. genui{"citation":{"refs":["turn1search8","turn1search17","turn1search25"]}} |
| MyMiniFactory | Creator näkee oman raporttinsa; julkinen yksittäisen tuotteen ostoluku ei ole yleinen. | Arviot/kommentit ja mallien sisältö. | Julkinen kaupallinen bulkki-API ei tullut esiin. | Creator-taso 15/12,5/10 % + käsittelykulut 3,49 % + $0,49 yli $3 maksuista. Digitaalinen jakelu. genui{"citation":{"ref":"turn4view4"}} |
| Thangs | Julkiset yksittäismyynnit eivät ole yleisiä. | Maksulliset jäsenyydet, kertaostot ja bundle-tilaus. | Ei vahvistettua julkista myynti-API:a. | Monipuolinen maker-jakelu, mutta tässä tutkimuksessa myyntikulujen tarkka malli ei varmistunut. genui{"citation":{"ref":"turn0search41"}} |
| Etsy | Kaupan kokonaismyynti julkinen; listauksen tilaus/tuotto näkyy vain myyjälle. | Hinta, digitaalisuus, arvostelut, suosikit; arvostelu ei ole suora myyntimäärä. | Myyjän oma Stats-näkymä sisältää listauskohtaiset tilaukset ja tuoton; julkinen API ei ole tarpeen automaattisessa toimituksessa. | $0,20 listaus, 6,5 % tapahtuma + Suomessa 4 % + €0,30 käsittely; valinnainen offsite ads 12–15 %. Suomi mukana Etsy Paymentsissa; digitaalisten tuotteiden toimitus automaattinen. genui{"citation":{"refs":["turn4view1","turn4view2","turn6search3","turn6search4","turn5search9"]}} |
| Gumroad | Markkinapaikkamyyntejä ei yleisesti näytetä julkisesti. | Tuotteen hinnat, arviot tietyissä tuotteissa. | Creatorin oma myyntidata. | Suora myynti 10 % + $0,50; Discover 30 %. Gumroad toimii merchant of record -mallilla ja hoitaa kuluttajamyynnin välilliset verot maailmanlaajuisesti. genui{"citation":{"ref":"turn4view6"}} |
| Superhive (Blender Market) | Kyllä: osa tuotesivuista näyttää kumulatiivisen myyntimäärän, markkinapaikka näyttää kokonaisluvut. | Myynnit ja arvostelut tuotetasolla, sorttaus “Most Sales”. | Tekijä näkee Sales/Earnings/Product Events raportit ja voi viedä dataa; julkista yleis-API:a ei varmistettu. | Maksuton: tekijälle 70 %, lisäksi 5,5 % kauppiasmaksu ja $0,49 per kohde; Pro $49/kk, 80 %; Ultimate $199/kk, 90 %. Alkuun maksuton suunnitelma. genui{"citation":{"refs":["turn4view0","turn6search0","turn6search1","turn3search0"]}} |
| Fab | Yksittäislistauksen myynti ei yleensä näy. | Arvostelut/hinnat, kategoriasijoitukset. | Creator-dashboardissa omat analytiikat; julkista myynti-API:a ei varmistettu. | 88 % revenue share; automaattinen digitaalinen toimitus. Käyttäjäkunnan painotus pelisisältöihin ja 3D-assetien käyttäjiin. genui{"citation":{"ref":"turn5search0"}} |
| Creative Market | Joissakin julkisissa tuotekorteissa näkyy toteutuneita myyntikertymiä; myyjä näkee tarkemmat raportit/CSV:n. | Hinta, arvostelut, myyntimäärä. | Myyjän oma CSV-vienti. | Komissio ei tässä tarkastelussa varmistunut luotettavasta ensisijaislähteestä; tarkista ennen myyjätilin avaamista. Automaattinen digitaalinen jakelu. genui{"citation":{"refs":["turn3search50","turn6search2"]}} |
| Teachers Pay Teachers | Myyjälle oma raportti; julkinen tuotekohtainen myyntimäärä ei ole tavallinen. | Arviot, hinnat, bestseller/kategoriahaut. | Oma myyjätili/raportointi. | Basic $29 kertamaksu, 55 % tilitys ja $0,30/resource; Exclusive 77,5 %, alle $3 tilauksista $0,15/resource. Maksut kuukausittain. Opetusmateriaalille vahva alusta, mutta standardien ja opettaja-audience-osaamisen vaatimus. genui{"citation":{"ref":"turn4view8"}} |
| Obsidian-ekosysteemi | Ei ostomääriä; plugin-lataustilastot ovat julkisia GitHub-pohjaisia. | Yhteisöpluginien lataukset ja viimeisimmät julkaisut. | Koneellisesti saatavilla, mutta lataukset eivät ole maksavia käyttäjiä. | Yleensä ilmainen plugin-jakelu; maksu pitää tuotteistaa erikseen esim. Gumroadissa. genui{"citation":{"ref":"turn1search4"}} |
| Home Assistant | Ei ostomääriä; viralliset ja yhteisön käyttötelemetriat tarjoavat käyttö-/asennusmittareita. | Julkinen analytics JSON custom-integrationien käytöstä; käyttö ei ole ostoa. | Virallinen aggregaattidata ja integraatiohakemisto. | Maksullinen paketti voidaan myydä Etsy/Gumroadissa, mutta tuen ja versioyhteensopivuuden ylläpito on merkittävä. genui{"citation":{"ref":"turn6search6"}} |

## Mitä aineistossa ostetaan ja mitä vain ladataan?

- **Ostoksi todennettu:** Superhiven tuotesivuilla on suorat myyntiluvut, Creative Market -esimerkissä 2 064 myyntiä. Näitä voi käyttää näyttönä siitä, että ostajat maksavat Blender-työnkulkujen ja template-tuotteiden ratkaisuista. Ne eivät kerro uuden kilpailijan konversiosta tai nykyisestä myyntivauhdista. genui{"citation":{"refs":["turn3search10","turn3search11","turn3search50"]}}
- **Etsy-arvostelut:** havaituissa korjaus-STL- ja adapterilistauksissa on kymmeniä tai satoja arvosteluja, ja yksittäisille digitaalitiedostoille näkyy hintapisteitä noin €2–€12. Tämä todistaa ostotapahtumista ja toimitetuista tuotteista, mutta ei item-kohtaista myyntimäärää. Bundlejen alle €5 hinnat kertovat kovasta hintapaineesta. genui{"citation":{"refs":["turn7view10","turn7view11","turn7view12"]}}
- **Lataukset eivät ole myyntiä:** Printablesin 3D Benchy -mallin 592 413 latausta, 9 115 toteutusta ja 4 183 arviota koskeva esimerkki on ilmainen. Se mittaa yhteisön kiinnostusta ja käyttöä, ei maksuhalukkuutta. API.SH:n data on kolmannen osapuolen rajapinnasta, ei Prusan virallinen data-API. genui{"citation":{"ref":"turn1search29"}}
- **AI ei poista luotettavuuden arvoa:** markkinoilla on jo AI-avusteisia Home Assistant -paketteja, joiden myyjä kertoo testanneensa tuotteen oikeassa HA-asennuksessa. Tekoäly voi nopeuttaa koodia ja dokumentaatiota; ostaja maksaa ennen kaikkea testatuista versioista, selkeästä yhteensopivuudesta, päivityksistä ja käytön helppoudesta. genui{"citation":{"ref":"turn7view13"}}

## Kilpailu ja AI-vaikutus

Ylikilpailluimmat ovat geneeriset STL-koristeet, fan art -mallit, jättipaketit (“1 000+ STL”) ja Canva-printables. Halvat, runsaat AI-generoidut tiedostopaketit laskevat hintoja; fan art tuo lisäksi tekijänoikeus- ja tavaramerkkiriskiä. Yksi havaittu geneerinen bundle oli alennuksessa noin $2, toinen noin $5, mikä tekee 500 € tulostavoitteesta volyymipelin.

Parempi puolustus syntyy tarkasta yhteensopivuudesta, testistä oikealla laitteella, materiaalin/mittojen dokumentaatiosta, versioiduista tiedostoista sekä ratkaistusta yksittäisestä ongelmasta. Näitä ominaisuuksia AI ei tuota luotettavasti ilman fyysistä testausta ja ihmisen vastuuta. Tuotteen kestävyys on vahvimmillaan korjaus-, yhteensopivuus- ja työkalutuotteissa; heikoimmillaan trendeihin tai fan artiin nojaavissa malleissa.

## 20 lupaavaa markkinarakoa

Täydellinen pistetaulukko laskentaoletuksineen on tiedostossa `top20_opportunity_scorecard.csv`. Alla tulos on järjestetty painotetulla pistemäärällä; pisteet ovat päätöksenteon työkalu, eivät empiirinen todennäköisyys. Jokaisessa kriteerissä 5 tarkoittaa suotuisaa tilannetta (kilpailupisteessä vähäisempää kilpailupainetta). Scorecard sisältää jokaiselle mahdollisuudelle kriteerikohtaisen lyhyen perustelun. Kysynnän paino on 25 %, vähäisen jatkuvan työn 20 % ja 500 €/kk realistisuuden 20 %.

| Sija | Markkinarako | Alusta | Näyttö | Pisteet / 5 |
|---:|---|---|---|---:|
| 1 | Model-specific functional replacement STL files (obsolete clips, knobs, brackets) | Etsy | B | 3.67 |
| 2 | Blender workflow add-on for repetitive file/import/asset management | Superhive | A | 3.63 |
| 3 | Parametric workshop jigs/fixtures, editable STEP+STL files | Cults | B | 3.57 |
| 4 | Appliance repair STL catalog organized by exact model/part number | Etsy | B | 3.52 |
| 5 | Blender add-on that exports clean manufacturable geometry/part documentation | Superhive | A | 3.43 |
| 6 | Model-specific 3D printer upgrade/fitment kits (file packs) | Etsy | B | 3.37 |
| 7 | CNC/laser-cut machine-specific jigs and dust shoe adapters (DXF/STEP) | Etsy | B | 3.37 |
| 8 | Camera/audio accessory mounts and adapters with tested dimensions | Etsy | B | 3.37 |
| 9 | Home-lab rack/cable-management exact-fit CAD files | Etsy | B | 3.32 |
| 10 | Home Assistant tested dashboard + automation packs for defined household setups | Etsy | B | 3.27 |
| 11 | Small-business security baseline toolkit (editable assets, checklists, scripts) | Gumroad direct | B | 3.27 |
| 12 | Sim-racing rig mounts/adapters matched to named wheel/pedal ecosystem | Cults | B | 3.27 |
| 13 | Localized teacher STEM/CAD activity packs with printable files | TPT | B | 3.23 |
| 14 | Accessibility and adaptive device fixtures (non-medical, tested print files) | Etsy | C | 3.12 |
| 15 | IT admin incident-response automation scripts and tested runbooks | Gumroad direct | B | 3.02 |
| 16 | Parametric household organizer generator (OpenSCAD/customizer files) | Cults | C | 2.95 |
| 17 | Blender technical visualization asset packs (non-branded, reusable) | Fab | B | 2.86 |
| 18 | Obsidian security/IT operations vault templates with sample workflows | Gumroad direct | C | 2.67 |
| 19 | Original tabletop terrain/utility assets with commercial license | MyMiniFactory | B | 2.48 |
| 20 | Home Assistant custom integration for underserved local device/protocol | Gumroad direct | C | 2.40 |


Pisteytyksessä Superhive-työkalujen kysyntäpiste on korkein, mutta kilpailu- ja aloitusvaikeuspiste matala. Etsy-korjaus-STL:ien kilpailutilanne saa paremman pisteen vain, jos valitaan tarkka, vähän käsitelty laitemalli; geneerisissä STL-bundleissa kilpailupiste olisi 1/5. Alhainen ylläpito ei tarkoita passiivista: listauksen näkyvyys, yhteensopivuuskysymykset, virhekorjaukset ja alustamuutokset vaativat työtä.

### Talousmalli ja skenaariot

Laskelman “kate” on arvio myyntihinnasta vähennettynä alustan ilmoitetuilla transaktio-/käsittelykuluilla; se **ei** vähennä omaa työaikaa, tuloveroa, mainoksia, kirjanpitoa, palautuksia, valuutanvaihtoa eikä mahdollisia maksuja/muita kiinteitä kuluja. Etsy-mallissa käytetään 6,5 % + Suomen 4 % + €0,30 käsittelyä ja €0,20 listausmaksua per myynti. Superhiven maksuton tili: 70 % tilitys miinus 5,5 % kauppiasmaksu ja $0,49 transaktiomaksu; mallihinta €24 on vain esimerkkimuunnos, todellinen hinnoittelu on USD. Cults 80 %; Gumroad suoramyynti 10 % + $0,50; Fab 88 %; TPT Exclusive 77,5 % ja pienissä tilauksissa $0,15. MMF-mallissa sovellettiin 15 % alustan osuutta ja käsittelykuluja. Valuuttamuunnokset on pyöristetty suunnittelua varten.

**Esimerkki O02, Blender workflow -lisäosa:** oletushinta €24 vastaava, arvioitu nettopanos noin €13,5/kauppa, joten noin 38 myyntiä/kk tuottaa €500 alustakulujen jälkeistä katetta ja 75 myyntiä/kk €1 000. Superhiven dokumentoima keskimääräinen tuotekohtainen konversio on 4–5 %, joten 38 myyntiä vaatisi noin 760–950 tuotesivun katselua/kk tällä oletuksella; uuden tuotteen katselumäärää ei tunneta. Tämä on herkkyyslaskelma, ei ennuste. genui{"citation":{"ref":"turn6search1"}}

| Skenaario | Oletus | Esimerkkitulos |
|---|---|---|
| Heikko | Ei löydy tuotteen ja ongelman osumaa / listaus ei saa näkyvyyttä. | 0–5 myyntiä/kk; alle €70 alustakulujen jälkeistä katetta lisäosalle. |
| Perus | Rajattu tuote löytää pienen orgaanisen kohderyhmän. | 8–20 lisäosamyyntiä/kk; noin €108–€270 ennen muita yrityskuluja. Todennäköisyyttä ei voida johtaa julkisesta datasta. |
| Vahva | 38+ kauppaa/kk, 4–5 % oletuskonversiolla 760–950 käyntiä/kk. | Noin €500/kk alustakulujen jälkeen ennen kaikkia muita kuluja. Ei odotusarvo, vaan tavoiteskenaario. |

Kaikkien 20 tuoteryhmän netto/kauppa ja tarvittavat myyntimäärät ovat scorecard-CSV:ssä. Yrityksen tulos ja henkilökohtainen nettotulo ovat eri asioita: henkilökohtainen nettotulo riippuu yritysmuodosta, muista ansiotuloista, vähennyksistä ja verotuksesta. Suomessa vähäisen toiminnan ALV-rekisteröinnin raja on €20 000 kalenterivuodessa; ulkomaan kuluttajamyynnin arvonlisävero ja merchant-of-record-alustojen rooli on tarkistettava erikseen. Tulot digitaalisilta alustoilta pitää ilmoittaa verotuksessa. genui{"citation":{"refs":["turn5search5","turn5search28","turn5search34"]}}

## Viisi parasta toteutettavaa mahdollisuutta

1. **Blenderin rajattu workflow-lisäosa Superhiveen (A):** markkinapaikan paid-sales-data tekee kysyntätestistä poikkeuksellisen mitattavan. Aloita ilmaisella tasolla. Älä kehitä laajaa yleislisäosaa, vaan poista yksi toistuva kitka ja testaa käyttötapa.
2. **Mallikohtaiset korjaus-STL:t Etsyyn (B):** esimerkiksi tietyn työkalun tai laitteen varaosan tiedosto, jossa yhteensopivuus perustuu fyysiseen mitoitukseen. Kilpailu hajaantuu laitekohtaisiin hakuihin; myyntimäärä on silti testattava.
3. **Testatut Home Assistant -paketit (B):** ostajat maksavat valmiista dashboardista/automaatioista, mutta HA-versio- ja integraatiomuutokset voivat kasvattaa ylläpitotyötä. Rajaa tuki versioihin ja pidä kaikki ilman yksilökonfigurointia.
4. **Parametriset CNC/3D-työpajajigit (B/C):** tekninen tarkkuus ja STEP/DXF-lähdetiedostot erottavat AI:n nopeasti generoimasta yleismallista. Myyntiluvut heikosti näkyvissä.
5. **IT-/tietoturva-automaatiopaketit (B):** toteuttajan asiantuntemus tuo sisältöön laatua, mutta luottamus ja päivitystarve ovat korkeita. Myy vain kapeita, itsenäisesti käytettäviä työkaluja; vältä jatkuvan palvelun lupausta.

## Kolme maksuhalukkuustestiä

Täydet testiaskeleet ovat `three_demand_tests.csv`-tiedostossa. Kaikissa raja €50 alittuu. Testin onnistuminen tarkoittaa maksettua ostosta, ei katseluja, tykkäyksiä tai sähköpostilistalle liittymisiä.

1. Blender workflow -lisäosa: demoversio + maksullinen rajattu upgrade Superhivessä; jatka vain 10 maksullisen päivityksen tai vastaavan sitovan ennakkotilauksen jälkeen.
2. Täsmällisen laitemallin korjaus-STL-perhe: kolme erilaista yhteensopivaa tiedostoa; jatka, jos 30 päivässä tulee yhteensä ≥5 ostoa ja fit-tukipyyntöjä/palautuksia on <10 %.
3. Home Assistant -paketti: versioitu dashboard+automaatiot Etsyssä; jatka ≥5 ostolla, vähintään 4,5/5 keskiarvolla kun 10 arvostelua kertyy ja mediaanituki alle 10 min/tilaus.

## Monikanavajakelu ja saman tuotteen vertailu

Tämän tutkimuksen havaintojoukossa ei löytynyt luotettavasti varmennettua samaa tiedostoa kahdella alustalla, jossa tuoteidentiteetti ja käyttöoikeus olisi vahvistettu. En väitä samankaltaisia nimiä samoiksi tuotteiksi. Monikanavajakelu on järkevää vasta, kun yksi kanava konvertoi: Etsy tuo ostohakuja, Cults maker-yleisöä, Superhive näyttää Blender-ostojen toteutuneita myyntiluokkia ja Gumroad toimii suoramyynnissä mutta edellyttää yleensä oman liikenteen hankkimista. Listaus- ja asiakastuen lisätyö voi syödä pienen katteen.

## Suositus ja luottamus

**Valinta:** testaisin ensin Superhiveen Blender-työnkulun pientä lisäosaa, esimerkiksi lisäosien ryhmäasetuksen viennin/tuonnin ja versiokohtaisen tarkistuksen kaltaista tiimien toistuvaa hallintatyötä. Täsmällinen tuote pitää validoida ennen rakentamista: Superhivessä Addon Controllerin sivu näyttää tiimikonfiguraatioiden vienti-/palautusprosessin, 20+ myyntiä ja $7.50 alennushinnan; tämä on ongelmaa ja maksavaa tuotetta osoittava esimerkki, mutta ei todiste siitä, että oma vastaava tuote myisi. genui{"citation":{"ref":"turn7view5"}}

Laskelmassa €24 hinnalla ja noin €13,5 arvioidulla katteella tarvitaan noin 38 myyntiä/kk €500:aan. Mallin rakentaminen voi viedä 80 tuntia ja ylläpito 1–2 h/kk plus markkinointi; aloitusbudjetti riittää, mutta kahden–kolmen tunnin viikkoraja jättää uuden tuotteen lanseerauksen näkyvyystyölle vähän tilaa. Käynnistysvaiheessa tarvittava kertainvestointi on todennäköisesti suurempi kuin käyttäjän rajattu viikkotyö sallii, ellei työtä tehdä rauhallisesti useamman kuukauden aikana.

**Luottamustaso: keskitasoinen alustojen kuluihin ja näkyvissä oleviin A-esimerkkeihin; matala markkinarakojen myyntipotentiaaliin ja 500 €/kk saavuttamisen todennäköisyyteen.** Aineisto tukee maksavan Blender-työkalumarkkinan olemassaoloa, ei yksittäisen uuden tuotteen kannattavuutta. Siksi lopullinen toimintasuositus on testata maksuhalukkuus ennen varsinaista tuotekehitystä.

## Lähteiden tarkistuslista

Kaikkien tuotehavaintojen URL:t ja näkyvät kentät ovat `marketplace_product_observations.csv`-tiedostossa. Keskeiset ensisijaiset lähteet: Superhiven hinnoittelu ja markkinatilastot; Etsy-maksut ja myyjien/listausten tilastot; MyMiniFactory-kulut; Prusan Printables Club -ehdot; Gumroad-kulut; TPT-myyjäkulut; Verohallinnon ALV-raja; Home Assistantin julkiset analytics-dataohjeet.
