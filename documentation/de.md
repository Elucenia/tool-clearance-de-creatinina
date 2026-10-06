<!-- ELUCENIA technical documentation · clearance-de-creatinina · de · no clinical/professional/rights approval -->

# Kreatinin-Clearance (Cockcroft-Gault)

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/clearance-de-creatinina)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Alter

`idade`

Jahre · Bereich: 18–110

### Gewicht

`peso`

kg · Bereich: 25–300

### Serumkreatinin

`cr`

mg/dL · Bereich: 0,2–20

### Geschlecht

`sexo`

- `F` — Weiblich
- `M` — Männlich

## Fassung der Methode

Cockcroft–Gault 1976: (140−Alter)×Gewicht/(72×Cr); Faktor bei Frauen 0,85; nicht indexierte CrCl

## Dokumentierte Formel

ClCr (mL/min) = \[(140 − Alter) × Gewicht\] ÷ (72 × Kreatinin) × 0,85 bei Frauen.

## Grenzen und Population

Historischer Schätzwert der Kreatinin-Clearance in mL/min ohne Indexierung auf die Körperoberfläche; er entspricht weder der gemessenen GFR noch dem indexierten CKD-EPI-Wert. Die Berechnung verwendet genau das eingegebene Gewicht und wählt nicht automatisch tatsächliches, ideales oder angepasstes Körpergewicht aus. Atypische Körpermaße oder Muskelmasse sowie Zustände, die das Kreatinin verändern, können den Schätzwert beeinträchtigen. Prüfen Sie für die Arzneimitteldosierung die konkrete Fachinformation und das entsprechende Protokoll, die verwendete Methode zur Nierenfunktionsbestimmung und den Bedarf an einer Bestätigung, insbesondere bei geringer therapeutischer Breite. Der einzelne Wert legt keine Dosis fest.

## Referenzen

- [Cockcroft DW, Gault MH. Prediction of creatinine clearance from serum creatinine. Nephron, 1976.](https://doi.org/10.1159/000180580)

- [Steffel J et al. 2021 EHRA Practical Guide on the use of non-vitamin K antagonist oral anticoagulants in patients with atrial fibrillation. Europace, 2021.](https://doi.org/10.1093/europace/euab065)

- [NIDDK drug-dosing guidance, reviewedOctober2024](https://www.niddk.nih.gov/research-funding/research-programs/kidney-clinical-research-epidemiology/laboratory/ckd-drug-dosing-providers)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Dokumentierte Ergebnisse

Die folgenden Angaben bewahren die Ausgaben der Methode für synthetische Beispiele. Sie stellen keine unabhängige klinische Validierung dar.

### 1

Volle Dosis der meisten DOAKs


### 2

Volle Dosis der meisten DOAKs


### 3

Eingeschränkte Anwendung von DOAKs; Dabigatran kontraindiziert

