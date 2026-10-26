# giorgiocardullo.it

Pagina del biglietto NFC di Giorgio Cardullo (omnistudio): due pulsanti, "Scrivimi su WhatsApp" e "Salva il mio contatto".

Sito statico, nessuna build: si pubblica copiando i file alla radice di giorgiocardullo.it.

- `index.html`: la pagina
- `giorgio-cardullo.vcf`: il contatto che si salva in rubrica (servirlo come `text/vcard` o `text/x-vcard`)
- `favicon.svg`: l'icona della scheda

Note:
- Il messaggio precompilato di WhatsApp cita la GEPI Expo: va aggiornato dopo la fiera (link `wa.me` in `index.html`).
- La pagina ha `<meta name="robots" content="noindex">`: toglierlo se deve comparire sui motori di ricerca.
- Copia provvisoria online su GitHub Pages: https://wrsgio.github.io/card/
