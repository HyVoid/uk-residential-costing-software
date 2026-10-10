[ 🇫🇷 Français ](README.fr.md) | [ 🇬🇧 English ](README.md)

# Logiciel de métré et modèle de devis de construction résidentielle au Royaume-Uni (Excel)

[![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Platform](https://img.shields.io/badge/Platform-Browser%20(Free)%20%7C%20Excel%20(Paid)-emerald.svg)](#)
[![Tool Type](https://img.shields.io/badge/Tool%20Type-Decision%20Support%20%7C%20Costing%20Engine-orange.svg)](#)

**Un modèle d'estimation de la construction résidentielle britannique et un logiciel de métré de projet de bâtiment avancés, conçus pour transformer en quelques secondes les quantités mesurées sur les plans d'architecture en budgets d'appel d'offres spécifiques à l'entreprise, en marges commerciales internes et en devis client clairs. Disponible sous forme d'outil de devis de construction gratuit dans le navigateur et de classeur Excel d'estimation professionnel entièrement déverrouillé pour les constructeurs, avec une garantie de remboursement de 30 jours.**

> **Aucune inscription. Aucune installation.**  
> **Version navigateur : gratuite.**  
> **Version Excel : payante avec une garantie de remboursement de 30 jours.**  
> [🌐 Ouvrir l'application gratuite de métré de construction dans le navigateur](https://hyvoid.github.io/uk-residential-costing-software/)
>
> [📥 Télécharger le modèle Excel d'estimation pour constructeurs professionnels](https://theseusworkshop.com/l/arnghy?utm_source=github&utm_medium=GitHub%20README)

<img width="1920" height="828" alt="image" src="https://github.com/user-attachments/assets/6d58eaae-fcd8-4407-8678-25f5f3067d57" />
<img width="1163" height="790" alt="image" src="https://github.com/user-attachments/assets/b156ab36-5886-40cb-879d-fbadbbf32a7a" />


---

## Fonctionnalités clés : suivi des coûts de construction et gestion des appels d'offres

Les tableurs traditionnels échouent parce qu'ils mélangent les quantités et les prix. Ce système fonctionne comme un véritable **moteur de tarification de devis quantitatif (BOQ)**, explicitement conçu pour résoudre les erreurs les plus coûteuses de l'estimation de la construction.

| Problème de l'estimation de construction (requête de recherche) | Solution automatisée dans le moteur de métré |
| :--- | :--- |
| **Suivi de la marge de l'entreprise vs. perte d'exploitation** | Sépare les coûts directs des corps d'état, les frais généraux de chantier, les charges réglementaires et les aléas de la marge de l'entreprise, afin que les marges de soumission ne se transforment jamais en pertes d'exploitation. |
| **Tarification des sous-traitants et analyse des écarts de taux** | Évalue l'incidence immédiate du changement de partenaire (par exemple, constructeurs locaux du Hertfordshire contre sous-traitants régionaux) sur la rentabilité de base du projet, à partir du même devis quantitatif physique. |
| **Décomposition des coûts directs (main-d'œuvre et matériaux)** | Fournit une répartition précise par poste entre la main-d'œuvre, les matériaux, les sous-traitants spécialisés et la location d'engins, pour chaque phase structurelle et architecturale. |
| **Calcul des pertes de matériaux pour la construction** | Calcule dynamiquement les majorations de volume d'achat au niveau du poste (par exemple, la perte de coupe des briques de parement) au lieu de les masquer sous des marges forfaitaires uniformes. |
| **Tarification destinée au client vs. marges internes** | Génère automatiquement un bordereau d'appel d'offres client désensibilisé qui absorbe les frais généraux et les frais de chantier dans les prix unitaires mixtes, sans exposer les coûts de sous-traitance ni les marges brutes ciblées. |
| **Intégrité de l'appel d'offres et rapprochement du devis quantitatif** | Assure une validation en temps réel confirmant l'absence de codes de poste non enregistrés, de taux de corps d'état manquants ou de ruptures de formules, garantissant un équilibre strict entre les modèles de coûts internes et les totaux client à 0,01 £ près. |

---

## Tutoriel de démarrage rapide : construisez votre premier appel d'offres de construction

Suivez ce processus pour générer des estimations précises et des devis prêts à être remis au client grâce aux fonctionnalités de métré commercial intégrées.

1. **Définir les paramètres clés (configuration du projet)** : ouvrez `01_Setup` pour configurer les métadonnées du projet. Utilisez la **liste dynamique des entreprises** pour sélectionner votre partenaire de soumission en cours, définir la devise d'affichage (£) et confirmer les objectifs globaux pour le **mode des frais généraux de chantier**, les frais généraux et bénéfices (OHP %), les aléas (%) et la TVA réglementaire.
2. **Saisir les quantités physiques (import du métré)** : ouvrez `04_Project_Estimate` et saisissez les codes de métré issus des plans d'architecture (`Takeoff_Item_Code`) ainsi que les quantités physiques mesurées (`Measured_Quantity`). Le moteur rapproche instantanément les **matrices de tarification par corps d'état** de la bibliothèque centrale, sans manipulation manuelle de formules.
3. **Enregistrer la logistique de chantier et les allowances** : saisissez les engagements de chantier non standard (par exemple, durée de location de l'échafaudage, location de bennes de déchets, installations de bien-être de chantier) et les sommes provisionnelles client (par exemple, packages de cuisines, allowances pour les appareils sanitaires) dans le **calculateur de frais de chantier** `05_Adjustments`.
4. **Examiner les vues d'aide à la décision et exporter** : analysez les seuils de marge interne et les planchers de rentabilité dans `06_Internal_Estimate`, vérifiez l'absence d'alertes dans `08_Checks`, puis exportez directement en PDF le bordereau de devis désensibilisé et prêt à être remis au client depuis `07_Customer_Estimate`. 

> **Prêt à industrialiser votre processus de devis ?** Après avoir essayé la version navigateur, [📥 Télécharger le modèle Excel d'estimation réutilisable pour des appels d'offres illimités et un accès hors ligne à vie](https://theseusworkshop.com/l/arnghy?utm_source=github&utm_medium=GitHub%20README).

---

## Pourquoi j'ai développé ce logiciel de métré

La plupart des estimations résidentielles de petite et moyenne taille (£100k–£500k) échouent bien avant le démarrage des travaux. Elles échouent parce que les constructeurs et les gestionnaires de projets de petite à moyenne taille s'appuient sur des **tableurs d'estimation de la construction** monolithiques où la tarification par corps d'état, la logistique de chantier, les pertes de matériaux et les quantités physiques sont soudées dans une seule cellule. Lorsqu'une entreprise générale reçoit des tarifs de sous-traitants mis à jour ou doit remettre une offre en utilisant une autre équipe de ossature, l'intégralité du devis quantitatif doit être reconstruite à la main.

Dans une estimation récente d'extension à deux étages de 260 000 £, le constructeur principal a appliqué une marge forfaitaire habituelle de 15 % à un taux composite de maçonnerie au mètre carré. Toutefois, le chantier était desservi par une ruelle arrière à accès restreint nécessitant un transport en petit engin, et les briques de parement sur mesure comportaient un facteur de perte de coupe de 10 % au lieu du standard de 5 %. Comme le taux était un nombre composite codé en dur, les 4 200 £ supplémentaires de surconsommation de briques et les 3 800 £ de location d'engins prolongée n'ont jamais été imputés à la base du chantier. L'offre semblait compétitive, mais à l'achèvement, l'entreprise a réalisé une marge nette de 3,4 % au lieu des 16 % ciblées — ce qui a totalement éliminé la trésorerie d'exploitation.

J'ai développé ce **moteur d'estimation de la construction** pour éliminer définitivement ce mode de défaillance. Au lieu de traiter une estimation comme une toile arithmétique statique, cet outil industrialise l'ingénierie de coûts commerciale : il sépare la géométrie physique immuable d'un bâtiment des taux de main-d'œuvre par corps d'état volatils, isole les frais généraux de chantier et répercute dynamiquement les marges commerciales sur les livrables clients.

---

## Les problèmes d'estimation résidentielle courants que cet outil résout

| Problème d'estimation et de métré | Limites des tableurs traditionnels | Solution du moteur de métré automatisé |
| :--- | :--- | :--- |
| **Couplage des quantités et de la tarification de la main-d'œuvre** | Retarifier un appel d'offres avec un nouveau sous-traitant impose de ressaisir les dimensions du projet et de recopier les formules sur des dizaines de lignes du devis quantitatif. | Les quantités de métré physique restent intactes ; changer l'entreprise dans la liste déroulante de `01_Setup` réindexe tous les taux de main-d'œuvre, d'engins et de matériaux en moins d'une seconde. |
| **Sous-estimation silencieuse des pertes de matériaux** | Les marges forfaituelles en pourcentage appliquées aux totaux ne couvrent pas les pertes de coupe sur la maçonnerie, les carrelages et le bois de structure de forte valeur. | Une logique hiérarchisée spécifique à chaque poste applique des paramètres de perte dédiés aux quantités d'achat avant la tarification, garantissant des **estimations de métré** exactes. |
| **Fuite des concessions sur les frais de chantier** | L'échafaudage, la location de bennes et la gestion de projet sont présentés en forfaits transparents, que les clients négocient régulièrement à la baisse lors de la revue du contrat. | Les frais généraux de chantier et les frais généraux d'entreprise sont mathématiquement absorbés dans les taux client mixtes, garantissant que la récupération des frais généraux est protégée dans les prix unitaires contractuels. |
| **Dérive des formules et références rompues** | L'ajout de postes structurels imprévus impose l'insertion manuelle de lignes et le glissement de formules, laissant souvent des lignes exclues des totaux. | Les matricules dynamiques modernes à point d'entrée unique intègrent automatiquement les nouvelles lignes et propagent les sommes sur toutes les feuilles d'analyse pour un **métré de chantier** infaillible. |
| **Exposition du client aux marges commerciales** | Les estimateurs passent des heures à assainir manuellement les tableurs de calcul interne en devis client, risquant de divulguer accidentellement les marges par corps d'état. | Une feuille client entièrement découplée lit le moteur central et affiche des rubriques de travaux propres tout en masquant complètement les taux internes par corps d'état et les marges bénéficiaires. |

---

## Utilisateurs cibles et scénarios d'estimation spécifiques

Ce modèle fait office d'ERP léger pour les professionnels de la construction qui gèrent des contrats résidentiels. 

- **Constructeurs résidentiels et entreprises générales (£100k–£500k)** : entreprises générales utilisant ce **logiciel d'estimation pour extensions de maisons**, les rénovations complètes de logement et les **modèles de métré pour conversion de combles** afin de sécuriser des marges internes défendables avant la signature de contrats JCT à prix ferme.
- **Économistes de la construction et consultants en estimation** : professionnels gérant plusieurs fichiers de taux de sous-traitants qui ont besoin d'un **modèle de tarification de devis quantitatif** évolutif et d'un **classeur Excel de bordereau d'appel d'offres** reproductible, sans avoir à maintenir une infrastructure d'entreprise fragile et complexe.
- **Promoteurs immobiliers et auto-constructeurs** : opérateurs recherchant un **calculateur de coût de construction de maison** transparent et un outil de référence ascendante pour examiner les offres des entreprises et repérer les postes de corps d'état surchargés.

*Non conçu pour* : les projets de génie civil de grande hauteur dans le commerce exigeant des devis quantitatifs complets de consultants selon SMM7/NRM2, les ERP comptables multi-utilisateurs d'entreprise, ou l'extraction automatisée directe de polygones CAD/BIM.

Aucune expertise en tableur n'est nécessaire. Ouvrez l'application gratuite dans le navigateur et commencez à estimer immédiatement. Besoin de la version bureau robuste ? [Acheter le modèle Excel d'estimation professionnel avec une garantie de remboursement de 30 jours](https://theseusworkshop.com/l/arnghy?utm_source=github&utm_medium=GitHub%20README).

---

## À propos du développeur

Je développe des outils d'aide à la décision industrialisés et des modèles opérationnels légers pour des environnements où les pièces sont simplement trop nombreuses pour être gérées à l'intuition. Dans la construction résidentielle, les oublis d'estimation à un seul point se transforment en défaillances structurelles de trésorerie. Mon travail consiste à répondre à une question fondamentale : *« De quelles informations ai-je besoin, réunies en un seul endroit, pour prendre la prochaine décision commerciale avec une confiance absolue ? »* Le **moteur d'estimation de la construction résidentielle britannique** est la traduction exacte de cette approche.

---


## Détails techniques

<details>
<summary>Pour les réviseurs techniques, les praticiens d'Excel et les collaborateurs</summary>

### Architecture du classeur

Le système fonctionne à travers quatre couches fonctionnelles distinctes réparties sur huit feuilles de calcul. Les données s'écoulent strictement dans un seul sens (Configuration $\rightarrow$ Données de base $\rightarrow$ Calcul $\rightarrow$ Sortie), éliminant les références circulaires et garantissant l'intégrité des données :

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

| Couche | Nom de la feuille de calcul | Responsabilité opérationnelle | Type d'entrée / de formule |
| :--- | :--- | :--- | :--- |
| **01. Contrôle** | `01_Setup` | Contient toutes les variables de configuration globales, les métadonnées de l'entreprise, les marges cibles et les déclencheurs de la liste déroulante des entreprises. | Saisies utilisateur et listes dynamiques |
| **02. Données de base** | `02_Item_Master` | Définit le WBS standard, les codes de corps d'état (`GW`, `MAS`, `CAR`, etc.), les unités de mesure et la perte de matériaux par défaut. | Taxonomie de base (statique / ajout) |
| **02. Données de base** | `03_Rate_Library` | Maintient des vecteurs de coûts multi-entreprises pour la main-d'œuvre, les matériaux, la sous-traitance et les engins. | Tables de tarification relationnelles |
| **03. Calcul** | `04_Project_Estimate` | Espace de travail principal. Intègre les quantités de métré, évalue la perte effective, rapproche les taux des entreprises et agrège les lignes de coûts directs. | Matricules dynamiques à point d'entrée unique |
| **03. Calcul** | `05_Adjustments` | Isole les frais généraux de chantier, les durées d'échafaudage et de bennes, et les allowances provisionnelles client. | Bordereaux d'articles structurés |
| **04. Reporting** | `06_Internal_Estimate` | Construit la cascade commerciale complète : coûts directs + frais de chantier = coût principal $\rightarrow$ frais généraux et bénéfices $\rightarrow$ aléas $\rightarrow$ seuil de rentabilité. | Agrégation dynamique par section |
| **04. Reporting** | `07_Customer_Estimate` | Synthétise un bordereau de devis client auditable et désensibilisé, en mélangeant les frais généraux dans les taux unitaires. | Matricules dynamiques désensibilisés |
| **04. Gouvernance** | `08_Checks` | Exécute en continu 6 contrôles d'intégrité des données, la détection des codes non mappés, les alertes de taux manquants et le rapprochement de la balance. | Audits booléens automatisés et analyse d'écarts |

---

### Trois pièges qui piègent même les estimateurs expérimentés

#### Piège 1 : compression des taux de sous-traitant fusionnés
1. **Décision prise** : un estimateur applique un taux historique agrégé de 85,00 £/m² à un lot de 140 m² de bloc-maçonnerie et de maçonnerie de briques, en supposant que la main-d'œuvre et les matériaux s'équilibreront sur la base d'un chantier précédent.
2. **Le défaut non remarqué** : le projet utilise des briques de parement water-struck traditionnelles (1 150 £/1 000 briques) au lieu de briques d'ingénierie standard (450 £/1 000 briques), et le chantier est desservi par un chemin étroit non goudronné imposant un transport manuel à la brouette.
3. **Impact du défaut** : le coût réel des matériaux grimpe à 62,00 £/m² et la main-d'œuvre à 48,00 £/m², soit un coût direct total de 110,00 £/m².
4. **Pourquoi le raisonnement est faux** : les taux agrégés masquent les variations de répartition des ressources. La maçonnerie est rarement répartie à 50/50 ; l'inflation des matériaux et la logistique de chantier découplent la main-d'œuvre et la vitesse d'approvisionnement.
5. **Approche corrigée** : décomposer les coûts directs en quatre vecteurs distincts (main-d'œuvre, matériaux, sous-traitance, engins) reliés directement à la bibliothèque de taux de l'entreprise concernée.
6. **Résultat corrigé** : le coût réel est signalé à 110,00 £/m² de coût direct, ce qui tarifie la ligne à 15 400 £ au lieu de 11 900 £, protégeant 3 500 £ de trésorerie nette.

<details>
<summary>Voir la logique de correspondance des taux multi-vecteurs</summary>

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

#### Piège 2 : pertes non composées sur les quantités nettes
1. **Décision prise** : pour une dalle de rez-de-chaussée et un mur à cavité, l'estimateur relève 100 m² de carrelage de sol et 80 m² de maçonnerie de briques de parement sur le plan CAD, en appliquant un aléa budgétaire global standard de 5 % au niveau du récapitulatif de l'appel d'offres.
2. **Le défaut non remarqué** : les poses de carrelage en diagonale dans une pièce en L génèrent 12 % de chutes ; les briques de parement autour de baies décalées produisent 8 % de perte.
3. **Impact du défaut** : l'entreprise sous-commande 7 m² de carrelage et 6,4 m² de maçonnerie, ce qui l'oblige à un réapprovisionnement d'urgence à des prix de petites séries majorés et immobilise les carreleurs pendant trois jours.
4. **Pourquoi le raisonnement est faux** : la perte est une réalité géométrique, pas un aléa financier. Un aléa financier ne peut pas remplacer des palettes manquantes de carrelage d'un même lot.
5. **Approche corrigée** : calculer le volume net d'approvisionnement avant la tarification unitaire à l'aide d'une hiérarchie à niveaux : Correction manuelle % $>$ Référence de l'article maître % $>$ Valeur par défaut globale %.
6. **Résultat corrigé** : les volumes d'approvisionnement sont correctement dimensionnés à 112 m² pour le carrelage et 86,4 m² pour les briques, supprimant le fret d'urgence et les interruptions de chantier.

<details>
<summary>Voir la logique de détermination de la perte effective</summary>

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

#### Piège 3 : postes de frais de chantier transparents négociés à la baisse par les clients
1. **Décision prise** : l'entreprise inscrit l'échafaudage (6 500 £), les sanitaires mobiles et le bien-être de chantier (1 800 £) ainsi que la conduite des travaux par un superviseur de chantier (9 000 £) comme postes explicites sur le devis client.
2. **Le défaut non remarqué** : le client argue : *« Je ne veux pas payer 1 800 £ pour un sanitaire portable et votre devis d'échafaudage est plus cher que ce que mon ami a payé ; retirez ces lignes ou je trouverai un autre constructeur. »*
3. **Impact du défaut** : pour décrocher le contrat, l'entreprise retire 8 300 £ de frais de chantier du contrat, comptant les « absorber dans les bénéfices généraux ».
4. **Pourquoi le raisonnement est faux** : les frais de chantier sont des dépenses d'exploitation directes et rigides, et non une marge discrétionnaire. Supprimer la ligne ne réduit ni le bien-être de chantier ni les coûts de location d'échafaudage.
5. **Approche corrigée** : maintenir une visibilité interne absolue sur les frais de chantier dans `05_Adjustments` et `06_Internal_Estimate`, mais les absorber dynamiquement dans le bordereau client via une répartition proportionnelle de la marge sur les sections de travaux physiques.
6. **Résultat corrigé** : le client reçoit un bordereau de travaux propre où tous les frais de chantier et frais généraux sont mathématiquement intégrés dans les taux unitaires par corps d'état, rendant la logistique non négociable.

<details>
<summary>Voir la logique d'absorption proportionnelle de la marge</summary>

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

### Scénario d'exemple : extension et conversion de combles dans le Hertfordshire

#### 1. Données d'entrée brutes (`01_Setup` et `04_Project_Estimate`)
- **Projet** : extension enveloppante de 45 m² au rez-de-chaussée + conversion de combles avec lucarne arrière.
- **Entreprise sélectionnée** : `Apex_Builders_Herts`
- **Paramètres globaux** : perte par défaut = 5,0 %, mode frais de chantier = Fixe (`05_Adjustments`), OHP = 15,0 %, aléas = 5,0 %, TVA = 20,0 %.
- **Principaux métrés mesurés** :
  - `GW-001` (excavation de fondations en bande) : $24.0\,\text{m}^3$
  - `GW-002` (béton prêt à l'emploi C20/25 coulé) : $16.5\,\text{m}^3$ (perte standard 5,0 %)
  - `MAS-001` (maçonnerie de briques de parement de 102,5 mm) : $68.0\,\text{m}^2$ (perte corrigée manuellement : 8,0 %)
  - `STL-001` (poutres universelles en acier de structure fabricate et hissées) : $1.85\,\text{t}$
  - `ROO-001` (tuiles béton interlocking) : $52.0\,\text{m}^2$ (perte standard 8,0 %)
- **Ajustements saisis (`05_Adjustments`)** :
  - Échafaudage indépendant (location 10 semaines) : 4 800,00 £
  - Évacuation des déchets de chantier (4 bennes de 8 yards) : 1 440,00 £
  - Bien-être de chantier temporaire et stockage sécurisé : 1 250,00 £
  - Somme provisionnelle (allocation pour les meubles de cuisine et les appareils) : 20 000,00 £

#### 2. Calculs intermédiaires du moteur (`04_Project_Estimate`)
- `MAS-001` quantité nette calculée : $68.0 \times (1 + 0.08) = 73.44\,\text{m}^2$
→- `MAS-001` taux de l'entreprise : main-d'œuvre 42,00 £, matériaux 48,50 £, sous-traitance 0,00 £, engins 4,50 £ $\rightarrow$ taux composite = 95,00 £/m²
- `MAS-001` coût direct de la ligne : $73.44\,\text{m}^2 \times £95.00 = £6,976.80$
- Coûts directs agrégés du projet ($\sum \text{coût direct}$ pour tous les corps d'état) : **112 450,00 £**

#### 3. Cascade commerciale (`06_Internal_Estimate`)
$$\begin{aligned}
\text{Coût direct total} &= £112,450.00 \\
\text{Frais de chantier total} &= £7,490.00 \\
\hline
\mathbf{\text{Coût principal}} &= £119,940.00 \\
\text{Frais généraux \& bénéfices (15.0\% sur le coût principal)} &= £17,991.00 \\
\text{Aléas (5.0\% sur le coût principal)} &= £5,997.00 \\
\text{Sommes provisionnelles} &= £20,000.00 \\
\hline
\mathbf{\text{Montant total du contrat interne brut (HT)}} &= \mathbf{£163,928.00} \\
\text{Plancher de rentabilité (direct + frais de chantier)} &= £119,940.00 \\
\text{Marge brute cible du projet} &= \frac{£163,928 - £119,940}{£163,928} = \mathbf{26.83\%} \quad (\text{comprend les sommes provisionnelles})
\end{aligned}$$

#### 4. Interprétation analytique et recommandation
- **Multiplicateur de marge** : facteur d'absorption proportionnel appliqué aux postes client :
  $$\text{Markup Factor} = \frac{£163,928 - £20,000}{£112,450} = 1.27993$$
- **Traduction destinée au client** : le client voit `MAS-001` tarifé à $£95.00 \times 1.27993 = \mathbf{£121.59/\text{m}^2}$, soit un total de ligne de 8 929,57 £.
- **Résultat de la décision** : l'entreprise soumissionne à **163 928,00 £ + TVA (196 713,60 £ TTC)**. Aucun poste de frais de chantier individuel n'est exposé au contrôle client ligne par ligne, et le coussin commercial de 23 988 £ de l'entreprise (OHP + aléas) reste protégé.

---

### Référence des formules

<details>
<summary>01_Setup : indexation dynamique des entreprises</summary>

```excel
=SORT(UNIQUE(FILTER('03_Rate_Library'!A4:A500, '03_Rate_Library'!A4:A500<>"")))
```
*Objet* : extrait un vecteur trié et unique des entreprises actives à partir de la matrice de taux pour alimenter dynamiquement la validation de données de la cellule `$C$5`.
</details>

<details>
<summary>04_Project_Estimate : multiplication du vecteur complet des coûts directs</summary>

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
*Objet* : exécute un débordement horizontal de 5 colonnes (Q à U) multipliant les quantités nettes par les vecteurs de coûts en quatre composantes et par les taux composites, simultanément.
</details>

<details>
<summary>06_Internal_Estimate : agrégation dynamique des sections de travaux</summary>

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
*Objet* : regroupe dynamiquement toutes les dépenses directes du projet par corps d'état respectifs, sans nécessiter de lignes prédéfinies.
</details>

<details>
<summary>08_Checks : rapprochement mathématique de la balance</summary>

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
*Objet* : effectue une vérification stricte de l'équilibre entre les appels d'offres destinés au client et les coûts internes de marge.
</details>

---

### Règles de validation

| Feuille de calcul | Cellule / Plage | Cible de la règle | Règle de validation | Comportement en cas d'erreur |
| :--- | :--- | :--- | :--- | :--- |
| `01_Setup` | `$C$5` | Entreprise active | Liste déroulante liée à `='01_Setup'!$F$4#` | Rejette les noms d'entreprise non enregistrés. |
| `01_Setup` | `$C$6:$C$11` | Pourcentages financiers | Validation numérique : $\ge 0.0\%$ et $\le 100.0\%$ | Empêche les saisies de TVA ou de marge négatives ou mathématiquement catastrophiques. |
| `02_Item_Master` | `A4:A500` | Code article maître | Chaîne de texte unique ; les doublons sont audités dans `08_Checks` | Signale un avertissement dans le tableau de bord de gouvernance si la clé maîtresse est dupliquée. |
| `04_Project_Estimate` | `A4:A500` | Code de poste de métré | Doit exister dans `02_Item_Master!A4:A500` | Affiche `"⚠️ Unregistered Code"` dans la description et déclenche un échec d'audit dans `08_Checks`. |
| `04_Project_Estimate` | `B4:B500` | Quantité mesurée | Valeur numérique $\ge 0$ | La formule supprime les calculs si la quantité est omise ou non numérique. |
| `04_Project_Estimate` | `N4:N500` | Correction du taux | Valeur numérique $> 0$ | Exige un texte d'explication obligatoire dans la colonne O (`Override_Reason`). |
| `08_Checks` | `$C$9` | Contrôle de l'équilibre du modèle | $| \text{net client} - \text{brut interne} | \le 0.01$ | Affiche un signal rouge appuyé : `"❌ FAIL: Imbalance detected"`. |

</details>

---


## Logique métier et méthodologie

Ce système repose sur une **décomposition en trois niveaux de l'économie unitaire** associée à un **modèle de coûts par absorption proportionnelle**. L'estimation de construction traditionnelle s'appuie sur des taux unitaires historiques bruts (par exemple, 2 200 £ par mètre carré de surface intérieure brute), ce qui masque les écarts par corps d'état, les contraintes topographiques du chantier et les perturbations de l'offre de marché.

Pour résoudre ce problème, le moteur impose un découplage strict :
1. **Couche des quantités physiques** : capture le métré géométrique réel avec des facteurs de perte de matériaux dédiés.
2. **Matrice de tarification des ressources** : décompose chaque tâche de construction standard en ses quatre composantes commerciales fondamentales (main-d'œuvre, matériaux, sous-traitance, engins), reliées dynamiquement aux entreprises de corps d'état désignées.
3. **Cascade à double marge** : distingue les coûts de production directs des frais de chantier spécifiques afin d'établir une **base de coût principal**. Les frais généraux d'entreprise, les marges bénéficiaires et les aléas de projet sont ensuite appliqués à cette base consolidée, établissant un plancher de rentabilité infranchissable.

Pour éviter l'érosion des marges côté client lors des négociations commerciales d'appel d'offres, le bordereau destiné au client utilise l'**absorption proportionnelle**. Plutôt que de présenter les frais de chantier, la marge de l'entreprise et les réserves de risque comme des sommes discrétionnaires isolées, le moteur répartit mathématiquement ces charges sur les postes physiques facturables. Le bordereau client qui en résulte s'aligne au centime près sur l'évaluation commerciale interne, tout en protégeant complètement les marges sensibles par corps d'état.

---

## Autres outils de cette série

- **[Moteur de comparaison des devis de sous-traitants et d'analyse des écarts](#)** : examine plusieurs offres de corps d'état par rapport aux estimations internes de référence afin de repérer les anomalies de tarification et les lacunes de périmètre.
- **[Planificateur de courbe en S des flux de trésorerie et des jalons de construction](#)** : convertit les bordereaux de devis quantitatifs en prévisions de situation mensuelles, suivi des retenues de garantie et tirages de besoin en fonds de roulement.
- **[Suivi du métré de chantier et des réalisations pour les projets résidentiels](#)** : système de contrôle des coûts après attribution suivant les commandes d'achat, les feuilles de temps de main-d'œuvre et les avenants par rapport aux référentiels d'appel d'offres initiaux.

---

## Licence

Ce projet est sous licence **Apache License 2.0**. Consultez le fichier [LICENSE](LICENSE) pour plus de détails.

