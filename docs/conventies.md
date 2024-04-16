# Conventies

## Identificatie van richtlijnen

Richtlijnen krijgen unieke en permanente codes ter identificatie. Indien richtlijnen verouderd (of 'deprecated') zijn,
dan worden deze uit de lijst verwijderd. Zodoende kunnen er gaten ontstaan in de nummering van richtlijnen. Nieuwe
richtlijnen krijgen altijd een hoger volgnummer.

Het formaat van een code is als volgt: `CC-OO.nnn`

- `CC`: twee-letter categorie
- `OO`: twee-letter onderwerp
- `nnn`: drie-cijfer volgnummer

Het volgnummer start bij `001`, per unieke `CC-OO` combinatie.

We onderscheiden de volgende categorieën en onderliggende onderwerpen:

| Categorie | Beschrijving    | Onderwerp | Beschrijving                       | Voorbeeld   |
|-----------|-----------------|-----------|------------------------------------|-------------|
| `TE`      | Terminologie    | `BW`      | Binding waardelijst                | `TE-BW.001` |
|           |                 | `DW`      | Dynamische waardelijst             | `TE-DW.001` |
|           |                 | `WZ`      | Waardelijst in afgeleide zib       | `TE-WZ.001` |
|           |                 | `WI`      | Waardelijst in informatiestandaard | `TE-WI.001` |
|           |                 | `VW`      | Verwerking waarden                 | `TE-VW.001` |
| `ZB`      | Zib-blauwdruk   | `DO`      | Documentatie                       | `ZB-DO.001` |
|           |                 | `GE`      | Gebruik                            | `ZB-GE.001` |
| `ZM`      | Zib-modellering | `KA`      | Kardinaliteit                      | `ZM-KA.001` |

## Regels voor het schrijven van richtlijnen

Om consistente en duidelijke richtlijnen te borgen, moeten ze voldoen aan de volgende regels:

- Sleutelwoorden MOETEN met hoofdletters worden geschreven
- Als een richtlijn conditioneel is, dan MOET deze worden geschreven in de vorm: "ALS \[conditie\], DAN: \[richtlijn\]"
- Een richtlijn MOET NIET met een punt eindigen

Bovendien:

- Vaktermen en afkortingen MOETEN correct worden geschreven
- Rechte aanhalingstekens ( ' of " ) MOETEN worden gebruikt in plaats van gekrulde aanhalingstekens (ook wel bekend als
  "slimme aanhalingstekens")