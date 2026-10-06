<!-- ELUCENIA technical documentation · apgar-familiar · en · no clinical/professional/rights approval -->

# Family APGAR

[conditions, sources and permissions](https://elucenia.org/en/tools/apgar-familiar)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Adaptation: I am satisfied with the help I receive from my family when something worries me

`a`

- `0` — Almost never
- `1` — Sometimes
- `2` — Almost always

### Participation: I am satisfied with how my family talks with me and shares problems

`p`

- `0` — Almost never
- `1` — Sometimes
- `2` — Almost always

### Growth: I am satisfied with how my family accepts and supports my wishes to begin new activities or change direction

`g`

- `0` — Almost never
- `1` — Sometimes
- `2` — Almost always

### Affection: I am satisfied with how my family shows affection and responds to my emotions (anger, sadness, love)

`af`

- `0` — Almost never
- `1` — Sometimes
- `2` — Almost always

### Resolve: I am satisfied with how my family and I share time together

`r`

- `0` — Almost never
- `1` — Sometimes
- `2` — Almost always

## Method edition

Family APGAR/Smilkstein 1978: 5 items 0–2, total 0–10; cited Portuguese adaptation Duarte 2020

## Documented formula

Five items (Adaptation, Partnership, growth or Growth, Affection and Resolve), each scored 2 (almost always), 1 (sometimes) or 0 (hardly ever). Total 0 to 10.

## Limits and population

Family APGAR records the respondent’s perception and satisfaction with five aspects of family function; it is not neonatal Apgar or an objective assessment of all members. The original definition of family includes the patient and other people committed to mutual support, without requiring biological kinship. Responses may indicate a need to explore the interview further, not establish a family diagnosis by themselves. The 1982 abstract mentions a study in Taiwanese students aged 10 or older; this does not automatically validate every age, culture or the Portuguese wording cited in this implementation.

## References

- [Smilkstein G. The family APGAR: a proposal for a family function test and its use by physicians. J Fam Pract, 1978.](https://pubmed.ncbi.nlm.nih.gov/660126/)

- [Smilkstein G, Ashworth C, Montano D. Validity and reliability of the family APGAR as a test of family function. J Fam Pract, 1982.](https://pubmed.ncbi.nlm.nih.gov/7097168/)

- [Duarte YAO. Tradução, adaptação transcultural e validação do "Family Apgar". Em: Família, Rede de Suporte Social e Idosos: Instrumentos de Avaliação. Blucher, 2020.](https://doi.org/10.5151/9788580394344-04)

- [Smilkstein1978](https://cdn-uat.mdedge.com/files/s3fs-public/jfp-archived-issues/1978-volume_6-7/JFP_1978-06_v6_i6_the-family-apgar-a-proposal-for-a-family.pdf)

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

## Documented results

The information below preserves the method outputs for synthetic examples. It does not constitute independent clinical validation.

### 1

Good family functionality (7 to 10 points)


### 2

Good family functionality (7 to 10 points)


### 3

Moderate family dysfunction (4 to 6 points)

Explore the dimensions with the lowest score and follow up.


### 4

High family dysfunction (0 to 3 points)

Further assess the family (genogram, ecomap) and consider a family approach and support network.

