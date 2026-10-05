<!-- ELUCENIA technical documentation · apgar-familiar · zh · no clinical/professional/rights approval -->

# 家庭 APGAR

[条件、来源与许可](https://elucenia.org/zh/tools/apgar-familiar)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 适应：有烦心事时，我满意家人给我的帮助

`a`

- `0` — 几乎从不
- `1` — 有时
- `2` — 几乎总是

### 合作：我满意家人与我交流及共同分担问题的方式

`p`

- `0` — 几乎从不
- `1` — 有时
- `2` — 几乎总是

### 成长：我满意家人接受并支持我开展新活动或改变方向的意愿

`g`

- `0` — 几乎从不
- `1` — 有时
- `2` — 几乎总是

### 情感：我满意家人表达关爱及回应我的情绪（愤怒、悲伤、爱）的方式

`af`

- `0` — 几乎从不
- `1` — 有时
- `2` — 几乎总是

### 亲密：我满意与家人共同度过时间的方式

`r`

- `0` — 几乎从不
- `1` — 有时
- `2` — 几乎总是

## 方法版本

家庭APGAR/Smilkstein 1978：5项，各0–2分，总分0–10；所引葡萄牙语改编Duarte 2020

## 已记录的公式

五个项目（适应、合作、成长，即 Growth, 、情感和解决问题），各计2分（几乎总是）、1分（有时）或0分（几乎从不）。总分0至10。

## 限制与适用人群

家庭APGAR记录回答者对家庭功能五个方面的感受与满意度；它不是新生儿Apgar，也不是对所有家庭成员的客观评估。原始家庭定义包括患者及承诺相互支持的其他人，不要求生物学亲属关系。回答可提示需要进一步访谈，不能单独确定家庭诊断。1982年的摘要提到一项针对台湾10岁及以上学生的研究；这不能自动验证所有年龄、文化或本实现所引用的葡萄牙语措辞。

## 参考文献

- [Smilkstein G. The family APGAR: a proposal for a family function test and its use by physicians. J Fam Pract, 1978.](https://pubmed.ncbi.nlm.nih.gov/660126/)

- [Smilkstein G, Ashworth C, Montano D. Validity and reliability of the family APGAR as a test of family function. J Fam Pract, 1982.](https://pubmed.ncbi.nlm.nih.gov/7097168/)

- [Duarte YAO. Tradução, adaptação transcultural e validação do "Family Apgar". Em: Família, Rede de Suporte Social e Idosos: Instrumentos de Avaliação. Blucher, 2020.](https://doi.org/10.5151/9788580394344-04)

- [Smilkstein1978](https://cdn-uat.mdedge.com/files/s3fs-public/jfp-archived-issues/1978-volume_6-7/JFP_1978-06_v6_i6_the-family-apgar-a-proposal-for-a-family.pdf)

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
