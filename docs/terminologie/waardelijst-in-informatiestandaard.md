# Waardelijst in informatiestandaard

Omdat zibs in informatiestandaarden worden gebruikt, worden ook de waardelijsten bij zib-elementen van het type 'Coded
Description' (CD) in die informatiestandaarden gebuikt. Afwijkingen van waardelijsten in informatiestandaarden zouden
moeten worden voorkomen en zijn aan regels gebonden.

## TE-WI.001: Waardelijsten in informatiestandaarden MOGEN minder waarden bevatten dan de corresponderende waardelijsten in de zibs

Dit is toegestaan omdat in dit geval ontvangen informatie nog altijd voldoet aan de zib.

| Toepasselijke rollen          | Eisniveau |
|-------------------------------|-----------|
| Informatiestandaard-ontwerper | MAY       |

## TE-WI.002: ALS een waardelijst in een informatiestandaard minder waarden bevat dan in de zib, DAN: MOET de informatiestandaard beschrijven hoe wordt geborgd dat alleen de ingeperkte lijst wordt verwerkt en/of gedeeld

Bij het verzenden of beschikbaar stellen van informatie moet duidelijk zijn hoe wordt voorkomen dat informatie wordt
verzonden die waarden bevat die niet tot de informatiestandaard behoren maar wel tot de zib. Meestal betreft dit
filtercriteria voor de te verzenden/beschikbaar te stellen informatie.

| Toepasselijke rollen          | Eisniveau |
|-------------------------------|-----------|
| Informatiestandaard-ontwerper | MUST      |

## TE-WI.003: Waardelijsten in informatiestandaarden MOETEN NIET meer waarden bevatten dan in de zib, tenzij de binding van de waardelijst 'extensible' is, en de uitgebreide waarden voldoen aan de criteria voor 'extensible'

Als de informatiestandaard waarden bevat die niet bestaan in de gebruikte zib(s), dan kunnen deze waarden potentieel
niet worden verwerkt en/of getoond door het ontvangende systeem, tenzij de waardelijst 'extensible' is en de waarden
binnen de criteria voor 'extensible' vallen.

| Toepasselijke rollen          | Eisniveau |
|-------------------------------|-----------|
| Informatiestandaard-ontwerper | MUST NOT  |