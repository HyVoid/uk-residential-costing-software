[ 🌐 عربي ](README.ar.md) | [ 🇩🇪 Deutsch ](README.de.md) | [ 🇫🇷 Français ](README.fr.md) | [ 🇳🇱 Nederlands ](README.nl.md) | [ 🇪🇸 Español ](README.sp.md) | [ 🇬🇧 English ](README.md)

# Britische bouwcalculatiesoftware voor woningbouw & Excel-sjabloon voor kostenraming voor bouwbedrijven

[![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Platform](https://img.shields.io/badge/Platform-Browser%20(Free)%20%7C%20Excel%20(Paid)-emerald.svg)](#)
[![Tool Type](https://img.shields.io/badge/Tool%20Type-Decision%20Support%20%7C%20Costing%20Engine-orange.svg)](#)

**Een geavanceerd Britisch sjabloon voor kostenraming van woningbouw en software voor kostenraming van bouwprojecten, ontworpen om gemeten hoeveelheden uit architectuurtekeningen in seconden om te zetten in aanbiederspecifieke offertebudgetten, interne commerciële ondergrenzen en heldere klantoffertes. Beschikbaar als gratis browsergebaseerd tool voor bouwcalculatie en als volledig ontgrendeld professioneel Excel-werkboek voor kostenraming voor bouwbedrijven, met 30 dagen geld-teruggarantie.**

> **Geen registratie. Geen installatie.**  
> **Browserversie: gratis.**  
> **Excel-versie: betaald met 30 dagen geld-teruggarantie.**  
> [🌐 Open de gratis browsergebaseerde app voor bouwcalculatie](https://hyvoid.github.io/uk-residential-costing-software/)
>
> [📥 Download het professionele Excel-sjabloon voor kostenraming voor bouwbedrijven](https://theseusworkshop.com/l/arnghy?utm_source=github&utm_medium=GitHub%20README)

<img width="1920" height="828" alt="image" src="https://github.com/user-attachments/assets/6d58eaae-fcd8-4407-8678-25f5f3067d57" />
<img width="1163" height="790" alt="image" src="https://github.com/user-attachments/assets/b156ab36-5886-40cb-879d-fbadbbf32a7a" />


---

## Kernfuncties: bouwkostenvolging & oplossingen voor offertebeheer

Traditionele spreadsheets falen omdat ze hoeveelheden en prijzen met elkaar vermengen. Dit systeem fungeert als een echte **prijsbepalingsmotor voor hoeveelheidsstaten (BOQ)**, expliciet ontworpen om de duurste fouten in de bouwcalculatie op te lossen.

| Probleem bij bouwcalculatie (zoekopdracht) | Geautomatiseerde oplossing in de calculatiemotor |
| :--- | :--- |
| **Aannemersmarge vs. verlies van operationele kosten** | Scheidt directe vakmannenkosten, algemene kosten ter plaatse, wettelijke gemeenskosten en onvoorzien van de aannemersmarge, zodat offertemarges nooit in operationele verliezen verzanden. |
| **Prijzen van subcontractoren & analyse van prijsafwijkingen** | Beoordeelt hoe het wisselen van vakpartners (bijv. lokale bouwbedrijven uit Hertfordshire vs. regionale subcontractoren) direct de basisrentabiliteit van het project verandert op exact dezelfde fysieke BOQ. |
| **Uitsplitsing van directe kosten (arbeid & materialen)** | Biedt exacte uitsplitsing per post over arbeid, materialen, gespecialiseerde subcontractoren en machinehuur voor elke structurele en architectonische fase. |
| **Berekening van materiaalverlies voor de bouw** | Berekent dynamisch de stijging van het inkoopvolume per post (bijv. snijverlies bij gevelstenen) in plaats van ze te maskeren met uniforme vuistregel-toeslagen. |
| **Klantgerichte prijzen vs. interne marges** | Genereert automatisch een gedesensibiliseerd offerteschema voor de klant dat gemeenskosten en algemene kosten ter plaatse soepel in gemengde eenheidsprijzen verwerkt, zonder vakmannenkosten van subcontractoren of doel-bruto-marges bloot te leggen. |
| **Offerte-integriteit & BOQ-afstemming** | Levert realtime validatie die bevestigt dat er geen niet-geregistreerde postcodes, ontbrekende vakprijzen of formulebreuken zijn, en waarborgt strikte balans tussen interne kostenmodellen en klanttotalen binnen een tolerantie van £0,01. |

---

## Snelstarttutorial: stel uw eerste bouwofferte samen

Volg dit werkproces om met onze ingebouwde commerciële calculatiefuncties nauwkeurige ramingen en klantklare offertes te genereren.

1. **Stel sleutelparameters in (projectopzet)**: Open `01_Setup` om de projectmetadata te configureren. Gebruik de **dynamische dropdownlijst van aannemers** om uw actieve offertepartner te selecteren, stel de valutaweergave (£) in en bevestig de globale doelen voor de **modus algemene kosten ter plaatse**, gemeenschappelijke kosten & winst (OHP %), onvoorzien % en de wettelijke btw.
2. **Voer fysieke hoeveelheden in (opname-import)**: Open `04_Project_Estimate` en voer de opnamecodes uit de architectuurtekeningen (`Takeoff_Item_Code`) in samen met de fysiek gemeten hoeveelheden (`Measured_Quantity`). De motor koppelt direct de **prijsmatrices per vak** uit de centrale bibliotheek, zonder handmatig formules slepen.
3. **Leg sitelogistiek & toeslagen vast**: Voer niet-standaard siteverplichtingen (bijv. duur van steigerhuur, huur van afvalcontainers, sanitaire voorzieningen) en voorlopige klantsommen (bijv. keukenpakketten, toeslagen voor sanitair) in de **calculator voor algemene kosten ter plaatse** `05_Adjustments` in.
4. **Inspecteer beslissingsweergaven & exporteer**: Controleer interne margedrempels en break-even-vloeren in `06_Internal_Estimate`, vergewis u ervan dat `08_Checks` geen rode vlaggen activeert, en exporteer het gedesensibiliseerde, klantklare offerte direct uit `07_Customer_Estimate` naar PDF. 

> **Klaar om uw offerteproces te schalen?** Nadat u de browserversie heeft uitgeprobeerd, [📥 download het herbruikbare Excel-sjabloon voor kostenraming voor onbeperkte offertes en levenslange offline toegang](https://theseusworkshop.com/l/arnghy?utm_source=github&utm_medium=GitHub%20README).

---

## Waarom ik deze calculatiesoftware heb gebouwd

De meeste ramingen voor particuliere en mid-market woningbouwprojecten (£100.000–£500.000) falen lang voordat de eerste spade in de grond gaat. Ze falen omdat kleine en middelgrote bouwbedrijven en projectmanagers vertrouwen op monolithische **bouwcalculatie-spreadsheets** waarin vakprijzen, sitelogistiek, materiaalverlies en fysieke hoeveelheden in één enkele cel zijn vastgesoldeerd. Wanneer een hoofdaannemer bijgewerkte subcontractorsprijzen ontvangt of een offerte moet indienen met een ander timmerteam, moet de volledige BOQ met de hand worden herbouwd.

Bij een recente raming voor een tweelaags uitbouw van £260.000 paste de hoofdaannemer een gebruikelijke forfaitaire opslag van 15% toe op een samengestelde prijs per vierkante meter voor metselwerk. De site was echter alleen bereikbaar via een smalle onverharde steeg achter, wat transport met kleine machines vereiste, en de op maat gemaakte gevelstenen hadden een snijverliesfactor van 10% in plaats van de standaard 5%. Omdat het tarief een hard gecodeerd samengesteld getal was, werden de extra £4.200 aan overschot aan stenen en £3.800 aan extra machinehuur nooit aan de projectbasis toegerekend. De offerte leek concurrerend, maar na oplevering realiseerde de aannemer een nettomarge van 3,4% in plaats van de beoogde 16% — waardoor de operationele cashflow volledig werd weggevaagd.

Ik heb deze **bouwcalculatiemotor** gebouwd om dit faalpatroon voor altijd uit te roeien. In plaats van een raming te behandelen als een statisch rekenblad, maakt dit tool commercieel kostenengineering tot product: het scheidt de onveranderlijke fysieke geometrie van een gebouw van vluchtige vaklonen, isoleert algemene kosten ter plaatse en cascadeert commerciële opslagen dynamisch over de klantdocumenten.

---

## Veelvoorkomende problemen bij woningbouwraming die dit tool oplost

| Probleem bij raming & calculatie | Beperkingen van traditionele spreadsheets | Oplossing van de geautomatiseerde calculatiemotor |
| :--- | :--- | :--- |
| **Gekoppelde hoeveelheden en arbeidprijzen** | Het opnieuw ramen van een offerte met een nieuwe subcontractor vereist het opnieuw invoeren van projectafmetingen en het kopiëren van formules over tientallen BOQ-regels. | De fysieke opnamehoeveelheden blijven onaangeroerd; het wisselen van de aannemersdropdown in `01_Setup` herindexeert alle loon-, machine- en materiaaltarieven in minder dan een seconde. |
| **Stille onderschatting van materiaalverlies** | Forfaitaire procentuele toeslagen op totalsommen dekken geen snijverlies op hoogwaardig metselwerk, tegels en structureel hout. | Postspecifieke gelaagde logica paste dedicated verliesparameters toe op inkoophoeveelheden voordat de prijsvorming plaatsvindt, wat nauwkeurige **opnameringen** waarborgt. |
| **Lekkage van toegevingen aan voorkosten** | Steigers, containerhuur en projectleiding staan als transparante forfaits op de offerte, die klanten routineus wegonderhandelen tijdens de contractreview. | Algemene kosten ter plaatse en bedrijfsgemeenskosten worden wiskundig verwerkt in gemengde klantpostprijzen, waardoor de dekking van gemeenskosten beschermd blijft binnen bindende eenheidsprijzen. |
| **Formule-drift & gebroken verwijzingen** | Het toevoegen van onverwachte structurele posten vereist handmatig invoegen van regels en slepen van formules, waardoor regels vaak uit de totalen blijven. | Moderne dynamische spill-arrays met één enkel invoerpunt nemen nieuwe regels automatisch op en verdelen sommen over alle analysewerkbladen voor waterdichte **projectkostenberekening**. |
| **Klantzicht op commerciële ondergrenzen** | Calculateurs besteden uren aan het handmatig opschonen van interne calculatiespreadsheets tot klantoffertes, met het risico op accidentele openbaarmaking van vakmarges. | Een volledig ontkoppeld klantwerkblad leest uit de centrale motor en toont heldere werksecties, terwijl het interne vakprijzen en winstmarges volledig verbergt. |

---

## Doelgroepen & specifieke calculatiescenario's

Dit sjabloon fungeert als een lichtgewicht ERP voor bouwprofessionals die woningbouwopdrachten afhandelen. 

- **Woningbouwers & hoofdaannemers (£100.000–£500.000)**: Algemene bouwbedrijven die deze **calculatiesoftware voor woninguitbouwen**, complete renovaties van woningen en **sjablonen voor kostenraming van zolderkamers** gebruiken om verdedigbare interne marges te beveiligen voordat zij vaste-prijs-JCT-contracten ondertekenen.
- **Kostenramers & calculatieadviseurs**: Professionals die meerdere prijsbestanden van subcontractoren beheren en een schaalbaar **BOQ-prijsbepalingssjabloon** en een herbruikbaar **Excel-werkblad voor offertes** nodig hebben, zonder fragiele, complexe bedrijfsinfrastructuur te onderhouden.
- **Projectontwikkelaars & zelfbouwers**: Actoren die een transparante **kostencalculator voor huisbouw** en een bottom-up-benchmarktool zoeken om offertepakketten van aannemers tegen het licht te houden en belaste vakposten te identificeren.

*Niet ontworpen voor*: Commerciële hoogbouw- en civiele techniekprojecten die volledige SMM7/NRM2-advies-hoeveelheidsstaten vereisen, multi-user ERP-boekhouding voor bedrijven, of directe geautomatiseerde CAD/BIM-polygonextractie.

Geen spreadsheet-expertise nodig. Open de gratis browserapp en begin direct met ramen. Het robuuste desktopversie nodig? [Koop het professionele Excel-sjabloon voor kostenraming met 30 dagen geld-teruggarantie](https://theseusworkshop.com/l/arnghy?utm_source=github&utm_medium=GitHub%20README).

---

## Over de ontwikkelaar

Ik bouw geproductualiseerde beslissingsondersteunende tools en lichte operationele modellen voor omgevingen waarin er simpelweg te veel bewegende delen zijn om ze op intuïtie te managen. In de woningbouw accumuleren enkele tekortkomingen in de raming zich tot structurele cashflow-fouten. Mijn werk richt zich op het beantwoorden van één fundamentele vraag: *„Welke informatie heb ik op één duidelijke plek nodig om de volgende commerciële beslissing met absolute zekerheid te nemen?“* De **Britse bouwcalculatiemotor voor woningbouw** is de exacte realisatie van deze aanpak.

---


## Technische details

<details>
<summary>Voor technische reviewers, Excel-practitioners en medewerkers</summary>

### Werkboekarchitectuur

Het systeem werkt over vier duidelijke functionele lagen op acht werkbladen. Data stroomt strikt in één richting (Configuratie $\rightarrow$ Stamdata $\rightarrow$ Berekening $\rightarrow$ Output), waardoor circulaire verwijzingen worden geëlimineerd en de dataintegriteit wordt beschermd:

```
[01_Setup] (Global Parameters & Contractor Switcher)
   │
   ├── Controls currency, contractor selection, waste defaults, prelims mode, and margin targets
   ▼
[02_Item_Master] ─────────────▶ [03_Rate_Library]
(WBS Taxonomy & Descriptions)    (Subcontractor Rate Matrix: Labour / Material / Plant)
   │                               │
   └──────────────┬────────────────┘
                  ▼
       [04_Project_Estimate] ◀────── [05_Adjustments]
       (Dynamic Calculation Engine)   (Prelims, Provisional Sums, Site Allowances)
                  │
         ┌────────┴────────────────────────┐
         ▼                                 ▼
[06_Internal_Estimate]           [07_Customer_Estimate]
(Detailed Commercial Bottom-Line) (Clean Desensitized Client Tender)
         │                                 │
         └────────────────┬────────────────┘
                          ▼
                     [08_Checks]
         (Data Integrity, Code Mapping, Margin Audit)
```

| Laag | Werkbladnaam | Operationele verantwoordelijkheid | Type invoer / formule |
| :--- | :--- | :--- | :--- |
| **01. Beheer** | `01_Setup` | Bevat alle globale configuratievariabelen, bedrijfsmetadata, doel-marges en triggers voor de aannemersdropdown. | Gebruikersinvoer & dynamische lijsten |
| **02. Stamdata** | `02_Item_Master` | Vaststelt de standaard-WBS, vakcodes (`GW`, `MAS`, `CAR` enz.), maateenheden en het standaard materiaalverlies. | Stamtaxonomie (statisch / toevoegbaar) |
| **02. Stamdata** | `03_Rate_Library` | Onderhoudt multi-aannemer kostenvectoren over arbeid, materiaal, subcontract en machines. | Relationele prijstabellen |
| **03. Berekening** | `04_Project_Estimate` | Primaire werkruimte. Neemt opnamehoeveelheden op, evalueert effectief verlies, koppelt aannemerstarieven en aggregeert directe kostenregels. | Dynamische spill-arrays met één enkel invoerpunt |
| **03. Berekening** | `05_Adjustments` | Isoleert algemene kosten ter plaatse, steiger-/containerduren en voorlopige klanttoeslagen. | Gestructureerde postenschema's |
| **04. Rapportage** | `06_Internal_Estimate` | Bouwt de volledige commerciële waterval: directe kosten + algemene kosten ter plaatse = prime cost $\rightarrow$ gemeenschappelijke kosten & winst $\rightarrow$ onvoorzien $\rightarrow$ break-even. | Dynamische sectie-aggregatie |
| **04. Rapportage** | `07_Customer_Estimate` | Synthetiseert een controleerbaar, gedesensibiliseerd offerteschema voor de klant, dat gemeenskosten in postprijzen verwerkt. | Gedesensibiliseerde spill-arrays |
| **04. Governance** | `08_Checks` | Voert continue 6-punts dataintegriteit, detectie van niet-gemapte codes, waarschuwingen voor ontbrekende tarieven en afstemming van de proefbalans uit. | Geautomatiseerde booleaanse & afwijkingsaudits |

---

### Drie valkuilen die zelfs ervaren calculateurs vangen

#### Valkuil 1: compressie van gemengde subcontractortarieven
1. **Genomen beslissing**: Een calculateur past een geaggregeerd historisch tarief van £85,00/m² toe op een pakket van 140 m² betonblok- en stenenmetselwerk, in de veronderstelling dat arbeid en materialen zouden uitgemiddeld raken op basis van een eerdere klus.
2. **Het onopgemerkte gebrek**: Het project gebruikt gespecialiseerde met de hand gevormde gevelstenen uit het natgietprocédé (£1.150/1.000 stenen) in plaats van standaard technische stenen (£450/1.000 stenen), terwijl de site aan het einde van een onverharde smalle straat ligt, wat handmatig vervoer met een kruiwagen vereist.
3. **Gevolg van het gebrek**: De werkelijke materiaalkosten springen naar £62,00/m² en de arbeidskosten klimmen naar £48,00/m², wat totale directe kosten van £110,00/m² oplevert.
4. **Waarom de redenering gebrekkig is**: Geaggregeerde tarieven verhullen verschuivingen in de verhouding van middelen. Metselwerk is zelden 50/50 verdeeld; materiaalinflatie en sitelogistiek ontkoppelen arbeid en inkoopsnelheid.
5. **Gecorrigeerde aanpak**: Ontbind directe kosten in vier duidelijke vectoren (arbeid, materiaal, subcontract, machines), direct gekoppeld aan de tariefbibliotheek van de specifieke aannemer.
6. **Gecorrigeerd resultaat**: De werkelijke kosten worden gemarkeerd op £110,00/m² directe kosten, waardoor de post op £15.400 wordt geprijsd in plaats van £11.900, wat £3.500 netto liquiditeit beschermt.

<details>
<summary>Bekijk de logica voor matching van multi-vector-tarieven</summary>

```excel
=LET(
    target_contractor, '01_Setup'!$C$5,
    input_codes, A4:A500,
    rate_contractors, '03_Rate_Library'!A4:A1000,
    rate_codes, '03_Rate_Library'!B4:B1000,
    rate_matrix, '03_Rate_Library'!D4:G1000,
    composite_keys, rate_contractors & "|" & rate_codes,
    lookup_keys, target_contractor & "|" & input_codes,
    IF(input_codes="", "", 
        XLOOKUP(lookup_keys, composite_keys, rate_matrix, 0, 0)
    )
)
```
</details>

---

#### Valkuil 2: niet-gecapitaliseerd verlies op nettohoeveelheden
1. **Genomen beslissing**: Voor een vloerplaat op de begane grond en een spouwmuur meet de calculateur 100 m² vloertegels en 80 m² gevelstenenmetselwerk van de CAD-tekening, en past een standaard forfaitaire budgettoeslag van 5% toe op de offertesamenvatting.
2. **Het onopgemerkte gebrek**: Diagonale tegelpatronen in een L-vormige kamer genereren 12% snijverlies; gevelstenen rondom verspringende openingen leveren 8% verlies.
3. **Gevolg van het gebrek**: De aannemer bestelt 7 m² tegels en 6,4 m² metselwerk te weinig, wat noodbijbestelling tegen premieprijzen voor kleine series forceert en tegelsetters drie dagen lang stillelegt.
4. **Waarom de redenering gebrekkig is**: Verlies is fysieke geometrie, geen commercieel financiële onvoorzien. Een financiële onvoorzien kan geen ontbrekende pallets met batch-gelijkaardige tegels aanvullen.
5. **Gecorrigeerde aanpak**: Bereken het netto-inkoopvolume vóór de prijsvorming per eenheid met een gelaagde hiërarchie: handmatige overschrijving % $>$ basislijn stamitem % $>$ globale standaard %.
6. **Gecorrigeerd resultaat**: De inkoopvolumes schalen correct naar 112 m² voor tegels en 86,4 m² voor stenen, waardoor noodvracht en stilstand op de werf verdwijnen.

<details>
<summary>Bekijk de logica voor bepaling van effectief verlies</summary>

```excel
=LET(
    codes, A4:A500,
    manual_waste, G4:G500,
    master_codes, '02_Item_Master'!A4:A500,
    master_waste, '02_Item_Master'!F4:F500,
    global_default, '01_Setup'!$C$6,
    looked_up_waste, XLOOKUP(codes, master_codes, master_waste, global_default, 0),
    IF(codes="", "", 
        IF(manual_waste<>"", manual_waste, 
            IF(looked_up_waste<>"", looked_up_waste, global_default)
        )
    )
)
```
</details>

---

#### Valkuil 3: transparante algemene kosten ter plaatse die klanten wegonderhandelen
1. **Genomen beslissing**: De aannemer neemt steigers (£6.500), mobiele toiletten/sanitaire voorzieningen (£1.800) en leiding door een sitesupervisor (£9.000) op als expliciete posten op de klantofferte.
2. **Het onopgemerkte gebrek**: De klant argumenteert: *„Ik wil geen £1.800 betalen voor een mobiel toilet en uw steigerofferte is duurder dan wat mijn vriend heeft betaald; haal die regels eraf of ik zoek een andere aannemer.“*
3. **Gevolg van het gebrek**: Om de klus binnen te halen, schrapt de aannemer £8.300 aan algemene kosten ter plaatse uit het contract, met de bedoeling het te „absorberen in de algemene winst“.
4. **Waarom de redenering gebrekkig is**: Algemene kosten ter plaatse zijn rigide directe operationele uitgaven, geen discretionaire opslag. Het schrappen van de regel verlaagt noch de sanitaire voorzieningen noch de steigerhuur.
5. **Gecorrigeerde aanpak**: Behoud absolute interne zichtbaarheid van algemene kosten ter plaatse in `05_Adjustments` en `06_Internal_Estimate`, maar verwerk ze dynamisch in het klantschema via een proportionele verdeling van de opslag over de fysieke werksecties.
6. **Gecorrigeerd resultaat**: De klant ontvangt een schoon werkschema waarin alle algemene kosten ter plaatse en gemeenskosten wiskundig zijn verwerkt in de eenheidsprijzen per vak, waardoor logistiek niet onderhandelbaar wordt.

<details>
<summary>Bekijk de logica voor proportionele absorptie van opslag</summary>

```excel
=LET(
    codes, '04_Project_Estimate'!A4:A500,
    base_rates, '04_Project_Estimate'!P4:P500,
    direct_total, '06_Internal_Estimate'!$C$22,
    internal_gross, '06_Internal_Estimate'!$C$28,
    ps_total, '06_Internal_Estimate'!$C$27,
    markup_factor, IF(direct_total>0, (internal_gross - ps_total) / direct_total, 1),
    filtered_rates, FILTER(base_rates, codes<>""),
    filtered_rates * markup_factor
)
```
</details>

---

### Voorbeeldscenario: uitbouw & zolderkamerconversie in Hertfordshire

#### 1. Ruwe invoeren (`01_Setup` & `04_Project_Estimate`)
- **Project**: 45 m² rondom lopende uitbouw op de begane grond + zolderkamerconversie met achterdakkapel.
- **Geselecteerde aannemer**: `Apex_Builders_Herts`
- **Globale parameters**: standaard verlies = 5,0%, modus algemene kosten ter plaatse = vast (`05_Adjustments`), OHP = 15,0%, onvoorzien = 5,0%, btw = 20,0%.
- **Belangrijkste gemeten opnames**:
  - `GW-001` (ontgraving strookfundering): $24.0\,\text{m}^3$
  - `GW-002` (transportbeton C20/25 gegoten): $16.5\,\text{m}^3$ (standaard verlies 5,0%)
  - `MAS-001` (gevelstenenmetselwerk 102,5 mm): $68.0\,\text{m}^2$ (handmatige overschrijving verlies: 8,0%)
  - `STL-001` (structurele stalen I-balken geproduceerd & gehesen): $1.85\,\text{t}$
  - `ROO-001` (betonnen dakpannen met kliksysteem): $52.0\,\text{m}^2$ (standaard verlies 8,0%)
- **Ingevoerde aanpassingen (`05_Adjustments`)**:
  - Onafhankelijke steigers (10 weken huur): £4.800,00
  - Afvoer bouwafval (4 containers van 8 yard): £1.440,00
  - Tijdelijke sanitaire voorzieningen & beveiligde opslag: £1.250,00
  - Voorlopige som (toeslag voor keukenmeubelen & apparaten): £20.000,00

#### 2. Tussenliggende motorberekeningen (`04_Project_Estimate`)
- `MAS-001` berekende nettohoeveelheid: $68.0 \times (1 + 0.08) = 73.44\,\text{m}^2$
- `MAS-001` tarieven van de aannemer: arbeid £42,00, materiaal £48,50, subcontract £0,00, machines £4,50 $\rightarrow$ samengesteld tarief = £95,00/m²
- `MAS-001` directe postkosten: $73.44\,\text{m}^2 \times £95.00 = £6,976.80$
- Geaggregeerde directe projectkosten ($\sum \text{Direct Cost}$ over alle vakken): **£112.450,00**

#### 3. Commerciële waterval (`06_Internal_Estimate`)
$$\begin{aligned}
\text{Total Direct Cost} &= £112,450.00 \\
\text{Total Preliminaries} &= £7,490.00 \\
\hline
\mathbf{\text{Prime Cost}} &= £119,940.00 \\
\text{Overhead \& Profit (15.0\% on Prime)} &= £17,991.00 \\
\text{Contingency (5.0\% on Prime)} &= £5,997.00 \\
\text{Provisional Sums} &= £20,000.00 \\
\hline
\mathbf{\text{Gross Internal Contract Sum (Net of VAT)}} &= \mathbf{£163,928.00} \\
\text{Breakeven Floor (Direct + Prelims)} &= £119,940.00 \\
\text{Project Target Gross Margin} &= \frac{£163,928 - £119,940}{£163,928} = \mathbf{26.83\%} \quad (\text{includes Provisional Sums})
\end{aligned}$$

#### 4. Analytische interpretatie & aanbeveling
- **Opslagmultiplicator**: proportioneel absorptiefactor toegepast op klantposten:
  $$\text{Markup Factor} = \frac{£163,928 - £20,000}{£112,450} = 1.27993$$
- **Vertaling voor de klant**: De klant ziet `MAS-001` geprijsd op $£95.00 \times 1.27993 = \mathbf{£121.59/\text{m}^2}$, wat een posttotaal van £8.929,57 oplevert.
- **Besluitresultaat**: De aannemer biedt op **£163.928,00 + btw (£196.713,60 bruto)**. Geen enkele afzonderlijke post voor algemene kosten ter plaatse wordt blootgesteld aan regel-voor-regel controle door de klant, en het commerciële kussen van het bedrijf van £23.988 (OHP + onvoorzien) blijft beschermd.

---

### Formulereferentie

<details>
<summary>01_Setup: dynamische indexering van aannemers</summary>

```excel
=SORT(UNIQUE(FILTER('03_Rate_Library'!A4:A500, '03_Rate_Library'!A4:A500<>"")))
```
*Doel*: Extraheert een gesorteerde, unieke vector van actieve aannemers uit de tariefmatrix om de datavalidatie van cel `$C$5` dynamisch te vullen.
</details>

<details>
<summary>04_Project_Estimate: volledige-vectorvermenigvuldiging van directe kosten</summary>

```excel
=LET(
    codes, A4:A500,
    net_qty, I4:I500,
    labour_r, J4:J500,
    mat_r, K4:K500,
    subc_r, L4:L500,
    plant_r, M4:M500,
    tot_rate, P4:P500,
    IF(codes="", "",
        HSTACK(
            net_qty * labour_r,
            net_qty * mat_r,
            net_qty * subc_r,
            net_qty * plant_r,
            net_qty * tot_rate
        )
    )
)
```
*Doel*: Voert een horizontale spill van 5 kolommen (Q t/m U) uit die nettohoeveelheden gelijktijdig vermenigvuldigt met vierweg kostenvectoren en samengestelde tarieven.
</details>

<details>
<summary>06_Internal_Estimate: dynamische aggregatie van werksecties</summary>

```excel
=LET(
    active_sections, SORT(UNIQUE(FILTER('04_Project_Estimate'!D4:D500, '04_Project_Estimate'!D4:D500<>""))),
    labour_col, SUMIFS('04_Project_Estimate'!Q$4:Q$500, '04_Project_Estimate'!$D$4:$D$500, active_sections),
    mat_col, SUMIFS('04_Project_Estimate'!R$4:R$500, '04_Project_Estimate'!$D$4:$D$500, active_sections),
    subc_col, SUMIFS('04_Project_Estimate'!S$4:S$500, '04_Project_Estimate'!$D$4:$D$500, active_sections),
    plant_col, SUMIFS('04_Project_Estimate'!T$4:T$500, '04_Project_Estimate'!$D$4:$D$500, active_sections),
    total_col, labour_col + mat_col + subc_col + plant_col,
    HSTACK(active_sections, labour_col, mat_col, subc_col, plant_col, total_col)
)
```
*Doel*: Groepeert alle directe projectuitgaven dynamisch op hun respectievelijke bouwvakken, zonder vooraf ingestelde regels nodig te hebben.
</details>

<details>
<summary>08_Checks: wiskundige afstemming van de proefbalans</summary>

```excel
=LET(
    customer_net, SUM('07_Customer_Estimate'!F4:F500) + '06_Internal_Estimate'!$C$27,
    internal_gross, '06_Internal_Estimate'!$C$28,
    tolerance, '01_Setup'!$C$12,
    IF(ABS(customer_net - internal_gross) <= tolerance, 
        "✅ PASS: Trial balance reconciled within tolerance", 
        "❌ FAIL: Imbalance detected [" & TEXT(customer_net - internal_gross, "£#,##0.00") & "]"
    )
)
```
*Doel*: Voert een strikte verificatie van de proefbalans uit tussen klantgerichte offertes en interne ondergrenskosten.
</details>

---

### Validatieregels

| Werkblad | Cel / bereik | Doel van de regel | Validatieregel | Gedrag bij fouten |
| :--- | :--- | :--- | :--- | :--- |
| `01_Setup` | `$C$5` | Actieve aannemer | Dropdownlijst gebonden aan `='01_Setup'!$F$4#` | Wijst niet-geregistreerde aannemersnamen af. |
| `01_Setup` | `$C$6:$C$11` | Financiële percentages | Getalvalidatie: $\ge 0.0\%$ en $\le 100.0\%$ | Voorkomt negatieve of wiskundig catastrofale belasting-/opslaginvoer. |
| `02_Item_Master` | `A4:A500` | Stamitemcode | Unieke tekststring; duplicaten worden geaudit in `08_Checks` | Markeert een waarschuwing in het governance-dashboard als de stamcode is gedupliceerd. |
| `04_Project_Estimate` | `A4:A500` | Opnamepostcode | Moet bestaan in `02_Item_Master!A4:A500` | Toont `"⚠️ Unregistered Code"` in de beschrijving en triggert een auditfout in `08_Checks`. |
| `04_Project_Estimate` | `B4:B500` | Gemeten hoeveelheid | Numerieke waarde $\ge 0$ | Formule onderdrukt berekeningen als de hoeveelheid ontbreekt of niet numeriek is. |
| `04_Project_Estimate` | `N4:N500` | Tariefoverschrijving | Numerieke waarde $> 0$ | Vereist verplichte verklarende tekst in kolom O (`Override_Reason`). |
| `08_Checks` | `$C$9` | Modelbalanscontrole | $| \text{Customer Net} - \text{Internal Gross} | \le 0.01$ | Toont een prominente rode vlag: `"❌ FAIL: Imbalance detected"`. |

</details>

---


## De bedrijfslogica & methodologie

Dit systeem vertrouwt op een **drie-traps decompositie van de eenheidseconomie**, gecombineerd met een **proportioneel absorptiekostenmodel**. Traditionele bouwraming vertrouwt op brute historische eenheidstarieven (bijv. £2.200 per vierkante meter bruto binnenoppervlak), wat afwijkingen op vakniveau, topografische beperkingen van de site en verstoringen in de marktanbod verbergt.

Om dit op te lossen, dwingt de motor strikte ontkoppeling af:
1. **Laag van fysieke hoeveelheden**: Legt de werkelijke geometrische opname vast met dedicated materiaalverliesfactoren.
2. **Resourceprijsmatrix**: Ontbindt elke standaard bouwtaak in zijn vier fundamentele commerciële componenten (arbeid, materiaal, subcontract, machines), dynamisch gekoppeld aan benoemde vakbedrijven.
3. **Dubbelmarge-waterval**: Onderscheidt directe productiekosten van sitespecifieke algemene kosten ter plaatse om een **prime-cost-basislijn** vast te stellen. Commerciële gemeenskosten, winstmarges en projectonvoorzien worden vervolgens op deze geconsolideerde basislijn toegepast, wat een ondoordringbare break-even-vloer tot stand brengt.

Om klantzijdige marge-erosie tijdens commerciële offerteonderhandelingen te voorkomen, past het klantschema **proportionele absorptie** toe. In plaats van algemene kosten ter plaatse, aannemersmarge en risicoreserves als zelfstandige discretionaire sommen te presenteren, verdeelt de motor deze lasten wiskundig over de factureerbare fysieke posten. Het resulterende klantschema stemt tot op de cent nauwkeurig overeen met de interne commerciële taxatie, terwijl gevoelige vakmarges volledig beschermd blijven.

---

## Andere tools in deze serie

- **[Vergelijkings- & afwijkingsmotor voor subcontractorsoffertes](#)**: Legt meerdere vakoffertes tegen basale interne ramingen bloot om prijsafwijkingen en scooplekten te identificeren.
- **[Planner voor bouwcashflow & mijlpaal-S-curve](#)**: Zet schema's van hoeveelheidsstaten om in maandelijkse waarderingsprognoses, tracking van retenties en afboekingen van werkkapitaal.
- **[Tracker voor projectkosten & werkelijke kosten van woningbouwprojecten](#)**: Kostenregelsysteem na gunning dat inkooporders, urentabellen en wijzigingsopdrachten volgt tegen de oorspronkelijke offertebaselines.

---

## Licentie

Dit project is gelicentieerd onder de **Apache License 2.0**. Zie het [LICENSE](LICENSE)-bestand voor details.
