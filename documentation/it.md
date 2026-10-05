<!-- ELUCENIA technical documentation · clearance-de-creatinina · it · no clinical/professional/rights approval -->

# Clearance della creatinina (Cockcroft-Gault)

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/clearance-de-creatinina)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Età

`idade`

anni · intervallo: 18–110

### Peso

`peso`

kg · intervallo: 25–300

### Creatinina sierica

`cr`

mg/dL · intervallo: 0,2–20

### Sesso

`sexo`

- `F` — Femminile
- `M` — Maschile

## Edizione del metodo

Cockcroft–Gault 1976: (140−età)×peso/(72×Cr); fattore femminile 0,85; clearance non indicizzata

## Formula documentata

ClCr (mL/min) = \[(140 − età) × peso\] ÷ (72 × creatinina) × 0,85 nelle donne.

## Limiti e popolazione

Stima storica della clearance della creatinina in mL/min, senza indicizzazione per superficie corporea; non equivale alla GFR misurata né al valore CKD-EPI indicizzato. Il calcolo usa esattamente il peso inserito e non sceglie automaticamente il peso corporeo reale, ideale o aggiustato. Dimensioni corporee o massa muscolare atipiche e condizioni che modificano la creatinina possono compromettere la stima. Per il dosaggio di un farmaco, verificare il riassunto delle caratteristiche del prodotto e il protocollo specifici, il metodo renale usato e la necessità di conferma, soprattutto in presenza di un indice terapeutico stretto. Il risultato isolato non prescrive una dose.

## Riferimenti

- [Cockcroft DW, Gault MH. Prediction of creatinine clearance from serum creatinine. Nephron, 1976.](https://doi.org/10.1159/000180580)

- [Steffel J et al. 2021 EHRA Practical Guide on the use of non-vitamin K antagonist oral anticoagulants in patients with atrial fibrillation. Europace, 2021.](https://doi.org/10.1093/europace/euab065)

- [NIDDK drug-dosing guidance, reviewedOctober2024](https://www.niddk.nih.gov/research-funding/research-programs/kidney-clinical-research-epidemiology/laboratory/ckd-drug-dosing-providers)

## Riprodurre i test tecnici

Esegua node test.cjs nella cartella principale di questo repository per ripetere i casi sintetici registrati. Gli input, i risultati attesi e le tolleranze originali sono conservati. I test tecnici non costituiscono validazione clinica.

```sh
node test.cjs
```

tool.json contiene le fonti, l’edizione e l’ambito della revisione. examples.json conserva gli input e i risultati attesi dei casi sintetici; results.json registra i risultati ottenuti.

[Scheda e riferimenti](../tool.json) · [Codice JavaScript](../calculator.js) · [Casi di riferimento](../examples.json) · [results.json](../results.json)

## Revisione e condizioni d’uso

Non è stata effettuata una revisione clinica indipendente.

Questa interfaccia è una traduzione realizzata dagli autori, non un’edizione ufficiale o certificata. Non sono state eseguite la revisione clinica indipendente, la revisione linguistica professionale né la verifica delle autorizzazioni relative ai diritti sugli strumenti.

Risultato della formula o classificazione. Interpretazione, condotta e applicabilità dipendono dalla valutazione professionale e dalla fonte selezionata.

## Licenza e attribuzione

Apache-2.0 si applica solo al codice di ELUCENIA. I diritti su strumenti, pubblicazioni, traduzioni e dati restano ai rispettivi titolari. Conservi LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
