# Portfolio Nicola Aversa - Versione v5 Pro

## Struttura
- index.html
- assets/css/style.css
- assets/js/main.js
- assets/img/profile/
- assets/img/projects/
- assets/img/3d/
- assets/video/
- robots.txt
- sitemap.xml

## Note produzione
1. Quando scegli il dominio finale, aggiorna:
   - canonical in index.html
   - URL in sitemap.xml
   - riga Sitemap in robots.txt
2. Inserisci immagini reali dentro assets/img/.
3. Inserisci video brevi mp4 dentro assets/video/.
4. Il sito non usa form backend: i contatti aprono il client email tramite mailto.
5. Il sito non imposta cookie tramite JavaScript, non usa analytics, pixel, embed social o mappe esterne.

## Deploy
Carica questa cartella su Cloudflare come static assets oppure collegala a GitHub.


## Aggiornare foto e video

### Con upload manuale Cloudflare
Ogni modifica richiede un nuovo upload/deploy della cartella o dello ZIP aggiornato.

### Con GitHub collegato
Modifichi i file, fai commit/push e Cloudflare aggiorna automaticamente il sito.

Percorsi consigliati:
- assets/img/profile/nicola.jpg
- assets/img/projects/sea-garden.jpg
- assets/img/projects/notte-cerasia.jpg
- assets/img/3d/gadget-01.jpg
- assets/img/3d/prototipo-01.jpg
- assets/video/stampa-3d-demo.mp4


## v7 Interactive
Aggiunti:
- mini terminale interattivo
- pulsanti comando rapidi
- glow del mouse
- modale dettagli progetto
- pulsanti Dettagli sulle card progetto


## v8 Mobile Menu
Aggiunto:
- hamburger menu mobile
- sidebar laterale destra
- overlay scuro
- chiusura con X
- chiusura cliccando fuori
- chiusura automatica dopo click su link
- blocco scroll pagina quando il menu è aperto


## Social collegati
- GitHub: https://github.com/nicoave97
- LinkedIn: https://www.linkedin.com/in/nicola-aversa/

## Asset folders predisposte
- assets/img/profile/
- assets/img/projects/
- assets/img/3d/
- assets/video/

Ogni cartella contiene un README con nomi consigliati e formati.


## v10 SEO
Aggiunto:
- title ottimizzato per "Nicola Aversa"
- meta description ottimizzata
- meta keywords
- Open Graph
- Twitter card
- JSON-LD Person
- H1 con nome "Nicola Aversa"
- sitemap.xml con lastmod
- robots.txt predisposto

## Prima di andare online con dominio definitivo
Aggiorna in index.html:
- JSON-LD url: https://www.tuodominio.it/
- canonical: https://www.tuodominio.it/
- eventualmente og:url quando vuoi aggiungerlo
- eventuale og:image quando hai una immagine preview

Aggiorna in sitemap.xml:
- https://www.tuodominio.it/

Aggiorna in robots.txt:
- Sitemap: https://www.tuodominio.it/sitemap.xml

## Dopo la pubblicazione
- aggiungi il dominio a Google Search Console
- invia sitemap.xml
- usa URL Inspection per richiedere indicizzazione della homepage
