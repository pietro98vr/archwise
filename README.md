# ArchWise — supporto decisionale per protesi full-arch

Web app a pagina singola che guida il clinico, tramite un questionario passo-passo,
verso la riabilitazione protesica full-arch avvitata su impianti piu indicata, con
punteggio delle sei soluzioni, mappa decisionale a nodi e resoconto PDF stampabile.
Bilingue (IT/EN).

## Cos'e
- Questionario guidato "una domanda per volta" con comparsa allo scroll, senza
  risposte predefinite: il risultato compare solo dopo aver risposto a tutte le domande.
- Motore deterministico che riproduce il flowchart della classificazione, con un
  modello di punteggio pesato fondato sulla biomeccanica protesica (parafunzione,
  passive fit, cantilever, spazio protesico) e su letteratura Q1/Q2.
- Confronto delle sei soluzioni (Toronto, Natural bridge, Thimble, Titanio-Zirconia,
  Overdenture su barra, Full Zirconia) con spiegazione dei fattori e citazioni.
- Materiale del framework (Titanio vs Cromo-cobalto) integrato come variante di
  ciascuna soluzione: ogni disegno flessibile compare in due varianti a punteggio
  distinto (Cr-Co con spazio ridotto o cantilever esteso, Titanio negli altri casi).
- Resoconto decisionale in PDF (2 pagine): opzione consigliata, confronto,
  fattori, materiale e albero decisionale a nodi con la strada percorsa evidenziata.

La veste grafica e armonizzata con la palette turchese di Quintessenza Edizioni,
editore del libro di cui lo strumento fa parte.

## Basi scientifiche e crediti
Basata su: Gelpi F, Alberti C, Bevilacqua M, Montagna P, De Santis D, Tealdo T.
*A novel classification and a chart-making decision flow proposal for fixed
full-arch implant-supported prosthesis.* Eur J Musculoskelet Dis 2024;13(1):17-40.

- **Pietro Montagna** — sviluppo e ricerca scientifica
- **Federico Gelpi** — ricerca scientifica
- **Tiziano Tealdo** — supervisione

## Come si usa
Apri `index.html` in un browser moderno (Chrome, Edge, Safari, Firefox). Nessuna
installazione, nessuna connessione richiesta: l'app funziona interamente in locale.

## Pubblicazione su GitHub Pages
1. Crea un repository su GitHub (es. `archwise`).
2. Carica nella **radice** del repo: `index.html`, `favicon.svg`, `.nojekyll`, `README.md`.
3. Vai su **Settings -> Pages**.
4. In **Source** scegli **Deploy from a branch**.
5. Seleziona **Branch: `main`** e cartella **`/ (root)`**, poi **Save**.
6. Dopo circa un minuto l'app sara online su
   `https://<tuo-utente>.github.io/<nome-repo>/`.

Il file `.nojekyll` disattiva l'elaborazione Jekyll e serve i file cosi come sono.

## Privacy
L'app non invia alcun dato: input e risultati restano nel browser dell'utente.
I link a DOI/PubMed si aprono solo su clic esplicito.

## Avvertenza
Strumento di supporto alla decisione a fini informativi ed educativi. Non e un
dispositivo medico e non sostituisce l'esame clinico, la diagnosi e il giudizio
del professionista.
