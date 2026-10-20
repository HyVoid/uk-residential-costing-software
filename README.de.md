[ 🌐 عربي ](README.ar.md) | [ 🇩🇪 Deutsch ](README.de.md) | [ 🇫🇷 Français ](README.fr.md) | [ 🇳🇱 Nederlands ](README.nl.md) | [ 🇪🇸 Español ](README.sp.md) | [ 🇬🇧 English ](README.md)

# Britische Baukalkulationssoftware für Wohnbau & Excel-Vorlage zur Kostenermittlung für Bauunternehmer

[![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Platform](https://img.shields.io/badge/Platform-Browser%20(Free)%20%7C%20Excel%20(Paid)-emerald.svg)](#)
[![Tool Type](https://img.shields.io/badge/Tool%20Type-Decision%20Support%20%7C%20Costing%20Engine-orange.svg)](#)

**Eine fortschrittliche britische Baukalkulationsvorlage für Wohnprojekte und Software zur Kostenermittlung von Bauprojekten, die dafür ausgelegt ist, aus gemessenen Mengen von Architekturplänen in Sekunden anbieterspezifische Ausschreibungsbudgets, interne kommerzielle Untergrenzen und saubere Kundenangebote zu erstellen. Verfügbar als kostenloses browserbasiertes Tool zur Baukalkulation und als vollständig freigeschaltete professionelle Excel-Kalkulationsmappe für Bauunternehmer, mit 30-tägiger Geld-zurück-Garantie.**

> **Keine Registrierung. Keine Installation.**  
> **Browser-Version: Kostenlos.**  
> **Excel-Version: Kostenpflichtig mit 30-tägiger Geld-zurück-Garantie.**  
> [🌐 Die kostenlose browserbasierte Baukalkulations-App öffnen](https://hyvoid.github.io/uk-residential-costing-software/)
>
> [📥 Die professionelle Excel-Kalkulationsvorlage für Bauunternehmer herunterladen](https://theseusworkshop.com/l/arnghy?utm_source=github&utm_medium=GitHub%20README)

<img width="1920" height="828" alt="image" src="https://github.com/user-attachments/assets/6d58eaae-fcd8-4407-8678-25f5f3067d57" />
<img width="1163" height="790" alt="image" src="https://github.com/user-attachments/assets/b156ab36-5886-40cb-879d-fbadbbf32a7a" />


---

## Kernfunktionen: Baukostenverfolgung & Lösungen für das Ausschreibungsmanagement

Traditionelle Tabellenkalkulationen scheitern, weil sie Mengen und Preise vermischen. Dieses System fungiert als echte **Preisermittlungsmaschine für Leistungsverzeichnisse (BOQ)**, die explizit dafür entwickelt wurde, die teuersten Fehler der Baukalkulation zu beseitigen.

| Problem der Baukalkulation (Suchanfrage) | Automatisierte Lösung in der Kalkulationsmaschine |
| :--- | :--- |
| **Anbietermarge vs. Betriebsverlust-Verfolgung** | Trennt direkte Gewerkskosten, Baustellengemeinkosten, behördliche Gemeinkosten und Eventualitäten von der Anbietermarge, damit Angebotsmargen nie in Betriebsverluste umschlagen. |
| **Subunternehmerpreise & Analyse der Preisabweichungen** | Bewertet, wie der Wechsel von Gewerbepartnern (z. B. lokale Bauunternehmer aus Hertfordshire vs. regionale Subunternehmer) die grundlegende Projektrentabilität bei exakt demselben physischen BOQ sofort verändert. |
| **Aufschlüsselung der direkten Kosten (Arbeitskräfte & Material)** | Liefert exakte Aufschlüsselungen nach Einzelposten über Arbeitskräfte, Material, Fachsubunternehmer und Gerätemiete für jede strukturelle und architektonische Phase. |
| **Materialverschnitt-Berechnung für das Bauwesen** | Berechnet dynamisch die Steigerungen des Einkaufsvolumens auf Postenebene (z. B. Verschnitt beim Schneiden von Sichtziegeln), anstatt sie mit einheitlichen Faustregel-Zuschlägen zu verdecken. |
| **Kundenseitige Preisgestaltung vs. interne Margen** | Erzeugt automatisch ein desensibilisiertes Kundenangebot, das Gemeinkosten und Baustellengemeinkosten reibungslos in gemischte Einzelpreise einarbeitet, ohne Gewerkskosten von Subunternehmern oder Ziel-Bruttomargen offenzulegen. |
| **Angebotsintegrität & BOQ-Abstimmung** | Liefert Echtzeit-Validierung, die bestätigt, dass keine nicht registrierten Postencodes, fehlende Gewerkpreise oder Formelunterbrechungen vorliegen, und gewährleistet strikte Übereinstimmung zwischen internen Kostenmodellen und Kundengesamtsummen innerhalb einer Toleranz von 0,01 £. |

---

## Schnellstart-Tutorial: Erstellen Sie Ihr erstes Bauangebot

Folgen Sie diesem Arbeitsablauf, um mit unseren integrierten kommerziellen Kalkulationsfunktionen genaue Kostenschätzungen und kundenfertige Angebote zu erstellen.

1. **Schlüsselparameter festlegen (Projekteinrichtung)**: Öffnen Sie `01_Setup`, um die Projektmetadaten zu konfigurieren. Nutzen Sie die **dynamische Bauunternehmer-Dropdown-Liste**, um Ihren aktiven Angebotspartner auszuwählen, legen Sie die Währungsanzeige (£) fest und bestätigen Sie die globalen Ziele für den **Baustellengemeinkosten-Modus**, Gemeinkosten & Gewinn (OHP %), Eventualitäten % und die gesetzliche Mehrwertsteuer.
2. **Physische Mengen erfassen (Aufmaß-Import)**: Öffnen Sie `04_Project_Estimate` und geben Sie die Aufmaß-Codes aus den Architekturplänen (`Takeoff_Item_Code`) zusammen mit den physisch gemessenen Mengen (`Measured_Quantity`) ein. Die Maschine vergleicht sofort die **Preismatrizen der Gewerke** aus der zentralen Bibliothek, ohne manuelles Formelziehen.
3. **Baustellenlogistik & Zuschläge erfassen**: Geben Sie nicht standardisierte Baustellenverpflichtungen (z. B. Gerüststandzeit, Containermiete für Abfälle, Sozialeinrichtungen) und vorläufige Kundensummen (z. B. Küchenpakete, Zuschüsse für Sanitärinstallationen) in den **Baustellengemeinkosten-Rechner** `05_Adjustments` ein.
4. **Entscheidungsansichten prüfen & exportieren**: Überprüfen Sie interne Margenschwellen und Break-even-Untergrenzen in `06_Internal_Estimate`, vergewissern Sie sich, dass in `08_Checks` keine roten Warnflaggen ausgelöst werden, und exportieren Sie das desensibilisierte, kundenfertige Angebot direkt aus `07_Customer_Estimate` als PDF. 

> **Bereit, Ihren Angebotsprozess zu skalieren?** Nachdem Sie die Browser-Version ausprobiert haben, [📥 laden Sie die wiederverwendbare Excel-Kalkulationsvorlage für unbegrenzte Angebote und lebenslangen Offline-Zugriff herunter](https://theseusworkshop.com/l/arnghy?utm_source=github&utm_medium=GitHub%20README).

---

## Warum ich diese Kalkulationssoftware entwickelt habe

Die meisten Schätzungen für private und mittelständische Wohnprojekte (100.000 £–500.000 £) scheitern lange vor dem ersten Spatenstich. Sie scheitern, weil kleine und mittlere Bauunternehmer und Projektmanager auf monolithische **Baukalkulations-Tabellen** angewiesen sind, in denen Gewerkpreise, Baustellenlogistik, Materialverschnitt und physische Mengen in einer einzigen Zelle verschweißt sind. Wenn ein Generalunternehmer aktualisierte Subunternehmerpreise erhält oder ein Angebot mit einem alternativen Zimmererteam einreichen muss, muss das gesamte BOQ von Hand neu aufgebaut werden.

Bei einer kürzlichen Schätzung für einen zweistöckigen Anbau über 260.000 £ wendete der leitende Bauunternehmer einen üblichen pauschalen Aufschlag von 15 % auf einen zusammengesetzten Quadratmeterpreis für Mauerwerk an. Die Baustelle hatte jedoch einen eingeschränkten Zugang über eine schmale Hintergasse, der den Transport mit Kleingeräten erforderte, und die maßgefertigten Sichtziegel wiesen einen Verschnittfaktor von 10 % statt der üblichen 5 % auf. Da der Preis eine fest codierte zusammengesetzte Zahl war, wurden die zusätzlichen 4.200 £ für Ziegelmehrmenge und 3.800 £ für verlängerte Gerätemiete niemals der Auftragsbasis zugeordnet. Das Angebot sah wettbewerbsfähig aus, aber nach Fertigstellung erzielte der Bauunternehmer eine Nettomarge von 3,4 % statt der angestrebten 16 % — was den Betriebs-Cashflow vollständig zunichtemachte.

Ich habe diese **Baukalkulationsmaschine** entwickelt, um diesen Fehlermodus für immer zu beseitigen. Anstatt eine Schätzung als statische Rechenleinwand zu behandeln, verwandelt dieses Werkzeug kommerzielles Kosten-Engineering in ein Produkt: Es trennt die unveränderliche physische Geometrie eines Gebäudes von volatilen Gewerk-Lohnsätzen, isoliert Baustellengemeinkosten und kaskadiert kommerzielle Aufschläge dynamisch über die Kundendokumente.

---

## Typische Probleme bei der Wohnbau-Kalkulation, die dieses Werkzeug löst

| Problem bei Schätzung & Kalkulation | Grenzen traditioneller Tabellenkalkulation | Lösung der automatisierten Kalkulationsmaschine |
| :--- | :--- | :--- |
| **Verkoppelte Mengen und Arbeitspreise** | Das Neukalkulieren eines Angebots mit einem neuen Subunternehmer erfordert die Neueingabe der Projektmaße und das Kopieren von Formeln über Dutzende von BOQ-Zeilen. | Die physischen Aufmaßmengen bleiben unberührt; das Wechseln der Bauunternehmer-Dropdown-Liste in `01_Setup` reindexiert alle Lohn-, Geräte- und Materialsätze in unter einer Sekunde. |
| **Stille Unterschätzung des Materialverschnitts** | Pauschale prozentuale Zuschläge auf Gesamtsummen decken nicht den Schnittverschnitt bei hochwertigem Mauerwerk, Fliesen und Konstruktionsholz. | Postenspezifische gestufte Logik wendet dedizierte Verschnittparameter auf die Beschaffungsmengen an, bevor die Preisbildung erfolgt, und gewährleistet genaue **Aufmaßschätzungen**. |
| **Leckage bei Zugeständnissen für Vorkosten** | Gerüst, Containermiete und Bauleitung werden als transparente Pauschalen ausgewiesen, die Kunden bei der Vertragsprüfung routinemäßig wegverhandeln. | Baustellengemeinkosten und Betriebsgemeinkosten werden mathematisch in gemischte Kundenpostenpreise eingearbeitet, wodurch die Gemeinkostendeckung in verbindlichen Einheitspreisen geschützt bleibt. |
| **Formelabweichung & gebrochene Bezüge** | Das Hinzufügen unerwarteter Konstruktionsposten erfordert manuelles Zeileneinfügen und Formelziehen, wodurch Zeilen häufig aus den Summen ausgeschlossen bleiben. | Moderne dynamische Überlauf-Arrays mit einem einzigen Einstiegspunkt übernehmen neue Zeilen automatisch und verteilen Summen über alle Analysearbeitsblätter für wasserdichte **Auftragskostenrechnung**. |
| **Kundeneinblick in kommerzielle Untergrenzen** | Kalkulatoren verbringen Stunden damit, interne Kalkulationstabellen manuell in Kundenangebote zu bereinigen, wodurch die Gefahr versehentlicher Offenlegung von Gewerkmargen besteht. | Ein vollständig entkoppeltes Kundenarbeitsblatt liest aus der zentralen Maschine und zeigt saubere Arbeitsabschnitte, während es interne Gewerkpreise und Gewinnmargen vollständig verbirgt. |

---

## Zielgruppen & konkrete Kalkulationsszenarien

Diese Vorlage fungiert als leichtes ERP für Bauprofis, die Wohnbauaufträge abwickeln. 

- **Wohnungsbauer & Generalunternehmer (100.000 £–500.000 £)**: Allgemeine Bauunternehmer, die diese **Kalkulationssoftware für Hausanbauten**, komplette Wohnraumsanierungen und **Kalkulationsvorlagen für Dachgeschossausbauten** nutzen, um vor der Unterzeichnung von Festpreis-JCT-Verträgen verteidigungsfähige interne Margen zu sichern.
- **Mengenermittler & Kalkulationsberater**: Fachleute, die mehrere Subunternehmer-Preisdateien verwalten und eine skalierbare **BOQ-Preisermittlungsvorlage** und ein wiederholbares **Excel-Angebots-Arbeitsblatt** benötigen, ohne fragile, komplexe Unternehmensinfrastruktur zu pflegen.
- **Immobilienentwickler & Selbstbauer**: Akteure, die einen transparenten **Hausbau-Kostenrechner** und ein Bottom-Up-Benchmark-Werkzeug suchen, um Angebotspakete von Bauunternehmern zu durchleuchten und überhöhte Gewerkposten zu identifizieren.

*Nicht ausgelegt für*: Gewerbliche Hochhaus-Tiefbauprojekte, die vollständige SMM7/NRM2-Berater-Leistungsverzeichnisse erfordern, Multi-User-ERP-Buchhaltung für Unternehmen oder direkte automatisierte CAD/BIM-Polygonextraktion.

Keine Tabellenkalkulations-Expertise erforderlich. Öffnen Sie die kostenlose Browser-App und beginnen Sie sofort mit der Kalkulation. Benötigen Sie die robuste Desktop-Version? [Kaufen Sie die professionelle Excel-Kalkulationsvorlage mit 30-tägiger Geld-zurück-Garantie](https://theseusworkshop.com/l/arnghy?utm_source=github&utm_medium=GitHub%20README).

---

## Über den Entwickler

Ich entwickle produktualisierte Entscheidungsunterstützungswerkzeuge und leichte Betriebsmodelle für Umgebungen, in denen es einfach zu viele bewegliche Teile gibt, um sie intuitiv zu steuern. Im Wohnbau summieren sich einzelne Kalkulationsversäumnisse zu strukturellen Cashflow-Ausfällen. Meine Arbeit konzentriert sich auf die Beantwortung einer grundlegenden Frage: *„Welche Informationen brauche ich an einem klaren Ort, um die nächste kommerzielle Entscheidung mit absoluter Sicherheit zu treffen?“* Die **britische Baukalkulationsmaschine für Wohnbau** ist die exakte Realisierung dieses Ansatzes.

---


## Technische Details

<details>
<summary>Für technische Prüfer, Excel-Praktiker und Mitarbeiter</summary>

### Arbeitsmappenarchitektur

Das System arbeitet über vier deutliche funktionale Schichten auf acht Arbeitsblättern. Daten fließen streng in eine Richtung (Konfiguration $\rightarrow$ Stammdaten $\rightarrow$ Berechnung $\rightarrow$ Ausgabe), wodurch Zirkelbezüge eliminiert und die Datenintegrität geschützt wird:

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

| Schicht | Arbeitsblattname | Operative Verantwortung | Eingabe-/Formeltyp |
| :--- | :--- | :--- | :--- |
| **01. Steuerung** | `01_Setup` | Enthält alle globalen Konfigurationsvariablen, Unternehmensmetadaten, Zielmargen und Auslöser für die Bauunternehmer-Dropdown-Liste. | Benutzereingaben & dynamische Listen |
| **02. Stammdaten** | `02_Item_Master` | Etabliert den Standard-WBS, Gewerkcodes (`GW`, `MAS`, `CAR` usw.), Maßeinheiten und den Standard-Materialverschnitt. | Stammtaxonomie (statisch / anfügbar) |
| **02. Stammdaten** | `03_Rate_Library` | Pflegt Multi-Bauunternehmer-Kostenvektoren über Arbeitskräfte, Material, Subunternehmer und Geräte. | Relationale Preistabellen |
| **03. Berechnung** | `04_Project_Estimate` | Primärer Arbeitsbereich. Übernimmt Aufmaßmengen, bewertet effektiven Verschnitt, vergleicht Bauunternehmerpreise und aggregiert direkte Kostenzeilen. | Dynamische Überlauf-Arrays mit einem Einstiegspunkt |
| **03. Berechnung** | `05_Adjustments` | Isoliert Baustellengemeinkosten, Gerüst-/Containerstandzeiten und vorläufige Kundenzuschüsse. | Strukturierte Postenpläne |
| **04. Berichtswesen** | `06_Internal_Estimate` | Erstellt die vollständige kommerzielle Wasserfallkette: Direktkosten + Baustellengemeinkosten = Primärkosten $\rightarrow$ Gemeinkosten & Gewinn $\rightarrow$ Eventualitäten $\rightarrow$ Break-even. | Dynamische Abschnittsaggregation |
| **04. Berichtswesen** | `07_Customer_Estimate` | Synthetisiert einen prüffähigen, desensibilisierten Kundenangebotsplan und arbeitet Gemeinkosten in die Einzelpreise ein. | Desensibilisierte Überlauf-Arrays |
| **04. Überwachung** | `08_Checks` | Führt kontinuierlich 6-Punkt-Datenintegritätsprüfungen, Erkennung nicht zugeordneter Codes, Fehlpreis-Alerts und Summenabstimmung durch. | Automatisierte boolesche & Abweichungsaudits |

---

### Drei Fallen, in die selbst erfahrene Kalkulatoren tappen

#### Falle 1: Kompression gemischter Subunternehmerpreise
1. **Getroffene Entscheidung**: Ein Kalkulator wendet einen aggregierten historischen Preis von 85,00 £/m² auf ein 140-m²-Paket aus Betonblock- und Ziegelmauerwerk an, in der Annahme, Arbeitskräfte und Materialien würden sich auf Basis eines früheren Auftrags ausgleichen.
2. **Der unbemerkte Fehler**: Das Projekt verwendet spezielle handgeformte Sichtziegel aus dem Nassgussverfahren (1.150 £/1.000 Ziegel) anstelle von Standard-Ingenieurziegeln (450 £/1.000 Ziegel), während die Baustelle am Ende einer unbefestigten schmalen Gasse liegt, die Handtransport mit einer Karre erfordert.
3. **Auswirkung des Fehlers**: Die tatsächlichen Materialkosten springen auf 62,00 £/m² und die Arbeitskosten steigen auf 48,00 £/m², was direkte Gesamtkosten von 110,00 £/m² ergibt.
4. **Warum die Begründung fehlerhaft ist**: Aggregierte Preise verdecken Verschiebungen in den Ressourcenverhältnissen. Mauerwerk ist selten 50/50 aufgeteilt; Materialinflation und Baustellenlogistik entkoppeln Arbeitskräfte und Beschaffungsgeschwindigkeit.
5. **Korrigierter Ansatz**: Direktkosten in vier deutliche Vektoren aufschlüsseln (Arbeitskräfte, Material, Subunternehmer, Geräte), die direkt mit der Preisbibliothek des jeweiligen Bauunternehmers verknüpft sind.
6. **Korrigiertes Ergebnis**: Die tatsächlichen Kosten werden mit 110,00 £/m² direkten Kosten markiert, wodurch die Zeile mit 15.400 £ statt 11.900 £ bepreist wird und 3.500 £ Nettoliquidität geschützt werden.

<details>
<summary>Logik der Multi-Vektor-Preisabgleichung ansehen</summary>

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

#### Falle 2: Nicht aufgezinster Verschnitt auf Nettomengen
1. **Getroffene Entscheidung**: Für eine Bodenplatte im Erdgeschoss und eine Hohlwand misst der Kalkulator 100 m² Bodenfliesen und 80 m² Sichtziegelmauerwerk von der CAD-Zeichnung und wendet einen üblichen pauschalen Budgetzuschlag von 5 % auf die Angebotszusammenfassung an.
2. **Der unbemerkte Fehler**: Diagonale Fliesenmuster in einem L-förmigen Raum erzeugen 12 % Verschnitt; Sichtziegel um versetzte Öffnungen ergeben 8 % Verschnitt.
3. **Auswirkung des Fehlers**: Der Bauunternehmer bestellt 7 m² Fliesen und 6,4 m² Mauerwerk zu wenig, was eine Nachbeschaffung zu Notfallpreisen für Kleinserien erzwingt und die Fliesenleger drei Tage lang stoppt.
4. **Warum die Begründung fehlerhaft ist**: Verschnitt ist physische Geometrie, kein finanzieller Eventualzuschlag. Ein Finanzzuschlag kann keine fehlenden Paletten chargengleicher Fliesen ersetzen.
5. **Korrigierter Ansatz**: Das Netto-Beschaffungsvolumen vor der Einzelpreisbildung mit einer gestuften Hierarchie berechnen: Manuelle Überschreibung % $>$ Stammposten-Basislinie % $>$ Globale Vorgabe %.
6. **Korrigiertes Ergebnis**: Die Beschaffungsmengen skalieren korrekt auf 112 m² für Fliesen und 86,4 m² für Ziegel, wodurch Notfallfracht und Betriebsstillstand entfallen.

<details>
<summary>Logik zur Bestimmung des effektiven Verschnitts ansehen</summary>

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

#### Falle 3: Transparente Baustellengemeinkosten, die Kunden wegverhandeln
1. **Getroffene Entscheidung**: Der Bauunternehmer weist Gerüst (6.500 £), mobile Toiletten/Baustellen-Sozialeinrichtungen (1.800 £) und Baustellenüberwachung (9.000 £) als explizite Einzelposten auf dem Kundenangebot aus.
2. **Der unbemerkte Fehler**: Der Kunde argumentiert: *„Ich werde keine 1.800 £ für eine mobile Toilette bezahlen, und Ihr Gerüstangebot ist teurer als das meines Freundes; nehmen Sie diese Zeilen heraus, oder ich finde einen anderen Bauunternehmer.“*
3. **Auswirkung des Fehlers**: Um den Auftrag zu sichern, streicht der Bauunternehmer 8.300 £ an Baustellengemeinkosten aus dem Vertrag, in der Absicht, sie „in den allgemeinen Gewinn aufzunehmen“.
4. **Warum die Begründung fehlerhaft ist**: Baustellengemeinkosten sind starre direkte Betriebsausgaben, kein beliebiger Aufschlag. Das Streichen der Zeile senkt weder die Kosten für Sozialeinrichtungen noch für Gerüstmiete.
5. **Korrigierter Ansatz**: Absolute interne Transparenz der Baustellengemeinkosten in `05_Adjustments` und `06_Internal_Estimate` beibehalten, sie aber dynamisch über eine proportionale Aufschlagsverteilung über die physischen Arbeitsabschnitte in den Kundenplan einarbeiten.
6. **Korrigiertes Ergebnis**: Der Kunde erhält einen sauberen Arbeitsplan, in dem alle Baustellengemeinkosten und Gemeinkosten mathematisch in die Gewerk-Einheitspreise eingearbeitet sind, wodurch die Logistik nicht verhandelbar wird.

<details>
<summary>Logik der proportionalen Aufschlagsabsorption ansehen</summary>

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

### Beispielszenario: Anbau & Dachgeschossausbau in Hertfordshire

#### 1. Rohe Eingaben (`01_Setup` & `04_Project_Estimate`)
- **Projekt**: 45 m² umlaufender Anbau im Erdgeschoss + Dachgeschossausbau mit hinterer Gaube.
- **Ausgewählter Bauunternehmer**: `Apex_Builders_Herts`
- **Globale Parameter**: Standardverschnitt = 5,0 %, Baustellengemeinkosten-Modus = Fest (`05_Adjustments`), OHP = 15,0 %, Eventualitäten = 5,0 %, Mehrwertsteuer = 20,0 %.
- **Wichtigste gemessene Aufmaße**:
  - `GW-001` (Aushub der Streifenfundamente): $24.0\,\text{m}^3$
  - `GW-002` (Transportbeton C20/25 vergossen): $16.5\,\text{m}^3$ (Standardverschnitt 5,0 %)
  - `MAS-001` (Sichtziegelmauerwerk 102,5 mm): $68.0\,\text{m}^2$ (Manuelle Verschnittüberschreibung: 8,0 %)
  - `STL-001` (Breitflanschträger aus Baustahl, gefertigt & gehoben): $1.85\,\text{t}$
  - `ROO-001` (Verfalzte Betondachsteine): $52.0\,\text{m}^2$ (Standardverschnitt 8,0 %)
- **Eingegebene Anpassungen (`05_Adjustments`)**:
  - Unabhängiges Gerüst (10-Wochen-Miete): 4.800,00 £
  - Baustellenentsorgung (4 Container à 8 Yards): 1.440,00 £
  - Temporäre Baustellen-Sozialeinrichtungen & sichere Lagerung: 1.250,00 £
  - Vorbehaltsposten (Zuschuss für Küchenmöbel & -geräte): 20.000,00 £

#### 2. Zwischenberechnungen der Maschine (`04_Project_Estimate`)
- `MAS-001` berechnete Nettomenge: $68.0 \times (1 + 0.08) = 73.44\,\text{m}^2$
- `MAS-001` Preise des Bauunternehmers: Arbeitskräfte 42,00 £, Material 48,50 £, Subunternehmer 0,00 £, Geräte 4,50 £ $\rightarrow$ Gemischter Preis = 95,00 £/m²
- `MAS-001` direkte Zeilenkosten: $73.44\,\text{m}^2 \times £95.00 = £6,976.80$
- Aggregierte direkte Projektkosten ($\sum \text{Direct Cost}$ über alle Gewerke): **112.450,00 £**

#### 3. Kommerzielle Wasserfallkette (`06_Internal_Estimate`)
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

#### 4. Analytische Interpretation & Empfehlung
- **Aufschlagsmultiplikator**: Proportionaler Absorptionsfaktor, angewendet auf Kundenposten:
  $$\text{Markup Factor} = \frac{£163,928 - £20,000}{£112,450} = 1.27993$$
- **Übersetzung für den Kunden**: Der Kunde sieht `MAS-001` bepreist mit $£95.00 \times 1.27993 = \mathbf{£121.59/\text{m}^2}$, was eine Zeilensumme von 8.929,57 £ ergibt.
- **Entscheidungsergebnis**: Der Bauunternehmer bietet mit **163.928,00 £ + Mehrwertsteuer (196.713,60 £ brutto)** an. Kein einzelner Baustellengemeinkostenposten wird der zeilenweisen Kundenprüfung ausgesetzt, und das kommerzielle Polster des Unternehmens von 23.988 £ (OHP + Eventualitäten) bleibt geschützt.

---

### Formelreferenz

<details>
<summary>01_Setup: Dynamische Bauunternehmer-Indexierung</summary>

```excel
=SORT(UNIQUE(FILTER('03_Rate_Library'!A4:A500, '03_Rate_Library'!A4:A500<>"")))
```
*Zweck*: Extrahiert einen sortierten, eindeutigen Vektor aktiver Bauunternehmer aus der Preismatrix, um die Datenvalidierung der Zelle `$C$5` dynamisch zu befüllen.
</details>

<details>
<summary>04_Project_Estimate: Vollvektor-Multiplikation der direkten Kosten</summary>

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
*Zweck*: Führt einen horizontalen 5-Spalten-Überlauf (Q bis U) aus, der Nettomengen gleichzeitig mit vier Kostenvektoren und gemischten Preisen multipliziert.
</details>

<details>
<summary>06_Internal_Estimate: Dynamische Aggregation der Arbeitsabschnitte</summary>

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
*Zweck*: Gruppiert alle direkten Projektausgaben dynamisch nach ihren jeweiligen Baugewerken, ohne voreingestellte Zeilen zu benötigen.
</details>

<details>
<summary>08_Checks: Mathematische Summenabstimmung</summary>

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
*Zweck*: Führt eine strikte Summenabstimmungsprüfung zwischen Kundenangeboten und internen Untergrenzkosten durch.
</details>

---

### Validierungsregeln

| Arbeitsblatt | Zelle / Bereich | Regelziel | Validierungsregel | Fehlerverhalten |
| :--- | :--- | :--- | :--- | :--- |
| `01_Setup` | `$C$5` | Aktiver Bauunternehmer | Dropdown-Liste gebunden an `='01_Setup'!$F$4#` | Weist nicht registrierte Bauunternehmernamen ab. |
| `01_Setup` | `$C$6:$C$11` | Finanzprozentsätze | Zahlenvalidierung: $\ge 0.0\%$ und $\le 100.0\%$ | Verhindert negative oder mathematisch katastrophale Steuer-/Aufschlagseingaben. |
| `02_Item_Master` | `A4:A500` | Stammpostencode | Eindeutige Textzeichenfolge; Duplikate werden in `08_Checks` geprüft | Markiert eine Warnung im Überwachungs-Dashboard, wenn der Stammschlüssel dupliziert ist. |
| `04_Project_Estimate` | `A4:A500` | Aufmaß-Postencode | Muss in `02_Item_Master!A4:A500` existieren | Zeigt `"⚠️ Unregistered Code"` in der Beschreibung an und löst ein Auditversagen in `08_Checks` aus. |
| `04_Project_Estimate` | `B4:B500` | Gemessene Menge | Numerischer Wert $\ge 0$ | Formel unterdrückt Berechnungen, wenn die Menge fehlt oder nicht numerisch ist. |
| `04_Project_Estimate` | `N4:N500` | Preisüberschreibung | Numerischer Wert $> 0$ | Erfordert obligatorischen Erklärungstext in Spalte O (`Override_Reason`). |
| `08_Checks` | `$C$9` | Modellgleichgewichtsprüfung | $| \text{Customer Net} - \text{Internal Gross} | \le 0.01$ | Zeigt eine prominente rote Warnflagge: `"❌ FAIL: Imbalance detected"`. |

</details>

---


## Die Geschäftslogik & Methodik

Dieses System stützt sich auf eine **dreistufige Zerlegung der Kosten je Einheit**, gepaart mit einem **proportionalen Absorptionskostenmodell**. Traditionelle Baukalkulation stützt sich auf brutto historische Einheitspreise (z. B. 2.200 £ pro Quadratmeter Bruttoinnenfläche), was Abweichungen auf Gewerkeebene, topografische Einschränkungen der Baustelle und Marktangebotsstörungen verbirgt.

Um dies zu lösen, erzwingt die Maschine eine strikte Entkopplung:
1. **Schicht der physischen Mengen**: Erfasst das tatsächliche geometrische Aufmaß mit dedizierten Materialverschnittfaktoren.
2. **Ressourcen-Preismatrix**: Zerlegt jede Standard-Bauaufgabe in ihre vier fundamentalen kommerziellen Komponenten (Arbeitskräfte, Material, Subunternehmer, Geräte), dynamisch verknüpft mit benannten Gewerksunternehmern.
3. **Doppelmargen-Wasserfallkette**: Unterscheidet direkte Produktionskosten von baustellenspezifischen Baustellengemeinkosten, um eine **Primärkosten-Basislinie** zu etablieren. Kommerzielle Gemeinkosten, Gewinnmargen und Projekt-Eventualitäten werden anschließend auf diese konsolidierte Basislinie angewendet, wodurch eine unüberwindbare Break-even-Untergrenze entsteht.

Um eine kundenseitige Margenerosion während kommerzieller Angebotsverhandlungen zu verhindern, setzt der Kundenplan **proportionale Absorption** ein. Anstatt Baustellengemeinkosten, Bauunternehmermarge und Risikoreserven als eigenständige beliebige Summen darzustellen, verteilt die Maschine diese Lasten mathematisch auf die abrechenbaren physischen Posten. Der resultierende Kundenplan stimmt auf den Cent genau mit der internen kommerziellen Bewertung überein, während sensible Gewerkmargen vollständig geschützt bleiben.

---

## Weitere Werkzeuge dieser Reihe

- **[Vergleichs- & Abweichungsmaschine für Subunternehmerangebote](#)**: Durchleuchtet mehrere Gewerksangebote gegen die basalen internen Schätzungen, um Preisanomalien und Leistungslücken zu identifizieren.
- **[Planer für Bau-Cashflow & Meilenstein-S-Kurve](#)**: Wandelt Leistungsverzeichnispläne in monatliche Bewertungsprognosen, Verfolgung von Sicherheitseinbehalten und Abrufe von Betriebskapital um.
- **[Auftragskosten- & Ist-Kosten-Tracker für Wohnprojekte](#)**: Kostenkontrollsystem nach Auftragsvergabe, das Bestellungen, Stundenzettel und Nachtragsleistungen gegen die ursprünglichen Angebotsbaselines verfolgt.

---

## Lizenz

Dieses Projekt ist unter der **Apache License 2.0** lizenziert. Siehe die Datei [LICENSE](LICENSE) für Details.
