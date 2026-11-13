# Menetelmä: Micro-Niche Opportunity Discovery

**Tarkasteluhetki:** 13.11.2026. **Tavoite:** tunnistaa käyttäjien ja välittäjien raportoimia ratkaisemattomia ongelmia; ei päätellä kysyntää markkinapaikan suosiosta.

## Toteutus

1. Aiemmat tutkimukset käytiin läpi repositorion `research/`, `grok/` ja `synthesis/` sisällöistä. Aiemmat tutkimukset painottuivat digimarkkinapaikkoihin, CAD/3D-tuotteisiin ja Blenderiin. Niiden omat raportit tunnistivat, että näkyvät arvostelut/lataukset eivät ole myyntilukuja.
2. Uudessa Problem Hunter -vaiheessa haettiin julkisia keskusteluja, korjausfoorumeita ja jälleenmyyjien sivuja avainsanoilla kuten *replacement*, *discontinued*, *adapter*, *missing part*, *I would pay*, *no longer available* sekä suomeksi/englanniksi. Tähän osatulokseen kirjattiin 38 erillistä lähdehavaintoa. Samassa keskustelussa olevia kommentteja ei laskettu erillisiksi riveiksi. Päällekkäisyyksiä poistettiin.
3. Innovation Architect muodosti 15 hypoteesia ja kuvasi fyysisen, digitaalisen ja ryhmä-/välittäjäkanavan vaihtoehtoja. Nämä ovat ehdotuksia, eivät kysyntänäyttöä.
4. Red Team tarkisti löydetyt kilpailijat, olemassa olevat korvauskanavat, turvallisuusrajat, IP-riskit, tuotteen kopioitavuuden ja ylläpitotyön.
5. Commercial Analyst käytti säädettäviä oletuksia pisteytyksessä ja talousmallissa. Arviot eivät ole toteutunutta myyntiä.

## Aineiston tila ja rajoitukset

Tavoite oli 100 erillistä ongelmahavaintoa; tähän toimitettavaan osatulokseen on kirjattu **38 havaintoa, joista useita on C-luokan yksittäisiä keskustelusignaaleja**. Kaikille ei löytynyt riippumatonta toista signaalia. Tavoite ei täyttynyt, joten rivejä ei täytetty johdetuilla oletuksilla. Osa riveistä osoittaa päällekkäisen teeman, ei erillistä markkinaa. Lähteet ovat pitkälti käyttäjien omia viestejä, joten taajuusväitteet ovat epävarmoja. Yksittäisen ongelman esilläolo ei osoita ostohalukkuutta.

Ensimmäisessä kierroksessa nousivat esiin varaosien puute, yhteensopivuusadapterit ja ryhmätilausmahdollisuudet. Konkreettisesti kaupallinen näyttö on vahvinta lautapelien palveluhinnoittelusta, Etsyssä tarjolla olevista appliance replacement -tuotteista, pyörätelineadapterien listauksista ja Reppukoukku-esimerkistä. Näistä mikään ei yksin todista kannattavuutta.

## Näyttöluokat

- **A:** toteutuneet tuotekohtaiset maksulliset ostot tai sitovat kaupalliset tilaukset. Tässä osatutkimuksessa ei ole A-luokan signaalia finalistien omalle tuotteelle.
- **B:** useita uskottavia kaupallisia signaaleja, kuten listattu hinta ja palvelun olemassaolo tai useampi erillinen saman ongelman lähde.
- **C:** dokumentoitu ongelma tai yleinen kaupallinen tarjonta ilman mitattua tuotekohtaista ostoa.
- **D:** hypoteesi ilman löydettyä suoraa ongelmalähdettä.

## Valintaperusteet

Pisteytys: ongelman vakavuus/maksuhalukkuus 25 %, tavoitettavuus/jakelu 25 %, kate suhteessa työhön 20 %, ryhmätilaukset/vipuvaikutus 15 %, erottuvuus/kopiointivaikeus 10 %, käynnistämisen helppous 5 %. Pisteet ovat 0–100 suhteellinen priorisointi-indeksi, eivät onnistumistodennäköisyys. Näytön taso näytetään erillisenä.

## Eri analyysiroolit

- **A Problem Hunter:** havainnot koottiin ennen konseptipisteytystä.
- **B Innovation Architect:** loi 15 ratkaisuhypoteesia ja mietti fyysiset, digitaaliset ja B2B-mallit.
- **C Red Team:** haki kilpailijoita ja etsi syitä, miksi ideat eivät kannattaisi.
- **D Commercial Analyst:** rakensi oletuspohjaisen katemallin ja validointikokeet.

## Lähdekäytännöt

Havaintojen URL:t ovat CSV:ssä. Kaupalliset hinnat ovat lähdesivuilta havaittuja vain silloin, kun rivillä niin sanotaan. Reddit-/foorumiviesteissä hinnat ja käyttömäärät ovat kirjoittajien ilmoituksia, eivät riippumattomasti tarkistettuja. Lähteitä tarkasteltiin julkisesti ilman massakeruuta. Käyttöehtoja rajoittavia kirjautumis- tai keruumenetelmiä ei käytetty.
