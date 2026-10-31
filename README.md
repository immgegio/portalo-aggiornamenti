# Portalo Online – canale degli aggiornamenti

Questo repository contiene solo `canale.json`: il file che il programma Portalo Online legge per sapere se c'è una
versione nuova e quali chiavi di licenza sono state revocate.

- Qui non ci sono il programma, i dati dei clienti né chiavi segrete.
- `canale.json` è firmato (Ed25519): il programma rifiuta qualsiasi file non firmato dal venditore o modificato da
  altri.
- Il programma lo legge da `https://immgegio.github.io/portalo-aggiornamenti/canale.json` e, se non risponde, da
  `https://raw.githubusercontent.com/immgegio/portalo-aggiornamenti/main/canale.json`.

**Non rinominare il repository né l'account:** questi indirizzi sono scritti nelle copie già vendute.
