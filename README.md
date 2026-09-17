<h2><span style="text-decoration: underline;"><strong>🛜 Fritz!box Info</strong></span></h2>

CARD per mostrare informazioni del nostro Fritz!box
<p><img src="example/example1.jpg" alt="" /></p>

<p>Volevo condividere una scheda che ho creato con l'aiuto delle varie community per visualizzare le informazioni di una persona tramite l'utilizzo dell'app HA companion.</p>

<p dir="auto">Istruzioni:</p>

da Hacs, installare:
1. button-card

poi ...
1. nel file sensor.yaml, inserire il contenuto di sensor.yaml, se non si dispone del file:
    - è necessario creare sensor.yaml nella cartella config/
    - aprire il file configuration.yaml e inserire questa riga: sensor: !include sensor.yaml
2. in HA create una card manuale e incollate il contenuto del file: card.yaml
3. all'interno del codice della card e del codice inserito nel sensor.yaml, dovete andare a sostituire tutti i sensori del mio fritz con quelli del vostro fritz (solitamente cambia il numero e basta).


<strong>Alla fine ci troveremo ad avere questo risultato finale:</strong><br />

<p><img src="example/example2.jpg" alt="" /></p>

<p><img src="example/example3.jpg" alt="" /></p>

<p>Enjoy!</p>

---

## ☕ Vuoi darmi una mano?

Il contenuto di questa pagina è completamente gratuito e lo scopo non è certamente fare soldi. Se vuoi darmi una mano per le spese e il tempo perso, ecco alcuni modi:

| | |
|---|---|
| [![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/C0C713VTGJ) | Offrimi un caffè su Ko-fi |
| [![PayPal](https://github.com/Simonz82/shared-assets/blob/main/paypal.svg)](https://www.paypal.com/paypalme/simongmail) | Una donazione libera su PayPal |
| [![Amazon](https://github.com/Simonz82/shared-assets/blob/main/Amazon_logo.png)](https://amzn.to/3XWWTgz) | Fai i tuoi acquisti Amazon partendo da questo link |

**Canali Telegram:**

| | |
|---|---|
| [![Home_Assistant_News](https://github.com/Simonz82/shared-assets/blob/main/home_assistant_news.jpg)](https://t.me/Home_Assistant_News) | Notizie dedicate a Home Assistant |
| [![Offerte Domotica](https://github.com/Simonz82/shared-assets/blob/main/offerte_domotica.jpg)](https://t.me/offerte_domotica_ita) | Offerte sui prodotti di domotica |

---

Sviluppato e curato da [Simonz82](https://t.me/Simonz82) · © 2026
