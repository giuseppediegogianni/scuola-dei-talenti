---
tags: [libro, idea, tecnologia]
---

# Blockchain educativa

Un registro **immutabile e trasparente** dove ogni ragazzo accumula prove concrete dei suoi contributi nei diversi ambiti (scientifico, artistico, sociale, letterario, sportivo...) — un portfolio certificato che mostra cosa sa fare e cosa ha creato nel tempo, al posto dei soli voti su esami standardizzati.

## Architettura sensata
- **Non** una blockchain pubblica (Ethereum): troppo costosa, lenta e problematica per dati di minori.
- Una blockchain **permissioned** (consorzio): nodi gestiti da Ministero dell'Istruzione, uffici scolastici regionali, università, enti certificatori terzi.
- Precedente europeo: **EBSI** (European Blockchain Services Infrastructure), pensata per credenziali educative verificabili. Non si parte da zero.
- Regola d'oro: **sulla catena solo gli hash** (impronte crittografiche) delle attestazioni; i dati veri stanno in archivi protetti fuori catena. La blockchain garantisce solo che nessuno li abbia alterati.

## Identità digitale
- Ogni studente ha un'identità digitale sovrana: gestita dai genitori all'inizio, trasferita progressivamente al ragazzo.
- Aggancio possibile in Italia: SPID / CIE.
- Serve un "**wallet educativo**" pensato per minori — territorio quasi inesplorato.

## Standard tecnici già maturi (ma per adulti)
La ricerca su [[00 - Confronto scuole alternative]] mostra che gli standard esistono già: **Open Badges 3.0** (allineato al modello W3C Verifiable Credentials dal 2024) ed **Europass digitale**. Sono usati per micro-credenziali professionali e universitarie ([[Scuole/Technical school - VET duale]], [[Scuole/Online school]]), mai per un percorso continuo di minori.

### Un precedente universitario reale con badge su blockchain: Universidad de los Andes
Nel 2024 l'Universidad de los Andes (Bogotà, Colombia) ha introdotto credenziali digitali universitarie garantite da blockchain: lo studente avvia il percorso, ma il badge viene rilasciato solo dopo una **valutazione autentica delle competenze applicate** — non il completamento di un corso, ma la prova pratica — e l'ufficio di segreteria centrale verifica l'integrità prima di emettere il badge sicuro su blockchain. È un pezzo del sistema qui descritto già in produzione, anche se solo a livello universitario e non ancora per un percorso continuo dall'infanzia.

### Registro immutabile vs. vista attuale — un chiarimento architetturale
La blockchain resta un registro che **non cambia mai** ciò che è stato scritto: un blocco certifica che una competenza era vera in un momento preciso, per sempre. Ma questo non significa che la ragnatela mostrata oggi debba trattare quel blocco come ancora valido senza limiti di tempo — vedi [[Decadenza e rinnovo delle competenze]] per la distinzione tra il registro immutabile (livello 1) e la vista attuale calcolata (livello 2), che applica finestre di validità e pesi di recency senza mai toccare il registro storico.

## Limite chiave da ricordare
La blockchain risolve la **certificazione**, non la **scoperta** dei talenti. La tecnologia documenta; serve comunque un ambiente che permetta di sperimentare, sbagliare, scoprire (→ [[Visione - La scuola dei talenti]]).

Collegamenti: [[Il nodo GDPR e i minori]] · [[Il modello ibrido uomo-macchina]] · [[Cosa serve per scalare a livello nazionale]] · [[Decadenza e rinnovo delle competenze]]
