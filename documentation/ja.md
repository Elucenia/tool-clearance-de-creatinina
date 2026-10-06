<!-- ELUCENIA technical documentation · clearance-de-creatinina · ja · no clinical/professional/rights approval -->

# クレアチニンクリアランス（Cockcroft-Gault）

[条件・出典・許諾](https://elucenia.org/ja/tools/clearance-de-creatinina)

## 使い方

ポータルでツールを使用するか、ローカルHTTPサーバー経由でindex.htmlを開いてください。言語を選択し、項目を入力して計算してください。

## 入力項目と単位

### 年齢

`idade`

年 · 範囲: 18–110

### 体重

`peso`

kg · 範囲: 25–300

### 血清クレアチニン

`cr`

mg/dL · 範囲: 0.2–20

### 性別

`sexo`

- `F` — 女性
- `M` — 男性

## 方法の版

Cockcroft–Gault 1976：(140−年齢)×体重/(72×Cr)；女性係数0.85；体表面積非補正CrCl

## 記載された計算式

ClCr (mL/min) = \[(140 − 年齢) × 体重\] ÷ (72 × クレアチニン) × 0.85 女性の場合.

## 限界・対象集団

体表面積で補正しない、mL/min単位の歴史的なクレアチニンクリアランス推算です。実測糸球体濾過量や、体表面積で補正したCKD-EPI値と同じではありません。計算では入力した体重をそのまま用い、実体重、理想体重、補正体重を自動的に選択しません。非典型的な体格や筋肉量、クレアチニン値に影響する状態によって、推算の精度が損なわれる可能性があります。薬剤用量については、その薬剤の添付文書と個別のプロトコル、用いられる腎機能評価法、確認の必要性を検討してください。特に治療域が狭い場合は注意が必要です。結果だけで用量を処方するものではありません。

## 参考文献

- [Cockcroft DW, Gault MH. Prediction of creatinine clearance from serum creatinine. Nephron, 1976.](https://doi.org/10.1159/000180580)

- [Steffel J et al. 2021 EHRA Practical Guide on the use of non-vitamin K antagonist oral anticoagulants in patients with atrial fibrillation. Europace, 2021.](https://doi.org/10.1093/europace/euab065)

- [NIDDK drug-dosing guidance, reviewedOctober2024](https://www.niddk.nih.gov/research-funding/research-programs/kidney-clinical-research-epidemiology/laboratory/ckd-drug-dosing-providers)

## 技術テストの再現

このリポジトリのルートディレクトリでnode test.cjsを実行すると、記録された合成ケースを再実行できます。元の入力、期待結果、許容誤差は保持されています。技術テストは臨床的検証を意味しません。

```sh
node test.cjs
```

tool.jsonには出典、版、確認範囲が記録されています。examples.jsonには合成入力と期待結果が保持され、results.jsonには実際に得られた結果が記録されています。

[記録・参考文献](../tool.json) · [JavaScriptコード](../calculator.js) · [参照ケース](../examples.json) · [results.json](../results.json)

## 確認状況と使用条件

独立した臨床レビューは実施されていません。

このインターフェースは独自に作成した翻訳であり、公式版や認証済みの版ではありません。独立した臨床レビュー、専門家による言語レビュー、評価尺度等の権利許諾の確認は実施されていません。

式または分類の結果です。解釈、対応、適用可能性は専門家による評価と選択した出典に依存します。

## ライセンスと帰属表示

Apache-2.0はELUCENIAのコードにのみ適用されます。評価尺度等、出版物、翻訳、データの権利は、それぞれの権利者に帰属します。LICENSEとNOTICEを保持してください。

ELUCENIA · Felipe Guedes · Copyright © 2026

## 記録された結果

以下の情報は、合成例に対する手法の出力を保持したものです。独立した臨床的検証を示すものではありません。

### 1

ほとんどのDOACsの全量


### 2

ほとんどのDOACsの全量


### 3

DOACsの使用は制限される；ダビガトランは禁忌

