<!-- ELUCENIA technical documentation · clearance-de-creatinina · en · no clinical/professional/rights approval -->

# Creatinine clearance (Cockcroft–Gault)

[conditions, sources and permissions](https://elucenia.org/en/tools/clearance-de-creatinina)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Age

`idade`

years · range: 18–110

### Weight

`peso`

kg · range: 25–300

### Serum creatinine

`cr`

mg/dL · range: 0.2–20

### Sex

`sexo`

- `F` — Female
- `M` — Male

## Method edition

Cockcroft–Gault 1976: (140−age)×weight/(72×Cr); female factor 0.85; non-indexed CrCl

## Documented formula

ClCr (mL/min) = \[(140 − age) × weight\] ÷ (72 × creatinine) × 0.85 in women.

## Limits and population

Historical estimate of creatinine clearance in mL/min without body-surface-area indexing; it is not equivalent to measured GFR or the indexed CKD-EPI value. The calculation uses exactly the weight entered and does not automatically select actual, ideal or adjusted body weight. Atypical body size or muscle mass and conditions that alter creatinine may impair the estimate. For medication dosing, check the specific medicine’s label and protocol, the kidney-function method used and the need for confirmation, particularly with a narrow therapeutic index. The result alone does not prescribe a dose.

## References

- [Cockcroft DW, Gault MH. Prediction of creatinine clearance from serum creatinine. Nephron, 1976.](https://doi.org/10.1159/000180580)

- [Steffel J et al. 2021 EHRA Practical Guide on the use of non-vitamin K antagonist oral anticoagulants in patients with atrial fibrillation. Europace, 2021.](https://doi.org/10.1093/europace/euab065)

- [NIDDK drug-dosing guidance, reviewedOctober2024](https://www.niddk.nih.gov/research-funding/research-programs/kidney-clinical-research-epidemiology/laboratory/ckd-drug-dosing-providers)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
