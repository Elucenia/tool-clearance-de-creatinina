<!-- ELUCENIA technical documentation · clearance-de-creatinina · pt-BR · no clinical/professional/rights approval -->

# Clearance de creatinina (Cockcroft-Gault)

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/clearance-de-creatinina)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Idade

`idade`

anos · intervalo: 18–110

### Peso

`peso`

kg · intervalo: 25–300

### Creatinina sérica

`cr`

mg/dL · intervalo: 0,2–20

### Sexo

`sexo`

- `F` — Feminino
- `M` — Masculino

## Edição do método

Cockcroft Gault 1976:(140−idade)×peso/(72×Cr); fator mulher 0,85; Cl Crnãoindexado

## Fórmula documentada

ClCr (mL/min) = \[(140 − idade) × peso\] ÷ (72 × creatinina) × 0,85 nas mulheres.

## Limites e população

Estimativa histórica de clearance de creatinina em mL/min, sem indexação por superfície corporal; não equivale à TFG medida nem ao valor CKD-EPI indexado. O cálculo usa exatamente o peso informado e não escolhe automaticamente peso real, ideal ou ajustado. Tamanho corporal ou massa muscular atípicos e condições que alteram a creatinina podem prejudicar a estimativa. Para dose de medicamento, confira a bula e o protocolo específicos, o método renal usado e a necessidade de confirmação, sobretudo com margem terapêutica estreita. O resultado isolado não prescreve dose.

## Referências

- [Cockcroft DW, Gault MH. Prediction of creatinine clearance from serum creatinine. Nephron, 1976.](https://doi.org/10.1159/000180580)

- [Steffel J et al. 2021 EHRA Practical Guide on the use of non-vitamin K antagonist oral anticoagulants in patients with atrial fibrillation. Europace, 2021.](https://doi.org/10.1093/europace/euab065)

- [NIDDK drug-dosing guidance, reviewedOctober2024](https://www.niddk.nih.gov/research-funding/research-programs/kidney-clinical-research-epidemiology/laboratory/ckd-drug-dosing-providers)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
