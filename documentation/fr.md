<!-- ELUCENIA technical documentation · apgar-familiar · fr · no clinical/professional/rights approval -->

# APGAR familial

[conditions, sources et autorisations](https://elucenia.org/fr/outils/apgar-familiar)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Adaptation : je suis satisfait de l’aide que ma famille m’apporte lorsque quelque chose me préoccupe

`a`

- `0` — Presque jamais
- `1` — Parfois
- `2` — Presque toujours

### Participation : je suis satisfait de la façon dont ma famille échange avec moi et partage les problèmes

`p`

- `0` — Presque jamais
- `1` — Parfois
- `2` — Presque toujours

### Épanouissement : je suis satisfait de la façon dont ma famille accepte et soutient mon souhait de commencer de nouvelles activités ou de changer de direction

`g`

- `0` — Presque jamais
- `1` — Parfois
- `2` — Presque toujours

### Affection : je suis satisfait de la façon dont ma famille exprime son affection et réagit à mes émotions (colère, tristesse, amour)

`af`

- `0` — Presque jamais
- `1` — Parfois
- `2` — Presque toujours

### Résolution : je suis satisfait de la façon dont ma famille et moi partageons du temps ensemble

`r`

- `0` — Presque jamais
- `1` — Parfois
- `2` — Presque toujours

## Édition de la méthode

APGAR familial/Smilkstein 1978 : 5 items 0–2, total 0–10 ; adaptation portugaise citée Duarte 2020

## Formule documentée

Cinq items (Adaptation, Partenariat, croissance ou Growth, Affection et Résolution), notés chacun 2 (presque toujours), 1 (parfois) ou 0 (presque jamais). Total de 0 à 10.

## Limites et population

L’APGAR familial consigne la perception et la satisfaction du répondant concernant cinq aspects du fonctionnement familial ; ce n’est ni l’Apgar néonatal ni une évaluation objective de tous les membres. La définition originale de la famille inclut le patient et d’autres personnes engagées dans un soutien mutuel, sans exiger de parenté biologique. Les réponses peuvent indiquer la nécessité d’approfondir l’entretien, et non établir à elles seules un diagnostic familial. Le résumé de 1982 mentionne une étude chez des élèves taïwanais de 10 ans ou plus ; cela ne valide pas automatiquement tous les âges, toutes les cultures ou la formulation portugaise citée dans cette implémentation.

## Références

- [Smilkstein G. The family APGAR: a proposal for a family function test and its use by physicians. J Fam Pract, 1978.](https://pubmed.ncbi.nlm.nih.gov/660126/)

- [Smilkstein G, Ashworth C, Montano D. Validity and reliability of the family APGAR as a test of family function. J Fam Pract, 1982.](https://pubmed.ncbi.nlm.nih.gov/7097168/)

- [Duarte YAO. Tradução, adaptação transcultural e validação do "Family Apgar". Em: Família, Rede de Suporte Social e Idosos: Instrumentos de Avaliação. Blucher, 2020.](https://doi.org/10.5151/9788580394344-04)

- [Smilkstein1978](https://cdn-uat.mdedge.com/files/s3fs-public/jfp-archived-issues/1978-volume_6-7/JFP_1978-06_v6_i6_the-family-apgar-a-proposal-for-a-family.pdf)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
