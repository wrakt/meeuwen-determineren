MEEUWEN EXACT V4 - IPHONE WEBAPP

INHOUD
- Complete offline webapp
- 5 soortfoto's
- 31 leeftijds- en kleedcategorieen
- Fotovergelijking en vergroting
- Manifest, app-iconen en serviceworker

PUBLICEREN
1. Pak het ZIP-bestand uit.
2. Upload de volledige map naar een HTTPS-webserver, bijvoorbeeld GitHub Pages, Netlify of eigen hosting.
3. Open de URL in Safari op de iPhone.
4. Tik op Deel > Zet op beginscherm.
5. Schakel Open als webapp in en tik op Voeg toe.

LOKAAL TESTEN
Voer in deze map uit: python3 -m http.server 8000
Open daarna http://localhost:8000 op de computer. Voor iPhone-installatie is een HTTPS-URL nodig.

LET OP
De leeftijdsbeelden zijn gemaakt uit de betreffende cursuspagina's. Controleer voor publicatie per foto de bronvermelding en het gebruiksrecht.

OPGELOST IN DEZE VERSIE
De opmaak en JavaScript staan ook in index.html zelf. Daardoor verschijnt niet langer alleen een kale titel wanneer losse CSS- of JS-bestanden niet worden geladen. Pak wel altijd de volledige ZIP uit.

VERSIE 3
Alle soort- en leeftijdsfoto's zijn in index.html ingebed. Hierdoor blijven de foto's zichtbaar, ook wanneer alleen index.html wordt gehost.
