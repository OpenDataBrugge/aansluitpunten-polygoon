# Stroomaansluitingen — v26 totaal vermogen enkel numeriek

Deze versie bouwt voort op v25.

Aanpassing:
- in de fiche wordt bij `TOTAAL_VERMOGEN` alleen de eerste numerieke waarde weergegeven;
- extra tekst tussen haakjes wordt niet getoond;
- cijfers die deel uitmaken van codes zoals `MKT2` of `EVN2` worden genegeerd.

Voorbeelden:

`150 (MKT2+EVN2)` → `150 A`

`63 A` → `63 A`

`1.250,5 (extra info)` → `1.250,5 A`

Alle andere functies uit v25 blijven behouden, inclusief:
- ID kopiëren tot aan de eerste spatie;
- selectie van één punt;
- polygoonselectie van meerdere punten;
- mobiele en desktopweergave;
- helpfunctie.

Na deployment moet in de console staan:

`Stroomaansluitingen app v26.0.0`
