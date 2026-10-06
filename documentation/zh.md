<!-- ELUCENIA technical documentation · clearance-de-creatinina · zh · no clinical/professional/rights approval -->

# 肌酐清除率（Cockcroft-Gault）

[条件、来源与许可](https://elucenia.org/zh/tools/clearance-de-creatinina)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 年龄

`idade`

年 · 范围: 18–110

### 体重

`peso`

kg · 范围: 25–300

### 血清肌酐

`cr`

mg/dL · 范围: 0.2–20

### 性别

`sexo`

- `F` — 女性
- `M` — 男性

## 方法版本

Cockcroft–Gault 1976：(140−年龄)×体重/(72×Cr)；女性系数0.85；非体表面积标准化CrCl

## 已记录的公式

ClCr (mL/min) = \[(140 − 年龄) × 体重\] ÷ (72 × 肌酐) × 0.85 女性.

## 限制与适用人群

这是以mL/min表示的历史性肌酐清除率估算，未按体表面积标化；不等同于实测肾小球滤过率，也不等同于CKD-EPI按体表面积标化的数值。计算直接使用所输入的体重，不会自动选择实际体重、理想体重或校正体重。非典型体型或肌肉量以及影响肌酐的情况可能使估算不准确。确定药物剂量时，应核对该药的说明书和具体方案、所采用的肾功能评估方法及是否需要确认，尤其是治疗窗狭窄的药物。单独的结果不会开具剂量处方。

## 参考文献

- [Cockcroft DW, Gault MH. Prediction of creatinine clearance from serum creatinine. Nephron, 1976.](https://doi.org/10.1159/000180580)

- [Steffel J et al. 2021 EHRA Practical Guide on the use of non-vitamin K antagonist oral anticoagulants in patients with atrial fibrillation. Europace, 2021.](https://doi.org/10.1093/europace/euab065)

- [NIDDK drug-dosing guidance, reviewedOctober2024](https://www.niddk.nih.gov/research-funding/research-programs/kidney-clinical-research-epidemiology/laboratory/ckd-drug-dosing-providers)

## 复现技术测试

在此仓库的根目录中运行 node test.cjs，以重复已记录的合成案例。原始输入、预期结果和容差保持不变。技术测试不构成临床验证。

```sh
node test.cjs
```

tool.json 包含来源、版本和审查范围。examples.json 保留合成输入与预期结果；results.json 记录实际得到的结果。

[记录与参考文献](../tool.json) · [JavaScript代码](../calculator.js) · [参考案例](../examples.json) · [results.json](../results.json)

## 审查与使用条件

尚未开展独立临床审查。

此界面为自主编写的翻译，并非官方或认证版本。尚未完成独立临床审查、专业语言审查或工具权利授权。

公式或分类结果。解释、处理及适用性须结合专业评估和所选来源。

## 许可与署名

Apache-2.0 仅适用于 ELUCENIA 代码。工具、出版物、翻译和数据的权利仍归各自权利人所有。请保留 LICENSE 和 NOTICE。

ELUCENIA · Felipe Guedes · Copyright © 2026

## 已记录的结果

以下信息保留该方法对合成示例的输出，不构成独立的临床验证。

### 1

大多数DOACs的全剂量


### 2

大多数DOACs的全剂量


### 3

DOACs使用受限；达比加群禁用

