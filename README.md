# Stroomaansluitingen — v17 polygoonselectie

Deze versie bouwt voort op de werkende v16/v15.

Nieuw:
- knop **Selecteer gebied** onder de teller;
- de gebruiker kan rechtstreeks op de kaart een polygoon tekenen;
- dubbelklik sluit de polygoon af;
- alle stroompunten die de polygoon raken worden ruimtelijk geselecteerd;
- de geselecteerde punten worden op de kaart gemarkeerd;
- de zijbalk toont alleen het aantal geselecteerde punten, geen scrollbare lijst;
- knop **Kopieer X ID's** kopieert alle `AANSLUITPUNT_ID`-waarden;
- de ID's worden standaard één per regel naar het klembord gekopieerd;
- **Wis selectie** verwijdert de polygoon en de gebiedshighlight;
- tijdens het tekenen wordt de gewone puntselectie tijdelijk genegeerd.

Bestaande functies blijven behouden:
- geen kaartpopup;
- detailkaart in Arcade-stijl;
- kopieerknop voor één aansluitpunt;
- teller met vorige/volgende;
- automatisch zoomen naar zoomniveau 16.5;
- automatische keuze van de juiste featurelaag;
- Experience Builder-achtige header.

Na deployment hoort in de console te staan:

`Stroomaansluitingen app v17.0.0`
