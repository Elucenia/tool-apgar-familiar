<!-- ELUCENIA technical documentation · apgar-familiar · it · no clinical/professional/rights approval -->

# APGAR familiare

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/apgar-familiar)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Adattamento: sono soddisfatto dell’aiuto della mia famiglia quando qualcosa mi preoccupa

`a`

- `0` — Quasi mai
- `1` — A volte
- `2` — Quasi sempre

### Partecipazione: sono soddisfatto di come la mia famiglia parla con me e condivide i problemi

`p`

- `0` — Quasi mai
- `1` — A volte
- `2` — Quasi sempre

### Crescita: sono soddisfatto di come la mia famiglia accetta e sostiene il mio desiderio di iniziare nuove attività o cambiare direzione

`g`

- `0` — Quasi mai
- `1` — A volte
- `2` — Quasi sempre

### Affetto: sono soddisfatto di come la mia famiglia esprime affetto e risponde alle mie emozioni (rabbia, tristezza, amore)

`af`

- `0` — Quasi mai
- `1` — A volte
- `2` — Quasi sempre

### Risoluzione: sono soddisfatto di come la mia famiglia e io condividiamo il tempo insieme

`r`

- `0` — Quasi mai
- `1` — A volte
- `2` — Quasi sempre

## Edizione del metodo

APGAR familiare/Smilkstein 1978: 5 item 0–2, totale 0–10; adattamento portoghese citato Duarte 2020

## Formula documentata

Cinque item (Adattamento, Partecipazione, crescita o Growth, Affetto e Risoluzione), ciascuno con 2 (quasi sempre), 1 (a volte) o 0 (quasi mai). Totale da 0 a 10.

## Limiti e popolazione

L’APGAR familiare registra la percezione e la soddisfazione del rispondente rispetto a cinque aspetti della funzione familiare; non è l’Apgar neonatale né una valutazione oggettiva di tutti i membri. La definizione originale di famiglia comprende il paziente e altre persone impegnate nel sostegno reciproco, senza richiedere parentela biologica. Le risposte possono indicare la necessità di approfondire il colloquio, non stabilire da sole una diagnosi familiare. L’abstract del 1982 menziona uno studio su studenti taiwanesi di almeno 10 anni; ciò non valida automaticamente ogni età, cultura o la formulazione portoghese citata in questa implementazione.

## Riferimenti

- [Smilkstein G. The family APGAR: a proposal for a family function test and its use by physicians. J Fam Pract, 1978.](https://pubmed.ncbi.nlm.nih.gov/660126/)

- [Smilkstein G, Ashworth C, Montano D. Validity and reliability of the family APGAR as a test of family function. J Fam Pract, 1982.](https://pubmed.ncbi.nlm.nih.gov/7097168/)

- [Duarte YAO. Tradução, adaptação transcultural e validação do "Family Apgar". Em: Família, Rede de Suporte Social e Idosos: Instrumentos de Avaliação. Blucher, 2020.](https://doi.org/10.5151/9788580394344-04)

- [Smilkstein1978](https://cdn-uat.mdedge.com/files/s3fs-public/jfp-archived-issues/1978-volume_6-7/JFP_1978-06_v6_i6_the-family-apgar-a-proposal-for-a-family.pdf)

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

## Risultati documentati

Le informazioni seguenti conservano gli output del metodo per esempi sintetici. Non costituiscono una validazione clinica indipendente.

### 1

Buona funzionalità familiare (7 a 10 punti)


### 2

Buona funzionalità familiare (7 a 10 punti)


### 3

Disfunzione familiare moderata (4 a 6 punti)

Esplorare le dimensioni con il punteggio più basso e fare follow-up.


### 4

Disfunzione familiare elevata (0 a 3 punti)

Approfondire la valutazione della famiglia (genogramma, ecomappa) e considerare un approccio familiare e la rete di supporto.

