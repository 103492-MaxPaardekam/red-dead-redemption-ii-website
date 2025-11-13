# Red Dead Redemption 2 - Museum De Pixel Expositie

Dit project is een interactieve webpagina, ontworpen als een "museumexpositie" over de game Red Dead Redemption 2. Het is opgezet als een subpagina voor de fictieve "Museum De Pixel" website.

De pagina functioneert als een **Single Page Application (SPA)**, waarbij alle content (Wereld, Karakters, Details) op één pagina wordt beheerd en dynamisch wordt weergegeven of verborgen met JavaScript.

## Features

* **Meertalige Ondersteuning:** De gehele pagina kan met één knop worden omgeschakeld tussen **Nederlands (nl)** en **Engels (en)**. Alle teksten worden dynamisch bijgewerkt vanuit een JavaScript-object.
* **Tab-Navigatie:** Drie hoofdsecties ("De Wereld & Verhaal", "De Van der Linde Gang", "Creatieve Keuzes & Details") die als tabbladen functioneren zonder dat de pagina opnieuw hoeft te laden.
* **Interactieve Modals (Pop-ups):**
    * **Karakter Pop-ups:** Bij het klikken op een karakterkaart (Arthur, Dutch, John) wordt een gedetailleerde modal geopend met meer informatie en een citaat.
    * **Afbeeldingsgalerij:** Een klikbare landschapsfoto opent een interactieve galerij-modal met navigatieknoppen (vorige/volgende).
* **Dynamische Content:** Alle content (teksten, karakterinfo, galerij-afbeeldingen) wordt beheerd vanuit JavaScript-objecten (`languageData`, `characterData`, `galleryImages`), wat onderhoud en vertalingen eenvoudig maakt.
* **Responsief Ontwerp:** De layout is gebouwd met CSS Grid en Flexbox en is schaalbaar.
* **Mobiele Navigatie:** Ondersteunt **swipe-gebaren** (links/rechts) om te wisselen tussen de drie hoofdsecties op mobiele apparaten.
* **Embedded Media:** Bevat een ingesloten YouTube-video.

## Gebruikte Technologieën

* **HTML5:** Voor de semantische structuur van de pagina.
* **CSS3:** Voor alle styling, layout (Flexbox, Grid), animaties en het responsieve ontwerp.
* **JavaScript (ES6+):**
    * DOM-manipulatie voor het tonen/verbergen van secties en modals.
    * Beheren van de taalwissel.
    * Dynamisch vullen van de content in de modals.
    * Event listeners voor alle interactiviteit (knoppen, kaarten, swipen).

## Hoe te gebruiken

Om dit project lokaal te bekijken:

1.  Zorg ervoor dat alle bestanden en mappen in de juiste structuur staan (zie hieronder).
2.  Open het `index.html` bestand in een moderne web browser (zoals Chrome, Firefox, of Edge).

## Bestandsstructuur

```

rdr2/
├── index.html          (Het hoofd-HTML-bestand)
├── css/
│   └── styles.css      (Alle styling)
├── js/
│   └── script.js       (Alle logica en content)
└── media/
├── logo.png
├── arthur.jpg
├── dutch.png
├── john.jpg
├── mountains.jpg
├── valley.jpg
├── swamps.jpg
└── desert.png

```

## Credits

* **Ontwikkelaar:** Max Paardekam (zoals vermeld in de footer)
* **Content:** Gebaseerd op *Red Dead Redemption 2* (ontwikkeld door Rockstar Games).
```
