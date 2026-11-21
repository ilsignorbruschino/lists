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
formato: un elemento per riga
---
Breve descrizione. Si possono usare formule LaTeX come $x^2$.
```

Dopo uno o due minuti la nuova pagina compare sul sito e la lista è già cercabile.

Nota: nei titoli usa gli apici singoli `'...'` se contengono il simbolo `\`.
