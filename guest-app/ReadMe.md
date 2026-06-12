# Amandola Guest App

Guest App statica per gli ospiti della casa vacanze ad Amandola.  
Include informazioni utili, servizi, ristoranti, trasporti e contenuti multilingua.

## Struttura del progetto

index.html 
Amandola.html
Barconsigliati.html
ComeArrivare.html
Parcheggi.html
RaccoltaDifferenziata.html
Ristoranti consigliati.html
Servizi.html
robots.txt
css/
js/


## Indicizzazione

Il sito è privato e non deve essere indicizzato.  
Sono presenti:

- `robots.txt` con `Disallow: /`
- meta tag `<meta name="robots" content="noindex, nofollow">` in ogni pagina

## Multilingua

Il sistema multilingua usa attributi `data-i18n` e un dizionario JS.  
La lingua è salvata in `localStorage` con la chiave `guestapp_lang`.

## Aggiornamenti

Per aggiornare una pagina:

1. Modificare il file HTML
2. Caricarlo su GitHub con “Upload files”
3. GitHub Pages aggiorna automaticamente il sito

## QR Code

Il QR code deve puntare a:

https://tuonome.github.io/guest-app/


## Note

Questa Guest App non raccoglie dati e non utilizza cookie di tracciamento.
