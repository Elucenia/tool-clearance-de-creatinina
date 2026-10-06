<!-- ELUCENIA technical documentation · clearance-de-creatinina · fr · no clinical/professional/rights approval -->

# Clairance de la créatinine (Cockcroft-Gault)

[conditions, sources et autorisations](https://elucenia.org/fr/outils/clearance-de-creatinina)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Âge

`idade`

ans · intervalle: 18–110

### Poids

`peso`

kg · intervalle: 25–300

### Créatinine sérique

`cr`

mg/dL · intervalle: 0,2–20

### Sexe

`sexo`

- `F` — Féminin
- `M` — Masculin

## Édition de la méthode

Cockcroft–Gault 1976 : (140−âge)×poids/(72×Cr) ; facteur féminin 0,85 ; clairance non indexée

## Formule documentée

ClCr (mL/min) = \[(140 − âge) × poids\] ÷ (72 × créatinine) × 0,85 chez la femme.

## Limites et population

Estimation historique de la clairance de la créatinine en mL/min, sans indexation sur la surface corporelle ; elle n’équivaut ni au DFG mesuré ni à la valeur CKD-EPI indexée. Le calcul utilise exactement le poids saisi et ne choisit pas automatiquement le poids réel, idéal ou ajusté. Une taille corporelle ou une masse musculaire atypiques et des situations modifiant la créatinine peuvent altérer l’estimation. Pour la posologie d’un médicament, vérifiez son résumé des caractéristiques et le protocole spécifiques, la méthode rénale utilisée et la nécessité d’une confirmation, notamment en cas de marge thérapeutique étroite. Le résultat isolé ne prescrit pas une dose.

## Références

- [Cockcroft DW, Gault MH. Prediction of creatinine clearance from serum creatinine. Nephron, 1976.](https://doi.org/10.1159/000180580)

- [Steffel J et al. 2021 EHRA Practical Guide on the use of non-vitamin K antagonist oral anticoagulants in patients with atrial fibrillation. Europace, 2021.](https://doi.org/10.1093/europace/euab065)

- [NIDDK drug-dosing guidance, reviewedOctober2024](https://www.niddk.nih.gov/research-funding/research-programs/kidney-clinical-research-epidemiology/laboratory/ckd-drug-dosing-providers)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Résultats documentés

Les informations ci-dessous conservent les sorties de la méthode pour des exemples synthétiques. Elles ne constituent pas une validation clinique indépendante.

### 1

Dose pleine de la plupart des AOD


### 2

Dose pleine de la plupart des AOD


### 3

Utilisation restreinte des AOD ; dabigatran contre-indiqué

