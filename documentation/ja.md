<!-- ELUCENIA technical documentation · apgar-familiar · ja · no clinical/professional/rights approval -->

# 家族APGAR

[条件・出典・許諾](https://elucenia.org/ja/tools/apgar-familiar)

## 使い方

ポータルでツールを使用するか、ローカルHTTPサーバー経由でindex.htmlを開いてください。言語を選択し、項目を入力して計算してください。

## 入力項目と単位

### 適応：心配事があるときに家族から受ける助けに満足している

`a`

- `0` — ほとんどない
- `1` — ときどき
- `2` — ほぼいつも

### 協力：家族が話し合い、問題を分かち合うことに満足している

`p`

- `0` — ほとんどない
- `1` — ときどき
- `2` — ほぼいつも

### 成長：新しい活動や方向転換への希望を家族が受け入れ支えることに満足している

`g`

- `0` — ほとんどない
- `1` — ときどき
- `2` — ほぼいつも

### 愛情：家族の愛情表現と感情（怒り、悲しみ、愛）への反応に満足している

`af`

- `0` — ほとんどない
- `1` — ときどき
- `2` — ほぼいつも

### 親密さ：家族と一緒に時間を過ごすことに満足している

`r`

- `0` — ほとんどない
- `1` — ときどき
- `2` — ほぼいつも

## 方法の版

家族APGAR/Smilkstein 1978：5項目、各0～2点、合計0～10点；引用したポルトガル語版はDuarte 2020

## 記載された計算式

5項目（適応、協力、成長、すなわち Growth, 、愛情、問題解決）。各項目2点（ほぼいつも）、1点（ときどき）、0点（ほとんどない）。合計0～10点。

## 限界・対象集団

家族APGARは、家族機能の五側面に対する回答者の受け止め方と満足度を記録します。新生児Apgarではなく、全構成員の客観的評価でもありません。元の家族の定義は、生物学的血縁を必要とせず、患者と相互支援を約束した人々を含みます。回答は面接を深める必要性を示すことがありますが、それだけで家族の診断を確定しません。1982年の要旨には台湾の10歳以上の生徒の研究が記載されており、すべての年齢・文化や、この実装で引用したポルトガル語表現の妥当性を自動的に示すものではありません。

## 参考文献

- [Smilkstein G. The family APGAR: a proposal for a family function test and its use by physicians. J Fam Pract, 1978.](https://pubmed.ncbi.nlm.nih.gov/660126/)

- [Smilkstein G, Ashworth C, Montano D. Validity and reliability of the family APGAR as a test of family function. J Fam Pract, 1982.](https://pubmed.ncbi.nlm.nih.gov/7097168/)

- [Duarte YAO. Tradução, adaptação transcultural e validação do "Family Apgar". Em: Família, Rede de Suporte Social e Idosos: Instrumentos de Avaliação. Blucher, 2020.](https://doi.org/10.5151/9788580394344-04)

- [Smilkstein1978](https://cdn-uat.mdedge.com/files/s3fs-public/jfp-archived-issues/1978-volume_6-7/JFP_1978-06_v6_i6_the-family-apgar-a-proposal-for-a-family.pdf)

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
