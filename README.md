# Due dritte su Napoli

Guida statica con 26 luoghi provvisori, cinque categorie, ricerca, filtri per zona e imperdibili, mappa con pin colorati e collegamenti a Google Maps.

Vicino a me usa il GPS con consenso oppure un punto indicativo della zona scelta. Le fasce entro 5 minuti, da 5 a 10, da 10 a 30 e oltre 30 sono stime: distanza in linea d’aria moltiplicata per 1,4 e velocità di 65 metri/minuto. Strade e dislivelli non vengono calcolati.

Non sono previsti itinerari o note personali. Verificare aperture e prenotazioni prima della visita.

Per pubblicare su GitHub Pages carica index.html nella root del repository e attiva Settings → Pages → Deploy from a branch → main / root. Il file contiene già tutto il codice applicativo; upgrade.js è una copia leggibile delle funzioni di prossimità. Leaflet e le mappe OpenStreetMap richiedono Internet. GPS disponibile su HTTPS o localhost.

Per personalizzare i luoghi modifica l’array places in index.html. luoghi.json è una copia dei dati iniziali.

Pulsante fisso “Riportami in hotel”: indicazioni Google Maps a piedi verso Grand Hotel Santa Lucia, Via Partenope 46, Napoli. Maps gestisce il punto di partenza e i permessi di posizione.
