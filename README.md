# Stroomaansluitingen — v22 responsive desktop + mobiel

Deze versie bouwt voort op v21 en behoudt dezelfde desktopopmaak en functies.
Er is dus maar **één app en één codebase** nodig voor desktop, tablet en mobiel.

## Mobiele werking

Op schermen tot 900 px:
- de kaart blijft het hoofdscherm;
- `Selectie & details` opent als een bottom sheet vanaf de onderkant;
- de knop rechtsboven opent/sluit dat paneel;
- bij het aanklikken van één stroompunt opent het detailpaneel automatisch;
- bij `Meerdere punten > Selecteer gebied` sluit het paneel automatisch zodat
  de volledige kaart beschikbaar is om te tekenen;
- zodra de polygoon klaar is, opent het paneel opnieuw met de resultaten;
- `toon op kaart` bij een resultaat sluit het paneel zodat het punt zichtbaar is;
- touchknoppen zijn minimaal ongeveer 44 px;
- inhoud in het paneel is touch-scrollbaar;
- het helpvenster werkt ook mobiel;
- rekening gehouden met `safe-area` onderaan op moderne smartphones.

## Desktop

Boven 900 px blijft de gekende v21-layout actief met de vaste zijbalk links.

## Controle

Na deployment moet de browserconsole tonen:

`Stroomaansluitingen app v22.0.0`
