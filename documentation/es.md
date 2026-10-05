<!-- ELUCENIA technical documentation · clearance-de-creatinina · es · no clinical/professional/rights approval -->

# Aclaramiento de creatinina (Cockcroft-Gault)

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/clearance-de-creatinina)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Edad

`idade`

años · intervalo: 18–110

### Peso

`peso`

kg · intervalo: 25–300

### Creatinina sérica

`cr`

mg/dL · intervalo: 0,2–20

### Sexo

`sexo`

- `F` — Femenino
- `M` — Masculino

## Edición del método

Cockcroft–Gault 1976: (140−edad)×peso/(72×Cr); factor femenino 0,85; ClCr no indexado

## Fórmula documentada

ClCr (mL/min) = \[(140 − edad) × peso\] ÷ (72 × creatinina) × 0,85 en mujeres.

## Límites y población

Estimación histórica del aclaramiento de creatinina en mL/min, sin indexación por superficie corporal; no equivale a la TFG medida ni al valor CKD-EPI indexado. El cálculo utiliza exactamente el peso introducido y no selecciona automáticamente el peso real, ideal o ajustado. Un tamaño corporal o una masa muscular atípicos y las condiciones que alteran la creatinina pueden perjudicar la estimación. Para dosificar un medicamento, compruebe su ficha técnica y el protocolo específicos, el método renal utilizado y la necesidad de confirmación, especialmente con un margen terapéutico estrecho. El resultado aislado no prescribe una dosis.

## Referencias

- [Cockcroft DW, Gault MH. Prediction of creatinine clearance from serum creatinine. Nephron, 1976.](https://doi.org/10.1159/000180580)

- [Steffel J et al. 2021 EHRA Practical Guide on the use of non-vitamin K antagonist oral anticoagulants in patients with atrial fibrillation. Europace, 2021.](https://doi.org/10.1093/europace/euab065)

- [NIDDK drug-dosing guidance, reviewedOctober2024](https://www.niddk.nih.gov/research-funding/research-programs/kidney-clinical-research-epidemiology/laboratory/ckd-drug-dosing-providers)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
