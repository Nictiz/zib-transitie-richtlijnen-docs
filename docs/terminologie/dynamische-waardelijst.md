# Dynamische waardelijst

Een dynamische waardelijst heeft geen vaste elementen, maar verwijst naar een terminologie-query of een referentieset
uit een bestaande terminologie. De inhoud van een dynamische waardelijst wordt dus bepaald door de (versie van) de
terminologie, en niet door de zib.

## TE002.001: Waardelijsten ZOUDEN 'dynamisch' moeten zijn

Dynamische waardelijsten verwijzen naar een achterliggende terminologie op basis van een terminologie-query of
referentieset. De meest actuele inhoud van de lijst wordt niet bepaald door de zib maar door de terminologie, en kan
altijd worden opgevraagd bij de nationale terminologieserver.

| Toepasselijke rollen | Eisniveau |
|----------------------|-----------|
| Zib-ontwerper        | SHOULD    |

## TE002.002: ALS de waarden in een waardelijst niet toepasbaar zijn buiten de context van een bepaalde zib, DAN: MAG een waardelijst 'statisch' zijn

Indien de waarden van een waardelijst uniek zijn voor een bepaalde zib en niet buiten die zib worden gebruikt, dan is
een statische lijst toegestaan.

| Toepasselijke rollen | Eisniveau |
|----------------------|-----------|
| Zib-ontwerper        | MAY       |

## TE002.003: ALS een waardelijst niet op een terminologie-query of (SNOMED CT) referentieset kan worden gebaseerd, DAN: MAG een waardelijst 'statisch' zijn

Een waardelijst die niet op een query of referentieset kan worden gebaseerd kan niet dynamisch zijn. Overweeg om het
terminologiecentrum te verzoeken een nieuwe referentieset te ontwikkelen.

| Toepasselijke rollen | Eisniveau |
|----------------------|-----------|
| Zib-ontwerper        | MAY       |

## TE002.004: ALS systemen een 'dynamische' waardelijst aanbieden, DAN: MOET de gebruikte versie van de achterliggende terminologie niet ouder zijn dan actueel minus 1

Verschillen in gebruikte terminologie tussen systemen kunnen ertoe leiden dat data door een systeem (onterecht) niet kan
worden verwerkt of niet (correct) kan worden getoond aan de eindgebruiker.

| Toepasselijke rollen                  | Eisniveau |
|---------------------------------------|-----------|
| Systeemontwikkelaar,<br>Zorgaanbieder | MUST      |

## TE002.005: Systemen ZOUDEN de aan de zorgverlener getoonde inhoud van 'dynamische' waardelijsten moeten baseren op een online query naar de nationale terminologieserver

Door bij invoer van gegevens de inhoud van een dynamische waardelijst op te halen bij de nationale terminologieserver,
wordt altijd de meest recente versie van de waardelijst gebruikt.

| Toepasselijke rollen | Eisniveau |
|----------------------|-----------|
| Systeemontwikkelaar  | SHOULD    |