# Esercizi in C: AND, OR, NOT (Classe terza)

---

## Esercizio 1 – Operatore AND (`&&`): l'accesso alla palestra

Una palestra permette l'ingresso alla sala pesi solo a chi soddisfa **tutte** le seguenti condizioni. Scrivere un programma in C che legga da tastiera:

- l'età del cliente (intero);
- se l'abbonamento è in corso di validità (carattere `'S'` oppure `'N'`);
- l'ora di arrivo (intero da 0 a 23).

Il cliente può accedere alla sala pesi se e solo se:

- ha almeno 16 anni, **e**
- l'abbonamento è in corso di validità, **e**
- l'ora di arrivo è compresa tra le 8 e le 21 (estremi inclusi).

Il programma deve stampare `"Accesso consentito"` se tutte le condizioni sono soddisfatte, altrimenti `"Accesso negato"`.

**Richiesta:** utilizzare esclusivamente l'operatore `&&` per costruire un'unica condizione. Non sono ammessi `||` e `!`.

---

## Esercizio 2 – Operatore OR (`||`): il bonus scolastico

Una scuola assegna un bonus (borsa di studio) a uno studente se **almeno una** delle seguenti condizioni è verificata. Scrivere un programma in C che legga da tastiera:

- la media dei voti (numero reale);
- il reddito annuo della famiglia in euro (intero);
- il numero di fratelli iscritti alla stessa scuola (intero).

Lo studente ottiene il bonus se:

- la media dei voti è maggiore o uguale a 9, **oppure**
- il reddito familiare è inferiore a 15000 euro, **oppure**
- ha almeno 2 fratelli iscritti alla stessa scuola.

Il programma deve stampare `"Bonus assegnato"` se almeno una condizione è verificata, altrimenti `"Bonus non assegnato"`.

**Richiesta:** utilizzare esclusivamente l'operatore `||` per costruire un'unica condizione. Non sono ammessi `&&` e `!`.

---

## Esercizio 3 – Operatore NOT (`!`): il sistema di allarme

Un sistema di allarme domestico deve decidere se far suonare la sirena. Scrivere un programma in C che legga da tastiera tre valori interi, ciascuno uguale a `1` (vero) oppure `0` (falso):

- `sensore`: vale 1 se il sensore di movimento rileva un intruso;
- `disattivato`: vale 1 se il proprietario ha disattivato l'allarme con il codice;
- `manutenzione`: vale 1 se il sistema è in modalità manutenzione.

Il programma deve stampare:

- `"Sirena attiva"` se il sensore rileva un intruso **e** l'allarme **non** è disattivato **e** il sistema **non** è in manutenzione;
- `"Sirena spenta"` negli altri casi.

Inoltre, il programma deve stampare `"Sistema operativo"` se il sistema **non** è in modalità manutenzione, oppure `"Sistema fuori servizio"` in caso contrario.

**Richiesta:** utilizzare l'operatore `!` per negare le variabili `disattivato` e `manutenzione` direttamente nelle condizioni (per il solo collegamento tra le condizioni è ammesso l'uso di `&&`; l'attenzione dell'esercizio è sull'operatore `!`).

---

*Nota: per tutti gli esercizi usare solo le strutture di selezione (`if`, `else if`, `else`) e nessun ciclo.*
