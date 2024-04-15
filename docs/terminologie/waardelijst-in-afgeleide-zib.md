# Waardelijst in afgeleide zib

Afgeleide zibs 'overerven' de waardelijsten van hun ouders.

## TE003.001: Waardelijsten in afgeleide zibs MOETEN NIET waarden bevatten die niet ook in de waardelijst van de ouder-zib voorkomen

Als een afgeleide zib waarden bevat die niet in de ouder-zib voorkomen, is een instantie van de afgeleide zib niet
gegarandeerd een geldige instantie van de ouder-zib. Dit beperkt de vertaalbaarheid van zibs naar fysieke opslagmodellen
of uitwisselingsmodellen.

| Toepasselijke rollen | Eisniveau |
|----------------------|-----------|
| Zib-ontwerper        | MUST NOT  |

## TE003.002: Waardelijsten in afgeleide zibs MOGEN minder waarden bevatten dan de waardelijst van de ouder-zib

Als een afgeleide zib minder waarden bevat dan in de ouder-zib voorkomen, is een instantie van de afgeleide zib
gegarandeerd een geldige instantie van de ouder-zib. Dit is dus toegestaan.

| Toepasselijke rollen | Eisniveau |
|----------------------|-----------|
| Zib-ontwerper        | MAY       |

## TE003.003: ALS een waardelijst van een afgeleide zib minder waarden bevat dan die van de ouder-zib, DAN: MOET de binding van deze waardelijst 'extensible' zijn

De afgeleide zib mag niet restrictiever zijn dan de ouder-zib.

| Toepasselijke rollen | Eisniveau |
|----------------------|-----------|
| Zib-ontwerper        | MUST      |