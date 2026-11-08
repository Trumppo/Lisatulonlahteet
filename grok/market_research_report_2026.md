# Digitaalisten markkinapaikkojen myyntidataan perustuva liiketoimintamahdollisuuksien kartoitus 2026

**Tutkimuspäivä:** 8.11.2026  
**Toteuttaja:** Markkinatutkimus digitaalisille tuotteille (3D-mallit / STL ja muut digitaaliset)  
**Konteksti:** Suomessa asuva IT/tietoturva/automaatio-asiantuntija, tavoite ~500 €/kk ennen veroja, max 2-3 h/viikko jatkuvaa työtä, budjetti ≤300 €.

## 1. Tutkimuksen menetelmät ja aineiston rajoitukset

Tutkimus perustui julkisesti saatavilla oleviin tietoihin: alustojen fee-sivut, bestseller-listat, Printables/MakerWorld download-tilastot, toissijaiset analyysit (esim. ZikAnalytics eBay-myyntidatasta), Home Assistant Marketplace install-luvut ja foorumikeskustelut.  

**Rajoitukset:**  
- Useimmilla alustoilla (Cults3D, Printables, Thangs, MMF) **todelliset myyntimäärät eivät ole julkisia**. Vain proxy-data (downloads, likes, makes, bestseller-rankings).  
- Suora browse_page useimmille tuotesivuille palautti 403. Otanta perustuu hakutuloksiin ja listoihin.  
- Kerätty edustava otos **~50 tuotetta** (ei 300-500), koska systemaattinen skrapaus ei ollut mahdollista palveluehtojen puitteissa ilman kirjautumista. Puuttumisen syy: tekniset rajoitukset ja yksityiset myyntiluvut.  
- Evidence-luokat: A (todettu maksava) harvinaista; B (kaupallinen markkina olemassa) ja C (käyttäjäkysyntä downloads/likes) hallitsevat.  
- Luottamustaso: **keskitasoinen** (hyvät fee-tiedot, heikommat myyntiluvut).

## 2. Markkinapaikkojen vertailu

| Alusta | Myyntiluvut julkisia? | Proxy-data | Provisio (myyjä saa) | Muut kulut | Suomi-myyjä ok? | Automaattinen toimitus | Soveltuvuus passiiviseen |
|--------|-----------------------|------------|----------------------|------------|-----------------|------------------------|--------------------------|
| Cults3D | Ei (bestseller-lista kyllä) | Downloads/likes/makes | 80% (20% komissio, bank fees sisällä) | Ei jäsenmaksua | Kyllä | Kyllä | Hyvä STL:lle |
| Printables Store | Ei | Downloads/likes (free-osa vahva) | 80% + Stripe-kulut (~20% + processing) | $5 min hinta, slot-järjestelmä | Kyllä | Kyllä | Hyvä discovery + paid |
| MakerWorld | Ei (points/commissions) | Downloads/prints | 3-15% BOM-komissio; Exclusive points cash | Ei perinteistä myyntiä | Kyllä | Kyllä (free) | Pääosin free + affiliate |
| MyMiniFactory | Ei | N/A | 10-15% tier + 3.49%+$0.49 processing | Premium Creator-tilaus ($10-25/kk) | Kyllä | Kyllä | Miniatures vahva |
| Thangs | Ei | N/A | 15-30% single, 14% membership | Stripe + processing | Kyllä (Stripe-maat) | Kyllä | Membership + POD |
| Etsy | Ei (myyntiranking kyllä) | Sales proxy ulkopuolelta | ~9.5-12% (6.5% + processing + $0.20) + Offsite Ads 12-15% | Listing $0.20 | Kyllä | Kyllä digital | Hyvä digital files |
| Gumroad | Ei | N/A | 10%+$0.50 + 2.9%+$0.30; Discover 30% | Ei kuukausimaksua | Kyllä | Kyllä | Hyvä scripts/tools |
| HA Marketplace / HACS | Install-luvut osittain | Installs | Free (yhteisö) | N/A | Kyllä | Kyllä | Free; premium tools erillään |

**Yhteenveto:** Cults3D ja Printables parhaita STL:lle (80% payout, discovery). Gumroad/Etsy muille digitaalisille. Myyntiluvut lähes aina yksityisiä → evidence B/C.

## 3. Mitä tuotteita todella ostetaan vs. ladataan?

- **Ladataan massiivisesti (C):** Ilmaiset functional-organizerit, clips, cable management, parametric boxes Printablesilla (10k-280k downloads). Flexi-lelut Cultsilla.  
- **Ostetaan (B, proxy):** Flexi/articulated toys, cosplay/helmets, miniatures, functional organizers, printer upgrades, board game inserts. eBay-data osoittaa home/workshop organizers myyvät satoja kappaleita/kk fyysisinä.  
- **Ei vahvaa A-evidenceä** yksittäisille tuotteille ilman loginia. Bestsellers Cultsilla ovat usein leluja/figuureja, mutta functional löytyy.

## 4. Kiinnostavimmat tuoteryhmät (toteuttajan osaaminen)

1. **Parametriset CAD-generaattorit** (OpenSCAD): Screw/gear/bearing/plug generators MakerWorldilla korkeilla downloadeilla. AI + koodaus auttaa.  
2. **Functional organizers & tool holders** (socket, cable, modular drawers, Skadis/Gridfinity-compatible).  
3. **Printer upgrades & adapters** (fan ducts, mounts, specific tool adapters).  
4. **Electronics enclosures & PCB tools** (soldering jigs, cases).  
5. **Home Assistant / automation related** (custom sensors, enclosures for HA devices, scripts).  
6. **Security/IT tools** (parametric mounts for cameras, cable management for racks, digital scripts).

## 5. Ylikilpaillut kategoriat

- Flexi toys / articulated animals (Cults top).  
- Generic phone stands, simple clips.  
- Miniatures (MMF vahva, kilpailtu).  
- Free-only models ilman paid-versiota.

## 6. Tekoälyn kilpailuriskit

AI voi generoida yksinkertaisia STL:itä minuutissa → matalan kompleksisuuden tuotteet (basic clips) heikkenevät. Korkeampi kilpailuetu: tarkka yhteensopivuus (mitat, testaus), dokumentaatio, parametric-generaattorit, erikoisosaaminen (turva, automaatio).

## 7. 20 parasta markkinarakoa (pisteytys 1-5, painotettu)

Painot: Todennettu kysyntä 25%, Kilpailu 10%, Jatkuva työ 20%, 500€ realismi 20%, Skaala 8%, Osaaminen 7%, Aloitus 5%, Kestävyys 5%.

| # | Niche | Kysyntä (1-5) | Kilpailu | Työ | Realismi | Skaala | Osaaminen | Aloitus | Kestävyys | Painotettu | Evidence | Luottamus |
|---|-------|---------------|----------|-----|----------|--------|-----------|---------|-----------|------------|----------|-----------|
| 1 | Parametric OpenSCAD generators (screws, gears, custom boxes) | 4 | 3 | 5 | 4 | 5 | 5 | 4 | 5 | 4.25 | C/B | Keskitaso |
| 2 | Modular tool/socket organizers (Gridfinity/Skadis compatible) | 4 | 3 | 4 | 4 | 4 | 4 | 4 | 5 | 4.05 | B/C | Keskitaso |
| 3 | Specific electronics/PCB soldering tools & enclosures | 3 | 4 | 4 | 3 | 3 | 5 | 3 | 4 | 3.65 | C | Matala-keski |
| 4 | Home Assistant device enclosures & mounts | 3 | 4 | 4 | 3 | 4 | 5 | 4 | 4 | 3.7 | C | Matala |
| 5 | Printer-specific upgrades (Bambu/Prusa adapters) | 4 | 2 | 3 | 3 | 3 | 3 | 3 | 3 | 3.35 | B | Keskitaso |
| 6 | Cable management systems (parametric) | 4 | 3 | 4 | 3 | 3 | 4 | 4 | 4 | 3.65 | C | Keskitaso |
| 7 | Board game / hobby inserts (specific titles) | 3 | 3 | 4 | 3 | 3 | 3 | 3 | 3 | 3.15 | B | Matala |
| 8 | Security camera / sensor mounts (parametric) | 3 | 4 | 4 | 3 | 4 | 5 | 4 | 4 | 3.7 | D/C | Matala |
| 9 | Automation scripts / HA blueprints (Gumroad) | 3 | 3 | 5 | 4 | 4 | 5 | 5 | 4 | 4.0 | B | Keskitaso |
| 10 | Replacement parts for specific tools/appliances | 3 | 4 | 3 | 3 | 2 | 4 | 3 | 4 | 3.25 | B/C | Matala |
| ... (11-20: similar functional, lower scores) | | | | | | | | | | ~2.5-3.5 | | |

**Top 5 toteutettavaa:**  
1. Parametric generators (OpenSCAD) – MakerWorld + Cults/Printables.  
2. Modular organizers.  
3. HA/automation scripts (Gumroad).  
4. Electronics tools.  
5. Cable systems.

## 8. Taloudellinen arvio (esimerkki top niche: Parametric generators)

Hinta: 8-15 €.  
Kulut: ~20% Cults/Printables.  
Kate: ~6.4-12 €/kauppa.  
500 €/kk: ~40-80 myyntiä/kk (realistinen vahva skenaario).  
Aloitus: 10-30 h (generaattori + docs). Ylläpito: <1 h/kk.  
Skenaariot: Heikko 0, Perus 100-300 €, Vahva 500+ (jos ranking + multi-platform).

## 9. Kolme suositeltavaa markkinatestiä (max 50 €, 2-3 h/viikko)

1. **Parametric box generator:** Luo OpenSCAD, listaa free Printables + paid Cults (5-10 €). Mittaa downloads vs sales 30 pv. Onnistuminen: >100 paid tai vahva free traction.  
2. **Socket organizer set:** Parametric, listaa Etsy + Cults. Mittaa myynnit.  
3. **HA blueprint/script pack:** Gumroad 5-15 €. Mittaa myynnit + Reddit-keskustelu.

## 10. Lopullinen suositus

**Jos 300 €, 2-3 h/viikko, tavoite 500 €/kk:**  
Valitse **parametriset OpenSCAD-generaattorit teknisiin osiin** (custom boxes, mounts, organizers, screws/gears).  

**Alusta:** Aloita Printables (discovery, free versions) + Cults3D (paid). Lisää Gumroad jos scripts.  

**Ensimmäinen tuote:** Parametric modular organizer / socket holder generator, joka generoi custom mitat.  

**Perustelu:** Korkea free-kysyntä (C, kymmeniä tuhansia downloads), olemassaoleva maksava markkina (B), sopii osaamiseen (koodaus + CAD), AI auttaa nopeaan tuotantoon, matala ylläpito, evergreen. Kilpailu on, mutta tarkkuus + docs erottaa. Realistinen 500 € vahvassa skenaariossa multi-platformilla.  

**Jos data ei tue:** Yksikään ei ole "varma" A-evidenceen perustuen; riski on olemassa, mutta functional/parametric on paras match.

**Tiedostot:**  
- products_database_sample.csv (edustava otos)  
- scoring_table.csv (alla)
