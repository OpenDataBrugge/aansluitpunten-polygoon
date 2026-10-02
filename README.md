# Stroomaansluitingen — v27

Deze versie bouwt voort op v26 en is aangepast aan het nieuwe schema van de stroomaansluitingen.

Belangrijkste wijziging:
- `BLAUW_230V_32A` is vervangen door twee afzonderlijke velden:
  - `BLAUW_230V_32A_2F`
  - `BLAUW_230V_32A_3F`
- in de detailweergave worden deze getoond als `CEE 32 A — 2F` en `CEE 32 A — 3F`;
- de automatische veldherkenning en laagselectie verwachten nu beide nieuwe velden;
- de overige functies uit v26 blijven behouden.

Na deployment moet in de browserconsole staan:

`Stroomaansluitingen app v27.0.0`
