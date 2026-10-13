# PalAIna – guida online

Pagina statica per GitHub Pages: spiega come funziona la PalAIna (pannello a LED con gli arrivi degli
autobus) e offre il manuale in PDF. Si raggiunge dal QR sul cartello dello stand.

- `index.html`: la pagina (nessuna dipendenza esterna), pensata per il telefono e per chi non è tecnico: testo semplice,
  disegni SVG scritti a mano dentro la pagina (colori con variabili CSS, chiari e scuri), nessun testo dentro le immagini.
  Il pannello in alto (e nei passi) è `img/display_arrivi.png`: quando c'è una foto del pannello acceso basta sostituire
  quell'`<img>` (c'è un commento nel codice).
- `img/`: immagini. Quelle `.webp` delle pagine di configurazione che la pagina non usa più (destinazione, display, riepilogo,
  live, alexa) restano prodotte da `tools/build_guida.py` per il manuale. `PalAIna_Manuale.pdf`: manuale. `qr/`: il QR della pagina.

Dati: Roma Servizi per la Mobilità (CC BY-SA 4.0). Indirizzi: © OpenStreetMap.
