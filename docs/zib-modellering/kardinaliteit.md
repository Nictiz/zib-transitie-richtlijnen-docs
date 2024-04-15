# Kardinaliteit

Richtlijnen voor kardinaliteit bepalen hoe vaak een bepaald zib-element moet of mag worden ingevuld. Bijvoorbeeld:
minimaal 0 en maximaal 1 keer, of minimaal 1 en maximaal 3 keer.

## ZM001.001: De minimumkardinaliteit van een zib-element ZOU 0 moeten zijn

In de context van gezondheid en zorg moet men er vanuit gaan dat gegevens niet bekend zijn of om andere redenen niet
vastgelegd kunnen worden. Daarom zou de minimale kardinaliteit altijd 0 moeten zijn en niet 1 of hoger.

| Toepasselijke rollen | Eisniveau |
|----------------------|-----------|
| Zib-ontwerper        | SHOULD    |

## ZM001.002: ALS een zib-element in alle denkbare gevallen, onafhankelijk van de usecase, moet worden geregistreerd en/of uitgewisseld, DAN: MAG de minimumkardinaliteit van het element 1 zijn

Alleen wanneer een element zo'n elementair onderdeel van de zib is dat zij bij registratie of uitwisseling nooit
achterwege kan blijven, ongeacht de usecase, dan mag de kardinaliteit van dat element 1 zijn.

| Toepasselijke rollen | Eisniveau |
|----------------------|-----------|
| Zib-ontwerper        | MAY       |