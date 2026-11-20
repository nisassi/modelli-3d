# Forme allotropiche del carbonio – modelli 3D

Visualizzatori 3D interattivi di grafite, diamante, grafene, nanotubi di carbonio e fullereni.
Sito statico (HTML, CSS, JavaScript): nessuna libreria esterna, nessun servizio a pagamento.

## Pubblicazione su GitHub Pages

1. Su GitHub crea un repository **pubblico** chiamato `modelli-3d` nell'account `nisassi`.
2. Carica in questo repository il contenuto di questa cartella (il file `README.md` e la cartella `docs/`).
   Dalla pagina del repository: *Add file → Upload files*, trascina `docs` e `README.md`, poi *Commit changes*.
3. Vai in *Settings → Pages*. In *Build and deployment* scegli *Source: Deploy from a branch*,
   *Branch: main*, cartella **/docs**, poi *Save*.
4. Dopo 1–2 minuti il sito è raggiungibile a:
   `https://nisassi.github.io/modelli-3d/`

Indirizzi dei visualizzatori (quelli usati nei pulsanti della presentazione):

- https://nisassi.github.io/modelli-3d/grafite.html
- https://nisassi.github.io/modelli-3d/diamante.html
- https://nisassi.github.io/modelli-3d/grafene.html
- https://nisassi.github.io/modelli-3d/nanotubi.html
- https://nisassi.github.io/modelli-3d/fullereni.html

Se username o nome del repository sono diversi, gli indirizzi cambiano e vanno aggiornati i 5 collegamenti
nelle slide 4, 6, 8, 10 e 12 della presentazione (clic destro sul pulsante → Collegamento).

## Contenuto di `docs/`

- `index.html` – pagina iniziale con i cinque modelli
- `grafite.html`, `diamante.html`, `grafene.html`, `nanotubi.html`, `fullereni.html` – un visualizzatore ciascuno
- `assets/*.png` – immagini statiche di emergenza (si aprono dal riquadro «versione statica» di ogni pagina)
- `.nojekyll` – impedisce a GitHub di elaborare i file con Jekyll

## Uso offline

La cartella `docs/` è autonoma: aprendo `docs/index.html` con un doppio clic nel browser funziona anche senza Internet.

## Controlli dei visualizzatori

Trascina per ruotare (mouse o dito) · rotella o slider per lo zoom (5%–500%) · pulsanti −/+ Zoom e Reimposta ·
interruttori per rotazione automatica ed etichette · menu «Indicatore» · legenda nel pannello laterale.
