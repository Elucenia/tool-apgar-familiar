<!-- ELUCENIA technical documentation · apgar-familiar · de · no clinical/professional/rights approval -->

# Familien-APGAR

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/apgar-familiar)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Anpassung: Ich bin mit der Hilfe meiner Familie zufrieden, wenn mich etwas beunruhigt

`a`

- `0` — Fast nie
- `1` — Manchmal
- `2` — Fast immer

### Beteiligung: Ich bin damit zufrieden, wie meine Familie mit mir spricht und Probleme gemeinsam angeht

`p`

- `0` — Fast nie
- `1` — Manchmal
- `2` — Fast immer

### Entwicklung: Ich bin zufrieden damit, wie meine Familie meine Wünsche nach neuen Aktivitäten oder einer neuen Richtung akzeptiert und unterstützt

`g`

- `0` — Fast nie
- `1` — Manchmal
- `2` — Fast immer

### Zuneigung: Ich bin zufrieden damit, wie meine Familie Zuneigung zeigt und auf meine Gefühle reagiert (Wut, Trauer, Liebe)

`af`

- `0` — Fast nie
- `1` — Manchmal
- `2` — Fast immer

### Gemeinsame Zeit: Ich bin zufrieden damit, wie meine Familie und ich Zeit miteinander verbringen

`r`

- `0` — Fast nie
- `1` — Manchmal
- `2` — Fast immer

## Fassung der Methode

Familien-APGAR/Smilkstein 1978: 5 Items 0–2, gesamt 0–10; zitierte portugiesische Adaptation Duarte 2020

## Dokumentierte Formel

Fünf Items (Anpassung, Partnerschaft, Entwicklung oder Growth, Zuneigung und Problemlösung), jeweils 2 (fast immer), 1 (manchmal) oder 0 (fast nie) Punkte. Gesamt 0 bis 10.

## Grenzen und Population

Der Familien-APGAR erfasst die Wahrnehmung und Zufriedenheit der antwortenden Person mit fünf Aspekten der Familienfunktion; er ist weder der neonatale Apgar noch eine objektive Bewertung aller Mitglieder. Die ursprüngliche Familiendefinition umfasst den Patienten und andere zur gegenseitigen Unterstützung verpflichtete Personen, ohne biologische Verwandtschaft zu verlangen. Antworten können Anlass für eine vertiefte Befragung sein, stellen aber allein keine Familiendiagnose. Das Abstract von 1982 erwähnt eine Studie bei taiwanischen Schülern ab 10 Jahren; dadurch werden nicht automatisch alle Altersgruppen, Kulturen oder die in dieser Implementierung zitierte portugiesische Formulierung validiert.

## Referenzen

- [Smilkstein G. The family APGAR: a proposal for a family function test and its use by physicians. J Fam Pract, 1978.](https://pubmed.ncbi.nlm.nih.gov/660126/)

- [Smilkstein G, Ashworth C, Montano D. Validity and reliability of the family APGAR as a test of family function. J Fam Pract, 1982.](https://pubmed.ncbi.nlm.nih.gov/7097168/)

- [Duarte YAO. Tradução, adaptação transcultural e validação do "Family Apgar". Em: Família, Rede de Suporte Social e Idosos: Instrumentos de Avaliação. Blucher, 2020.](https://doi.org/10.5151/9788580394344-04)

- [Smilkstein1978](https://cdn-uat.mdedge.com/files/s3fs-public/jfp-archived-issues/1978-volume_6-7/JFP_1978-06_v6_i6_the-family-apgar-a-proposal-for-a-family.pdf)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026
