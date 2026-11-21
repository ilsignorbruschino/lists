# lists

Liste di oggetti matematici, ciascuna scaricabile come file di testo.

Sito: https://ilsignorbruschino.github.io/lists/

## Come aggiungere una lista

1. Carica il file di dati nella cartella `dati/`, per esempio `dati/L0004.txt`.
2. Crea una scheda nella cartella `_liste/` con lo stesso codice, per esempio `_liste/L0004.md`:

```markdown
---
codice: L0004
titolo: 'Titolo della lista'
parole_chiave: [parola1, parola2]
file: /dati/L0004.txt
elementi: 100
formato: una lista tra parentesi quadre, come [1,2,3,4]
---
Breve descrizione. Si possono usare formule LaTeX come $x^2$.
```

Dopo uno o due minuti la nuova pagina compare sul sito e la lista è già cercabile.

Il file di dati va salvato con codifica **UTF-8 con BOM**: nel Blocco note scegli *Salva con nome* e, alla voce Codifica, *UTF-8 con BOM*. Serve a evitare che alcuni programmi Windows mostrino caratteri cinesi al posto dei numeri.

Nota: nei titoli usa gli apici singoli `'...'` se contengono il simbolo `\`.
