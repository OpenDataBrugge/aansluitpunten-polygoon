# Stroomaansluitingen — v19 logische selectiemodi

Deze versie bouwt voort op v18 en maakt de interactie duidelijker.

Bovenaan de zijbalk staat nu een expliciete keuze:

- **1 punt — Klik op de kaart**
- **Meerdere punten — Teken een gebied**

Gedrag:

## 1 punt
- de teller met vorige/volgende is zichtbaar;
- een klik op een stroompunt toont één detailkaart;
- de individuele Kopieer-knop blijft behouden;
- gebiedstools zijn volledig verborgen.

## Meerdere punten
- de teller voor één punt verdwijnt;
- de gebiedstools worden zichtbaar;
- gewone klikken op losse punten doen niets;
- de gebruiker tekent een polygoon;
- alle geselecteerde stroompunten worden gemarkeerd;
- alle detailkaarten van de selectie verschijnen in de zijbalk;
- alle ID's kunnen in één keer gekopieerd worden;
- per detailkaart blijft een individuele kopieerknop beschikbaar.

Bij het wisselen van modus wordt de oude selectie bewust opgeruimd. Daardoor
staan een selectie van één punt en een gebiedsselectie nooit tegelijk actief.

Na deployment moet de console tonen:

`Stroomaansluitingen app v19.0.0`
